# Audio Analyzer Feature Documentation

This is the documentation for the Cyanite Audio Analyzer output features.

#### Feature Matrix:

The feature matrix can be used to look up which marketplace version corresponds to which feature versions.

| | marketplace_v1.1 | 
| :--- | :--- |
| [transformerCaption](#transformercaption)   | v8 |
| [transformerGenreTags](#transformergenretags) | v8 |          
| [genre](#genre) | v8 |                                
| [mood](#mood) | v8 |                               
| [moodAdvanced](#moodadvanced) | v8 |                                       
| [character](#character) | v8 |                                    
| [movement](#movement) | v8 |                                   
| [instruments](#instruments) | v8 |                                      
| [voice](#voice) | v8 |                                
| [valenceArousal](#valencearousal) | v8 |                                         
| [musicalEra](#musicalera) | v8 |                                     
| [musicalFeatures](#musicalfeatures) | v8 |                                       
| [voiceover](#voiceover) | v8 |                                    
| [augmentedKeywords](#augmentedkeywords) | v8 |                                    


#### JSON Schemes:
| Version | Raw Schema | Documentation | Example Output
| :--- | :--- | :--- | :--- |
| marketplace_v1.1 | [here](schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json) | [here](schemes/marketplace_v1.1/documentation/marketplace_v1.md) | [here](schemes/marketplace_v1.1/example/marketplace_v1.1_example_output.json) |


___

### 0. Miscellaneous:

#### `version`

The version field contains the version name linked to the analysis.

#### `timestamps`

For analysis, audio is being split into segments of equal length. The `timestamps` array contains the center values in seconds for each segment. As many features will be predicted using the segmented audio signal, the `timestamps` also correspond to the _segments_ field contained in many feature objects. 

#### `representativeSegmentIndex`

The `representativeSegmentIndex` is computed based on latent transformer features. It represents the index of the segment that is most representative of a song. 


___
<a name="transformercaption"></a>
### 1. `transformerCaption`

| Features | Description |
| :--- | :--- |
| caption | String of text describing the audio content | 

The `transformerCaption` is predicted on a transformer-based model. 
The caption output is a string of max. 30 words describing various aspects of the audio track in one or few sentences (full text).

___
<a name="transformergenretags"></a>
### 2. `transformerGenreTags`

| Features | Description |
| :--- | :--- |
| tags | Array of tags describing the genre(s) of the audio | 

The `transformerGenreTags` is predicted on a transformer-based model. The output is a string of comma delimited genre tags for the track. It is different to the genre models as it does not follow a fixed taxonomy and does instead cover a very broad range of musical genres. Due to its text generator nature, there are no scores returned for the tags given. 


___
<a name="genre"></a>
### 3. `genre`

The genre object combines results of several dependent classifiers. 

#### 3.1. `mainGenre`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| mean | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

The `mainGenre` is a multi-label classifier, predicting a per segment probability within the range of $[0,1]$ for each of the 23 main genre classes:

<details>
  <summary>Click to Expand</summary>

 - `afro`
 - `ambient`
 - `arab`
 - `asian`
 - `blues`
 - `childrenJingle`
 - `classical`
 - `electronicDance`
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

 
#### 3.2. `subgenre`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| mean | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 
 
There are 7 `subgenre` models available, of which 2 can be triggered at the same time. A `subgenre` model is triggered if its respective `mainGenre` is within the top 2 main genre tags. Additionally, the `folkCountry` subgenre model is also triggered by the main genre `singerSongwriter`. 
Analogous to the subgenre classifiers, for the main genre `classical`, there is a classifier for classical epochs which is triggered once the Classical main genre is tagged.

There is a total of 64 subgenre classes:

<details>
  <summary>Click to Expand</summary>

  - `classical`
    - `classicalEpochMiddleAge`
    - `classicalEpochRenaissance`
    - `classicalEpochBaroque`
    - `classicalEpochClassical`
    - `classicalEpochRomantic`
    - `classicalEpochContemporary`
  - `electronicDance`
    - `abstractIDMLeftfield`
    - `BreakbeatDnB`
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
    - `contemporaryRnB`
    - `gangsta`
    - `jazzyHipHop`
    - `popRap`
    - `trap`
  - `rock`
    - `bluesRock`
    - `folkRock`
    - `hardRock`
    - `indieAlternative`
    - `psychedelicProgressiveRock`
    - `punk`
    - `rockAndRoll`
    - `popSoftRock`
    
</details>

___
<a name="mood"></a>
### 4. `mood`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| mean | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

The `mood_model` is a multi-label classifier, predicting a per segment probability within the range of $[0,1]§ for each of the 13 mood classes:

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
<a name="moodadvanced"></a>
### 5. `moodAdvanced`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| mean | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

The `mood_advanced_model` is a multi-label classifier, predicting a per segment probability within the range of $[0,1]$ for each of the 132 advanced mood classes:

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
<a name="character"></a>
### 6. `character`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| mean | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

`character` depicts the expressive form of music which is rather headed towards its appearance than its mood. It is much related to brand values of music.

The `character_model` is a multi-label classifier, predicting a per segment probability within the range of $[0,1]$ for each of the 16 classes:

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
<a name="movement"></a>
### 7. `movement`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| mean | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 

`movement` describes the rhythmic structure of music on a high level.

The `movement_model` is a multi-label classifier, predicting a per segments probability within the range of $[0,1]$ for each of the 10 classes:

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
<a name="instruments"></a>
### 8. `instruments`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| segments | Array of probabilities for each class and segment | 
| presence | A tag for each class describing the presence throughout the track |

All instrument models are binary classifiers (with one or two output neurons), predicting a per segment probability within the range of $[0,1]$ for a instrument being present.

The `presence` feature can have the following values:

| Value | Description |
| :--- | :--- |
| "absent" | instrument has not been tagged |
| "partially" | instrument result has exceeded classification threshold in less than half of the segments |
| "frequenty" | instrument result has exceeded classification threshold in at least half of the segments |
| "throughout" | instrument result has exceeded classification threshold over the whole duration. |


There are models available for the following instruments:

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
<a name="voice"></a>
### 9. `voice`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 
| mean | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 
| voicePresenceProfile | String describing the voice presence |
| predominantVoiceGender | String describing the predominant voice gender |

The `voice_model` is a multi-label classifier, predicting a per segment probability within the range of $[0,1]$ for each of the 3 classes below:

  - `female`
  - `male`
  - `instrumental`

On top of the probabilities, tags regarding the voice presence and predominant voice gender are generated. Following values are possible:

 - `voicePresenceProfile`: "None" | "Low" | "Medium" | "High"
 - `predominantVoiceGender` : "None" | "Female" | "Male"



___
<a name="valencearousal"></a>
### 10. `valenceArousal`

| Features | Description |
| :--- | :--- |
| mean | Mean probabilites for each class over the whole track | 
| segments | Array of probabilities for each class and segment | 
| energyLevel | String describing the energy level |
| energyDynamics | String descrining the energy dynamics |
| emotionalProfile | String describing emotional profile |
| emotionalDynamics | String describing the emotional dynamics |

For theoretical background for the `valenceArousal` model, please refer to the [Circumplex Model by Russell](https://en.wikipedia.org/wiki/Emotion_classification)

Based on the mood model, values in the range of $[0,1]$ for valence and arousal are computed  and passed in the `valenceArousal` object.

For both valence (emotion) and arousal (energy), tags are generated describing their overall level and the variation throughout the track. Following values are possible:
 
  - `energyLevel`: "low" | "medium" | "high"
  - `energyDynamics` : "variable" | "low" | "medium" | "high"
  - `emotionalProfile` : "low" | "medium" | "high"
  - `emotionalDynamics` : "variable" | "negative" | "balanced" | "positive"
 

___
<a name="musicalera"></a>
### 11. `musicalEra`

| Features | Description |
| :--- | :--- |
| tags | String describing the approximate musical era of the track | 
| exactYear | Integer describing the exact predicted year of the track | 

The `musical_era_model` is a binary regressor, predicting the most probable musical era of production of a track. 
 
The result is returned as a mean value for the full duration of the track. Additionally, a string is generated describing the approximate era of the track. String values range from "late 40s / early 50s" to "contemporary". 


___
<a name="musicalfeatures"></a>
### 12. `musicalFeatures`

#### 12.1. `bpm`

| Features | Description |
| :--- | :--- |
| tags | Integer describing the global bpm value | 
| tagsRangeAdjusted | Integer describing the global bpm value adjusted to a custom range of 60-180 | 
| confidence | number describing the confidence of the prediction |

`bpm` is a multi-label classifier predicting the global BPM value for a track. It can take values from 30 to 285. `tagsRangeAdjusted` will return values within the range of 60 to 180. Values not lying within these bounds will be doubled/halved. 


#### 12.2. `timeSignature`

| Features | Description |
| :--- | :--- |
| timeSignature | String describing the global time signature of the track | 

`timeSignature` is a multi-label classifier predicting the global time signature for a track. 


#### 12.3. `key`

| Features | Description |
| :--- | :--- |
| tags | String describing the global key value | 
| confidence | number describing the confidence of the prediction |

`key` is a multi-label classifier predicting the global key for a track.


___
<a name="voiceover"></a>
### 13. `voiceover`

| Features | Description |
| :--- | :--- |
| voiceoverDegree | Number describing the percentage of voiceover in the track | 
| isVoiceoverDominant | Boolean describing whether an audio is flagged as containing a considerable amount of voiceover |

The voiceover classifier is a binary classifier that detects the likelihood of an audio file (specifically music) containing a voiceover as this might be the case when the audio is extracted from a video, advertisement or similar. In case of a voiceover present, we have seen decreasing performance in basically all analysis results. The voiceover score can therefore be used as an indicator for potentially noisy analysis results. 


___
<a name="augmentedKeywords"></a>
### 13. `augmentedKeywords`

| Features | Description |
| :--- | :--- |
| tags | Array of tags that were predicted globally | 

The augmented keywords freely describe a track using 20 tags from a taxonomy of 1500 unique terms.

Excerpt of available tags:

<details>
  <summary>Click to Expand</summary>

  - `joy` 
  - `travel` 
  - `summer` 
  - `motivating`
  - `pleasant` 
  - `happy` 
  - `energetic` 
  - `electro`
  - `bliss`
  - `gladness` 
  - `auspicious` 
  - `pleasure` 
  - `forceful`
  - `determined`
  - `confident`
  - `positive` 
  - `optimistic`
  - `agile`
  - `animated` 
  - `journey` 
  - `party`
  - `driving` 
  - `kicking` 
  - `impelling` 
  - `upbeat`

</details>




