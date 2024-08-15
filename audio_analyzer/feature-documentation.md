# Audio Analyzer Feature Documentation

This is the documentation for the Cyanite Audio Analyzer output features.

#### Feature Matrix:

The feature matrix can be used to look up which tagging version corresponds to which feature versions.

| | TaggingV8 | 
| :--- | :--- |
| [audioFileInfo](#audiofileinfo)   | V1 |
| [autoDescription](#autodescription)   | V2 |
| [bpm](#bpm) | V1 |
| [character](#character) | V1 |
| [freeGenre](#freegenre) | V1 |
| [instrument](#instrument) | V1 |
| [key](#key) | V1 |
| [mainGenre](#maingenre) | V1 |
| [moodAdvanced](#moodadvanced) | V1 |
| [moodSimple](#moodsimple) | V1 |
| [movement](#movement) | V1 |
| [musicalEra](#musicalera) | V1 |
| [representativeSegmentIndex15s](#representativesegmentindex15s) | V1 |
| [subGenre](#subgenre) | V1 |
| [timeSignature](#timesignature) | V1 |
| [timeStamps15s](#timestamps15s) | V1 |
| [valenceArousal](#valencearousal) | V1 |
| [vocal](#vocal) | V1 |
| [voiceover](#voiceover) | V1 |

#### JSON Schemes:
| Version | Raw Schema | Documentation | Example Output
| :--- | :--- | :--- | :--- |
| TaggingV8 | [here](schemes/marketplace_v1/schema/TaggingV8.schema.json) | [here](schemes/marketplace_v1/documentation/TaggingV8.md) | [here](schemes/marketplace_v1/example/tagging_v8_example_output.json) |


___
<a name="audiofileinfo"></a>
### 1. `audioFileInfo`

| Features | Description |
| :--- | :--- |
| duration | Duration of the audio | 
| fileSizeB | Audio file size in Bytes | 
| bitrate | Bitrate of the audio | 
| samplerate | Samplerate of the audio | 

The `audioFileInfo` contains meta-information about the analyzed file. 

___
<a name="autodescription"></a>
### 2. `autoDescription`

| Features | Description |
| :--- | :--- |
| description | String of text describing the audio content | 

The `autoDescription` is predicted on a transformer-based model. 
The caption output is a string of max. 30 words describing various aspects of the audio track in one or few sentences (full text).

___
<a name="bpm"></a>
### 3. `bpm`

| Features | Description |
| :--- | :--- |
| segments | Array of integers describing bpm value per segment | 
| segmentsRange | Array of integers describing bpm value per segment adjusted to a custom range of 60-180 | 
| tag | Integer describing the global bpm value | 
| tagRange | Integer describing the global bpm value adjusted to a custom range of 60-180 | 
| confidence | number describing the confidence of the prediction |

`bpm` is a multi-label classifier predicting the local and global BPM value for a track. It can take values from 30 to 285. `tagsRangeAdjusted` will return values within the range of 60 to 180. Values not lying within these bounds will be doubled/halved. 

___
<a name="character"></a>
### 4. `character`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| scores | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

`character` depicts the expressive form of music which is rather headed towards its appearance than its mood. It is much related to brand values of music.

The `character` model is a multi-label classifier, predicting a per segment probability within the range of $[0,1]$ for each of the 16 classes:

<details>
  <summary>Click to Expand</summary>

  - `bold` 
  - `cool` 
  - `epic` 
  - `ethereal` 
  - `heroic` 
  - `luxurious` 
  - `magical` 
  - `mysterious` 
  - `playful` 
  - `powerful` 
  - `retro` 
  - `sophisticated` 
  - `sparkling` 
  - `sparse` 
  - `unpolished`
  - `warm`

</details>


___
<a name="freegenre"></a>
### 5. `freeGenre`

| Features | Description |
| :--- | :--- |
| tags | Array of tags describing the free genre(s) of the audio | 

The `freeGenre` is predicted on a transformer-based model. The output is a list of genre tags for the track. It is different to the genre models as it does not follow a fixed taxonomy and does instead cover a very broad range of musical genres. Due to its text generator nature, there are no scores returned for the tags given. 


___
<a name="instrument"></a>
### 6. `instrument`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| segments | Array of probabilities for each class and segment | 
| presence | A tags for each class describing the presence throughout the track |

All instrument models are binary classifiers (with one or two output neurons), predicting a per segment probability within the range of $[0,1]$ for a instrument being present.

The `presence` feature can have the following values:

| Value | Description |
| :--- | :--- |
| "absent" | instrument has not been tagged |
| "partially" | instrument result has exceeded classification threshold in less than half of the segments |
| "frequenty" | instrument result has exceeded classification threshold in at least half of the segments |
| "throughout" | instrument result has exceeded classification threshold over the whole duration. |


There are models available for the following instrument:

<details>
  <summary>Click to Expand</summary>

  - `acousticGuitar`
  - `africanPercussion`
  - `asianFlute`
  - `asianStrings`
  - `banjo`
  - `bass` (= Analog / Digital / Bass Guitar, etc.)
  - `bassGuitar`
  - `bells`
  - `bongoConga`
  - `brass`
  - `churchOrgan`
  - `celeste`
  - `cello`
  - `clarinet`
  - `doubleBass`
  - `drumKit`
  - `electricGuitar`
  - `electricOrgan`
  - `electricPiano`
  - `drumMachine`
  - `flute`
  - `frenchHorn`
  - `glockenspiel`
  - `harp`
  - `harpsichord`
  - `luteOud`
  - `mandolin`
  - `marimba`
  - `oboe`
  - `percussion`
  - `piano`
  - `pizzicato`
  - `sax`
  - `sitar`
  - `steelDrums`
  - `strings`
  - `synth`
  - `tabla`
  - `taiko`
  - `trumpet`
  - `tuba`
  - `ukulele`
  - `vibraphone`
  - `violin`
  - `woodwinds`
  
</details>


___
<a name="key"></a>
### 7. `key`

| Features | Description |
| :--- | :--- |
| segments | Array describing the key values per segment | 
| tag | String describing the global key value | 
| confidence | number describing the confidence of the prediction |

`key` is a multi-label classifier predicting the global key for a track.


___
<a name="maingenre"></a>
### 8. `mainGenre`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| scores | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

The `mainGenre` is a multi-label classifier, predicting a per segment probability within the range of $[0,1]$ for each of the 23 main main genre classes:

<details>
  <summary>Click to Expand</summary>

 - `african`
 - `ambient`
 - `middleEastern`
 - `asian`
 - `blues`
 - `childrenJingle`
 - `classical`
 - `electronic`
 - `folkCountry`
 - `funkSoul`
 - `indian`
 - `jazz`
 - `latin`
 - `metal`
 - `pop`
 - `rapHipHop`
 - `reggae`
 - `rnb`
 - `rock`
 - `singerSongwriter`
 - `sound`
 - `soundtrack`
 - `spokenWord`
 
</details>

___
<a name="moodadvanced"></a>
### 9. `moodAdvanced`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| scores | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

The `moodAdvanced` model is a multi-label classifier, predicting a per segment probability within the range of $[0,1]$ for each of the 132 advanced mood classes:

<details>
  <summary>Click to Expand</summary>
    
  - `anxious`
  - `barren`
  - `cold`
  - `creepy`
  - `dark`
  - `disturbing`
  - `eerie`
  - `evil`
  - `fearful`
  - `mysterious`
  - `nervous`
  - `restless`
  - `spooky`
  - `strange`
  - `supernatural`
  - `suspenseful`
  - `tense`
  - `weird`
  - `aggressive`
  - `agitated`
  - `angry`
  - `dangerous`
  - `fiery`
  - `intense`
  - `passionate`
  - `ponderous`
  - `violent`
  - `comedic`
  - `eccentric`
  - `funny`
  - `mischievous`
  - `quirky`
  - `whimsical`
  - `boisterous`
  - `boingy`
  - `bright`
  - `celebratory`
  - `cheerful`
  - `excited`
  - `feelGood`
  - `fun`
  - `happy`
  - `joyous`
  - `lighthearted`
  - `perky`
  - `playful`
  - `rollicking`
  - `upbeat`
  - `calm`
  - `contented`
  - `dreamy`
  - `introspective`
  - `laidBack`
  - `leisurely`
  - `lyrical`
  - `peaceful`
  - `quiet`
  - `relaxed`
  - `serene`
  - `soothing`
  - `spiritual`
  - `tranquil`
  - `Bittersweet`
  - `blue`
  - `depressing`
  - `gloomy`
  - `heavy`
  - `lonely`
  - `melancholic`
  - `mournful`
  - `poignant`
  - `sad`
  - `frightening`
  - `horror`
  - `menacing`
  - `nightmarish`
  - `ominous`
  - `panicStricken`
  - `scary`
  - `concerned`
  - `resolute`
  - `dignified`
  - `emotional`
  - `noble`
  - `serious`
  - `solemn`
  - `thoughtful`
  - `cool`
  - `seductive`
  - `sexy`
  - `adventurous`
  - `confident`
  - `courageous`
  - `resolute`
  - `energetic`
  - `epic`
  - `exciting`
  - `exhilarating`
  - `heroic`
  - `majestic`
  - `powerful`
  - `prestigious`
  - `relentless`
  - `strong`
  - `triumphant`
  - `victorious`
  - `delicate`
  - `graceful`
  - `hopeful`
  - `innocent`
  - `intimate`
  - `kind`
  - `light`
  - `loving`
  - `nostalgic`
  - `reflective`
  - `romantic`
  - `sentimental`
  - `soft`
  - `sweet`
  - `tender`
  - `warm`
  - `anthemic`
  - `aweInspiring`
  - `euphoric`
  - `inspirational`
  - `motivational`
  - `optimistic`
  - `positive`
  - `proud`
  - `soaring`
  - `uplifting`
    
</details>

___
<a name="moodsimple"></a>
### 10. `moodSimple`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| scores | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

The `moodSimple` model is a multi-label classifier, predicting a per segment probability within the range of $[0,1]§ for each of the 13 mood classes:

<details>
  <summary>Click to Expand</summary>
    
 - `aggressive`
 - `calm`
 - `chilled`
 - `dark`
 - `energetic`
 - `epic`
 - `ethereal`
 - `happy`
 - `romantic`
 - `sad`
 - `scary`
 - `sexy`
 - `uplifting`
 
</details>


___
<a name="movement"></a>
### 11. `movement`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| scores | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

`movement` describes the rhythmic structure of music on a high level.

The `movement` model is a multi-label classifier, predicting a per segments probability within the range of $[0,1]$ for each of the 10 classes:

<details>
  <summary>Click to Expand</summary>

  - `bouncy`
  - `driving` 
  - `flowing` 
  - `groovy` 
  - `nonrhythmic` 
  - `pulsing`
  - `robotic`
  - `running`
  - `steady` 
  - `stomping`

</details>


___
<a name="musicalera"></a>
### 12. `musicalEra`

| Features | Description |
| :--- | :--- |
| tag | String describing the approximate musical era of the track | 
| exactYear | Integer describing the exact predicted year of the track | 

The `musicalEra` model is a regressor, predicting the most probable musical era of production of a track. 
 
The result is returned as a scores value for the full duration of the track. Additionally, a string is generated describing the approximate era of the track. String values range from "earlyMid1950s" to "contemporary". 


___
<a name="representativesegmentindex15s"></a>
### 13. `representativeSegmentIndex15s`

The `representativeSegmentIndex15s` is computed based on latent features. It represents the index of the segment that is most representative of a song. 


____
<a name="subgenre"></a>
### 14. `subGenre`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| scores | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 
 
There are 7 `subgenre` models available, of which 2 can be triggered at the same time. A `subgenre` model is triggered if its respective `mainGenre` is within the top 2 main genre tags. Additionally, the `folkCountry` subgenre model is also triggered by the main genre `singerSongwriter`. 
Analogous to the subgenre classifiers, for the main genre `classical`, there is a classifier for classical epochs which is triggered once the Classical main genre is tagged.

There is a total of 64 subgenre classes:

<details>
  <summary>Click to Expand</summary>

  - `classical`
    - `medieval`
    - `renaissance`
    - `baroque`
    - `classical`
    - `romantic`
    - `contemporary`
  - `electronic`
    - `abstractIdm`
    - `breakbeatDnb`
    - `deepHouse`
    - `electro`
    - `house`
    - `minimal`
    - `synthPop`
    - `techHouse`
    - `techno`
    - `trance`
  - `folkCountry` | `singerSongwriter`
    - `folk`
    - `country`
  - `funkSoul`
    - `disco`
    - `funk`
    - `gospel`
    - `neoSoul`
    - `soul`
  - `jazz`
    - `bigBandSwing`
    - `bebop`
    - `contemporaryJazz`
    - `easyListening`
    - `fusion`
    - `latinJazz`
    - `smoothJazz`
  - `metal`
    - `blackMetal`
    - `deathMetal`
    - `doomMetal`
    - `heavyMetal`
    - `metalcore`
    - `nuMetal`
  - `rapHipHop`
    - `contemporaryRnb`
    - `gangsta`
    - `jazzyHipHop`
    - `popRap`
    - `trap`
  - `rock`
    - `bluesRock`
    - `folkRock`
    - `hardRock`
    - `indieAlternative`
    - `psychedelicProgRock`
    - `punk`
    - `rockAndRoll`
    - `softRock`
    
</details>


___
<a name="timesignature"></a>
### 15. `timeSignature`

| Features | Description |
| :--- | :--- |
| tag | String describing the global time signature of the track | 
| confidence | Number describing the confidence of the prediction |

`timeSignature` is a multi-label classifier predicting the global time signature for a track. 



___
<a name="timestamps15s"></a>
### 16. `timeStamps15s`

| Features | Description |
| :--- | :--- |
| timestamps | Array describing the center times for each segment | 

For analysis, audio is being split into segments of equal length. The `timeStamps15s` array contains the center values in seconds for each segment. As many features will be predicted using the segmented audio signal, the `timeStamps15s` also correspond to the _segments_ field contained in many feature objects. 


___
<a name="valencearousal"></a>
### 17. `valenceArousal`

| Features | Description |
| :--- | :--- |
| scores | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 
| energyLevel | String describing the energy level |
| energyChanges | String descrining the energy dynamics |
| emotionProfile | String describing emotional profile |
| emotionChanges | String describing the emotional dynamics |

For theoretical background for the `valenceArousal` model, please refer to the [Circumplex Model by Russell](https://en.wikipedia.org/wiki/Emotion_classification)

Based on the moodSimple model, values in the range of $[0,1]$ for valence and arousal are computed  and passed in the `valenceArousal` object.

For both valence (emotion) and arousal (energy), tags are generated describing their overall level and the variation throughout the track. Following values are possible:
 
  - `energyLevel`: "low" | "medium" | "high"
  - `energyChanges` : "variable" | "low" | "medium" | "high"
  - `emotionProfile` : "low" | "medium" | "high"
  - `emotionChanges` : "variable" | "negative" | "balanced" | "positive"
 

___
<a name="vocal"></a>
### 18. `vocal`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| scores | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 
| vocalPresence | String describing the vocal presence |
| predominantVocalGender | String describing the predominant vocal gender |

The `vocal` model is a multi-label classifier, predicting a per segment probability within the range of $[0,1]$ for each of the 3 classes below:

  - `female`
  - `male`
  - `instrumental`

On top of the probabilities, tags regarding the vocal presence and predominant vocal gender are generated. Following values are possible:

 - `vocalPresence`: "None" | "Low" | "Medium" | "High"
 - `predominantVocalGender` : "None" | "Female" | "Male"


___
<a name="voiceover"></a>
### 19. `voiceover`

| Features | Description |
| :--- | :--- |
| voiceoverDegree | Number describing the percentage of voiceover in the track | 
| isvoiceoverDominant | Boolean describing whether an audio is flagged as containing a considerable amount of voiceover |

The voiceover classifier is a binary classifier that detects the likelihood of an audio file (specifically music) containing a voiceover as this might be the case when the audio is extracted from a video, advertisement or similar. In case of a voiceover present, we have seen decreasing performance in basically all analysis results. The voiceover score can therefore be used as an indicator for potentially noisy analysis results. 


