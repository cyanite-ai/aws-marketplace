# TaggingV8 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [TaggingV8.schema.json](../out/TaggingV8.schema.json "open original schema") |

## TaggingV8 Type

`object` ([TaggingV8](taggingv8.md))

# TaggingV8 Properties

| Property                                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                            |
| :-------------------------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [audioFileInfo](#audiofileinfo)                                 | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-audiofileinfov1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/audioFileInfo")                                 |
| [autoDescription](#autodescription)                             | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-autodescriptionv2.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/autoDescription")                             |
| [bpm](#bpm)                                                     | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/bpm")                                                     |
| [character](#character)                                         | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/character")                                         |
| [freeGenre](#freegenre)                                         | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-freegenrev2.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/freeGenre")                                         |
| [instrument](#instrument)                                       | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/instrument")                                       |
| [key](#key)                                                     | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-keyv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/key")                                                     |
| [mainGenre](#maingenre)                                         | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/mainGenre")                                         |
| [moodAdvanced](#moodadvanced)                                   | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/moodAdvanced")                                   |
| [moodSimple](#moodsimple)                                       | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/moodSimple")                                       |
| [movement](#movement)                                           | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/movement")                                           |
| [musicalEra](#musicalera)                                       | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-musicalerav1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/musicalEra")                                       |
| [representativeSegmentIndex15s](#representativesegmentindex15s) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-representativesegmentindex15sv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/representativeSegmentIndex15s") |
| [subGenre](#subgenre)                                           | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-subgenrev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/subGenre")                                           |
| [timeSignature](#timesignature)                                 | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-timesignaturev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/timeSignature")                                 |
| [timeStamps15s](#timestamps15s)                                 | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-timestamps15sv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/timeStamps15s")                                 |
| [valenceArousal](#valencearousal)                               | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/valenceArousal")                               |
| [vocal](#vocal)                                                 | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/vocal")                                                 |
| [voiceover](#voiceover)                                         | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-voiceoverv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/voiceover")                                         |

## audioFileInfo



`audioFileInfo`

* is required

* Type: `object` ([AudioFileInfoV1](taggingv8-defs-audiofileinfov1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-audiofileinfov1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/audioFileInfo")

### audioFileInfo Type

`object` ([AudioFileInfoV1](taggingv8-defs-audiofileinfov1.md))

## autoDescription



`autoDescription`

* is required

* Type: `object` ([AutoDescriptionV2](taggingv8-defs-autodescriptionv2.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-autodescriptionv2.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/autoDescription")

### autoDescription Type

`object` ([AutoDescriptionV2](taggingv8-defs-autodescriptionv2.md))

## bpm



`bpm`

* is required

* Type: `object` ([BpmV1](taggingv8-defs-bpmv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/bpm")

### bpm Type

`object` ([BpmV1](taggingv8-defs-bpmv1.md))

## character



`character`

* is required

* Type: `object` ([CharacterV1](taggingv8-defs-characterv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/character")

### character Type

`object` ([CharacterV1](taggingv8-defs-characterv1.md))

## freeGenre



`freeGenre`

* is required

* Type: `object` ([FreeGenreV2](taggingv8-defs-freegenrev2.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-freegenrev2.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/freeGenre")

### freeGenre Type

`object` ([FreeGenreV2](taggingv8-defs-freegenrev2.md))

## instrument



`instrument`

* is required

* Type: `object` ([InstrumentV1](taggingv8-defs-instrumentv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/instrument")

### instrument Type

`object` ([InstrumentV1](taggingv8-defs-instrumentv1.md))

## key



`key`

* is required

* Type: `object` ([KeyV1](taggingv8-defs-keyv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-keyv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/key")

### key Type

`object` ([KeyV1](taggingv8-defs-keyv1.md))

## mainGenre



`mainGenre`

* is required

* Type: `object` ([MaingenreV1](taggingv8-defs-maingenrev1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/mainGenre")

### mainGenre Type

`object` ([MaingenreV1](taggingv8-defs-maingenrev1.md))

## moodAdvanced



`moodAdvanced`

* is required

* Type: `object` ([MoodAdvancedV1](taggingv8-defs-moodadvancedv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/moodAdvanced")

### moodAdvanced Type

`object` ([MoodAdvancedV1](taggingv8-defs-moodadvancedv1.md))

## moodSimple



`moodSimple`

* is required

* Type: `object` ([MoodSimpleV1](taggingv8-defs-moodsimplev1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/moodSimple")

### moodSimple Type

`object` ([MoodSimpleV1](taggingv8-defs-moodsimplev1.md))

## movement



`movement`

* is required

* Type: `object` ([MovementV1](taggingv8-defs-movementv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/movement")

### movement Type

`object` ([MovementV1](taggingv8-defs-movementv1.md))

## musicalEra



`musicalEra`

* is required

* Type: `object` ([MusicalEraV1](taggingv8-defs-musicalerav1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-musicalerav1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/musicalEra")

### musicalEra Type

`object` ([MusicalEraV1](taggingv8-defs-musicalerav1.md))

## representativeSegmentIndex15s



`representativeSegmentIndex15s`

* is required

* Type: `object` ([RepresentativeSegmentIndex15sV1](taggingv8-defs-representativesegmentindex15sv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-representativesegmentindex15sv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/representativeSegmentIndex15s")

### representativeSegmentIndex15s Type

`object` ([RepresentativeSegmentIndex15sV1](taggingv8-defs-representativesegmentindex15sv1.md))

## subGenre



`subGenre`

* is required

* Type: `object` ([SubgenreV1](taggingv8-defs-subgenrev1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/subGenre")

### subGenre Type

`object` ([SubgenreV1](taggingv8-defs-subgenrev1.md))

## timeSignature



`timeSignature`

* is required

* Type: `object` ([TimeSignatureV1](taggingv8-defs-timesignaturev1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-timesignaturev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/timeSignature")

### timeSignature Type

`object` ([TimeSignatureV1](taggingv8-defs-timesignaturev1.md))

## timeStamps15s



`timeStamps15s`

* is required

* Type: `object` ([Timestamps15sV1](taggingv8-defs-timestamps15sv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-timestamps15sv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/timeStamps15s")

### timeStamps15s Type

`object` ([Timestamps15sV1](taggingv8-defs-timestamps15sv1.md))

## valenceArousal



`valenceArousal`

* is required

* Type: `object` ([ValenceArousalV1](taggingv8-defs-valencearousalv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/valenceArousal")

### valenceArousal Type

`object` ([ValenceArousalV1](taggingv8-defs-valencearousalv1.md))

## vocal



`vocal`

* is required

* Type: `object` ([VocalV1](taggingv8-defs-vocalv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/vocal")

### vocal Type

`object` ([VocalV1](taggingv8-defs-vocalv1.md))

## voiceover



`voiceover`

* is required

* Type: `object` ([VoiceoverV1](taggingv8-defs-voiceoverv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-voiceoverv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/voiceover")

### voiceover Type

`object` ([VoiceoverV1](taggingv8-defs-voiceoverv1.md))

# TaggingV8 Definitions

## Definitions group AudioFileInfoV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1"}
```

| Property                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                     |
| :------------------------ | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [duration](#duration)     | `number`  | Required | cannot be null | [TaggingV8](taggingv8-defs-audiofileinfov1-properties-duration.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/duration")     |
| [fileSizeB](#filesizeb)   | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-audiofileinfov1-properties-filesizeb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/fileSizeB")   |
| [bitrate](#bitrate)       | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-audiofileinfov1-properties-bitrate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/bitrate")       |
| [samplerate](#samplerate) | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-audiofileinfov1-properties-samplerate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/samplerate") |

### duration



`duration`

* is required

* Type: `number` ([Duration](taggingv8-defs-audiofileinfov1-properties-duration.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-audiofileinfov1-properties-duration.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/duration")

#### duration Type

`number` ([Duration](taggingv8-defs-audiofileinfov1-properties-duration.md))

### fileSizeB



`fileSizeB`

* is required

* Type: `integer` ([Filesizeb](taggingv8-defs-audiofileinfov1-properties-filesizeb.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-audiofileinfov1-properties-filesizeb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/fileSizeB")

#### fileSizeB Type

`integer` ([Filesizeb](taggingv8-defs-audiofileinfov1-properties-filesizeb.md))

### bitrate



`bitrate`

* is required

* Type: `integer` ([Bitrate](taggingv8-defs-audiofileinfov1-properties-bitrate.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-audiofileinfov1-properties-bitrate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/bitrate")

#### bitrate Type

`integer` ([Bitrate](taggingv8-defs-audiofileinfov1-properties-bitrate.md))

### samplerate



`samplerate`

* is required

* Type: `integer` ([Samplerate](taggingv8-defs-audiofileinfov1-properties-samplerate.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-audiofileinfov1-properties-samplerate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/samplerate")

#### samplerate Type

`integer` ([Samplerate](taggingv8-defs-audiofileinfov1-properties-samplerate.md))

## Definitions group AutoDescriptionV2

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AutoDescriptionV2"}
```

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                           |
| :-------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [description](#description) | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-autodescriptionv2-properties-description.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AutoDescriptionV2/properties/description") |

### description



`description`

* is required

* Type: `string` ([Description](taggingv8-defs-autodescriptionv2-properties-description.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-autodescriptionv2-properties-description.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AutoDescriptionV2/properties/description")

#### description Type

`string` ([Description](taggingv8-defs-autodescriptionv2-properties-description.md))

## Definitions group BpmV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1"}
```

| Property                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                       |
| :------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments)           | `array`   | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/segments")           |
| [segmentsRange](#segmentsrange) | `array`   | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-segmentsrange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/segmentsRange") |
| [tag](#tag)                     | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-tag.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/tag")                     |
| [tagRange](#tagrange)           | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-tagrange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/tagRange")           |
| [confidence](#confidence)       | `number`  | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/confidence")       |

### segments



`segments`

* is required

* Type: `integer[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/segments")

#### segments Type

`integer[]`

### segmentsRange



`segmentsRange`

* is required

* Type: `integer[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-segmentsrange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/segmentsRange")

#### segmentsRange Type

`integer[]`

### tag



`tag`

* is required

* Type: `integer` ([Tag](taggingv8-defs-bpmv1-properties-tag.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-tag.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/tag")

#### tag Type

`integer` ([Tag](taggingv8-defs-bpmv1-properties-tag.md))

#### tag Constraints

**maximum**: the value of this number must smaller than or equal to: `285`

**minimum**: the value of this number must greater than or equal to: `30`

### tagRange



`tagRange`

* is required

* Type: `integer` ([Tagrange](taggingv8-defs-bpmv1-properties-tagrange.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-tagrange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/tagRange")

#### tagRange Type

`integer` ([Tagrange](taggingv8-defs-bpmv1-properties-tagrange.md))

#### tagRange Constraints

**maximum**: the value of this number must smaller than or equal to: `180`

**minimum**: the value of this number must greater than or equal to: `60`

### confidence



`confidence`

* is required

* Type: `number` ([Confidence](taggingv8-defs-bpmv1-properties-confidence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/confidence")

#### confidence Type

`number` ([Confidence](taggingv8-defs-bpmv1-properties-confidence.md))

#### confidence Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## Definitions group CharacterScoresV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1"}
```

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                               |
| :------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bold](#bold)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-bold.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/bold")                   |
| [cool](#cool)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-cool.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/cool")                   |
| [epic](#epic)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/epic")                   |
| [ethereal](#ethereal)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/ethereal")           |
| [heroic](#heroic)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-heroic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/heroic")               |
| [luxurious](#luxurious)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-luxurious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/luxurious")         |
| [magical](#magical)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-magical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/magical")             |
| [mysterious](#mysterious)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-mysterious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/mysterious")       |
| [playful](#playful)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-playful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/playful")             |
| [powerful](#powerful)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-powerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/powerful")           |
| [retro](#retro)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-retro.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/retro")                 |
| [sophisticated](#sophisticated) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-sophisticated.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/sophisticated") |
| [sparkling](#sparkling)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-sparkling.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/sparkling")         |
| [sparse](#sparse)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-sparse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/sparse")               |
| [unpolished](#unpolished)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-unpolished.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/unpolished")       |
| [warm](#warm)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-characterscoresv1-properties-warm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/warm")                   |

### bold



`bold`

* is required

* Type: `number` ([Bold](taggingv8-defs-characterscoresv1-properties-bold.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-bold.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/bold")

#### bold Type

`number` ([Bold](taggingv8-defs-characterscoresv1-properties-bold.md))

#### bold Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### cool



`cool`

* is required

* Type: `number` ([Cool](taggingv8-defs-characterscoresv1-properties-cool.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-cool.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/cool")

#### cool Type

`number` ([Cool](taggingv8-defs-characterscoresv1-properties-cool.md))

#### cool Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### epic



`epic`

* is required

* Type: `number` ([Epic](taggingv8-defs-characterscoresv1-properties-epic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/epic")

#### epic Type

`number` ([Epic](taggingv8-defs-characterscoresv1-properties-epic.md))

#### epic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### ethereal



`ethereal`

* is required

* Type: `number` ([Ethereal](taggingv8-defs-characterscoresv1-properties-ethereal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/ethereal")

#### ethereal Type

`number` ([Ethereal](taggingv8-defs-characterscoresv1-properties-ethereal.md))

#### ethereal Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### heroic



`heroic`

* is required

* Type: `number` ([Heroic](taggingv8-defs-characterscoresv1-properties-heroic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-heroic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/heroic")

#### heroic Type

`number` ([Heroic](taggingv8-defs-characterscoresv1-properties-heroic.md))

#### heroic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### luxurious



`luxurious`

* is required

* Type: `number` ([Luxurious](taggingv8-defs-characterscoresv1-properties-luxurious.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-luxurious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/luxurious")

#### luxurious Type

`number` ([Luxurious](taggingv8-defs-characterscoresv1-properties-luxurious.md))

#### luxurious Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### magical



`magical`

* is required

* Type: `number` ([Magical](taggingv8-defs-characterscoresv1-properties-magical.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-magical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/magical")

#### magical Type

`number` ([Magical](taggingv8-defs-characterscoresv1-properties-magical.md))

#### magical Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### mysterious



`mysterious`

* is required

* Type: `number` ([Mysterious](taggingv8-defs-characterscoresv1-properties-mysterious.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-mysterious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/mysterious")

#### mysterious Type

`number` ([Mysterious](taggingv8-defs-characterscoresv1-properties-mysterious.md))

#### mysterious Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### playful



`playful`

* is required

* Type: `number` ([Playful](taggingv8-defs-characterscoresv1-properties-playful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-playful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/playful")

#### playful Type

`number` ([Playful](taggingv8-defs-characterscoresv1-properties-playful.md))

#### playful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### powerful



`powerful`

* is required

* Type: `number` ([Powerful](taggingv8-defs-characterscoresv1-properties-powerful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-powerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/powerful")

#### powerful Type

`number` ([Powerful](taggingv8-defs-characterscoresv1-properties-powerful.md))

#### powerful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### retro



`retro`

* is required

* Type: `number` ([Retro](taggingv8-defs-characterscoresv1-properties-retro.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-retro.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/retro")

#### retro Type

`number` ([Retro](taggingv8-defs-characterscoresv1-properties-retro.md))

#### retro Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sophisticated



`sophisticated`

* is required

* Type: `number` ([Sophisticated](taggingv8-defs-characterscoresv1-properties-sophisticated.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-sophisticated.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/sophisticated")

#### sophisticated Type

`number` ([Sophisticated](taggingv8-defs-characterscoresv1-properties-sophisticated.md))

#### sophisticated Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sparkling



`sparkling`

* is required

* Type: `number` ([Sparkling](taggingv8-defs-characterscoresv1-properties-sparkling.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-sparkling.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/sparkling")

#### sparkling Type

`number` ([Sparkling](taggingv8-defs-characterscoresv1-properties-sparkling.md))

#### sparkling Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sparse



`sparse`

* is required

* Type: `number` ([Sparse](taggingv8-defs-characterscoresv1-properties-sparse.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-sparse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/sparse")

#### sparse Type

`number` ([Sparse](taggingv8-defs-characterscoresv1-properties-sparse.md))

#### sparse Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### unpolished



`unpolished`

* is required

* Type: `number` ([Unpolished](taggingv8-defs-characterscoresv1-properties-unpolished.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-unpolished.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/unpolished")

#### unpolished Type

`number` ([Unpolished](taggingv8-defs-characterscoresv1-properties-unpolished.md))

#### unpolished Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### warm



`warm`

* is required

* Type: `number` ([Warm](taggingv8-defs-characterscoresv1-properties-warm.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterscoresv1-properties-warm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterScoresV1/properties/warm")

#### warm Type

`number` ([Warm](taggingv8-defs-characterscoresv1-properties-warm.md))

#### warm Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## Definitions group CharacterSegmentsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1"}
```

| Property                          | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :-------------------------------- | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bold](#bold-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-bold.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/bold")                   |
| [cool](#cool-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-cool.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/cool")                   |
| [epic](#epic-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/epic")                   |
| [ethereal](#ethereal-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/ethereal")           |
| [heroic](#heroic-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-heroic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/heroic")               |
| [luxurious](#luxurious-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-luxurious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/luxurious")         |
| [magical](#magical-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-magical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/magical")             |
| [mysterious](#mysterious-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-mysterious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/mysterious")       |
| [playful](#playful-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-playful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/playful")             |
| [powerful](#powerful-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-powerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/powerful")           |
| [retro](#retro-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-retro.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/retro")                 |
| [sophisticated](#sophisticated-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-sophisticated.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/sophisticated") |
| [sparkling](#sparkling-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-sparkling.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/sparkling")         |
| [sparse](#sparse-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-sparse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/sparse")               |
| [unpolished](#unpolished-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-unpolished.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/unpolished")       |
| [warm](#warm-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-warm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/warm")                   |

### bold



`bold`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-bold.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/bold")

#### bold Type

`number[]`

### cool



`cool`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-cool.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/cool")

#### cool Type

`number[]`

### epic



`epic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/epic")

#### epic Type

`number[]`

### ethereal



`ethereal`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/ethereal")

#### ethereal Type

`number[]`

### heroic



`heroic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-heroic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/heroic")

#### heroic Type

`number[]`

### luxurious



`luxurious`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-luxurious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/luxurious")

#### luxurious Type

`number[]`

### magical



`magical`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-magical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/magical")

#### magical Type

`number[]`

### mysterious



`mysterious`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-mysterious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/mysterious")

#### mysterious Type

`number[]`

### playful



`playful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-playful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/playful")

#### playful Type

`number[]`

### powerful



`powerful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-powerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/powerful")

#### powerful Type

`number[]`

### retro



`retro`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-retro.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/retro")

#### retro Type

`number[]`

### sophisticated



`sophisticated`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-sophisticated.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/sophisticated")

#### sophisticated Type

`number[]`

### sparkling



`sparkling`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-sparkling.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/sparkling")

#### sparkling Type

`number[]`

### sparse



`sparse`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-sparse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/sparse")

#### sparse Type

`number[]`

### unpolished



`unpolished`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-unpolished.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/unpolished")

#### unpolished Type

`number[]`

### warm



`warm`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1-properties-warm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterSegmentsV1/properties/warm")

#### warm Type

`number[]`

## Definitions group CharacterTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group CharacterV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterV1"}
```

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                     |
| :---------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-1) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-charactersegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterV1/properties/segments")         |
| [scores](#scores)       | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-characterv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterV1/properties/scores") |
| [tags](#tags)           | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-characterv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterV1/properties/tags")     |

### segments



`segments`

* is required

* Type: `object` ([CharacterSegmentsV1](taggingv8-defs-charactersegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-charactersegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterV1/properties/segments")

#### segments Type

`object` ([CharacterSegmentsV1](taggingv8-defs-charactersegmentsv1.md))

### scores



`scores`

* is required

* Type: merged type ([Details](taggingv8-defs-characterv1-properties-scores.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterV1/properties/scores")

#### scores Type

merged type ([Details](taggingv8-defs-characterv1-properties-scores.md))

any of

* [CharacterScoresV1](taggingv8-defs-characterscoresv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-characterv1-properties-scores-anyof-1.md "check type definition")

### tags



`tags`

* is required

* Type: merged type ([Tags](taggingv8-defs-characterv1-properties-tags.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-characterv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/CharacterV1/properties/tags")

#### tags Type

merged type ([Tags](taggingv8-defs-characterv1-properties-tags.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-characterv1-properties-tags-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-characterv1-properties-tags-anyof-1.md "check type definition")

## Definitions group EmotionChangesTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/EmotionChangesTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group EmotionProfileTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/EmotionProfileTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group EnergyChangesTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/EnergyChangesTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group EnergyLevelTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/EnergyLevelTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group FreeGenreV2

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/FreeGenreV2"}
```

| Property        | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                 |
| :-------------- | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [tags](#tags-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-freegenrev2-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/FreeGenreV2/properties/tags") |

### tags



`tags`

* is required

* Type: `string[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-freegenrev2-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/FreeGenreV2/properties/tags")

#### tags Type

`string[]`

## Definitions group InstrumentPresenceV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1"}
```

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                            |
| :-------------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [accordion](#accordion)                 | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/accordion")           |
| [acousticGuitar](#acousticguitar)       | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/acousticGuitar")    |
| [africanPercussion](#africanpercussion) | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-2.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/africanPercussion") |
| [asianFlute](#asianflute)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-3.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/asianFlute")        |
| [asianStrings](#asianstrings)           | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-4.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/asianStrings")      |
| [banjo](#banjo)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-5.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/banjo")             |
| [bassGuitar](#bassguitar)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-6.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/bassGuitar")        |
| [bells](#bells)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-7.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/bells")             |
| [bongoConga](#bongoconga)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/bongoConga")        |
| [brass](#brass)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-9.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/brass")             |
| [celeste](#celeste)                     | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-10.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/celeste")          |
| [cello](#cello)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-11.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/cello")            |
| [clarinet](#clarinet)                   | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-12.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/clarinet")         |
| [doubleBass](#doublebass)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-13.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/doubleBass")       |
| [drumKit](#drumkit)                     | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-14.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/drumKit")          |
| [electricGuitar](#electricguitar)       | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-15.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/electricGuitar")   |
| [electricOrgan](#electricorgan)         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-16.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/electricOrgan")    |
| [electricPiano](#electricpiano)         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-17.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/electricPiano")    |
| [electronicDrums](#electronicdrums)     | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-18.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/electronicDrums")  |
| [flute](#flute)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-19.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/flute")            |
| [frenchHorn](#frenchhorn)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-20.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/frenchHorn")       |
| [harp](#harp)                           | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-21.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/harp")             |
| [harpsichord](#harpsichord)             | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-22.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/harpsichord")      |
| [luteOud](#luteoud)                     | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-23.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/luteOud")          |
| [mandolin](#mandolin)                   | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-24.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/mandolin")         |
| [marimba](#marimba)                     | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-25.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/marimba")          |
| [oboe](#oboe)                           | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-26.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/oboe")             |
| [churchOrgan](#churchorgan)             | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-27.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/churchOrgan")      |
| [piano](#piano)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-28.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/piano")            |
| [pizzicato](#pizzicato)                 | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-29.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/pizzicato")        |
| [saxophone](#saxophone)                 | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-30.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/saxophone")        |
| [sitar](#sitar)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-31.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/sitar")            |
| [steelDrums](#steeldrums)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-32.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/steelDrums")       |
| [strings](#strings)                     | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-33.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/strings")          |
| [synth](#synth)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-34.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/synth")            |
| [tabla](#tabla)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-35.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/tabla")            |
| [taiko](#taiko)                         | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-36.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/taiko")            |
| [trumpet](#trumpet)                     | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-37.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/trumpet")          |
| [tuba](#tuba)                           | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-38.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/tuba")             |
| [ukulele](#ukulele)                     | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-39.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/ukulele")          |
| [vibraphone](#vibraphone)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-40.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/vibraphone")       |
| [violin](#violin)                       | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-41.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/violin")           |
| [woodwinds](#woodwinds)                 | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-42.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/woodwinds")        |
| [glockenspiel](#glockenspiel)           | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-43.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/glockenspiel")     |
| [percussion](#percussion)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-44.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/percussion")       |
| [bass](#bass)                           | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-45.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/bass")             |

### accordion



`accordion`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/accordion")

#### accordion Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1.md))

#### accordion Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### acousticGuitar



`acousticGuitar`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/acousticGuitar")

#### acousticGuitar Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-1.md))

#### acousticGuitar Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### africanPercussion



`africanPercussion`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-2.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-2.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/africanPercussion")

#### africanPercussion Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-2.md))

#### africanPercussion Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### asianFlute



`asianFlute`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-3.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-3.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/asianFlute")

#### asianFlute Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-3.md))

#### asianFlute Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### asianStrings



`asianStrings`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-4.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-4.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/asianStrings")

#### asianStrings Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-4.md))

#### asianStrings Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### banjo



`banjo`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-5.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-5.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/banjo")

#### banjo Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-5.md))

#### banjo Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### bassGuitar



`bassGuitar`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-6.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-6.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/bassGuitar")

#### bassGuitar Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-6.md))

#### bassGuitar Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### bells



`bells`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-7.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-7.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/bells")

#### bells Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-7.md))

#### bells Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### bongoConga



`bongoConga`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-8.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/bongoConga")

#### bongoConga Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-8.md))

#### bongoConga Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### brass



`brass`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-9.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-9.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/brass")

#### brass Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-9.md))

#### brass Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### celeste



`celeste`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-10.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-10.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/celeste")

#### celeste Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-10.md))

#### celeste Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### cello



`cello`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-11.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-11.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/cello")

#### cello Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-11.md))

#### cello Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### clarinet



`clarinet`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-12.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-12.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/clarinet")

#### clarinet Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-12.md))

#### clarinet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### doubleBass



`doubleBass`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-13.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-13.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/doubleBass")

#### doubleBass Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-13.md))

#### doubleBass Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### drumKit



`drumKit`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-14.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-14.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/drumKit")

#### drumKit Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-14.md))

#### drumKit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### electricGuitar



`electricGuitar`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-15.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-15.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/electricGuitar")

#### electricGuitar Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-15.md))

#### electricGuitar Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### electricOrgan



`electricOrgan`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-16.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-16.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/electricOrgan")

#### electricOrgan Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-16.md))

#### electricOrgan Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### electricPiano



`electricPiano`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-17.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-17.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/electricPiano")

#### electricPiano Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-17.md))

#### electricPiano Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### electronicDrums



`electronicDrums`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-18.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-18.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/electronicDrums")

#### electronicDrums Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-18.md))

#### electronicDrums Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### flute



`flute`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-19.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-19.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/flute")

#### flute Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-19.md))

#### flute Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### frenchHorn



`frenchHorn`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-20.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-20.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/frenchHorn")

#### frenchHorn Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-20.md))

#### frenchHorn Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### harp



`harp`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-21.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-21.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/harp")

#### harp Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-21.md))

#### harp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### harpsichord



`harpsichord`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-22.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-22.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/harpsichord")

#### harpsichord Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-22.md))

#### harpsichord Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### luteOud



`luteOud`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-23.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-23.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/luteOud")

#### luteOud Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-23.md))

#### luteOud Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### mandolin



`mandolin`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-24.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-24.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/mandolin")

#### mandolin Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-24.md))

#### mandolin Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### marimba



`marimba`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-25.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-25.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/marimba")

#### marimba Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-25.md))

#### marimba Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### oboe



`oboe`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-26.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-26.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/oboe")

#### oboe Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-26.md))

#### oboe Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### churchOrgan



`churchOrgan`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-27.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-27.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/churchOrgan")

#### churchOrgan Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-27.md))

#### churchOrgan Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### piano



`piano`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-28.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-28.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/piano")

#### piano Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-28.md))

#### piano Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### pizzicato



`pizzicato`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-29.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-29.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/pizzicato")

#### pizzicato Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-29.md))

#### pizzicato Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### saxophone



`saxophone`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-30.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-30.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/saxophone")

#### saxophone Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-30.md))

#### saxophone Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### sitar



`sitar`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-31.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-31.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/sitar")

#### sitar Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-31.md))

#### sitar Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### steelDrums



`steelDrums`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-32.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-32.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/steelDrums")

#### steelDrums Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-32.md))

#### steelDrums Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### strings



`strings`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-33.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-33.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/strings")

#### strings Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-33.md))

#### strings Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### synth



`synth`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-34.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-34.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/synth")

#### synth Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-34.md))

#### synth Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### tabla



`tabla`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-35.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-35.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/tabla")

#### tabla Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-35.md))

#### tabla Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### taiko



`taiko`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-36.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-36.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/taiko")

#### taiko Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-36.md))

#### taiko Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### trumpet



`trumpet`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-37.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-37.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/trumpet")

#### trumpet Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-37.md))

#### trumpet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### tuba



`tuba`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-38.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-38.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/tuba")

#### tuba Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-38.md))

#### tuba Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### ukulele



`ukulele`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-39.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-39.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/ukulele")

#### ukulele Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-39.md))

#### ukulele Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### vibraphone



`vibraphone`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-40.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-40.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/vibraphone")

#### vibraphone Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-40.md))

#### vibraphone Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### violin



`violin`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-41.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-41.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/violin")

#### violin Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-41.md))

#### violin Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### woodwinds



`woodwinds`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-42.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-42.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/woodwinds")

#### woodwinds Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-42.md))

#### woodwinds Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### glockenspiel



`glockenspiel`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-43.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-43.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/glockenspiel")

#### glockenspiel Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-43.md))

#### glockenspiel Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### percussion



`percussion`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-44.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-44.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/percussion")

#### percussion Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-44.md))

#### percussion Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

### bass



`bass`

* is required

* Type: `string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-45.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-45.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentPresenceV1/properties/bass")

#### bass Type

`string` ([PresenceTagsV1](taggingv8-defs-instrumentpresencev1-properties-presencetagsv1-45.md))

#### bass Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"absent"`     |             |
| `"present"`    |             |
| `"partially"`  |             |
| `"frequently"` |             |
| `"throughout"` |             |

## Definitions group InstrumentSegmentsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1"}
```

| Property                                  | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                             |
| :---------------------------------------- | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [accordion](#accordion-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-accordion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/accordion")                 |
| [acousticGuitar](#acousticguitar-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-acousticguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/acousticGuitar")       |
| [africanPercussion](#africanpercussion-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-africanpercussion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/africanPercussion") |
| [asianFlute](#asianflute-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-asianflute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/asianFlute")               |
| [asianStrings](#asianstrings-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-asianstrings.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/asianStrings")           |
| [banjo](#banjo-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-banjo.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/banjo")                         |
| [bassGuitar](#bassguitar-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bassguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bassGuitar")               |
| [bells](#bells-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bells.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bells")                         |
| [bongoConga](#bongoconga-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bongoconga.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bongoConga")               |
| [brass](#brass-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-brass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/brass")                         |
| [celeste](#celeste-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-celeste.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/celeste")                     |
| [cello](#cello-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-cello.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/cello")                         |
| [clarinet](#clarinet-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-clarinet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/clarinet")                   |
| [doubleBass](#doublebass-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-doublebass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/doubleBass")               |
| [drumKit](#drumkit-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-drumkit.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/drumKit")                     |
| [electricGuitar](#electricguitar-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricGuitar")       |
| [electricOrgan](#electricorgan-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricorgan.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricOrgan")         |
| [electricPiano](#electricpiano-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricpiano.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricPiano")         |
| [electronicDrums](#electronicdrums-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electronicdrums.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electronicDrums")     |
| [flute](#flute-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-flute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/flute")                         |
| [frenchHorn](#frenchhorn-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-frenchhorn.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/frenchHorn")               |
| [harp](#harp-1)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-harp.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/harp")                           |
| [harpsichord](#harpsichord-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-harpsichord.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/harpsichord")             |
| [luteOud](#luteoud-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-luteoud.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/luteOud")                     |
| [mandolin](#mandolin-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-mandolin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/mandolin")                   |
| [marimba](#marimba-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-marimba.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/marimba")                     |
| [oboe](#oboe-1)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-oboe.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/oboe")                           |
| [churchOrgan](#churchorgan-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-churchorgan.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/churchOrgan")             |
| [piano](#piano-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-piano.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/piano")                         |
| [pizzicato](#pizzicato-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-pizzicato.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/pizzicato")                 |
| [saxophone](#saxophone-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-saxophone.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/saxophone")                 |
| [sitar](#sitar-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-sitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/sitar")                         |
| [steelDrums](#steeldrums-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-steeldrums.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/steelDrums")               |
| [strings](#strings-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-strings.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/strings")                     |
| [synth](#synth-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-synth.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/synth")                         |
| [tabla](#tabla-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-tabla.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/tabla")                         |
| [taiko](#taiko-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-taiko.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/taiko")                         |
| [trumpet](#trumpet-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-trumpet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/trumpet")                     |
| [tuba](#tuba-1)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-tuba.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/tuba")                           |
| [ukulele](#ukulele-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-ukulele.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/ukulele")                     |
| [vibraphone](#vibraphone-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-vibraphone.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/vibraphone")               |
| [violin](#violin-1)                       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-violin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/violin")                       |
| [woodwinds](#woodwinds-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-woodwinds.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/woodwinds")                 |
| [glockenspiel](#glockenspiel-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-glockenspiel.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/glockenspiel")           |
| [percussion](#percussion-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-percussion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/percussion")               |
| [bass](#bass-1)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bass")                           |

### accordion



`accordion`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-accordion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/accordion")

#### accordion Type

`number[]`

### acousticGuitar



`acousticGuitar`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-acousticguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/acousticGuitar")

#### acousticGuitar Type

`number[]`

### africanPercussion



`africanPercussion`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-africanpercussion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/africanPercussion")

#### africanPercussion Type

`number[]`

### asianFlute



`asianFlute`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-asianflute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/asianFlute")

#### asianFlute Type

`number[]`

### asianStrings



`asianStrings`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-asianstrings.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/asianStrings")

#### asianStrings Type

`number[]`

### banjo



`banjo`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-banjo.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/banjo")

#### banjo Type

`number[]`

### bassGuitar



`bassGuitar`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bassguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bassGuitar")

#### bassGuitar Type

`number[]`

### bells



`bells`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bells.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bells")

#### bells Type

`number[]`

### bongoConga



`bongoConga`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bongoconga.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bongoConga")

#### bongoConga Type

`number[]`

### brass



`brass`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-brass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/brass")

#### brass Type

`number[]`

### celeste



`celeste`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-celeste.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/celeste")

#### celeste Type

`number[]`

### cello



`cello`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-cello.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/cello")

#### cello Type

`number[]`

### clarinet



`clarinet`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-clarinet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/clarinet")

#### clarinet Type

`number[]`

### doubleBass



`doubleBass`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-doublebass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/doubleBass")

#### doubleBass Type

`number[]`

### drumKit



`drumKit`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-drumkit.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/drumKit")

#### drumKit Type

`number[]`

### electricGuitar



`electricGuitar`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricGuitar")

#### electricGuitar Type

`number[]`

### electricOrgan



`electricOrgan`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricorgan.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricOrgan")

#### electricOrgan Type

`number[]`

### electricPiano



`electricPiano`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricpiano.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricPiano")

#### electricPiano Type

`number[]`

### electronicDrums



`electronicDrums`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electronicdrums.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electronicDrums")

#### electronicDrums Type

`number[]`

### flute



`flute`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-flute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/flute")

#### flute Type

`number[]`

### frenchHorn



`frenchHorn`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-frenchhorn.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/frenchHorn")

#### frenchHorn Type

`number[]`

### harp



`harp`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-harp.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/harp")

#### harp Type

`number[]`

### harpsichord



`harpsichord`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-harpsichord.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/harpsichord")

#### harpsichord Type

`number[]`

### luteOud



`luteOud`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-luteoud.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/luteOud")

#### luteOud Type

`number[]`

### mandolin



`mandolin`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-mandolin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/mandolin")

#### mandolin Type

`number[]`

### marimba



`marimba`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-marimba.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/marimba")

#### marimba Type

`number[]`

### oboe



`oboe`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-oboe.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/oboe")

#### oboe Type

`number[]`

### churchOrgan



`churchOrgan`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-churchorgan.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/churchOrgan")

#### churchOrgan Type

`number[]`

### piano



`piano`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-piano.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/piano")

#### piano Type

`number[]`

### pizzicato



`pizzicato`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-pizzicato.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/pizzicato")

#### pizzicato Type

`number[]`

### saxophone



`saxophone`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-saxophone.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/saxophone")

#### saxophone Type

`number[]`

### sitar



`sitar`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-sitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/sitar")

#### sitar Type

`number[]`

### steelDrums



`steelDrums`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-steeldrums.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/steelDrums")

#### steelDrums Type

`number[]`

### strings



`strings`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-strings.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/strings")

#### strings Type

`number[]`

### synth



`synth`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-synth.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/synth")

#### synth Type

`number[]`

### tabla



`tabla`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-tabla.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/tabla")

#### tabla Type

`number[]`

### taiko



`taiko`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-taiko.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/taiko")

#### taiko Type

`number[]`

### trumpet



`trumpet`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-trumpet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/trumpet")

#### trumpet Type

`number[]`

### tuba



`tuba`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-tuba.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/tuba")

#### tuba Type

`number[]`

### ukulele



`ukulele`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-ukulele.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/ukulele")

#### ukulele Type

`number[]`

### vibraphone



`vibraphone`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-vibraphone.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/vibraphone")

#### vibraphone Type

`number[]`

### violin



`violin`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-violin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/violin")

#### violin Type

`number[]`

### woodwinds



`woodwinds`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-woodwinds.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/woodwinds")

#### woodwinds Type

`number[]`

### glockenspiel



`glockenspiel`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-glockenspiel.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/glockenspiel")

#### glockenspiel Type

`number[]`

### percussion



`percussion`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-percussion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/percussion")

#### percussion Type

`number[]`

### bass



`bass`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bass")

#### bass Type

`number[]`

## Definitions group InstrumentTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group InstrumentV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1"}
```

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                   |
| :---------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-2) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/segments")     |
| [presence](#presence)   | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/presence")     |
| [tags](#tags-2)         | `array`  | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/tags") |

### segments



`segments`

* is required

* Type: `object` ([InstrumentSegmentsV1](taggingv8-defs-instrumentsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/segments")

#### segments Type

`object` ([InstrumentSegmentsV1](taggingv8-defs-instrumentsegmentsv1.md))

### presence



`presence`

* is required

* Type: `object` ([InstrumentPresenceV1](taggingv8-defs-instrumentpresencev1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/presence")

#### presence Type

`object` ([InstrumentPresenceV1](taggingv8-defs-instrumentpresencev1.md))

### tags



`tags`

* is required

* Type: `string[]` ([InstrumentTagsV1](taggingv8-defs-instrumentv1-properties-tags-instrumenttagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/tags")

#### tags Type

`string[]` ([InstrumentTagsV1](taggingv8-defs-instrumentv1-properties-tags-instrumenttagsv1.md))

## Definitions group KeyTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group KeyV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1"}
```

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                 |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-3)     | `array`  | Required | cannot be null | [TaggingV8](taggingv8-defs-keyv1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/segments")     |
| [tag](#tag-1)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-keyv1-properties-keytagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/tag")         |
| [confidence](#confidence-1) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-keyv1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/confidence") |

### segments



`segments`

* is required

* Type: `string[]` ([KeyTagsV1](taggingv8-defs-keyv1-properties-segments-keytagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-keyv1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/segments")

#### segments Type

`string[]` ([KeyTagsV1](taggingv8-defs-keyv1-properties-segments-keytagsv1.md))

### tag



`tag`

* is required

* Type: `string` ([KeyTagsV1](taggingv8-defs-keyv1-properties-keytagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-keyv1-properties-keytagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/tag")

#### tag Type

`string` ([KeyTagsV1](taggingv8-defs-keyv1-properties-keytagsv1.md))

#### tag Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"aMajor"`      |             |
| `"aMinor"`      |             |
| `"bMajor"`      |             |
| `"bMinor"`      |             |
| `"bFlatMajor"`  |             |
| `"bFlatMinor"`  |             |
| `"cMajor"`      |             |
| `"cMinor"`      |             |
| `"dFlatMajor"`  |             |
| `"cSharpMinor"` |             |
| `"dMajor"`      |             |
| `"dMinor"`      |             |
| `"eFlatMajor"`  |             |
| `"dSharpMinor"` |             |
| `"eMajor"`      |             |
| `"eMinor"`      |             |
| `"fMajor"`      |             |
| `"fMinor"`      |             |
| `"fSharpMajor"` |             |
| `"fSharpMinor"` |             |
| `"gMajor"`      |             |
| `"gMinor"`      |             |
| `"aFlatMajor"`  |             |
| `"gSharpMinor"` |             |

### confidence



`confidence`

* is required

* Type: `number` ([Confidence](taggingv8-defs-keyv1-properties-confidence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-keyv1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/confidence")

#### confidence Type

`number` ([Confidence](taggingv8-defs-keyv1-properties-confidence.md))

#### confidence Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## Definitions group MaingenreScoresV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1"}
```

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                     |
| :------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [african](#african)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-african.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/african")                   |
| [ambient](#ambient)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-ambient.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/ambient")                   |
| [middleEastern](#middleeastern)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-middleeastern.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/middleEastern")       |
| [asian](#asian)                       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-asian.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/asian")                       |
| [blues](#blues)                       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-blues.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/blues")                       |
| [childrenJingle](#childrenjingle)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-childrenjingle.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/childrenJingle")     |
| [classical](#classical)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-classical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/classical")               |
| [electronic](#electronic)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-electronic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/electronic")             |
| [folkCountry](#folkcountry)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-folkcountry.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/folkCountry")           |
| [funkSoul](#funksoul)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-funksoul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/funkSoul")                 |
| [indian](#indian)                     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-indian.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/indian")                     |
| [jazz](#jazz)                         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-jazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/jazz")                         |
| [latin](#latin)                       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-latin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/latin")                       |
| [metal](#metal)                       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-metal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/metal")                       |
| [pop](#pop)                           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-pop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/pop")                           |
| [rapHipHop](#raphiphop)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-raphiphop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/rapHipHop")               |
| [reggae](#reggae)                     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-reggae.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/reggae")                     |
| [rnb](#rnb)                           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-rnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/rnb")                           |
| [rock](#rock)                         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-rock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/rock")                         |
| [singerSongwriter](#singersongwriter) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-singersongwriter.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/singerSongwriter") |
| [sound](#sound)                       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-sound.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/sound")                       |
| [soundtrack](#soundtrack)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-soundtrack.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/soundtrack")             |
| [spokenWord](#spokenword)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-spokenword.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/spokenWord")             |

### african



`african`

* is required

* Type: `number` ([African](taggingv8-defs-maingenrescoresv1-properties-african.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-african.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/african")

#### african Type

`number` ([African](taggingv8-defs-maingenrescoresv1-properties-african.md))

#### african Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### ambient



`ambient`

* is required

* Type: `number` ([Ambient](taggingv8-defs-maingenrescoresv1-properties-ambient.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-ambient.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/ambient")

#### ambient Type

`number` ([Ambient](taggingv8-defs-maingenrescoresv1-properties-ambient.md))

#### ambient Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### middleEastern



`middleEastern`

* is required

* Type: `number` ([Middleeastern](taggingv8-defs-maingenrescoresv1-properties-middleeastern.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-middleeastern.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/middleEastern")

#### middleEastern Type

`number` ([Middleeastern](taggingv8-defs-maingenrescoresv1-properties-middleeastern.md))

#### middleEastern Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### asian



`asian`

* is required

* Type: `number` ([Asian](taggingv8-defs-maingenrescoresv1-properties-asian.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-asian.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/asian")

#### asian Type

`number` ([Asian](taggingv8-defs-maingenrescoresv1-properties-asian.md))

#### asian Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### blues



`blues`

* is required

* Type: `number` ([Blues](taggingv8-defs-maingenrescoresv1-properties-blues.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-blues.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/blues")

#### blues Type

`number` ([Blues](taggingv8-defs-maingenrescoresv1-properties-blues.md))

#### blues Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### childrenJingle



`childrenJingle`

* is required

* Type: `number` ([Childrenjingle](taggingv8-defs-maingenrescoresv1-properties-childrenjingle.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-childrenjingle.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/childrenJingle")

#### childrenJingle Type

`number` ([Childrenjingle](taggingv8-defs-maingenrescoresv1-properties-childrenjingle.md))

#### childrenJingle Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### classical



`classical`

* is required

* Type: `number` ([Classical](taggingv8-defs-maingenrescoresv1-properties-classical.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-classical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/classical")

#### classical Type

`number` ([Classical](taggingv8-defs-maingenrescoresv1-properties-classical.md))

#### classical Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### electronic



`electronic`

* is required

* Type: `number` ([Electronic](taggingv8-defs-maingenrescoresv1-properties-electronic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-electronic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/electronic")

#### electronic Type

`number` ([Electronic](taggingv8-defs-maingenrescoresv1-properties-electronic.md))

#### electronic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### folkCountry



`folkCountry`

* is required

* Type: `number` ([Folkcountry](taggingv8-defs-maingenrescoresv1-properties-folkcountry.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-folkcountry.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/folkCountry")

#### folkCountry Type

`number` ([Folkcountry](taggingv8-defs-maingenrescoresv1-properties-folkcountry.md))

#### folkCountry Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### funkSoul



`funkSoul`

* is required

* Type: `number` ([Funksoul](taggingv8-defs-maingenrescoresv1-properties-funksoul.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-funksoul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/funkSoul")

#### funkSoul Type

`number` ([Funksoul](taggingv8-defs-maingenrescoresv1-properties-funksoul.md))

#### funkSoul Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### indian



`indian`

* is required

* Type: `number` ([Indian](taggingv8-defs-maingenrescoresv1-properties-indian.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-indian.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/indian")

#### indian Type

`number` ([Indian](taggingv8-defs-maingenrescoresv1-properties-indian.md))

#### indian Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### jazz



`jazz`

* is required

* Type: `number` ([Jazz](taggingv8-defs-maingenrescoresv1-properties-jazz.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-jazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/jazz")

#### jazz Type

`number` ([Jazz](taggingv8-defs-maingenrescoresv1-properties-jazz.md))

#### jazz Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### latin



`latin`

* is required

* Type: `number` ([Latin](taggingv8-defs-maingenrescoresv1-properties-latin.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-latin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/latin")

#### latin Type

`number` ([Latin](taggingv8-defs-maingenrescoresv1-properties-latin.md))

#### latin Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### metal



`metal`

* is required

* Type: `number` ([Metal](taggingv8-defs-maingenrescoresv1-properties-metal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-metal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/metal")

#### metal Type

`number` ([Metal](taggingv8-defs-maingenrescoresv1-properties-metal.md))

#### metal Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### pop



`pop`

* is required

* Type: `number` ([Pop](taggingv8-defs-maingenrescoresv1-properties-pop.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-pop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/pop")

#### pop Type

`number` ([Pop](taggingv8-defs-maingenrescoresv1-properties-pop.md))

#### pop Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### rapHipHop



`rapHipHop`

* is required

* Type: `number` ([Raphiphop](taggingv8-defs-maingenrescoresv1-properties-raphiphop.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-raphiphop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/rapHipHop")

#### rapHipHop Type

`number` ([Raphiphop](taggingv8-defs-maingenrescoresv1-properties-raphiphop.md))

#### rapHipHop Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### reggae



`reggae`

* is required

* Type: `number` ([Reggae](taggingv8-defs-maingenrescoresv1-properties-reggae.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-reggae.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/reggae")

#### reggae Type

`number` ([Reggae](taggingv8-defs-maingenrescoresv1-properties-reggae.md))

#### reggae Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### rnb



`rnb`

* is required

* Type: `number` ([Rnb](taggingv8-defs-maingenrescoresv1-properties-rnb.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-rnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/rnb")

#### rnb Type

`number` ([Rnb](taggingv8-defs-maingenrescoresv1-properties-rnb.md))

#### rnb Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### rock



`rock`

* is required

* Type: `number` ([Rock](taggingv8-defs-maingenrescoresv1-properties-rock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-rock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/rock")

#### rock Type

`number` ([Rock](taggingv8-defs-maingenrescoresv1-properties-rock.md))

#### rock Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### singerSongwriter



`singerSongwriter`

* is required

* Type: `number` ([Singersongwriter](taggingv8-defs-maingenrescoresv1-properties-singersongwriter.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-singersongwriter.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/singerSongwriter")

#### singerSongwriter Type

`number` ([Singersongwriter](taggingv8-defs-maingenrescoresv1-properties-singersongwriter.md))

#### singerSongwriter Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sound



`sound`

* is required

* Type: `number` ([Sound](taggingv8-defs-maingenrescoresv1-properties-sound.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-sound.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/sound")

#### sound Type

`number` ([Sound](taggingv8-defs-maingenrescoresv1-properties-sound.md))

#### sound Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### soundtrack



`soundtrack`

* is required

* Type: `number` ([Soundtrack](taggingv8-defs-maingenrescoresv1-properties-soundtrack.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-soundtrack.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/soundtrack")

#### soundtrack Type

`number` ([Soundtrack](taggingv8-defs-maingenrescoresv1-properties-soundtrack.md))

#### soundtrack Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### spokenWord



`spokenWord`

* is required

* Type: `number` ([Spokenword](taggingv8-defs-maingenrescoresv1-properties-spokenword.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrescoresv1-properties-spokenword.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreScoresV1/properties/spokenWord")

#### spokenWord Type

`number` ([Spokenword](taggingv8-defs-maingenrescoresv1-properties-spokenword.md))

#### spokenWord Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## Definitions group MaingenreSegmentsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1"}
```

| Property                                | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :-------------------------------------- | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [african](#african-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-african.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/african")                   |
| [ambient](#ambient-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-ambient.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/ambient")                   |
| [middleEastern](#middleeastern-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-middleeastern.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/middleEastern")       |
| [asian](#asian-1)                       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-asian.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/asian")                       |
| [blues](#blues-1)                       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-blues.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/blues")                       |
| [childrenJingle](#childrenjingle-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-childrenjingle.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/childrenJingle")     |
| [classical](#classical-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-classical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/classical")               |
| [electronic](#electronic-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-electronic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/electronic")             |
| [folkCountry](#folkcountry-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-folkcountry.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/folkCountry")           |
| [funkSoul](#funksoul-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-funksoul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/funkSoul")                 |
| [indian](#indian-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-indian.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/indian")                     |
| [jazz](#jazz-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-jazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/jazz")                         |
| [latin](#latin-1)                       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-latin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/latin")                       |
| [metal](#metal-1)                       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-metal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/metal")                       |
| [pop](#pop-1)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-pop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/pop")                           |
| [rapHipHop](#raphiphop-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-raphiphop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/rapHipHop")               |
| [reggae](#reggae-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-reggae.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/reggae")                     |
| [rnb](#rnb-1)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-rnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/rnb")                           |
| [rock](#rock-1)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-rock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/rock")                         |
| [singerSongwriter](#singersongwriter-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-singersongwriter.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/singerSongwriter") |
| [sound](#sound-1)                       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-sound.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/sound")                       |
| [soundtrack](#soundtrack-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-soundtrack.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/soundtrack")             |
| [spokenWord](#spokenword-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-spokenword.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/spokenWord")             |

### african



`african`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-african.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/african")

#### african Type

`number[]`

### ambient



`ambient`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-ambient.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/ambient")

#### ambient Type

`number[]`

### middleEastern



`middleEastern`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-middleeastern.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/middleEastern")

#### middleEastern Type

`number[]`

### asian



`asian`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-asian.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/asian")

#### asian Type

`number[]`

### blues



`blues`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-blues.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/blues")

#### blues Type

`number[]`

### childrenJingle



`childrenJingle`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-childrenjingle.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/childrenJingle")

#### childrenJingle Type

`number[]`

### classical



`classical`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-classical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/classical")

#### classical Type

`number[]`

### electronic



`electronic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-electronic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/electronic")

#### electronic Type

`number[]`

### folkCountry



`folkCountry`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-folkcountry.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/folkCountry")

#### folkCountry Type

`number[]`

### funkSoul



`funkSoul`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-funksoul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/funkSoul")

#### funkSoul Type

`number[]`

### indian



`indian`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-indian.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/indian")

#### indian Type

`number[]`

### jazz



`jazz`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-jazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/jazz")

#### jazz Type

`number[]`

### latin



`latin`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-latin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/latin")

#### latin Type

`number[]`

### metal



`metal`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-metal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/metal")

#### metal Type

`number[]`

### pop



`pop`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-pop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/pop")

#### pop Type

`number[]`

### rapHipHop



`rapHipHop`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-raphiphop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/rapHipHop")

#### rapHipHop Type

`number[]`

### reggae



`reggae`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-reggae.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/reggae")

#### reggae Type

`number[]`

### rnb



`rnb`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-rnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/rnb")

#### rnb Type

`number[]`

### rock



`rock`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-rock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/rock")

#### rock Type

`number[]`

### singerSongwriter



`singerSongwriter`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-singersongwriter.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/singerSongwriter")

#### singerSongwriter Type

`number[]`

### sound



`sound`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-sound.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/sound")

#### sound Type

`number[]`

### soundtrack



`soundtrack`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-soundtrack.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/soundtrack")

#### soundtrack Type

`number[]`

### spokenWord



`spokenWord`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1-properties-spokenword.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreSegmentsV1/properties/spokenWord")

#### spokenWord Type

`number[]`

## Definitions group MaingenreTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group MaingenreV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreV1"}
```

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                     |
| :---------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-4) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenresegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreV1/properties/segments")         |
| [scores](#scores-1)     | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrev1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreV1/properties/scores") |
| [tags](#tags-3)         | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-maingenrev1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreV1/properties/tags")     |

### segments



`segments`

* is required

* Type: `object` ([MaingenreSegmentsV1](taggingv8-defs-maingenresegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenresegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreV1/properties/segments")

#### segments Type

`object` ([MaingenreSegmentsV1](taggingv8-defs-maingenresegmentsv1.md))

### scores



`scores`

* is required

* Type: merged type ([Details](taggingv8-defs-maingenrev1-properties-scores.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrev1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreV1/properties/scores")

#### scores Type

merged type ([Details](taggingv8-defs-maingenrev1-properties-scores.md))

any of

* [MaingenreScoresV1](taggingv8-defs-maingenrescoresv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-maingenrev1-properties-scores-anyof-1.md "check type definition")

### tags



`tags`

* is required

* Type: merged type ([Tags](taggingv8-defs-maingenrev1-properties-tags.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-maingenrev1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MaingenreV1/properties/tags")

#### tags Type

merged type ([Tags](taggingv8-defs-maingenrev1-properties-tags.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-maingenrev1-properties-tags-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-maingenrev1-properties-tags-anyof-1.md "check type definition")

## Definitions group MoodAdvancedScoresV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1"}
```

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                     |
| :------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [adventurous](#adventurous)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-adventurous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/adventurous")     |
| [aggressive](#aggressive)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/aggressive")       |
| [agitated](#agitated)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-agitated.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/agitated")           |
| [angry](#angry)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-angry.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/angry")                 |
| [anthemic](#anthemic)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-anthemic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/anthemic")           |
| [anxious](#anxious)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-anxious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/anxious")             |
| [aweInspiring](#aweinspiring)   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-aweinspiring.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/aweInspiring")   |
| [barren](#barren)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-barren.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/barren")               |
| [bittersweet](#bittersweet)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-bittersweet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/bittersweet")     |
| [blue](#blue)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-blue.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/blue")                   |
| [boingy](#boingy)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-boingy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/boingy")               |
| [boisterous](#boisterous)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-boisterous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/boisterous")       |
| [bright](#bright)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-bright.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/bright")               |
| [calm](#calm)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/calm")                   |
| [celebratory](#celebratory)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-celebratory.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/celebratory")     |
| [cheerful](#cheerful)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-cheerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/cheerful")           |
| [cold](#cold)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-cold.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/cold")                   |
| [comedic](#comedic)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-comedic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/comedic")             |
| [concerned](#concerned)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-concerned.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/concerned")         |
| [confident](#confident)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-confident.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/confident")         |
| [contented](#contented)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-contented.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/contented")         |
| [cool](#cool-2)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-cool.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/cool")                   |
| [courageous](#courageous)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-courageous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/courageous")       |
| [creepy](#creepy)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-creepy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/creepy")               |
| [dangerous](#dangerous)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-dangerous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/dangerous")         |
| [dark](#dark)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/dark")                   |
| [delicate](#delicate)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-delicate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/delicate")           |
| [depressing](#depressing)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-depressing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/depressing")       |
| [determined](#determined)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-determined.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/determined")       |
| [dignified](#dignified)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-dignified.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/dignified")         |
| [disturbing](#disturbing)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-disturbing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/disturbing")       |
| [dreamy](#dreamy)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-dreamy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/dreamy")               |
| [eccentric](#eccentric)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-eccentric.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/eccentric")         |
| [eerie](#eerie)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-eerie.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/eerie")                 |
| [emotional](#emotional)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-emotional.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/emotional")         |
| [energetic](#energetic)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/energetic")         |
| [epic](#epic-2)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/epic")                   |
| [euphoric](#euphoric)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-euphoric.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/euphoric")           |
| [evil](#evil)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-evil.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/evil")                   |
| [excited](#excited)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-excited.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/excited")             |
| [exciting](#exciting)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-exciting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/exciting")           |
| [exhilarating](#exhilarating)   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-exhilarating.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/exhilarating")   |
| [fearful](#fearful)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-fearful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/fearful")             |
| [feelGood](#feelgood)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-feelgood.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/feelGood")           |
| [fiery](#fiery)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-fiery.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/fiery")                 |
| [frightening](#frightening)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-frightening.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/frightening")     |
| [fun](#fun)                     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-fun.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/fun")                     |
| [funny](#funny)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-funny.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/funny")                 |
| [gloomy](#gloomy)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-gloomy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/gloomy")               |
| [graceful](#graceful)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-graceful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/graceful")           |
| [happy](#happy)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/happy")                 |
| [heavy](#heavy)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-heavy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/heavy")                 |
| [heroic](#heroic-2)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-heroic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/heroic")               |
| [hopeful](#hopeful)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-hopeful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/hopeful")             |
| [horror](#horror)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-horror.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/horror")               |
| [innocent](#innocent)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-innocent.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/innocent")           |
| [inspirational](#inspirational) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-inspirational.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/inspirational") |
| [intense](#intense)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-intense.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/intense")             |
| [intimate](#intimate)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-intimate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/intimate")           |
| [introspective](#introspective) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-introspective.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/introspective") |
| [joyous](#joyous)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-joyous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/joyous")               |
| [kind](#kind)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-kind.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/kind")                   |
| [laidBack](#laidback)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-laidback.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/laidBack")           |
| [leisurely](#leisurely)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-leisurely.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/leisurely")         |
| [light](#light)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-light.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/light")                 |
| [lighthearted](#lighthearted)   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-lighthearted.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/lighthearted")   |
| [lonely](#lonely)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-lonely.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/lonely")               |
| [loving](#loving)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-loving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/loving")               |
| [lyrical](#lyrical)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-lyrical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/lyrical")             |
| [majestic](#majestic)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-majestic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/majestic")           |
| [melancholy](#melancholy)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-melancholy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/melancholy")       |
| [menacing](#menacing)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-menacing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/menacing")           |
| [mischievous](#mischievous)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-mischievous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/mischievous")     |
| [motivational](#motivational)   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-motivational.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/motivational")   |
| [mournful](#mournful)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-mournful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/mournful")           |
| [mysterious](#mysterious-2)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-mysterious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/mysterious")       |
| [nervous](#nervous)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-nervous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/nervous")             |
| [nightmarish](#nightmarish)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-nightmarish.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/nightmarish")     |
| [noble](#noble)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-noble.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/noble")                 |
| [nostalgic](#nostalgic)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-nostalgic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/nostalgic")         |
| [ominous](#ominous)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-ominous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/ominous")             |
| [optimistic](#optimistic)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-optimistic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/optimistic")       |
| [panicStricken](#panicstricken) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-panicstricken.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/panicStricken") |
| [passionate](#passionate)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-passionate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/passionate")       |
| [peaceful](#peaceful)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-peaceful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/peaceful")           |
| [perky](#perky)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-perky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/perky")                 |
| [playful](#playful-2)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-playful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/playful")             |
| [poignant](#poignant)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-poignant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/poignant")           |
| [ponderous](#ponderous)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-ponderous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/ponderous")         |
| [positive](#positive)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-positive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/positive")           |
| [powerful](#powerful-2)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-powerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/powerful")           |
| [prestigious](#prestigious)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-prestigious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/prestigious")     |
| [proud](#proud)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-proud.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/proud")                 |
| [quiet](#quiet)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-quiet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/quiet")                 |
| [quirky](#quirky)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-quirky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/quirky")               |
| [reflective](#reflective)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-reflective.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/reflective")       |
| [relaxed](#relaxed)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-relaxed.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/relaxed")             |
| [relentless](#relentless)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-relentless.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/relentless")       |
| [resolute](#resolute)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-resolute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/resolute")           |
| [restless](#restless)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-restless.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/restless")           |
| [rollicking](#rollicking)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-rollicking.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/rollicking")       |
| [romantic](#romantic)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/romantic")           |
| [sad](#sad)                     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/sad")                     |
| [scary](#scary)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/scary")                 |
| [seductive](#seductive)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-seductive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/seductive")         |
| [sentimental](#sentimental)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-sentimental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/sentimental")     |
| [serene](#serene)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-serene.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/serene")               |
| [serious](#serious)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-serious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/serious")             |
| [sexy](#sexy)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/sexy")                   |
| [soaring](#soaring)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-soaring.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/soaring")             |
| [soft](#soft)                   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-soft.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/soft")                   |
| [solemn](#solemn)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-solemn.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/solemn")               |
| [soothing](#soothing)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-soothing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/soothing")           |
| [spiritual](#spiritual)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-spiritual.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/spiritual")         |
| [spooky](#spooky)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-spooky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/spooky")               |
| [strange](#strange)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-strange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/strange")             |
| [strong](#strong)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-strong.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/strong")               |
| [supernatural](#supernatural)   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-supernatural.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/supernatural")   |
| [suspenseful](#suspenseful)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-suspenseful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/suspenseful")     |
| [sweet](#sweet)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-sweet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/sweet")                 |
| [tender](#tender)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-tender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/tender")               |
| [tense](#tense)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-tense.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/tense")                 |
| [thoughtful](#thoughtful)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-thoughtful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/thoughtful")       |
| [tranquil](#tranquil)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-tranquil.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/tranquil")           |
| [triumphant](#triumphant)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-triumphant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/triumphant")       |
| [upbeat](#upbeat)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-upbeat.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/upbeat")               |
| [uplifting](#uplifting)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/uplifting")         |
| [victorious](#victorious)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-victorious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/victorious")       |
| [violent](#violent)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-violent.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/violent")             |
| [warm](#warm-2)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-warm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/warm")                   |
| [weird](#weird)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-weird.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/weird")                 |
| [whimsical](#whimsical)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-whimsical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/whimsical")         |

### adventurous



`adventurous`

* is required

* Type: `number` ([Adventurous](taggingv8-defs-moodadvancedscoresv1-properties-adventurous.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-adventurous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/adventurous")

#### adventurous Type

`number` ([Adventurous](taggingv8-defs-moodadvancedscoresv1-properties-adventurous.md))

#### adventurous Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### aggressive



`aggressive`

* is required

* Type: `number` ([Aggressive](taggingv8-defs-moodadvancedscoresv1-properties-aggressive.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/aggressive")

#### aggressive Type

`number` ([Aggressive](taggingv8-defs-moodadvancedscoresv1-properties-aggressive.md))

#### aggressive Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### agitated



`agitated`

* is required

* Type: `number` ([Agitated](taggingv8-defs-moodadvancedscoresv1-properties-agitated.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-agitated.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/agitated")

#### agitated Type

`number` ([Agitated](taggingv8-defs-moodadvancedscoresv1-properties-agitated.md))

#### agitated Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### angry



`angry`

* is required

* Type: `number` ([Angry](taggingv8-defs-moodadvancedscoresv1-properties-angry.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-angry.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/angry")

#### angry Type

`number` ([Angry](taggingv8-defs-moodadvancedscoresv1-properties-angry.md))

#### angry Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### anthemic



`anthemic`

* is required

* Type: `number` ([Anthemic](taggingv8-defs-moodadvancedscoresv1-properties-anthemic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-anthemic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/anthemic")

#### anthemic Type

`number` ([Anthemic](taggingv8-defs-moodadvancedscoresv1-properties-anthemic.md))

#### anthemic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### anxious



`anxious`

* is required

* Type: `number` ([Anxious](taggingv8-defs-moodadvancedscoresv1-properties-anxious.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-anxious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/anxious")

#### anxious Type

`number` ([Anxious](taggingv8-defs-moodadvancedscoresv1-properties-anxious.md))

#### anxious Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### aweInspiring



`aweInspiring`

* is required

* Type: `number` ([Aweinspiring](taggingv8-defs-moodadvancedscoresv1-properties-aweinspiring.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-aweinspiring.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/aweInspiring")

#### aweInspiring Type

`number` ([Aweinspiring](taggingv8-defs-moodadvancedscoresv1-properties-aweinspiring.md))

#### aweInspiring Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### barren



`barren`

* is required

* Type: `number` ([Barren](taggingv8-defs-moodadvancedscoresv1-properties-barren.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-barren.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/barren")

#### barren Type

`number` ([Barren](taggingv8-defs-moodadvancedscoresv1-properties-barren.md))

#### barren Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### bittersweet



`bittersweet`

* is required

* Type: `number` ([Bittersweet](taggingv8-defs-moodadvancedscoresv1-properties-bittersweet.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-bittersweet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/bittersweet")

#### bittersweet Type

`number` ([Bittersweet](taggingv8-defs-moodadvancedscoresv1-properties-bittersweet.md))

#### bittersweet Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### blue



`blue`

* is required

* Type: `number` ([Blue](taggingv8-defs-moodadvancedscoresv1-properties-blue.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-blue.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/blue")

#### blue Type

`number` ([Blue](taggingv8-defs-moodadvancedscoresv1-properties-blue.md))

#### blue Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### boingy



`boingy`

* is required

* Type: `number` ([Boingy](taggingv8-defs-moodadvancedscoresv1-properties-boingy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-boingy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/boingy")

#### boingy Type

`number` ([Boingy](taggingv8-defs-moodadvancedscoresv1-properties-boingy.md))

#### boingy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### boisterous



`boisterous`

* is required

* Type: `number` ([Boisterous](taggingv8-defs-moodadvancedscoresv1-properties-boisterous.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-boisterous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/boisterous")

#### boisterous Type

`number` ([Boisterous](taggingv8-defs-moodadvancedscoresv1-properties-boisterous.md))

#### boisterous Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### bright



`bright`

* is required

* Type: `number` ([Bright](taggingv8-defs-moodadvancedscoresv1-properties-bright.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-bright.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/bright")

#### bright Type

`number` ([Bright](taggingv8-defs-moodadvancedscoresv1-properties-bright.md))

#### bright Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### calm



`calm`

* is required

* Type: `number` ([Calm](taggingv8-defs-moodadvancedscoresv1-properties-calm.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/calm")

#### calm Type

`number` ([Calm](taggingv8-defs-moodadvancedscoresv1-properties-calm.md))

#### calm Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### celebratory



`celebratory`

* is required

* Type: `number` ([Celebratory](taggingv8-defs-moodadvancedscoresv1-properties-celebratory.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-celebratory.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/celebratory")

#### celebratory Type

`number` ([Celebratory](taggingv8-defs-moodadvancedscoresv1-properties-celebratory.md))

#### celebratory Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### cheerful



`cheerful`

* is required

* Type: `number` ([Cheerful](taggingv8-defs-moodadvancedscoresv1-properties-cheerful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-cheerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/cheerful")

#### cheerful Type

`number` ([Cheerful](taggingv8-defs-moodadvancedscoresv1-properties-cheerful.md))

#### cheerful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### cold



`cold`

* is required

* Type: `number` ([Cold](taggingv8-defs-moodadvancedscoresv1-properties-cold.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-cold.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/cold")

#### cold Type

`number` ([Cold](taggingv8-defs-moodadvancedscoresv1-properties-cold.md))

#### cold Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### comedic



`comedic`

* is required

* Type: `number` ([Comedic](taggingv8-defs-moodadvancedscoresv1-properties-comedic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-comedic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/comedic")

#### comedic Type

`number` ([Comedic](taggingv8-defs-moodadvancedscoresv1-properties-comedic.md))

#### comedic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### concerned



`concerned`

* is required

* Type: `number` ([Concerned](taggingv8-defs-moodadvancedscoresv1-properties-concerned.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-concerned.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/concerned")

#### concerned Type

`number` ([Concerned](taggingv8-defs-moodadvancedscoresv1-properties-concerned.md))

#### concerned Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### confident



`confident`

* is required

* Type: `number` ([Confident](taggingv8-defs-moodadvancedscoresv1-properties-confident.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-confident.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/confident")

#### confident Type

`number` ([Confident](taggingv8-defs-moodadvancedscoresv1-properties-confident.md))

#### confident Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### contented



`contented`

* is required

* Type: `number` ([Contented](taggingv8-defs-moodadvancedscoresv1-properties-contented.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-contented.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/contented")

#### contented Type

`number` ([Contented](taggingv8-defs-moodadvancedscoresv1-properties-contented.md))

#### contented Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### cool



`cool`

* is required

* Type: `number` ([Cool](taggingv8-defs-moodadvancedscoresv1-properties-cool.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-cool.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/cool")

#### cool Type

`number` ([Cool](taggingv8-defs-moodadvancedscoresv1-properties-cool.md))

#### cool Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### courageous



`courageous`

* is required

* Type: `number` ([Courageous](taggingv8-defs-moodadvancedscoresv1-properties-courageous.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-courageous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/courageous")

#### courageous Type

`number` ([Courageous](taggingv8-defs-moodadvancedscoresv1-properties-courageous.md))

#### courageous Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### creepy



`creepy`

* is required

* Type: `number` ([Creepy](taggingv8-defs-moodadvancedscoresv1-properties-creepy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-creepy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/creepy")

#### creepy Type

`number` ([Creepy](taggingv8-defs-moodadvancedscoresv1-properties-creepy.md))

#### creepy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### dangerous



`dangerous`

* is required

* Type: `number` ([Dangerous](taggingv8-defs-moodadvancedscoresv1-properties-dangerous.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-dangerous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/dangerous")

#### dangerous Type

`number` ([Dangerous](taggingv8-defs-moodadvancedscoresv1-properties-dangerous.md))

#### dangerous Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### dark



`dark`

* is required

* Type: `number` ([Dark](taggingv8-defs-moodadvancedscoresv1-properties-dark.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/dark")

#### dark Type

`number` ([Dark](taggingv8-defs-moodadvancedscoresv1-properties-dark.md))

#### dark Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### delicate



`delicate`

* is required

* Type: `number` ([Delicate](taggingv8-defs-moodadvancedscoresv1-properties-delicate.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-delicate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/delicate")

#### delicate Type

`number` ([Delicate](taggingv8-defs-moodadvancedscoresv1-properties-delicate.md))

#### delicate Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### depressing



`depressing`

* is required

* Type: `number` ([Depressing](taggingv8-defs-moodadvancedscoresv1-properties-depressing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-depressing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/depressing")

#### depressing Type

`number` ([Depressing](taggingv8-defs-moodadvancedscoresv1-properties-depressing.md))

#### depressing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### determined



`determined`

* is required

* Type: `number` ([Determined](taggingv8-defs-moodadvancedscoresv1-properties-determined.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-determined.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/determined")

#### determined Type

`number` ([Determined](taggingv8-defs-moodadvancedscoresv1-properties-determined.md))

#### determined Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### dignified



`dignified`

* is required

* Type: `number` ([Dignified](taggingv8-defs-moodadvancedscoresv1-properties-dignified.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-dignified.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/dignified")

#### dignified Type

`number` ([Dignified](taggingv8-defs-moodadvancedscoresv1-properties-dignified.md))

#### dignified Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### disturbing



`disturbing`

* is required

* Type: `number` ([Disturbing](taggingv8-defs-moodadvancedscoresv1-properties-disturbing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-disturbing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/disturbing")

#### disturbing Type

`number` ([Disturbing](taggingv8-defs-moodadvancedscoresv1-properties-disturbing.md))

#### disturbing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### dreamy



`dreamy`

* is required

* Type: `number` ([Dreamy](taggingv8-defs-moodadvancedscoresv1-properties-dreamy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-dreamy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/dreamy")

#### dreamy Type

`number` ([Dreamy](taggingv8-defs-moodadvancedscoresv1-properties-dreamy.md))

#### dreamy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### eccentric



`eccentric`

* is required

* Type: `number` ([Eccentric](taggingv8-defs-moodadvancedscoresv1-properties-eccentric.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-eccentric.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/eccentric")

#### eccentric Type

`number` ([Eccentric](taggingv8-defs-moodadvancedscoresv1-properties-eccentric.md))

#### eccentric Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### eerie



`eerie`

* is required

* Type: `number` ([Eerie](taggingv8-defs-moodadvancedscoresv1-properties-eerie.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-eerie.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/eerie")

#### eerie Type

`number` ([Eerie](taggingv8-defs-moodadvancedscoresv1-properties-eerie.md))

#### eerie Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### emotional



`emotional`

* is required

* Type: `number` ([Emotional](taggingv8-defs-moodadvancedscoresv1-properties-emotional.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-emotional.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/emotional")

#### emotional Type

`number` ([Emotional](taggingv8-defs-moodadvancedscoresv1-properties-emotional.md))

#### emotional Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### energetic



`energetic`

* is required

* Type: `number` ([Energetic](taggingv8-defs-moodadvancedscoresv1-properties-energetic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/energetic")

#### energetic Type

`number` ([Energetic](taggingv8-defs-moodadvancedscoresv1-properties-energetic.md))

#### energetic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### epic



`epic`

* is required

* Type: `number` ([Epic](taggingv8-defs-moodadvancedscoresv1-properties-epic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/epic")

#### epic Type

`number` ([Epic](taggingv8-defs-moodadvancedscoresv1-properties-epic.md))

#### epic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### euphoric



`euphoric`

* is required

* Type: `number` ([Euphoric](taggingv8-defs-moodadvancedscoresv1-properties-euphoric.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-euphoric.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/euphoric")

#### euphoric Type

`number` ([Euphoric](taggingv8-defs-moodadvancedscoresv1-properties-euphoric.md))

#### euphoric Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### evil



`evil`

* is required

* Type: `number` ([Evil](taggingv8-defs-moodadvancedscoresv1-properties-evil.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-evil.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/evil")

#### evil Type

`number` ([Evil](taggingv8-defs-moodadvancedscoresv1-properties-evil.md))

#### evil Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### excited



`excited`

* is required

* Type: `number` ([Excited](taggingv8-defs-moodadvancedscoresv1-properties-excited.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-excited.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/excited")

#### excited Type

`number` ([Excited](taggingv8-defs-moodadvancedscoresv1-properties-excited.md))

#### excited Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### exciting



`exciting`

* is required

* Type: `number` ([Exciting](taggingv8-defs-moodadvancedscoresv1-properties-exciting.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-exciting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/exciting")

#### exciting Type

`number` ([Exciting](taggingv8-defs-moodadvancedscoresv1-properties-exciting.md))

#### exciting Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### exhilarating



`exhilarating`

* is required

* Type: `number` ([Exhilarating](taggingv8-defs-moodadvancedscoresv1-properties-exhilarating.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-exhilarating.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/exhilarating")

#### exhilarating Type

`number` ([Exhilarating](taggingv8-defs-moodadvancedscoresv1-properties-exhilarating.md))

#### exhilarating Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### fearful



`fearful`

* is required

* Type: `number` ([Fearful](taggingv8-defs-moodadvancedscoresv1-properties-fearful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-fearful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/fearful")

#### fearful Type

`number` ([Fearful](taggingv8-defs-moodadvancedscoresv1-properties-fearful.md))

#### fearful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### feelGood



`feelGood`

* is required

* Type: `number` ([Feelgood](taggingv8-defs-moodadvancedscoresv1-properties-feelgood.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-feelgood.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/feelGood")

#### feelGood Type

`number` ([Feelgood](taggingv8-defs-moodadvancedscoresv1-properties-feelgood.md))

#### feelGood Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### fiery



`fiery`

* is required

* Type: `number` ([Fiery](taggingv8-defs-moodadvancedscoresv1-properties-fiery.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-fiery.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/fiery")

#### fiery Type

`number` ([Fiery](taggingv8-defs-moodadvancedscoresv1-properties-fiery.md))

#### fiery Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### frightening



`frightening`

* is required

* Type: `number` ([Frightening](taggingv8-defs-moodadvancedscoresv1-properties-frightening.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-frightening.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/frightening")

#### frightening Type

`number` ([Frightening](taggingv8-defs-moodadvancedscoresv1-properties-frightening.md))

#### frightening Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### fun



`fun`

* is required

* Type: `number` ([Fun](taggingv8-defs-moodadvancedscoresv1-properties-fun.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-fun.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/fun")

#### fun Type

`number` ([Fun](taggingv8-defs-moodadvancedscoresv1-properties-fun.md))

#### fun Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### funny



`funny`

* is required

* Type: `number` ([Funny](taggingv8-defs-moodadvancedscoresv1-properties-funny.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-funny.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/funny")

#### funny Type

`number` ([Funny](taggingv8-defs-moodadvancedscoresv1-properties-funny.md))

#### funny Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### gloomy



`gloomy`

* is required

* Type: `number` ([Gloomy](taggingv8-defs-moodadvancedscoresv1-properties-gloomy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-gloomy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/gloomy")

#### gloomy Type

`number` ([Gloomy](taggingv8-defs-moodadvancedscoresv1-properties-gloomy.md))

#### gloomy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### graceful



`graceful`

* is required

* Type: `number` ([Graceful](taggingv8-defs-moodadvancedscoresv1-properties-graceful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-graceful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/graceful")

#### graceful Type

`number` ([Graceful](taggingv8-defs-moodadvancedscoresv1-properties-graceful.md))

#### graceful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### happy



`happy`

* is required

* Type: `number` ([Happy](taggingv8-defs-moodadvancedscoresv1-properties-happy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/happy")

#### happy Type

`number` ([Happy](taggingv8-defs-moodadvancedscoresv1-properties-happy.md))

#### happy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### heavy



`heavy`

* is required

* Type: `number` ([Heavy](taggingv8-defs-moodadvancedscoresv1-properties-heavy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-heavy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/heavy")

#### heavy Type

`number` ([Heavy](taggingv8-defs-moodadvancedscoresv1-properties-heavy.md))

#### heavy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### heroic



`heroic`

* is required

* Type: `number` ([Heroic](taggingv8-defs-moodadvancedscoresv1-properties-heroic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-heroic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/heroic")

#### heroic Type

`number` ([Heroic](taggingv8-defs-moodadvancedscoresv1-properties-heroic.md))

#### heroic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### hopeful



`hopeful`

* is required

* Type: `number` ([Hopeful](taggingv8-defs-moodadvancedscoresv1-properties-hopeful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-hopeful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/hopeful")

#### hopeful Type

`number` ([Hopeful](taggingv8-defs-moodadvancedscoresv1-properties-hopeful.md))

#### hopeful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### horror



`horror`

* is required

* Type: `number` ([Horror](taggingv8-defs-moodadvancedscoresv1-properties-horror.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-horror.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/horror")

#### horror Type

`number` ([Horror](taggingv8-defs-moodadvancedscoresv1-properties-horror.md))

#### horror Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### innocent



`innocent`

* is required

* Type: `number` ([Innocent](taggingv8-defs-moodadvancedscoresv1-properties-innocent.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-innocent.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/innocent")

#### innocent Type

`number` ([Innocent](taggingv8-defs-moodadvancedscoresv1-properties-innocent.md))

#### innocent Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### inspirational



`inspirational`

* is required

* Type: `number` ([Inspirational](taggingv8-defs-moodadvancedscoresv1-properties-inspirational.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-inspirational.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/inspirational")

#### inspirational Type

`number` ([Inspirational](taggingv8-defs-moodadvancedscoresv1-properties-inspirational.md))

#### inspirational Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### intense



`intense`

* is required

* Type: `number` ([Intense](taggingv8-defs-moodadvancedscoresv1-properties-intense.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-intense.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/intense")

#### intense Type

`number` ([Intense](taggingv8-defs-moodadvancedscoresv1-properties-intense.md))

#### intense Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### intimate



`intimate`

* is required

* Type: `number` ([Intimate](taggingv8-defs-moodadvancedscoresv1-properties-intimate.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-intimate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/intimate")

#### intimate Type

`number` ([Intimate](taggingv8-defs-moodadvancedscoresv1-properties-intimate.md))

#### intimate Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### introspective



`introspective`

* is required

* Type: `number` ([Introspective](taggingv8-defs-moodadvancedscoresv1-properties-introspective.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-introspective.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/introspective")

#### introspective Type

`number` ([Introspective](taggingv8-defs-moodadvancedscoresv1-properties-introspective.md))

#### introspective Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### joyous



`joyous`

* is required

* Type: `number` ([Joyous](taggingv8-defs-moodadvancedscoresv1-properties-joyous.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-joyous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/joyous")

#### joyous Type

`number` ([Joyous](taggingv8-defs-moodadvancedscoresv1-properties-joyous.md))

#### joyous Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### kind



`kind`

* is required

* Type: `number` ([Kind](taggingv8-defs-moodadvancedscoresv1-properties-kind.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-kind.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/kind")

#### kind Type

`number` ([Kind](taggingv8-defs-moodadvancedscoresv1-properties-kind.md))

#### kind Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### laidBack



`laidBack`

* is required

* Type: `number` ([Laidback](taggingv8-defs-moodadvancedscoresv1-properties-laidback.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-laidback.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/laidBack")

#### laidBack Type

`number` ([Laidback](taggingv8-defs-moodadvancedscoresv1-properties-laidback.md))

#### laidBack Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### leisurely



`leisurely`

* is required

* Type: `number` ([Leisurely](taggingv8-defs-moodadvancedscoresv1-properties-leisurely.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-leisurely.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/leisurely")

#### leisurely Type

`number` ([Leisurely](taggingv8-defs-moodadvancedscoresv1-properties-leisurely.md))

#### leisurely Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### light



`light`

* is required

* Type: `number` ([Light](taggingv8-defs-moodadvancedscoresv1-properties-light.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-light.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/light")

#### light Type

`number` ([Light](taggingv8-defs-moodadvancedscoresv1-properties-light.md))

#### light Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### lighthearted



`lighthearted`

* is required

* Type: `number` ([Lighthearted](taggingv8-defs-moodadvancedscoresv1-properties-lighthearted.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-lighthearted.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/lighthearted")

#### lighthearted Type

`number` ([Lighthearted](taggingv8-defs-moodadvancedscoresv1-properties-lighthearted.md))

#### lighthearted Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### lonely



`lonely`

* is required

* Type: `number` ([Lonely](taggingv8-defs-moodadvancedscoresv1-properties-lonely.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-lonely.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/lonely")

#### lonely Type

`number` ([Lonely](taggingv8-defs-moodadvancedscoresv1-properties-lonely.md))

#### lonely Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### loving



`loving`

* is required

* Type: `number` ([Loving](taggingv8-defs-moodadvancedscoresv1-properties-loving.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-loving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/loving")

#### loving Type

`number` ([Loving](taggingv8-defs-moodadvancedscoresv1-properties-loving.md))

#### loving Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### lyrical



`lyrical`

* is required

* Type: `number` ([Lyrical](taggingv8-defs-moodadvancedscoresv1-properties-lyrical.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-lyrical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/lyrical")

#### lyrical Type

`number` ([Lyrical](taggingv8-defs-moodadvancedscoresv1-properties-lyrical.md))

#### lyrical Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### majestic



`majestic`

* is required

* Type: `number` ([Majestic](taggingv8-defs-moodadvancedscoresv1-properties-majestic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-majestic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/majestic")

#### majestic Type

`number` ([Majestic](taggingv8-defs-moodadvancedscoresv1-properties-majestic.md))

#### majestic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### melancholy



`melancholy`

* is required

* Type: `number` ([Melancholy](taggingv8-defs-moodadvancedscoresv1-properties-melancholy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-melancholy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/melancholy")

#### melancholy Type

`number` ([Melancholy](taggingv8-defs-moodadvancedscoresv1-properties-melancholy.md))

#### melancholy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### menacing



`menacing`

* is required

* Type: `number` ([Menacing](taggingv8-defs-moodadvancedscoresv1-properties-menacing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-menacing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/menacing")

#### menacing Type

`number` ([Menacing](taggingv8-defs-moodadvancedscoresv1-properties-menacing.md))

#### menacing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### mischievous



`mischievous`

* is required

* Type: `number` ([Mischievous](taggingv8-defs-moodadvancedscoresv1-properties-mischievous.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-mischievous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/mischievous")

#### mischievous Type

`number` ([Mischievous](taggingv8-defs-moodadvancedscoresv1-properties-mischievous.md))

#### mischievous Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### motivational



`motivational`

* is required

* Type: `number` ([Motivational](taggingv8-defs-moodadvancedscoresv1-properties-motivational.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-motivational.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/motivational")

#### motivational Type

`number` ([Motivational](taggingv8-defs-moodadvancedscoresv1-properties-motivational.md))

#### motivational Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### mournful



`mournful`

* is required

* Type: `number` ([Mournful](taggingv8-defs-moodadvancedscoresv1-properties-mournful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-mournful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/mournful")

#### mournful Type

`number` ([Mournful](taggingv8-defs-moodadvancedscoresv1-properties-mournful.md))

#### mournful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### mysterious



`mysterious`

* is required

* Type: `number` ([Mysterious](taggingv8-defs-moodadvancedscoresv1-properties-mysterious.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-mysterious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/mysterious")

#### mysterious Type

`number` ([Mysterious](taggingv8-defs-moodadvancedscoresv1-properties-mysterious.md))

#### mysterious Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### nervous



`nervous`

* is required

* Type: `number` ([Nervous](taggingv8-defs-moodadvancedscoresv1-properties-nervous.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-nervous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/nervous")

#### nervous Type

`number` ([Nervous](taggingv8-defs-moodadvancedscoresv1-properties-nervous.md))

#### nervous Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### nightmarish



`nightmarish`

* is required

* Type: `number` ([Nightmarish](taggingv8-defs-moodadvancedscoresv1-properties-nightmarish.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-nightmarish.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/nightmarish")

#### nightmarish Type

`number` ([Nightmarish](taggingv8-defs-moodadvancedscoresv1-properties-nightmarish.md))

#### nightmarish Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### noble



`noble`

* is required

* Type: `number` ([Noble](taggingv8-defs-moodadvancedscoresv1-properties-noble.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-noble.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/noble")

#### noble Type

`number` ([Noble](taggingv8-defs-moodadvancedscoresv1-properties-noble.md))

#### noble Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### nostalgic



`nostalgic`

* is required

* Type: `number` ([Nostalgic](taggingv8-defs-moodadvancedscoresv1-properties-nostalgic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-nostalgic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/nostalgic")

#### nostalgic Type

`number` ([Nostalgic](taggingv8-defs-moodadvancedscoresv1-properties-nostalgic.md))

#### nostalgic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### ominous



`ominous`

* is required

* Type: `number` ([Ominous](taggingv8-defs-moodadvancedscoresv1-properties-ominous.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-ominous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/ominous")

#### ominous Type

`number` ([Ominous](taggingv8-defs-moodadvancedscoresv1-properties-ominous.md))

#### ominous Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### optimistic



`optimistic`

* is required

* Type: `number` ([Optimistic](taggingv8-defs-moodadvancedscoresv1-properties-optimistic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-optimistic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/optimistic")

#### optimistic Type

`number` ([Optimistic](taggingv8-defs-moodadvancedscoresv1-properties-optimistic.md))

#### optimistic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### panicStricken



`panicStricken`

* is required

* Type: `number` ([Panicstricken](taggingv8-defs-moodadvancedscoresv1-properties-panicstricken.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-panicstricken.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/panicStricken")

#### panicStricken Type

`number` ([Panicstricken](taggingv8-defs-moodadvancedscoresv1-properties-panicstricken.md))

#### panicStricken Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### passionate



`passionate`

* is required

* Type: `number` ([Passionate](taggingv8-defs-moodadvancedscoresv1-properties-passionate.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-passionate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/passionate")

#### passionate Type

`number` ([Passionate](taggingv8-defs-moodadvancedscoresv1-properties-passionate.md))

#### passionate Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### peaceful



`peaceful`

* is required

* Type: `number` ([Peaceful](taggingv8-defs-moodadvancedscoresv1-properties-peaceful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-peaceful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/peaceful")

#### peaceful Type

`number` ([Peaceful](taggingv8-defs-moodadvancedscoresv1-properties-peaceful.md))

#### peaceful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### perky



`perky`

* is required

* Type: `number` ([Perky](taggingv8-defs-moodadvancedscoresv1-properties-perky.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-perky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/perky")

#### perky Type

`number` ([Perky](taggingv8-defs-moodadvancedscoresv1-properties-perky.md))

#### perky Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### playful



`playful`

* is required

* Type: `number` ([Playful](taggingv8-defs-moodadvancedscoresv1-properties-playful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-playful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/playful")

#### playful Type

`number` ([Playful](taggingv8-defs-moodadvancedscoresv1-properties-playful.md))

#### playful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### poignant



`poignant`

* is required

* Type: `number` ([Poignant](taggingv8-defs-moodadvancedscoresv1-properties-poignant.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-poignant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/poignant")

#### poignant Type

`number` ([Poignant](taggingv8-defs-moodadvancedscoresv1-properties-poignant.md))

#### poignant Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### ponderous



`ponderous`

* is required

* Type: `number` ([Ponderous](taggingv8-defs-moodadvancedscoresv1-properties-ponderous.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-ponderous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/ponderous")

#### ponderous Type

`number` ([Ponderous](taggingv8-defs-moodadvancedscoresv1-properties-ponderous.md))

#### ponderous Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### positive



`positive`

* is required

* Type: `number` ([Positive](taggingv8-defs-moodadvancedscoresv1-properties-positive.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-positive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/positive")

#### positive Type

`number` ([Positive](taggingv8-defs-moodadvancedscoresv1-properties-positive.md))

#### positive Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### powerful



`powerful`

* is required

* Type: `number` ([Powerful](taggingv8-defs-moodadvancedscoresv1-properties-powerful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-powerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/powerful")

#### powerful Type

`number` ([Powerful](taggingv8-defs-moodadvancedscoresv1-properties-powerful.md))

#### powerful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### prestigious



`prestigious`

* is required

* Type: `number` ([Prestigious](taggingv8-defs-moodadvancedscoresv1-properties-prestigious.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-prestigious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/prestigious")

#### prestigious Type

`number` ([Prestigious](taggingv8-defs-moodadvancedscoresv1-properties-prestigious.md))

#### prestigious Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### proud



`proud`

* is required

* Type: `number` ([Proud](taggingv8-defs-moodadvancedscoresv1-properties-proud.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-proud.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/proud")

#### proud Type

`number` ([Proud](taggingv8-defs-moodadvancedscoresv1-properties-proud.md))

#### proud Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### quiet



`quiet`

* is required

* Type: `number` ([Quiet](taggingv8-defs-moodadvancedscoresv1-properties-quiet.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-quiet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/quiet")

#### quiet Type

`number` ([Quiet](taggingv8-defs-moodadvancedscoresv1-properties-quiet.md))

#### quiet Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### quirky



`quirky`

* is required

* Type: `number` ([Quirky](taggingv8-defs-moodadvancedscoresv1-properties-quirky.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-quirky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/quirky")

#### quirky Type

`number` ([Quirky](taggingv8-defs-moodadvancedscoresv1-properties-quirky.md))

#### quirky Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### reflective



`reflective`

* is required

* Type: `number` ([Reflective](taggingv8-defs-moodadvancedscoresv1-properties-reflective.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-reflective.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/reflective")

#### reflective Type

`number` ([Reflective](taggingv8-defs-moodadvancedscoresv1-properties-reflective.md))

#### reflective Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### relaxed



`relaxed`

* is required

* Type: `number` ([Relaxed](taggingv8-defs-moodadvancedscoresv1-properties-relaxed.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-relaxed.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/relaxed")

#### relaxed Type

`number` ([Relaxed](taggingv8-defs-moodadvancedscoresv1-properties-relaxed.md))

#### relaxed Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### relentless



`relentless`

* is required

* Type: `number` ([Relentless](taggingv8-defs-moodadvancedscoresv1-properties-relentless.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-relentless.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/relentless")

#### relentless Type

`number` ([Relentless](taggingv8-defs-moodadvancedscoresv1-properties-relentless.md))

#### relentless Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### resolute



`resolute`

* is required

* Type: `number` ([Resolute](taggingv8-defs-moodadvancedscoresv1-properties-resolute.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-resolute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/resolute")

#### resolute Type

`number` ([Resolute](taggingv8-defs-moodadvancedscoresv1-properties-resolute.md))

#### resolute Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### restless



`restless`

* is required

* Type: `number` ([Restless](taggingv8-defs-moodadvancedscoresv1-properties-restless.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-restless.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/restless")

#### restless Type

`number` ([Restless](taggingv8-defs-moodadvancedscoresv1-properties-restless.md))

#### restless Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### rollicking



`rollicking`

* is required

* Type: `number` ([Rollicking](taggingv8-defs-moodadvancedscoresv1-properties-rollicking.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-rollicking.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/rollicking")

#### rollicking Type

`number` ([Rollicking](taggingv8-defs-moodadvancedscoresv1-properties-rollicking.md))

#### rollicking Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### romantic



`romantic`

* is required

* Type: `number` ([Romantic](taggingv8-defs-moodadvancedscoresv1-properties-romantic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/romantic")

#### romantic Type

`number` ([Romantic](taggingv8-defs-moodadvancedscoresv1-properties-romantic.md))

#### romantic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sad



`sad`

* is required

* Type: `number` ([Sad](taggingv8-defs-moodadvancedscoresv1-properties-sad.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/sad")

#### sad Type

`number` ([Sad](taggingv8-defs-moodadvancedscoresv1-properties-sad.md))

#### sad Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### scary



`scary`

* is required

* Type: `number` ([Scary](taggingv8-defs-moodadvancedscoresv1-properties-scary.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/scary")

#### scary Type

`number` ([Scary](taggingv8-defs-moodadvancedscoresv1-properties-scary.md))

#### scary Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### seductive



`seductive`

* is required

* Type: `number` ([Seductive](taggingv8-defs-moodadvancedscoresv1-properties-seductive.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-seductive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/seductive")

#### seductive Type

`number` ([Seductive](taggingv8-defs-moodadvancedscoresv1-properties-seductive.md))

#### seductive Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sentimental



`sentimental`

* is required

* Type: `number` ([Sentimental](taggingv8-defs-moodadvancedscoresv1-properties-sentimental.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-sentimental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/sentimental")

#### sentimental Type

`number` ([Sentimental](taggingv8-defs-moodadvancedscoresv1-properties-sentimental.md))

#### sentimental Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### serene



`serene`

* is required

* Type: `number` ([Serene](taggingv8-defs-moodadvancedscoresv1-properties-serene.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-serene.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/serene")

#### serene Type

`number` ([Serene](taggingv8-defs-moodadvancedscoresv1-properties-serene.md))

#### serene Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### serious



`serious`

* is required

* Type: `number` ([Serious](taggingv8-defs-moodadvancedscoresv1-properties-serious.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-serious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/serious")

#### serious Type

`number` ([Serious](taggingv8-defs-moodadvancedscoresv1-properties-serious.md))

#### serious Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sexy



`sexy`

* is required

* Type: `number` ([Sexy](taggingv8-defs-moodadvancedscoresv1-properties-sexy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/sexy")

#### sexy Type

`number` ([Sexy](taggingv8-defs-moodadvancedscoresv1-properties-sexy.md))

#### sexy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### soaring



`soaring`

* is required

* Type: `number` ([Soaring](taggingv8-defs-moodadvancedscoresv1-properties-soaring.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-soaring.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/soaring")

#### soaring Type

`number` ([Soaring](taggingv8-defs-moodadvancedscoresv1-properties-soaring.md))

#### soaring Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### soft



`soft`

* is required

* Type: `number` ([Soft](taggingv8-defs-moodadvancedscoresv1-properties-soft.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-soft.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/soft")

#### soft Type

`number` ([Soft](taggingv8-defs-moodadvancedscoresv1-properties-soft.md))

#### soft Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### solemn



`solemn`

* is required

* Type: `number` ([Solemn](taggingv8-defs-moodadvancedscoresv1-properties-solemn.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-solemn.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/solemn")

#### solemn Type

`number` ([Solemn](taggingv8-defs-moodadvancedscoresv1-properties-solemn.md))

#### solemn Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### soothing



`soothing`

* is required

* Type: `number` ([Soothing](taggingv8-defs-moodadvancedscoresv1-properties-soothing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-soothing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/soothing")

#### soothing Type

`number` ([Soothing](taggingv8-defs-moodadvancedscoresv1-properties-soothing.md))

#### soothing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### spiritual



`spiritual`

* is required

* Type: `number` ([Spiritual](taggingv8-defs-moodadvancedscoresv1-properties-spiritual.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-spiritual.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/spiritual")

#### spiritual Type

`number` ([Spiritual](taggingv8-defs-moodadvancedscoresv1-properties-spiritual.md))

#### spiritual Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### spooky



`spooky`

* is required

* Type: `number` ([Spooky](taggingv8-defs-moodadvancedscoresv1-properties-spooky.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-spooky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/spooky")

#### spooky Type

`number` ([Spooky](taggingv8-defs-moodadvancedscoresv1-properties-spooky.md))

#### spooky Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### strange



`strange`

* is required

* Type: `number` ([Strange](taggingv8-defs-moodadvancedscoresv1-properties-strange.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-strange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/strange")

#### strange Type

`number` ([Strange](taggingv8-defs-moodadvancedscoresv1-properties-strange.md))

#### strange Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### strong



`strong`

* is required

* Type: `number` ([Strong](taggingv8-defs-moodadvancedscoresv1-properties-strong.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-strong.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/strong")

#### strong Type

`number` ([Strong](taggingv8-defs-moodadvancedscoresv1-properties-strong.md))

#### strong Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### supernatural



`supernatural`

* is required

* Type: `number` ([Supernatural](taggingv8-defs-moodadvancedscoresv1-properties-supernatural.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-supernatural.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/supernatural")

#### supernatural Type

`number` ([Supernatural](taggingv8-defs-moodadvancedscoresv1-properties-supernatural.md))

#### supernatural Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### suspenseful



`suspenseful`

* is required

* Type: `number` ([Suspenseful](taggingv8-defs-moodadvancedscoresv1-properties-suspenseful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-suspenseful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/suspenseful")

#### suspenseful Type

`number` ([Suspenseful](taggingv8-defs-moodadvancedscoresv1-properties-suspenseful.md))

#### suspenseful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sweet



`sweet`

* is required

* Type: `number` ([Sweet](taggingv8-defs-moodadvancedscoresv1-properties-sweet.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-sweet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/sweet")

#### sweet Type

`number` ([Sweet](taggingv8-defs-moodadvancedscoresv1-properties-sweet.md))

#### sweet Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### tender



`tender`

* is required

* Type: `number` ([Tender](taggingv8-defs-moodadvancedscoresv1-properties-tender.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-tender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/tender")

#### tender Type

`number` ([Tender](taggingv8-defs-moodadvancedscoresv1-properties-tender.md))

#### tender Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### tense



`tense`

* is required

* Type: `number` ([Tense](taggingv8-defs-moodadvancedscoresv1-properties-tense.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-tense.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/tense")

#### tense Type

`number` ([Tense](taggingv8-defs-moodadvancedscoresv1-properties-tense.md))

#### tense Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### thoughtful



`thoughtful`

* is required

* Type: `number` ([Thoughtful](taggingv8-defs-moodadvancedscoresv1-properties-thoughtful.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-thoughtful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/thoughtful")

#### thoughtful Type

`number` ([Thoughtful](taggingv8-defs-moodadvancedscoresv1-properties-thoughtful.md))

#### thoughtful Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### tranquil



`tranquil`

* is required

* Type: `number` ([Tranquil](taggingv8-defs-moodadvancedscoresv1-properties-tranquil.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-tranquil.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/tranquil")

#### tranquil Type

`number` ([Tranquil](taggingv8-defs-moodadvancedscoresv1-properties-tranquil.md))

#### tranquil Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### triumphant



`triumphant`

* is required

* Type: `number` ([Triumphant](taggingv8-defs-moodadvancedscoresv1-properties-triumphant.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-triumphant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/triumphant")

#### triumphant Type

`number` ([Triumphant](taggingv8-defs-moodadvancedscoresv1-properties-triumphant.md))

#### triumphant Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### upbeat



`upbeat`

* is required

* Type: `number` ([Upbeat](taggingv8-defs-moodadvancedscoresv1-properties-upbeat.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-upbeat.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/upbeat")

#### upbeat Type

`number` ([Upbeat](taggingv8-defs-moodadvancedscoresv1-properties-upbeat.md))

#### upbeat Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### uplifting



`uplifting`

* is required

* Type: `number` ([Uplifting](taggingv8-defs-moodadvancedscoresv1-properties-uplifting.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/uplifting")

#### uplifting Type

`number` ([Uplifting](taggingv8-defs-moodadvancedscoresv1-properties-uplifting.md))

#### uplifting Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### victorious



`victorious`

* is required

* Type: `number` ([Victorious](taggingv8-defs-moodadvancedscoresv1-properties-victorious.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-victorious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/victorious")

#### victorious Type

`number` ([Victorious](taggingv8-defs-moodadvancedscoresv1-properties-victorious.md))

#### victorious Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### violent



`violent`

* is required

* Type: `number` ([Violent](taggingv8-defs-moodadvancedscoresv1-properties-violent.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-violent.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/violent")

#### violent Type

`number` ([Violent](taggingv8-defs-moodadvancedscoresv1-properties-violent.md))

#### violent Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### warm



`warm`

* is required

* Type: `number` ([Warm](taggingv8-defs-moodadvancedscoresv1-properties-warm.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-warm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/warm")

#### warm Type

`number` ([Warm](taggingv8-defs-moodadvancedscoresv1-properties-warm.md))

#### warm Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### weird



`weird`

* is required

* Type: `number` ([Weird](taggingv8-defs-moodadvancedscoresv1-properties-weird.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-weird.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/weird")

#### weird Type

`number` ([Weird](taggingv8-defs-moodadvancedscoresv1-properties-weird.md))

#### weird Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### whimsical



`whimsical`

* is required

* Type: `number` ([Whimsical](taggingv8-defs-moodadvancedscoresv1-properties-whimsical.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedscoresv1-properties-whimsical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedScoresV1/properties/whimsical")

#### whimsical Type

`number` ([Whimsical](taggingv8-defs-moodadvancedscoresv1-properties-whimsical.md))

#### whimsical Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## Definitions group MoodAdvancedSegmentsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1"}
```

| Property                          | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :-------------------------------- | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [adventurous](#adventurous-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-adventurous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/adventurous")     |
| [aggressive](#aggressive-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/aggressive")       |
| [agitated](#agitated-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-agitated.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/agitated")           |
| [angry](#angry-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-angry.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/angry")                 |
| [anthemic](#anthemic-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-anthemic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/anthemic")           |
| [anxious](#anxious-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-anxious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/anxious")             |
| [aweInspiring](#aweinspiring-1)   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-aweinspiring.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/aweInspiring")   |
| [barren](#barren-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-barren.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/barren")               |
| [bittersweet](#bittersweet-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-bittersweet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/bittersweet")     |
| [blue](#blue-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-blue.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/blue")                   |
| [boingy](#boingy-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-boingy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/boingy")               |
| [boisterous](#boisterous-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-boisterous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/boisterous")       |
| [bright](#bright-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-bright.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/bright")               |
| [calm](#calm-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/calm")                   |
| [celebratory](#celebratory-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-celebratory.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/celebratory")     |
| [cheerful](#cheerful-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-cheerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/cheerful")           |
| [cold](#cold-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-cold.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/cold")                   |
| [comedic](#comedic-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-comedic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/comedic")             |
| [concerned](#concerned-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-concerned.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/concerned")         |
| [confident](#confident-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-confident.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/confident")         |
| [contented](#contented-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-contented.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/contented")         |
| [cool](#cool-3)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-cool.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/cool")                   |
| [courageous](#courageous-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-courageous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/courageous")       |
| [creepy](#creepy-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-creepy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/creepy")               |
| [dangerous](#dangerous-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-dangerous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/dangerous")         |
| [dark](#dark-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/dark")                   |
| [delicate](#delicate-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-delicate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/delicate")           |
| [depressing](#depressing-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-depressing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/depressing")       |
| [determined](#determined-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-determined.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/determined")       |
| [dignified](#dignified-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-dignified.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/dignified")         |
| [disturbing](#disturbing-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-disturbing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/disturbing")       |
| [dreamy](#dreamy-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-dreamy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/dreamy")               |
| [eccentric](#eccentric-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-eccentric.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/eccentric")         |
| [eerie](#eerie-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-eerie.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/eerie")                 |
| [emotional](#emotional-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-emotional.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/emotional")         |
| [energetic](#energetic-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/energetic")         |
| [epic](#epic-3)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/epic")                   |
| [euphoric](#euphoric-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-euphoric.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/euphoric")           |
| [evil](#evil-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-evil.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/evil")                   |
| [excited](#excited-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-excited.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/excited")             |
| [exciting](#exciting-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-exciting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/exciting")           |
| [exhilarating](#exhilarating-1)   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-exhilarating.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/exhilarating")   |
| [fearful](#fearful-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-fearful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/fearful")             |
| [feelGood](#feelgood-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-feelgood.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/feelGood")           |
| [fiery](#fiery-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-fiery.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/fiery")                 |
| [frightening](#frightening-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-frightening.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/frightening")     |
| [fun](#fun-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-fun.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/fun")                     |
| [funny](#funny-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-funny.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/funny")                 |
| [gloomy](#gloomy-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-gloomy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/gloomy")               |
| [graceful](#graceful-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-graceful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/graceful")           |
| [happy](#happy-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/happy")                 |
| [heavy](#heavy-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-heavy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/heavy")                 |
| [heroic](#heroic-3)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-heroic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/heroic")               |
| [hopeful](#hopeful-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-hopeful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/hopeful")             |
| [horror](#horror-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-horror.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/horror")               |
| [innocent](#innocent-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-innocent.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/innocent")           |
| [inspirational](#inspirational-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-inspirational.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/inspirational") |
| [intense](#intense-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-intense.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/intense")             |
| [intimate](#intimate-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-intimate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/intimate")           |
| [introspective](#introspective-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-introspective.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/introspective") |
| [joyous](#joyous-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-joyous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/joyous")               |
| [kind](#kind-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-kind.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/kind")                   |
| [laidBack](#laidback-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-laidback.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/laidBack")           |
| [leisurely](#leisurely-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-leisurely.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/leisurely")         |
| [light](#light-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-light.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/light")                 |
| [lighthearted](#lighthearted-1)   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-lighthearted.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/lighthearted")   |
| [lonely](#lonely-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-lonely.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/lonely")               |
| [loving](#loving-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-loving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/loving")               |
| [lyrical](#lyrical-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-lyrical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/lyrical")             |
| [majestic](#majestic-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-majestic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/majestic")           |
| [melancholy](#melancholy-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-melancholy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/melancholy")       |
| [menacing](#menacing-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-menacing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/menacing")           |
| [mischievous](#mischievous-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-mischievous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/mischievous")     |
| [motivational](#motivational-1)   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-motivational.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/motivational")   |
| [mournful](#mournful-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-mournful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/mournful")           |
| [mysterious](#mysterious-3)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-mysterious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/mysterious")       |
| [nervous](#nervous-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-nervous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/nervous")             |
| [nightmarish](#nightmarish-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-nightmarish.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/nightmarish")     |
| [noble](#noble-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-noble.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/noble")                 |
| [nostalgic](#nostalgic-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-nostalgic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/nostalgic")         |
| [ominous](#ominous-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-ominous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/ominous")             |
| [optimistic](#optimistic-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-optimistic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/optimistic")       |
| [panicStricken](#panicstricken-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-panicstricken.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/panicStricken") |
| [passionate](#passionate-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-passionate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/passionate")       |
| [peaceful](#peaceful-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-peaceful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/peaceful")           |
| [perky](#perky-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-perky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/perky")                 |
| [playful](#playful-3)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-playful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/playful")             |
| [poignant](#poignant-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-poignant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/poignant")           |
| [ponderous](#ponderous-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-ponderous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/ponderous")         |
| [positive](#positive-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-positive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/positive")           |
| [powerful](#powerful-3)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-powerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/powerful")           |
| [prestigious](#prestigious-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-prestigious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/prestigious")     |
| [proud](#proud-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-proud.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/proud")                 |
| [quiet](#quiet-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-quiet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/quiet")                 |
| [quirky](#quirky-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-quirky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/quirky")               |
| [reflective](#reflective-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-reflective.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/reflective")       |
| [relaxed](#relaxed-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-relaxed.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/relaxed")             |
| [relentless](#relentless-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-relentless.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/relentless")       |
| [resolute](#resolute-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-resolute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/resolute")           |
| [restless](#restless-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-restless.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/restless")           |
| [rollicking](#rollicking-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-rollicking.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/rollicking")       |
| [romantic](#romantic-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/romantic")           |
| [sad](#sad-1)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/sad")                     |
| [scary](#scary-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/scary")                 |
| [seductive](#seductive-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-seductive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/seductive")         |
| [sentimental](#sentimental-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-sentimental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/sentimental")     |
| [serene](#serene-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-serene.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/serene")               |
| [serious](#serious-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-serious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/serious")             |
| [sexy](#sexy-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/sexy")                   |
| [soaring](#soaring-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-soaring.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/soaring")             |
| [soft](#soft-1)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-soft.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/soft")                   |
| [solemn](#solemn-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-solemn.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/solemn")               |
| [soothing](#soothing-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-soothing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/soothing")           |
| [spiritual](#spiritual-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-spiritual.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/spiritual")         |
| [spooky](#spooky-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-spooky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/spooky")               |
| [strange](#strange-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-strange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/strange")             |
| [strong](#strong-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-strong.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/strong")               |
| [supernatural](#supernatural-1)   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-supernatural.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/supernatural")   |
| [suspenseful](#suspenseful-1)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-suspenseful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/suspenseful")     |
| [sweet](#sweet-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-sweet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/sweet")                 |
| [tender](#tender-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-tender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/tender")               |
| [tense](#tense-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-tense.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/tense")                 |
| [thoughtful](#thoughtful-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-thoughtful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/thoughtful")       |
| [tranquil](#tranquil-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-tranquil.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/tranquil")           |
| [triumphant](#triumphant-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-triumphant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/triumphant")       |
| [upbeat](#upbeat-1)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-upbeat.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/upbeat")               |
| [uplifting](#uplifting-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/uplifting")         |
| [victorious](#victorious-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-victorious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/victorious")       |
| [violent](#violent-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-violent.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/violent")             |
| [warm](#warm-3)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-warm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/warm")                   |
| [weird](#weird-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-weird.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/weird")                 |
| [whimsical](#whimsical-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-whimsical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/whimsical")         |

### adventurous



`adventurous`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-adventurous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/adventurous")

#### adventurous Type

`number[]`

### aggressive



`aggressive`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/aggressive")

#### aggressive Type

`number[]`

### agitated



`agitated`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-agitated.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/agitated")

#### agitated Type

`number[]`

### angry



`angry`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-angry.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/angry")

#### angry Type

`number[]`

### anthemic



`anthemic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-anthemic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/anthemic")

#### anthemic Type

`number[]`

### anxious



`anxious`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-anxious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/anxious")

#### anxious Type

`number[]`

### aweInspiring



`aweInspiring`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-aweinspiring.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/aweInspiring")

#### aweInspiring Type

`number[]`

### barren



`barren`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-barren.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/barren")

#### barren Type

`number[]`

### bittersweet



`bittersweet`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-bittersweet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/bittersweet")

#### bittersweet Type

`number[]`

### blue



`blue`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-blue.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/blue")

#### blue Type

`number[]`

### boingy



`boingy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-boingy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/boingy")

#### boingy Type

`number[]`

### boisterous



`boisterous`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-boisterous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/boisterous")

#### boisterous Type

`number[]`

### bright



`bright`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-bright.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/bright")

#### bright Type

`number[]`

### calm



`calm`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/calm")

#### calm Type

`number[]`

### celebratory



`celebratory`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-celebratory.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/celebratory")

#### celebratory Type

`number[]`

### cheerful



`cheerful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-cheerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/cheerful")

#### cheerful Type

`number[]`

### cold



`cold`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-cold.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/cold")

#### cold Type

`number[]`

### comedic



`comedic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-comedic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/comedic")

#### comedic Type

`number[]`

### concerned



`concerned`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-concerned.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/concerned")

#### concerned Type

`number[]`

### confident



`confident`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-confident.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/confident")

#### confident Type

`number[]`

### contented



`contented`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-contented.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/contented")

#### contented Type

`number[]`

### cool



`cool`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-cool.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/cool")

#### cool Type

`number[]`

### courageous



`courageous`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-courageous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/courageous")

#### courageous Type

`number[]`

### creepy



`creepy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-creepy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/creepy")

#### creepy Type

`number[]`

### dangerous



`dangerous`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-dangerous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/dangerous")

#### dangerous Type

`number[]`

### dark



`dark`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/dark")

#### dark Type

`number[]`

### delicate



`delicate`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-delicate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/delicate")

#### delicate Type

`number[]`

### depressing



`depressing`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-depressing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/depressing")

#### depressing Type

`number[]`

### determined



`determined`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-determined.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/determined")

#### determined Type

`number[]`

### dignified



`dignified`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-dignified.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/dignified")

#### dignified Type

`number[]`

### disturbing



`disturbing`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-disturbing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/disturbing")

#### disturbing Type

`number[]`

### dreamy



`dreamy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-dreamy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/dreamy")

#### dreamy Type

`number[]`

### eccentric



`eccentric`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-eccentric.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/eccentric")

#### eccentric Type

`number[]`

### eerie



`eerie`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-eerie.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/eerie")

#### eerie Type

`number[]`

### emotional



`emotional`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-emotional.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/emotional")

#### emotional Type

`number[]`

### energetic



`energetic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/energetic")

#### energetic Type

`number[]`

### epic



`epic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/epic")

#### epic Type

`number[]`

### euphoric



`euphoric`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-euphoric.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/euphoric")

#### euphoric Type

`number[]`

### evil



`evil`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-evil.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/evil")

#### evil Type

`number[]`

### excited



`excited`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-excited.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/excited")

#### excited Type

`number[]`

### exciting



`exciting`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-exciting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/exciting")

#### exciting Type

`number[]`

### exhilarating



`exhilarating`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-exhilarating.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/exhilarating")

#### exhilarating Type

`number[]`

### fearful



`fearful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-fearful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/fearful")

#### fearful Type

`number[]`

### feelGood



`feelGood`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-feelgood.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/feelGood")

#### feelGood Type

`number[]`

### fiery



`fiery`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-fiery.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/fiery")

#### fiery Type

`number[]`

### frightening



`frightening`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-frightening.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/frightening")

#### frightening Type

`number[]`

### fun



`fun`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-fun.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/fun")

#### fun Type

`number[]`

### funny



`funny`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-funny.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/funny")

#### funny Type

`number[]`

### gloomy



`gloomy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-gloomy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/gloomy")

#### gloomy Type

`number[]`

### graceful



`graceful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-graceful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/graceful")

#### graceful Type

`number[]`

### happy



`happy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/happy")

#### happy Type

`number[]`

### heavy



`heavy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-heavy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/heavy")

#### heavy Type

`number[]`

### heroic



`heroic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-heroic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/heroic")

#### heroic Type

`number[]`

### hopeful



`hopeful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-hopeful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/hopeful")

#### hopeful Type

`number[]`

### horror



`horror`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-horror.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/horror")

#### horror Type

`number[]`

### innocent



`innocent`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-innocent.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/innocent")

#### innocent Type

`number[]`

### inspirational



`inspirational`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-inspirational.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/inspirational")

#### inspirational Type

`number[]`

### intense



`intense`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-intense.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/intense")

#### intense Type

`number[]`

### intimate



`intimate`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-intimate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/intimate")

#### intimate Type

`number[]`

### introspective



`introspective`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-introspective.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/introspective")

#### introspective Type

`number[]`

### joyous



`joyous`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-joyous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/joyous")

#### joyous Type

`number[]`

### kind



`kind`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-kind.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/kind")

#### kind Type

`number[]`

### laidBack



`laidBack`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-laidback.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/laidBack")

#### laidBack Type

`number[]`

### leisurely



`leisurely`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-leisurely.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/leisurely")

#### leisurely Type

`number[]`

### light



`light`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-light.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/light")

#### light Type

`number[]`

### lighthearted



`lighthearted`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-lighthearted.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/lighthearted")

#### lighthearted Type

`number[]`

### lonely



`lonely`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-lonely.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/lonely")

#### lonely Type

`number[]`

### loving



`loving`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-loving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/loving")

#### loving Type

`number[]`

### lyrical



`lyrical`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-lyrical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/lyrical")

#### lyrical Type

`number[]`

### majestic



`majestic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-majestic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/majestic")

#### majestic Type

`number[]`

### melancholy



`melancholy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-melancholy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/melancholy")

#### melancholy Type

`number[]`

### menacing



`menacing`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-menacing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/menacing")

#### menacing Type

`number[]`

### mischievous



`mischievous`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-mischievous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/mischievous")

#### mischievous Type

`number[]`

### motivational



`motivational`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-motivational.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/motivational")

#### motivational Type

`number[]`

### mournful



`mournful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-mournful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/mournful")

#### mournful Type

`number[]`

### mysterious



`mysterious`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-mysterious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/mysterious")

#### mysterious Type

`number[]`

### nervous



`nervous`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-nervous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/nervous")

#### nervous Type

`number[]`

### nightmarish



`nightmarish`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-nightmarish.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/nightmarish")

#### nightmarish Type

`number[]`

### noble



`noble`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-noble.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/noble")

#### noble Type

`number[]`

### nostalgic



`nostalgic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-nostalgic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/nostalgic")

#### nostalgic Type

`number[]`

### ominous



`ominous`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-ominous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/ominous")

#### ominous Type

`number[]`

### optimistic



`optimistic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-optimistic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/optimistic")

#### optimistic Type

`number[]`

### panicStricken



`panicStricken`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-panicstricken.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/panicStricken")

#### panicStricken Type

`number[]`

### passionate



`passionate`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-passionate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/passionate")

#### passionate Type

`number[]`

### peaceful



`peaceful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-peaceful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/peaceful")

#### peaceful Type

`number[]`

### perky



`perky`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-perky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/perky")

#### perky Type

`number[]`

### playful



`playful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-playful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/playful")

#### playful Type

`number[]`

### poignant



`poignant`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-poignant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/poignant")

#### poignant Type

`number[]`

### ponderous



`ponderous`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-ponderous.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/ponderous")

#### ponderous Type

`number[]`

### positive



`positive`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-positive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/positive")

#### positive Type

`number[]`

### powerful



`powerful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-powerful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/powerful")

#### powerful Type

`number[]`

### prestigious



`prestigious`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-prestigious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/prestigious")

#### prestigious Type

`number[]`

### proud



`proud`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-proud.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/proud")

#### proud Type

`number[]`

### quiet



`quiet`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-quiet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/quiet")

#### quiet Type

`number[]`

### quirky



`quirky`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-quirky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/quirky")

#### quirky Type

`number[]`

### reflective



`reflective`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-reflective.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/reflective")

#### reflective Type

`number[]`

### relaxed



`relaxed`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-relaxed.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/relaxed")

#### relaxed Type

`number[]`

### relentless



`relentless`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-relentless.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/relentless")

#### relentless Type

`number[]`

### resolute



`resolute`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-resolute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/resolute")

#### resolute Type

`number[]`

### restless



`restless`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-restless.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/restless")

#### restless Type

`number[]`

### rollicking



`rollicking`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-rollicking.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/rollicking")

#### rollicking Type

`number[]`

### romantic



`romantic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/romantic")

#### romantic Type

`number[]`

### sad



`sad`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/sad")

#### sad Type

`number[]`

### scary



`scary`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/scary")

#### scary Type

`number[]`

### seductive



`seductive`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-seductive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/seductive")

#### seductive Type

`number[]`

### sentimental



`sentimental`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-sentimental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/sentimental")

#### sentimental Type

`number[]`

### serene



`serene`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-serene.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/serene")

#### serene Type

`number[]`

### serious



`serious`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-serious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/serious")

#### serious Type

`number[]`

### sexy



`sexy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/sexy")

#### sexy Type

`number[]`

### soaring



`soaring`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-soaring.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/soaring")

#### soaring Type

`number[]`

### soft



`soft`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-soft.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/soft")

#### soft Type

`number[]`

### solemn



`solemn`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-solemn.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/solemn")

#### solemn Type

`number[]`

### soothing



`soothing`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-soothing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/soothing")

#### soothing Type

`number[]`

### spiritual



`spiritual`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-spiritual.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/spiritual")

#### spiritual Type

`number[]`

### spooky



`spooky`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-spooky.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/spooky")

#### spooky Type

`number[]`

### strange



`strange`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-strange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/strange")

#### strange Type

`number[]`

### strong



`strong`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-strong.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/strong")

#### strong Type

`number[]`

### supernatural



`supernatural`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-supernatural.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/supernatural")

#### supernatural Type

`number[]`

### suspenseful



`suspenseful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-suspenseful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/suspenseful")

#### suspenseful Type

`number[]`

### sweet



`sweet`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-sweet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/sweet")

#### sweet Type

`number[]`

### tender



`tender`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-tender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/tender")

#### tender Type

`number[]`

### tense



`tense`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-tense.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/tense")

#### tense Type

`number[]`

### thoughtful



`thoughtful`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-thoughtful.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/thoughtful")

#### thoughtful Type

`number[]`

### tranquil



`tranquil`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-tranquil.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/tranquil")

#### tranquil Type

`number[]`

### triumphant



`triumphant`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-triumphant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/triumphant")

#### triumphant Type

`number[]`

### upbeat



`upbeat`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-upbeat.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/upbeat")

#### upbeat Type

`number[]`

### uplifting



`uplifting`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/uplifting")

#### uplifting Type

`number[]`

### victorious



`victorious`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-victorious.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/victorious")

#### victorious Type

`number[]`

### violent



`violent`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-violent.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/violent")

#### violent Type

`number[]`

### warm



`warm`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-warm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/warm")

#### warm Type

`number[]`

### weird



`weird`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-weird.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/weird")

#### weird Type

`number[]`

### whimsical



`whimsical`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1-properties-whimsical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedSegmentsV1/properties/whimsical")

#### whimsical Type

`number[]`

## Definitions group MoodAdvancedTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group MoodAdvancedV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1"}
```

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                           |
| :---------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-5) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/segments")         |
| [scores](#scores-2)     | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/scores") |
| [tags](#tags-4)         | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/tags")     |

### segments



`segments`

* is required

* Type: `object` ([MoodAdvancedSegmentsV1](taggingv8-defs-moodadvancedsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/segments")

#### segments Type

`object` ([MoodAdvancedSegmentsV1](taggingv8-defs-moodadvancedsegmentsv1.md))

### scores



`scores`

* is required

* Type: merged type ([Details](taggingv8-defs-moodadvancedv1-properties-scores.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/scores")

#### scores Type

merged type ([Details](taggingv8-defs-moodadvancedv1-properties-scores.md))

any of

* [MoodAdvancedScoresV1](taggingv8-defs-moodadvancedscoresv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-moodadvancedv1-properties-scores-anyof-1.md "check type definition")

### tags



`tags`

* is required

* Type: merged type ([Tags](taggingv8-defs-moodadvancedv1-properties-tags.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/tags")

#### tags Type

merged type ([Tags](taggingv8-defs-moodadvancedv1-properties-tags.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-moodadvancedv1-properties-tags-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-moodadvancedv1-properties-tags-anyof-1.md "check type definition")

## Definitions group MoodSimpleScoresV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1"}
```

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                           |
| :-------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [aggressive](#aggressive-2) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/aggressive") |
| [calm](#calm-2)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/calm")             |
| [chill](#chill)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-chill.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/chill")           |
| [dark](#dark-2)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/dark")             |
| [energetic](#energetic-2)   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/energetic")   |
| [epic](#epic-4)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/epic")             |
| [happy](#happy-2)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/happy")           |
| [romantic](#romantic-2)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/romantic")     |
| [sad](#sad-2)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/sad")               |
| [scary](#scary-2)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/scary")           |
| [sexy](#sexy-2)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/sexy")             |
| [ethereal](#ethereal-2)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/ethereal")     |
| [uplifting](#uplifting-2)   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/uplifting")   |

### aggressive



`aggressive`

* is required

* Type: `number` ([Aggressive](taggingv8-defs-moodsimplescoresv1-properties-aggressive.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/aggressive")

#### aggressive Type

`number` ([Aggressive](taggingv8-defs-moodsimplescoresv1-properties-aggressive.md))

#### aggressive Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### calm



`calm`

* is required

* Type: `number` ([Calm](taggingv8-defs-moodsimplescoresv1-properties-calm.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/calm")

#### calm Type

`number` ([Calm](taggingv8-defs-moodsimplescoresv1-properties-calm.md))

#### calm Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### chill



`chill`

* is required

* Type: `number` ([Chill](taggingv8-defs-moodsimplescoresv1-properties-chill.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-chill.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/chill")

#### chill Type

`number` ([Chill](taggingv8-defs-moodsimplescoresv1-properties-chill.md))

#### chill Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### dark



`dark`

* is required

* Type: `number` ([Dark](taggingv8-defs-moodsimplescoresv1-properties-dark.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/dark")

#### dark Type

`number` ([Dark](taggingv8-defs-moodsimplescoresv1-properties-dark.md))

#### dark Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### energetic



`energetic`

* is required

* Type: `number` ([Energetic](taggingv8-defs-moodsimplescoresv1-properties-energetic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/energetic")

#### energetic Type

`number` ([Energetic](taggingv8-defs-moodsimplescoresv1-properties-energetic.md))

#### energetic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### epic



`epic`

* is required

* Type: `number` ([Epic](taggingv8-defs-moodsimplescoresv1-properties-epic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/epic")

#### epic Type

`number` ([Epic](taggingv8-defs-moodsimplescoresv1-properties-epic.md))

#### epic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### happy



`happy`

* is required

* Type: `number` ([Happy](taggingv8-defs-moodsimplescoresv1-properties-happy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/happy")

#### happy Type

`number` ([Happy](taggingv8-defs-moodsimplescoresv1-properties-happy.md))

#### happy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### romantic



`romantic`

* is required

* Type: `number` ([Romantic](taggingv8-defs-moodsimplescoresv1-properties-romantic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/romantic")

#### romantic Type

`number` ([Romantic](taggingv8-defs-moodsimplescoresv1-properties-romantic.md))

#### romantic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sad



`sad`

* is required

* Type: `number` ([Sad](taggingv8-defs-moodsimplescoresv1-properties-sad.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/sad")

#### sad Type

`number` ([Sad](taggingv8-defs-moodsimplescoresv1-properties-sad.md))

#### sad Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### scary



`scary`

* is required

* Type: `number` ([Scary](taggingv8-defs-moodsimplescoresv1-properties-scary.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/scary")

#### scary Type

`number` ([Scary](taggingv8-defs-moodsimplescoresv1-properties-scary.md))

#### scary Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### sexy



`sexy`

* is required

* Type: `number` ([Sexy](taggingv8-defs-moodsimplescoresv1-properties-sexy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/sexy")

#### sexy Type

`number` ([Sexy](taggingv8-defs-moodsimplescoresv1-properties-sexy.md))

#### sexy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### ethereal



`ethereal`

* is required

* Type: `number` ([Ethereal](taggingv8-defs-moodsimplescoresv1-properties-ethereal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/ethereal")

#### ethereal Type

`number` ([Ethereal](taggingv8-defs-moodsimplescoresv1-properties-ethereal.md))

#### ethereal Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### uplifting



`uplifting`

* is required

* Type: `number` ([Uplifting](taggingv8-defs-moodsimplescoresv1-properties-uplifting.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/uplifting")

#### uplifting Type

`number` ([Uplifting](taggingv8-defs-moodsimplescoresv1-properties-uplifting.md))

#### uplifting Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## Definitions group MoodSimpleSegmentsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1"}
```

| Property                    | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                               |
| :-------------------------- | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [aggressive](#aggressive-3) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/aggressive") |
| [calm](#calm-3)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/calm")             |
| [chill](#chill-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-chill.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/chill")           |
| [dark](#dark-3)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/dark")             |
| [energetic](#energetic-3)   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/energetic")   |
| [epic](#epic-5)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/epic")             |
| [happy](#happy-3)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/happy")           |
| [romantic](#romantic-3)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/romantic")     |
| [sad](#sad-3)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/sad")               |
| [scary](#scary-3)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/scary")           |
| [sexy](#sexy-3)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/sexy")             |
| [ethereal](#ethereal-3)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/ethereal")     |
| [uplifting](#uplifting-3)   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/uplifting")   |

### aggressive



`aggressive`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/aggressive")

#### aggressive Type

`number[]`

### calm



`calm`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/calm")

#### calm Type

`number[]`

### chill



`chill`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-chill.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/chill")

#### chill Type

`number[]`

### dark



`dark`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/dark")

#### dark Type

`number[]`

### energetic



`energetic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/energetic")

#### energetic Type

`number[]`

### epic



`epic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/epic")

#### epic Type

`number[]`

### happy



`happy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/happy")

#### happy Type

`number[]`

### romantic



`romantic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/romantic")

#### romantic Type

`number[]`

### sad



`sad`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/sad")

#### sad Type

`number[]`

### scary



`scary`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/scary")

#### scary Type

`number[]`

### sexy



`sexy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/sexy")

#### sexy Type

`number[]`

### ethereal



`ethereal`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/ethereal")

#### ethereal Type

`number[]`

### uplifting



`uplifting`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleSegmentsV1/properties/uplifting")

#### uplifting Type

`number[]`

## Definitions group MoodSimpleTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group MoodSimpleV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleV1"}
```

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                       |
| :---------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-6) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplesegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleV1/properties/segments")         |
| [scores](#scores-3)     | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplev1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleV1/properties/scores") |
| [tags](#tags-5)         | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplev1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleV1/properties/tags")     |

### segments



`segments`

* is required

* Type: `object` ([MoodSimpleSegmentsV1](taggingv8-defs-moodsimplesegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplesegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleV1/properties/segments")

#### segments Type

`object` ([MoodSimpleSegmentsV1](taggingv8-defs-moodsimplesegmentsv1.md))

### scores



`scores`

* is required

* Type: merged type ([Details](taggingv8-defs-moodsimplev1-properties-scores.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplev1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleV1/properties/scores")

#### scores Type

merged type ([Details](taggingv8-defs-moodsimplev1-properties-scores.md))

any of

* [MoodSimpleScoresV1](taggingv8-defs-moodsimplescoresv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-moodsimplev1-properties-scores-anyof-1.md "check type definition")

### tags



`tags`

* is required

* Type: merged type ([Tags](taggingv8-defs-moodsimplev1-properties-tags.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplev1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleV1/properties/tags")

#### tags Type

merged type ([Tags](taggingv8-defs-moodsimplev1-properties-tags.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-moodsimplev1-properties-tags-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-moodsimplev1-properties-tags-anyof-1.md "check type definition")

## Definitions group MovementScoresV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1"}
```

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                         |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bouncing](#bouncing)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-bouncing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/bouncing")       |
| [driving](#driving)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-driving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/driving")         |
| [flowing](#flowing)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-flowing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/flowing")         |
| [groovy](#groovy)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-groovy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/groovy")           |
| [nonrhythmic](#nonrhythmic) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-nonrhythmic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/nonrhythmic") |
| [pulsing](#pulsing)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-pulsing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/pulsing")         |
| [robotic](#robotic)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-robotic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/robotic")         |
| [running](#running)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-running.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/running")         |
| [steady](#steady)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-steady.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/steady")           |
| [stomping](#stomping)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-stomping.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/stomping")       |

### bouncing



`bouncing`

* is required

* Type: `number` ([Bouncing](taggingv8-defs-movementscoresv1-properties-bouncing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-bouncing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/bouncing")

#### bouncing Type

`number` ([Bouncing](taggingv8-defs-movementscoresv1-properties-bouncing.md))

#### bouncing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### driving



`driving`

* is required

* Type: `number` ([Driving](taggingv8-defs-movementscoresv1-properties-driving.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-driving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/driving")

#### driving Type

`number` ([Driving](taggingv8-defs-movementscoresv1-properties-driving.md))

#### driving Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### flowing



`flowing`

* is required

* Type: `number` ([Flowing](taggingv8-defs-movementscoresv1-properties-flowing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-flowing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/flowing")

#### flowing Type

`number` ([Flowing](taggingv8-defs-movementscoresv1-properties-flowing.md))

#### flowing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### groovy



`groovy`

* is required

* Type: `number` ([Groovy](taggingv8-defs-movementscoresv1-properties-groovy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-groovy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/groovy")

#### groovy Type

`number` ([Groovy](taggingv8-defs-movementscoresv1-properties-groovy.md))

#### groovy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### nonrhythmic



`nonrhythmic`

* is required

* Type: `number` ([Nonrhythmic](taggingv8-defs-movementscoresv1-properties-nonrhythmic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-nonrhythmic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/nonrhythmic")

#### nonrhythmic Type

`number` ([Nonrhythmic](taggingv8-defs-movementscoresv1-properties-nonrhythmic.md))

#### nonrhythmic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### pulsing



`pulsing`

* is required

* Type: `number` ([Pulsing](taggingv8-defs-movementscoresv1-properties-pulsing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-pulsing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/pulsing")

#### pulsing Type

`number` ([Pulsing](taggingv8-defs-movementscoresv1-properties-pulsing.md))

#### pulsing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### robotic



`robotic`

* is required

* Type: `number` ([Robotic](taggingv8-defs-movementscoresv1-properties-robotic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-robotic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/robotic")

#### robotic Type

`number` ([Robotic](taggingv8-defs-movementscoresv1-properties-robotic.md))

#### robotic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### running



`running`

* is required

* Type: `number` ([Running](taggingv8-defs-movementscoresv1-properties-running.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-running.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/running")

#### running Type

`number` ([Running](taggingv8-defs-movementscoresv1-properties-running.md))

#### running Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### steady



`steady`

* is required

* Type: `number` ([Steady](taggingv8-defs-movementscoresv1-properties-steady.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-steady.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/steady")

#### steady Type

`number` ([Steady](taggingv8-defs-movementscoresv1-properties-steady.md))

#### steady Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### stomping



`stomping`

* is required

* Type: `number` ([Stomping](taggingv8-defs-movementscoresv1-properties-stomping.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-stomping.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/stomping")

#### stomping Type

`number` ([Stomping](taggingv8-defs-movementscoresv1-properties-stomping.md))

#### stomping Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## Definitions group MovementSegmentsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1"}
```

| Property                      | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                             |
| :---------------------------- | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bouncing](#bouncing-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-bouncing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/bouncing")       |
| [driving](#driving-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-driving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/driving")         |
| [flowing](#flowing-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-flowing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/flowing")         |
| [groovy](#groovy-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-groovy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/groovy")           |
| [nonrhythmic](#nonrhythmic-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-nonrhythmic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/nonrhythmic") |
| [pulsing](#pulsing-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-pulsing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/pulsing")         |
| [robotic](#robotic-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-robotic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/robotic")         |
| [running](#running-1)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-running.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/running")         |
| [steady](#steady-1)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-steady.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/steady")           |
| [stomping](#stomping-1)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-stomping.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/stomping")       |

### bouncing



`bouncing`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-bouncing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/bouncing")

#### bouncing Type

`number[]`

### driving



`driving`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-driving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/driving")

#### driving Type

`number[]`

### flowing



`flowing`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-flowing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/flowing")

#### flowing Type

`number[]`

### groovy



`groovy`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-groovy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/groovy")

#### groovy Type

`number[]`

### nonrhythmic



`nonrhythmic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-nonrhythmic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/nonrhythmic")

#### nonrhythmic Type

`number[]`

### pulsing



`pulsing`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-pulsing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/pulsing")

#### pulsing Type

`number[]`

### robotic



`robotic`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-robotic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/robotic")

#### robotic Type

`number[]`

### running



`running`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-running.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/running")

#### running Type

`number[]`

### steady



`steady`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-steady.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/steady")

#### steady Type

`number[]`

### stomping



`stomping`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1-properties-stomping.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementSegmentsV1/properties/stomping")

#### stomping Type

`number[]`

## Definitions group MovementTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group MovementV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1"}
```

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                               |
| :---------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-7) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/segments")     |
| [scores](#scores-4)     | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/scores")         |
| [tags](#tags-6)         | `array`  | Required | cannot be null | [TaggingV8](taggingv8-defs-movementv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/tags") |

### segments



`segments`

* is required

* Type: `object` ([MovementSegmentsV1](taggingv8-defs-movementsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/segments")

#### segments Type

`object` ([MovementSegmentsV1](taggingv8-defs-movementsegmentsv1.md))

### scores



`scores`

* is required

* Type: `object` ([MovementScoresV1](taggingv8-defs-movementscoresv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/scores")

#### scores Type

`object` ([MovementScoresV1](taggingv8-defs-movementscoresv1.md))

### tags



`tags`

* is required

* Type: `string[]` ([MovementTagsV1](taggingv8-defs-movementv1-properties-tags-movementtagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/tags")

#### tags Type

`string[]` ([MovementTagsV1](taggingv8-defs-movementv1-properties-tags-movementtagsv1.md))

## Definitions group MusicalEraTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group MusicalEraV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraV1"}
```

| Property                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                              |
| :---------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [exactYear](#exactyear) | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-musicalerav1-properties-exactyear.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraV1/properties/exactYear")  |
| [tag](#tag-2)           | `string`  | Required | cannot be null | [TaggingV8](taggingv8-defs-musicalerav1-properties-musicaleratagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraV1/properties/tag") |

### exactYear



`exactYear`

* is required

* Type: `integer` ([Exactyear](taggingv8-defs-musicalerav1-properties-exactyear.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-musicalerav1-properties-exactyear.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraV1/properties/exactYear")

#### exactYear Type

`integer` ([Exactyear](taggingv8-defs-musicalerav1-properties-exactyear.md))

#### exactYear Constraints

**maximum**: the value of this number must smaller than or equal to: `2022`

**minimum**: the value of this number must greater than or equal to: `1950`

### tag



`tag`

* is required

* Type: `string` ([MusicalEraTagsV1](taggingv8-defs-musicalerav1-properties-musicaleratagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-musicalerav1-properties-musicaleratagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraV1/properties/tag")

#### tag Type

`string` ([MusicalEraTagsV1](taggingv8-defs-musicalerav1-properties-musicaleratagsv1.md))

#### tag Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                   | Explanation |
| :---------------------- | :---------- |
| `"earlyMid1950s"`       |             |
| `"midLate1950s"`        |             |
| `"late1950sEarly1960s"` |             |
| `"earlyMid1960s"`       |             |
| `"midLate1960s"`        |             |
| `"late1960sEarly1970s"` |             |
| `"earlyMid1970s"`       |             |
| `"midLate1970s"`        |             |
| `"late1970sEarly1980s"` |             |
| `"earlyMid1980s"`       |             |
| `"midLate1980s"`        |             |
| `"late1980sEarly1990s"` |             |
| `"earlyMid1990s"`       |             |
| `"midLate1990s"`        |             |
| `"late1990sEarly2000s"` |             |
| `"earlyMid2000s"`       |             |
| `"midLate2000s"`        |             |
| `"late2000sEarly2010s"` |             |
| `"contemporary"`        |             |

## Definitions group PredominantVocalGenderTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/PredominantVocalGenderTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group PresenceTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/PresenceTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group RepresentativeSegmentIndex15sV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/RepresentativeSegmentIndex15sV1"}
```

| Property                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                             |
| :-------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [thumbnailIndex](#thumbnailindex) | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-representativesegmentindex15sv1-properties-thumbnailindex.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/RepresentativeSegmentIndex15sV1/properties/thumbnailIndex") |

### thumbnailIndex



`thumbnailIndex`

* is required

* Type: `integer` ([Thumbnailindex](taggingv8-defs-representativesegmentindex15sv1-properties-thumbnailindex.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-representativesegmentindex15sv1-properties-thumbnailindex.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/RepresentativeSegmentIndex15sV1/properties/thumbnailIndex")

#### thumbnailIndex Type

`integer` ([Thumbnailindex](taggingv8-defs-representativesegmentindex15sv1-properties-thumbnailindex.md))

## Definitions group SubgenreScoresV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1"}
```

| Property                                    | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :------------------------------------------ | :----- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [abstractIdm](#abstractidm)                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-abstractidm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/abstractIdm")                 |
| [breakbeatDnb](#breakbeatdnb)               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-breakbeatdnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/breakbeatDnb")               |
| [deepHouse](#deephouse)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-deephouse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/deepHouse")                     |
| [electro](#electro)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-electro.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/electro")                         |
| [house](#house)                             | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-house.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/house")                             |
| [minimal](#minimal)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-minimal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/minimal")                         |
| [synthPop](#synthpop)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-synthpop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/synthPop")                       |
| [techHouse](#techhouse)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-techhouse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/techHouse")                     |
| [techno](#techno)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-techno.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/techno")                           |
| [trance](#trance)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-trance.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/trance")                           |
| [medieval](#medieval)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-medieval.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/medieval")                       |
| [renaissance](#renaissance)                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-renaissance.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/renaissance")                 |
| [baroque](#baroque)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-baroque.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/baroque")                         |
| [classical](#classical-2)                   | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-classical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/classical")                     |
| [romantic](#romantic-4)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/romantic")                       |
| [contemporary](#contemporary)               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/contemporary")               |
| [bluesRock](#bluesrock)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bluesrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/bluesRock")                     |
| [folkRock](#folkrock)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-folkrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/folkRock")                       |
| [hardRock](#hardrock)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-hardrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/hardRock")                       |
| [indieAlternative](#indiealternative)       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-indiealternative.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/indieAlternative")       |
| [psychedelicProgRock](#psychedelicprogrock) | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-psychedelicprogrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/psychedelicProgRock") |
| [punk](#punk)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-punk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/punk")                               |
| [rockAndRoll](#rockandroll)                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-rockandroll.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/rockAndRoll")                 |
| [softRock](#softrock)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-softrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/softRock")                       |
| [contemporaryRnb](#contemporaryrnb)         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporaryrnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/contemporaryRnb")         |
| [gangsta](#gangsta)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-gangsta.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/gangsta")                         |
| [jazzyHipHop](#jazzyhiphop)                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-jazzyhiphop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/jazzyHipHop")                 |
| [popRap](#poprap)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-poprap.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/popRap")                           |
| [trap](#trap)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-trap.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/trap")                               |
| [blackMetal](#blackmetal)                   | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-blackmetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/blackMetal")                   |
| [deathMetal](#deathmetal)                   | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-deathmetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/deathMetal")                   |
| [doomMetal](#doommetal)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-doommetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/doomMetal")                     |
| [heavyMetal](#heavymetal)                   | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-heavymetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/heavyMetal")                   |
| [metalcore](#metalcore)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-metalcore.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/metalcore")                     |
| [nuMetal](#numetal)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-numetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/nuMetal")                         |
| [disco](#disco)                             | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-disco.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/disco")                             |
| [funk](#funk)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-funk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/funk")                               |
| [gospel](#gospel)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-gospel.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/gospel")                           |
| [neoSoul](#neosoul)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-neosoul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/neoSoul")                         |
| [soul](#soul)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-soul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/soul")                               |
| [bigBandSwing](#bigbandswing)               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bigbandswing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/bigBandSwing")               |
| [bop](#bop)                                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/bop")                                 |
| [contemporaryJazz](#contemporaryjazz)       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporaryjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/contemporaryJazz")       |
| [easyListening](#easylistening)             | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-easylistening.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/easyListening")             |
| [fusion](#fusion)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-fusion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/fusion")                           |
| [latinJazz](#latinjazz)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-latinjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/latinJazz")                     |
| [smoothJazz](#smoothjazz)                   | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-smoothjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/smoothJazz")                   |
| [country](#country)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-country.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/country")                         |
| [folk](#folk)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-folk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/folk")                               |

### abstractIdm



`abstractIdm`

* is optional

* Type: merged type ([Abstractidm](taggingv8-defs-subgenrescoresv1-properties-abstractidm.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-abstractidm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/abstractIdm")

#### abstractIdm Type

merged type ([Abstractidm](taggingv8-defs-subgenrescoresv1-properties-abstractidm.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-abstractidm-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-abstractidm-anyof-1.md "check type definition")

### breakbeatDnb



`breakbeatDnb`

* is optional

* Type: merged type ([Breakbeatdnb](taggingv8-defs-subgenrescoresv1-properties-breakbeatdnb.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-breakbeatdnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/breakbeatDnb")

#### breakbeatDnb Type

merged type ([Breakbeatdnb](taggingv8-defs-subgenrescoresv1-properties-breakbeatdnb.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-breakbeatdnb-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-breakbeatdnb-anyof-1.md "check type definition")

### deepHouse



`deepHouse`

* is optional

* Type: merged type ([Deephouse](taggingv8-defs-subgenrescoresv1-properties-deephouse.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-deephouse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/deepHouse")

#### deepHouse Type

merged type ([Deephouse](taggingv8-defs-subgenrescoresv1-properties-deephouse.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-deephouse-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-deephouse-anyof-1.md "check type definition")

### electro



`electro`

* is optional

* Type: merged type ([Electro](taggingv8-defs-subgenrescoresv1-properties-electro.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-electro.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/electro")

#### electro Type

merged type ([Electro](taggingv8-defs-subgenrescoresv1-properties-electro.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-electro-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-electro-anyof-1.md "check type definition")

### house



`house`

* is optional

* Type: merged type ([House](taggingv8-defs-subgenrescoresv1-properties-house.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-house.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/house")

#### house Type

merged type ([House](taggingv8-defs-subgenrescoresv1-properties-house.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-house-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-house-anyof-1.md "check type definition")

### minimal



`minimal`

* is optional

* Type: merged type ([Minimal](taggingv8-defs-subgenrescoresv1-properties-minimal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-minimal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/minimal")

#### minimal Type

merged type ([Minimal](taggingv8-defs-subgenrescoresv1-properties-minimal.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-minimal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-minimal-anyof-1.md "check type definition")

### synthPop



`synthPop`

* is optional

* Type: merged type ([Synthpop](taggingv8-defs-subgenrescoresv1-properties-synthpop.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-synthpop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/synthPop")

#### synthPop Type

merged type ([Synthpop](taggingv8-defs-subgenrescoresv1-properties-synthpop.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-synthpop-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-synthpop-anyof-1.md "check type definition")

### techHouse



`techHouse`

* is optional

* Type: merged type ([Techhouse](taggingv8-defs-subgenrescoresv1-properties-techhouse.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-techhouse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/techHouse")

#### techHouse Type

merged type ([Techhouse](taggingv8-defs-subgenrescoresv1-properties-techhouse.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-techhouse-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-techhouse-anyof-1.md "check type definition")

### techno



`techno`

* is optional

* Type: merged type ([Techno](taggingv8-defs-subgenrescoresv1-properties-techno.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-techno.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/techno")

#### techno Type

merged type ([Techno](taggingv8-defs-subgenrescoresv1-properties-techno.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-techno-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-techno-anyof-1.md "check type definition")

### trance



`trance`

* is optional

* Type: merged type ([Trance](taggingv8-defs-subgenrescoresv1-properties-trance.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-trance.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/trance")

#### trance Type

merged type ([Trance](taggingv8-defs-subgenrescoresv1-properties-trance.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-trance-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-trance-anyof-1.md "check type definition")

### medieval



`medieval`

* is optional

* Type: merged type ([Medieval](taggingv8-defs-subgenrescoresv1-properties-medieval.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-medieval.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/medieval")

#### medieval Type

merged type ([Medieval](taggingv8-defs-subgenrescoresv1-properties-medieval.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-medieval-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-medieval-anyof-1.md "check type definition")

### renaissance



`renaissance`

* is optional

* Type: merged type ([Renaissance](taggingv8-defs-subgenrescoresv1-properties-renaissance.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-renaissance.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/renaissance")

#### renaissance Type

merged type ([Renaissance](taggingv8-defs-subgenrescoresv1-properties-renaissance.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-renaissance-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-renaissance-anyof-1.md "check type definition")

### baroque



`baroque`

* is optional

* Type: merged type ([Baroque](taggingv8-defs-subgenrescoresv1-properties-baroque.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-baroque.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/baroque")

#### baroque Type

merged type ([Baroque](taggingv8-defs-subgenrescoresv1-properties-baroque.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-baroque-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-baroque-anyof-1.md "check type definition")

### classical



`classical`

* is optional

* Type: merged type ([Classical](taggingv8-defs-subgenrescoresv1-properties-classical.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-classical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/classical")

#### classical Type

merged type ([Classical](taggingv8-defs-subgenrescoresv1-properties-classical.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-classical-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-classical-anyof-1.md "check type definition")

### romantic



`romantic`

* is optional

* Type: merged type ([Romantic](taggingv8-defs-subgenrescoresv1-properties-romantic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/romantic")

#### romantic Type

merged type ([Romantic](taggingv8-defs-subgenrescoresv1-properties-romantic.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-romantic-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-romantic-anyof-1.md "check type definition")

### contemporary



`contemporary`

* is optional

* Type: merged type ([Contemporary](taggingv8-defs-subgenrescoresv1-properties-contemporary.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/contemporary")

#### contemporary Type

merged type ([Contemporary](taggingv8-defs-subgenrescoresv1-properties-contemporary.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporary-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporary-anyof-1.md "check type definition")

### bluesRock



`bluesRock`

* is optional

* Type: merged type ([Bluesrock](taggingv8-defs-subgenrescoresv1-properties-bluesrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bluesrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/bluesRock")

#### bluesRock Type

merged type ([Bluesrock](taggingv8-defs-subgenrescoresv1-properties-bluesrock.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bluesrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bluesrock-anyof-1.md "check type definition")

### folkRock



`folkRock`

* is optional

* Type: merged type ([Folkrock](taggingv8-defs-subgenrescoresv1-properties-folkrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-folkrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/folkRock")

#### folkRock Type

merged type ([Folkrock](taggingv8-defs-subgenrescoresv1-properties-folkrock.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-folkrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-folkrock-anyof-1.md "check type definition")

### hardRock



`hardRock`

* is optional

* Type: merged type ([Hardrock](taggingv8-defs-subgenrescoresv1-properties-hardrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-hardrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/hardRock")

#### hardRock Type

merged type ([Hardrock](taggingv8-defs-subgenrescoresv1-properties-hardrock.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-hardrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-hardrock-anyof-1.md "check type definition")

### indieAlternative



`indieAlternative`

* is optional

* Type: merged type ([Indiealternative](taggingv8-defs-subgenrescoresv1-properties-indiealternative.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-indiealternative.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/indieAlternative")

#### indieAlternative Type

merged type ([Indiealternative](taggingv8-defs-subgenrescoresv1-properties-indiealternative.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-indiealternative-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-indiealternative-anyof-1.md "check type definition")

### psychedelicProgRock



`psychedelicProgRock`

* is optional

* Type: merged type ([Psychedelicprogrock](taggingv8-defs-subgenrescoresv1-properties-psychedelicprogrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-psychedelicprogrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/psychedelicProgRock")

#### psychedelicProgRock Type

merged type ([Psychedelicprogrock](taggingv8-defs-subgenrescoresv1-properties-psychedelicprogrock.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-psychedelicprogrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-psychedelicprogrock-anyof-1.md "check type definition")

### punk



`punk`

* is optional

* Type: merged type ([Punk](taggingv8-defs-subgenrescoresv1-properties-punk.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-punk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/punk")

#### punk Type

merged type ([Punk](taggingv8-defs-subgenrescoresv1-properties-punk.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-punk-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-punk-anyof-1.md "check type definition")

### rockAndRoll



`rockAndRoll`

* is optional

* Type: merged type ([Rockandroll](taggingv8-defs-subgenrescoresv1-properties-rockandroll.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-rockandroll.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/rockAndRoll")

#### rockAndRoll Type

merged type ([Rockandroll](taggingv8-defs-subgenrescoresv1-properties-rockandroll.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-rockandroll-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-rockandroll-anyof-1.md "check type definition")

### softRock



`softRock`

* is optional

* Type: merged type ([Softrock](taggingv8-defs-subgenrescoresv1-properties-softrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-softrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/softRock")

#### softRock Type

merged type ([Softrock](taggingv8-defs-subgenrescoresv1-properties-softrock.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-softrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-softrock-anyof-1.md "check type definition")

### contemporaryRnb



`contemporaryRnb`

* is optional

* Type: merged type ([Contemporaryrnb](taggingv8-defs-subgenrescoresv1-properties-contemporaryrnb.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporaryrnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/contemporaryRnb")

#### contemporaryRnb Type

merged type ([Contemporaryrnb](taggingv8-defs-subgenrescoresv1-properties-contemporaryrnb.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporaryrnb-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporaryrnb-anyof-1.md "check type definition")

### gangsta



`gangsta`

* is optional

* Type: merged type ([Gangsta](taggingv8-defs-subgenrescoresv1-properties-gangsta.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-gangsta.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/gangsta")

#### gangsta Type

merged type ([Gangsta](taggingv8-defs-subgenrescoresv1-properties-gangsta.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-gangsta-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-gangsta-anyof-1.md "check type definition")

### jazzyHipHop



`jazzyHipHop`

* is optional

* Type: merged type ([Jazzyhiphop](taggingv8-defs-subgenrescoresv1-properties-jazzyhiphop.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-jazzyhiphop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/jazzyHipHop")

#### jazzyHipHop Type

merged type ([Jazzyhiphop](taggingv8-defs-subgenrescoresv1-properties-jazzyhiphop.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-jazzyhiphop-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-jazzyhiphop-anyof-1.md "check type definition")

### popRap



`popRap`

* is optional

* Type: merged type ([Poprap](taggingv8-defs-subgenrescoresv1-properties-poprap.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-poprap.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/popRap")

#### popRap Type

merged type ([Poprap](taggingv8-defs-subgenrescoresv1-properties-poprap.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-poprap-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-poprap-anyof-1.md "check type definition")

### trap



`trap`

* is optional

* Type: merged type ([Trap](taggingv8-defs-subgenrescoresv1-properties-trap.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-trap.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/trap")

#### trap Type

merged type ([Trap](taggingv8-defs-subgenrescoresv1-properties-trap.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-trap-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-trap-anyof-1.md "check type definition")

### blackMetal



`blackMetal`

* is optional

* Type: merged type ([Blackmetal](taggingv8-defs-subgenrescoresv1-properties-blackmetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-blackmetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/blackMetal")

#### blackMetal Type

merged type ([Blackmetal](taggingv8-defs-subgenrescoresv1-properties-blackmetal.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-blackmetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-blackmetal-anyof-1.md "check type definition")

### deathMetal



`deathMetal`

* is optional

* Type: merged type ([Deathmetal](taggingv8-defs-subgenrescoresv1-properties-deathmetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-deathmetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/deathMetal")

#### deathMetal Type

merged type ([Deathmetal](taggingv8-defs-subgenrescoresv1-properties-deathmetal.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-deathmetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-deathmetal-anyof-1.md "check type definition")

### doomMetal



`doomMetal`

* is optional

* Type: merged type ([Doommetal](taggingv8-defs-subgenrescoresv1-properties-doommetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-doommetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/doomMetal")

#### doomMetal Type

merged type ([Doommetal](taggingv8-defs-subgenrescoresv1-properties-doommetal.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-doommetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-doommetal-anyof-1.md "check type definition")

### heavyMetal



`heavyMetal`

* is optional

* Type: merged type ([Heavymetal](taggingv8-defs-subgenrescoresv1-properties-heavymetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-heavymetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/heavyMetal")

#### heavyMetal Type

merged type ([Heavymetal](taggingv8-defs-subgenrescoresv1-properties-heavymetal.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-heavymetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-heavymetal-anyof-1.md "check type definition")

### metalcore



`metalcore`

* is optional

* Type: merged type ([Metalcore](taggingv8-defs-subgenrescoresv1-properties-metalcore.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-metalcore.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/metalcore")

#### metalcore Type

merged type ([Metalcore](taggingv8-defs-subgenrescoresv1-properties-metalcore.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-metalcore-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-metalcore-anyof-1.md "check type definition")

### nuMetal



`nuMetal`

* is optional

* Type: merged type ([Numetal](taggingv8-defs-subgenrescoresv1-properties-numetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-numetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/nuMetal")

#### nuMetal Type

merged type ([Numetal](taggingv8-defs-subgenrescoresv1-properties-numetal.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-numetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-numetal-anyof-1.md "check type definition")

### disco



`disco`

* is optional

* Type: merged type ([Disco](taggingv8-defs-subgenrescoresv1-properties-disco.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-disco.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/disco")

#### disco Type

merged type ([Disco](taggingv8-defs-subgenrescoresv1-properties-disco.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-disco-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-disco-anyof-1.md "check type definition")

### funk



`funk`

* is optional

* Type: merged type ([Funk](taggingv8-defs-subgenrescoresv1-properties-funk.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-funk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/funk")

#### funk Type

merged type ([Funk](taggingv8-defs-subgenrescoresv1-properties-funk.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-funk-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-funk-anyof-1.md "check type definition")

### gospel



`gospel`

* is optional

* Type: merged type ([Gospel](taggingv8-defs-subgenrescoresv1-properties-gospel.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-gospel.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/gospel")

#### gospel Type

merged type ([Gospel](taggingv8-defs-subgenrescoresv1-properties-gospel.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-gospel-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-gospel-anyof-1.md "check type definition")

### neoSoul



`neoSoul`

* is optional

* Type: merged type ([Neosoul](taggingv8-defs-subgenrescoresv1-properties-neosoul.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-neosoul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/neoSoul")

#### neoSoul Type

merged type ([Neosoul](taggingv8-defs-subgenrescoresv1-properties-neosoul.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-neosoul-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-neosoul-anyof-1.md "check type definition")

### soul



`soul`

* is optional

* Type: merged type ([Soul](taggingv8-defs-subgenrescoresv1-properties-soul.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-soul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/soul")

#### soul Type

merged type ([Soul](taggingv8-defs-subgenrescoresv1-properties-soul.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-soul-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-soul-anyof-1.md "check type definition")

### bigBandSwing



`bigBandSwing`

* is optional

* Type: merged type ([Bigbandswing](taggingv8-defs-subgenrescoresv1-properties-bigbandswing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bigbandswing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/bigBandSwing")

#### bigBandSwing Type

merged type ([Bigbandswing](taggingv8-defs-subgenrescoresv1-properties-bigbandswing.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bigbandswing-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bigbandswing-anyof-1.md "check type definition")

### bop



`bop`

* is optional

* Type: merged type ([Bop](taggingv8-defs-subgenrescoresv1-properties-bop.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/bop")

#### bop Type

merged type ([Bop](taggingv8-defs-subgenrescoresv1-properties-bop.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bop-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-bop-anyof-1.md "check type definition")

### contemporaryJazz



`contemporaryJazz`

* is optional

* Type: merged type ([Contemporaryjazz](taggingv8-defs-subgenrescoresv1-properties-contemporaryjazz.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporaryjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/contemporaryJazz")

#### contemporaryJazz Type

merged type ([Contemporaryjazz](taggingv8-defs-subgenrescoresv1-properties-contemporaryjazz.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporaryjazz-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-contemporaryjazz-anyof-1.md "check type definition")

### easyListening



`easyListening`

* is optional

* Type: merged type ([Easylistening](taggingv8-defs-subgenrescoresv1-properties-easylistening.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-easylistening.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/easyListening")

#### easyListening Type

merged type ([Easylistening](taggingv8-defs-subgenrescoresv1-properties-easylistening.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-easylistening-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-easylistening-anyof-1.md "check type definition")

### fusion



`fusion`

* is optional

* Type: merged type ([Fusion](taggingv8-defs-subgenrescoresv1-properties-fusion.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-fusion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/fusion")

#### fusion Type

merged type ([Fusion](taggingv8-defs-subgenrescoresv1-properties-fusion.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-fusion-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-fusion-anyof-1.md "check type definition")

### latinJazz



`latinJazz`

* is optional

* Type: merged type ([Latinjazz](taggingv8-defs-subgenrescoresv1-properties-latinjazz.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-latinjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/latinJazz")

#### latinJazz Type

merged type ([Latinjazz](taggingv8-defs-subgenrescoresv1-properties-latinjazz.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-latinjazz-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-latinjazz-anyof-1.md "check type definition")

### smoothJazz



`smoothJazz`

* is optional

* Type: merged type ([Smoothjazz](taggingv8-defs-subgenrescoresv1-properties-smoothjazz.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-smoothjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/smoothJazz")

#### smoothJazz Type

merged type ([Smoothjazz](taggingv8-defs-subgenrescoresv1-properties-smoothjazz.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-smoothjazz-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-smoothjazz-anyof-1.md "check type definition")

### country



`country`

* is optional

* Type: merged type ([Country](taggingv8-defs-subgenrescoresv1-properties-country.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-country.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/country")

#### country Type

merged type ([Country](taggingv8-defs-subgenrescoresv1-properties-country.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-country-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-country-anyof-1.md "check type definition")

### folk



`folk`

* is optional

* Type: merged type ([Folk](taggingv8-defs-subgenrescoresv1-properties-folk.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrescoresv1-properties-folk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreScoresV1/properties/folk")

#### folk Type

merged type ([Folk](taggingv8-defs-subgenrescoresv1-properties-folk.md))

any of

* [Untitled number in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-folk-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrescoresv1-properties-folk-anyof-1.md "check type definition")

## Definitions group SubgenreSegmentsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1"}
```

| Property                                      | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                                                             |
| :-------------------------------------------- | :----- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [abstractIdm](#abstractidm-1)                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-abstractidm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/abstractIdm")                 |
| [breakbeatDnb](#breakbeatdnb-1)               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-breakbeatdnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/breakbeatDnb")               |
| [deepHouse](#deephouse-1)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-deephouse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/deepHouse")                     |
| [electro](#electro-1)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-electro.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/electro")                         |
| [house](#house-1)                             | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-house.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/house")                             |
| [minimal](#minimal-1)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-minimal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/minimal")                         |
| [synthPop](#synthpop-1)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-synthpop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/synthPop")                       |
| [techHouse](#techhouse-1)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-techhouse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/techHouse")                     |
| [techno](#techno-1)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-techno.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/techno")                           |
| [trance](#trance-1)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-trance.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/trance")                           |
| [medieval](#medieval-1)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-medieval.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/medieval")                       |
| [renaissance](#renaissance-1)                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-renaissance.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/renaissance")                 |
| [baroque](#baroque-1)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-baroque.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/baroque")                         |
| [classical](#classical-3)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-classical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/classical")                     |
| [romantic](#romantic-5)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/romantic")                       |
| [contemporary](#contemporary-1)               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/contemporary")               |
| [bluesRock](#bluesrock-1)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bluesrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/bluesRock")                     |
| [folkRock](#folkrock-1)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-folkrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/folkRock")                       |
| [hardRock](#hardrock-1)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-hardrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/hardRock")                       |
| [indieAlternative](#indiealternative-1)       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-indiealternative.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/indieAlternative")       |
| [psychedelicProgRock](#psychedelicprogrock-1) | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-psychedelicprogrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/psychedelicProgRock") |
| [punk](#punk-1)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-punk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/punk")                               |
| [rockAndRoll](#rockandroll-1)                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-rockandroll.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/rockAndRoll")                 |
| [softRock](#softrock-1)                       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-softrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/softRock")                       |
| [contemporaryRnb](#contemporaryrnb-1)         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporaryrnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/contemporaryRnb")         |
| [gangsta](#gangsta-1)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-gangsta.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/gangsta")                         |
| [jazzyHipHop](#jazzyhiphop-1)                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-jazzyhiphop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/jazzyHipHop")                 |
| [popRap](#poprap-1)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-poprap.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/popRap")                           |
| [trap](#trap-1)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-trap.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/trap")                               |
| [blackMetal](#blackmetal-1)                   | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-blackmetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/blackMetal")                   |
| [deathMetal](#deathmetal-1)                   | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-deathmetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/deathMetal")                   |
| [doomMetal](#doommetal-1)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-doommetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/doomMetal")                     |
| [heavyMetal](#heavymetal-1)                   | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-heavymetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/heavyMetal")                   |
| [metalcore](#metalcore-1)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-metalcore.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/metalcore")                     |
| [nuMetal](#numetal-1)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-numetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/nuMetal")                         |
| [disco](#disco-1)                             | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-disco.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/disco")                             |
| [funk](#funk-1)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-funk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/funk")                               |
| [gospel](#gospel-1)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-gospel.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/gospel")                           |
| [neoSoul](#neosoul-1)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-neosoul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/neoSoul")                         |
| [soul](#soul-1)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-soul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/soul")                               |
| [bigBandSwing](#bigbandswing-1)               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bigbandswing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/bigBandSwing")               |
| [bop](#bop-1)                                 | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/bop")                                 |
| [contemporaryJazz](#contemporaryjazz-1)       | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporaryjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/contemporaryJazz")       |
| [easyListening](#easylistening-1)             | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-easylistening.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/easyListening")             |
| [fusion](#fusion-1)                           | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-fusion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/fusion")                           |
| [latinJazz](#latinjazz-1)                     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-latinjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/latinJazz")                     |
| [smoothJazz](#smoothjazz-1)                   | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-smoothjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/smoothJazz")                   |
| [country](#country-1)                         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-country.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/country")                         |
| [folk](#folk-1)                               | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-folk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/folk")                               |

### abstractIdm



`abstractIdm`

* is optional

* Type: merged type ([Abstractidm](taggingv8-defs-subgenresegmentsv1-properties-abstractidm.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-abstractidm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/abstractIdm")

#### abstractIdm Type

merged type ([Abstractidm](taggingv8-defs-subgenresegmentsv1-properties-abstractidm.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-abstractidm-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-abstractidm-anyof-1.md "check type definition")

### breakbeatDnb



`breakbeatDnb`

* is optional

* Type: merged type ([Breakbeatdnb](taggingv8-defs-subgenresegmentsv1-properties-breakbeatdnb.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-breakbeatdnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/breakbeatDnb")

#### breakbeatDnb Type

merged type ([Breakbeatdnb](taggingv8-defs-subgenresegmentsv1-properties-breakbeatdnb.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-breakbeatdnb-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-breakbeatdnb-anyof-1.md "check type definition")

### deepHouse



`deepHouse`

* is optional

* Type: merged type ([Deephouse](taggingv8-defs-subgenresegmentsv1-properties-deephouse.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-deephouse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/deepHouse")

#### deepHouse Type

merged type ([Deephouse](taggingv8-defs-subgenresegmentsv1-properties-deephouse.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-deephouse-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-deephouse-anyof-1.md "check type definition")

### electro



`electro`

* is optional

* Type: merged type ([Electro](taggingv8-defs-subgenresegmentsv1-properties-electro.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-electro.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/electro")

#### electro Type

merged type ([Electro](taggingv8-defs-subgenresegmentsv1-properties-electro.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-electro-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-electro-anyof-1.md "check type definition")

### house



`house`

* is optional

* Type: merged type ([House](taggingv8-defs-subgenresegmentsv1-properties-house.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-house.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/house")

#### house Type

merged type ([House](taggingv8-defs-subgenresegmentsv1-properties-house.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-house-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-house-anyof-1.md "check type definition")

### minimal



`minimal`

* is optional

* Type: merged type ([Minimal](taggingv8-defs-subgenresegmentsv1-properties-minimal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-minimal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/minimal")

#### minimal Type

merged type ([Minimal](taggingv8-defs-subgenresegmentsv1-properties-minimal.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-minimal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-minimal-anyof-1.md "check type definition")

### synthPop



`synthPop`

* is optional

* Type: merged type ([Synthpop](taggingv8-defs-subgenresegmentsv1-properties-synthpop.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-synthpop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/synthPop")

#### synthPop Type

merged type ([Synthpop](taggingv8-defs-subgenresegmentsv1-properties-synthpop.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-synthpop-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-synthpop-anyof-1.md "check type definition")

### techHouse



`techHouse`

* is optional

* Type: merged type ([Techhouse](taggingv8-defs-subgenresegmentsv1-properties-techhouse.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-techhouse.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/techHouse")

#### techHouse Type

merged type ([Techhouse](taggingv8-defs-subgenresegmentsv1-properties-techhouse.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-techhouse-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-techhouse-anyof-1.md "check type definition")

### techno



`techno`

* is optional

* Type: merged type ([Techno](taggingv8-defs-subgenresegmentsv1-properties-techno.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-techno.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/techno")

#### techno Type

merged type ([Techno](taggingv8-defs-subgenresegmentsv1-properties-techno.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-techno-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-techno-anyof-1.md "check type definition")

### trance



`trance`

* is optional

* Type: merged type ([Trance](taggingv8-defs-subgenresegmentsv1-properties-trance.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-trance.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/trance")

#### trance Type

merged type ([Trance](taggingv8-defs-subgenresegmentsv1-properties-trance.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-trance-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-trance-anyof-1.md "check type definition")

### medieval



`medieval`

* is optional

* Type: merged type ([Medieval](taggingv8-defs-subgenresegmentsv1-properties-medieval.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-medieval.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/medieval")

#### medieval Type

merged type ([Medieval](taggingv8-defs-subgenresegmentsv1-properties-medieval.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-medieval-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-medieval-anyof-1.md "check type definition")

### renaissance



`renaissance`

* is optional

* Type: merged type ([Renaissance](taggingv8-defs-subgenresegmentsv1-properties-renaissance.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-renaissance.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/renaissance")

#### renaissance Type

merged type ([Renaissance](taggingv8-defs-subgenresegmentsv1-properties-renaissance.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-renaissance-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-renaissance-anyof-1.md "check type definition")

### baroque



`baroque`

* is optional

* Type: merged type ([Baroque](taggingv8-defs-subgenresegmentsv1-properties-baroque.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-baroque.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/baroque")

#### baroque Type

merged type ([Baroque](taggingv8-defs-subgenresegmentsv1-properties-baroque.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-baroque-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-baroque-anyof-1.md "check type definition")

### classical



`classical`

* is optional

* Type: merged type ([Classical](taggingv8-defs-subgenresegmentsv1-properties-classical.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-classical.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/classical")

#### classical Type

merged type ([Classical](taggingv8-defs-subgenresegmentsv1-properties-classical.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-classical-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-classical-anyof-1.md "check type definition")

### romantic



`romantic`

* is optional

* Type: merged type ([Romantic](taggingv8-defs-subgenresegmentsv1-properties-romantic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/romantic")

#### romantic Type

merged type ([Romantic](taggingv8-defs-subgenresegmentsv1-properties-romantic.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-romantic-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-romantic-anyof-1.md "check type definition")

### contemporary



`contemporary`

* is optional

* Type: merged type ([Contemporary](taggingv8-defs-subgenresegmentsv1-properties-contemporary.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/contemporary")

#### contemporary Type

merged type ([Contemporary](taggingv8-defs-subgenresegmentsv1-properties-contemporary.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporary-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporary-anyof-1.md "check type definition")

### bluesRock



`bluesRock`

* is optional

* Type: merged type ([Bluesrock](taggingv8-defs-subgenresegmentsv1-properties-bluesrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bluesrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/bluesRock")

#### bluesRock Type

merged type ([Bluesrock](taggingv8-defs-subgenresegmentsv1-properties-bluesrock.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bluesrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bluesrock-anyof-1.md "check type definition")

### folkRock



`folkRock`

* is optional

* Type: merged type ([Folkrock](taggingv8-defs-subgenresegmentsv1-properties-folkrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-folkrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/folkRock")

#### folkRock Type

merged type ([Folkrock](taggingv8-defs-subgenresegmentsv1-properties-folkrock.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-folkrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-folkrock-anyof-1.md "check type definition")

### hardRock



`hardRock`

* is optional

* Type: merged type ([Hardrock](taggingv8-defs-subgenresegmentsv1-properties-hardrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-hardrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/hardRock")

#### hardRock Type

merged type ([Hardrock](taggingv8-defs-subgenresegmentsv1-properties-hardrock.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-hardrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-hardrock-anyof-1.md "check type definition")

### indieAlternative



`indieAlternative`

* is optional

* Type: merged type ([Indiealternative](taggingv8-defs-subgenresegmentsv1-properties-indiealternative.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-indiealternative.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/indieAlternative")

#### indieAlternative Type

merged type ([Indiealternative](taggingv8-defs-subgenresegmentsv1-properties-indiealternative.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-indiealternative-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-indiealternative-anyof-1.md "check type definition")

### psychedelicProgRock



`psychedelicProgRock`

* is optional

* Type: merged type ([Psychedelicprogrock](taggingv8-defs-subgenresegmentsv1-properties-psychedelicprogrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-psychedelicprogrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/psychedelicProgRock")

#### psychedelicProgRock Type

merged type ([Psychedelicprogrock](taggingv8-defs-subgenresegmentsv1-properties-psychedelicprogrock.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-psychedelicprogrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-psychedelicprogrock-anyof-1.md "check type definition")

### punk



`punk`

* is optional

* Type: merged type ([Punk](taggingv8-defs-subgenresegmentsv1-properties-punk.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-punk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/punk")

#### punk Type

merged type ([Punk](taggingv8-defs-subgenresegmentsv1-properties-punk.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-punk-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-punk-anyof-1.md "check type definition")

### rockAndRoll



`rockAndRoll`

* is optional

* Type: merged type ([Rockandroll](taggingv8-defs-subgenresegmentsv1-properties-rockandroll.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-rockandroll.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/rockAndRoll")

#### rockAndRoll Type

merged type ([Rockandroll](taggingv8-defs-subgenresegmentsv1-properties-rockandroll.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-rockandroll-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-rockandroll-anyof-1.md "check type definition")

### softRock



`softRock`

* is optional

* Type: merged type ([Softrock](taggingv8-defs-subgenresegmentsv1-properties-softrock.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-softrock.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/softRock")

#### softRock Type

merged type ([Softrock](taggingv8-defs-subgenresegmentsv1-properties-softrock.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-softrock-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-softrock-anyof-1.md "check type definition")

### contemporaryRnb



`contemporaryRnb`

* is optional

* Type: merged type ([Contemporaryrnb](taggingv8-defs-subgenresegmentsv1-properties-contemporaryrnb.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporaryrnb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/contemporaryRnb")

#### contemporaryRnb Type

merged type ([Contemporaryrnb](taggingv8-defs-subgenresegmentsv1-properties-contemporaryrnb.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporaryrnb-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporaryrnb-anyof-1.md "check type definition")

### gangsta



`gangsta`

* is optional

* Type: merged type ([Gangsta](taggingv8-defs-subgenresegmentsv1-properties-gangsta.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-gangsta.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/gangsta")

#### gangsta Type

merged type ([Gangsta](taggingv8-defs-subgenresegmentsv1-properties-gangsta.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-gangsta-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-gangsta-anyof-1.md "check type definition")

### jazzyHipHop



`jazzyHipHop`

* is optional

* Type: merged type ([Jazzyhiphop](taggingv8-defs-subgenresegmentsv1-properties-jazzyhiphop.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-jazzyhiphop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/jazzyHipHop")

#### jazzyHipHop Type

merged type ([Jazzyhiphop](taggingv8-defs-subgenresegmentsv1-properties-jazzyhiphop.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-jazzyhiphop-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-jazzyhiphop-anyof-1.md "check type definition")

### popRap



`popRap`

* is optional

* Type: merged type ([Poprap](taggingv8-defs-subgenresegmentsv1-properties-poprap.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-poprap.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/popRap")

#### popRap Type

merged type ([Poprap](taggingv8-defs-subgenresegmentsv1-properties-poprap.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-poprap-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-poprap-anyof-1.md "check type definition")

### trap



`trap`

* is optional

* Type: merged type ([Trap](taggingv8-defs-subgenresegmentsv1-properties-trap.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-trap.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/trap")

#### trap Type

merged type ([Trap](taggingv8-defs-subgenresegmentsv1-properties-trap.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-trap-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-trap-anyof-1.md "check type definition")

### blackMetal



`blackMetal`

* is optional

* Type: merged type ([Blackmetal](taggingv8-defs-subgenresegmentsv1-properties-blackmetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-blackmetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/blackMetal")

#### blackMetal Type

merged type ([Blackmetal](taggingv8-defs-subgenresegmentsv1-properties-blackmetal.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-blackmetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-blackmetal-anyof-1.md "check type definition")

### deathMetal



`deathMetal`

* is optional

* Type: merged type ([Deathmetal](taggingv8-defs-subgenresegmentsv1-properties-deathmetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-deathmetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/deathMetal")

#### deathMetal Type

merged type ([Deathmetal](taggingv8-defs-subgenresegmentsv1-properties-deathmetal.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-deathmetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-deathmetal-anyof-1.md "check type definition")

### doomMetal



`doomMetal`

* is optional

* Type: merged type ([Doommetal](taggingv8-defs-subgenresegmentsv1-properties-doommetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-doommetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/doomMetal")

#### doomMetal Type

merged type ([Doommetal](taggingv8-defs-subgenresegmentsv1-properties-doommetal.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-doommetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-doommetal-anyof-1.md "check type definition")

### heavyMetal



`heavyMetal`

* is optional

* Type: merged type ([Heavymetal](taggingv8-defs-subgenresegmentsv1-properties-heavymetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-heavymetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/heavyMetal")

#### heavyMetal Type

merged type ([Heavymetal](taggingv8-defs-subgenresegmentsv1-properties-heavymetal.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-heavymetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-heavymetal-anyof-1.md "check type definition")

### metalcore



`metalcore`

* is optional

* Type: merged type ([Metalcore](taggingv8-defs-subgenresegmentsv1-properties-metalcore.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-metalcore.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/metalcore")

#### metalcore Type

merged type ([Metalcore](taggingv8-defs-subgenresegmentsv1-properties-metalcore.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-metalcore-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-metalcore-anyof-1.md "check type definition")

### nuMetal



`nuMetal`

* is optional

* Type: merged type ([Numetal](taggingv8-defs-subgenresegmentsv1-properties-numetal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-numetal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/nuMetal")

#### nuMetal Type

merged type ([Numetal](taggingv8-defs-subgenresegmentsv1-properties-numetal.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-numetal-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-numetal-anyof-1.md "check type definition")

### disco



`disco`

* is optional

* Type: merged type ([Disco](taggingv8-defs-subgenresegmentsv1-properties-disco.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-disco.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/disco")

#### disco Type

merged type ([Disco](taggingv8-defs-subgenresegmentsv1-properties-disco.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-disco-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-disco-anyof-1.md "check type definition")

### funk



`funk`

* is optional

* Type: merged type ([Funk](taggingv8-defs-subgenresegmentsv1-properties-funk.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-funk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/funk")

#### funk Type

merged type ([Funk](taggingv8-defs-subgenresegmentsv1-properties-funk.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-funk-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-funk-anyof-1.md "check type definition")

### gospel



`gospel`

* is optional

* Type: merged type ([Gospel](taggingv8-defs-subgenresegmentsv1-properties-gospel.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-gospel.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/gospel")

#### gospel Type

merged type ([Gospel](taggingv8-defs-subgenresegmentsv1-properties-gospel.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-gospel-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-gospel-anyof-1.md "check type definition")

### neoSoul



`neoSoul`

* is optional

* Type: merged type ([Neosoul](taggingv8-defs-subgenresegmentsv1-properties-neosoul.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-neosoul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/neoSoul")

#### neoSoul Type

merged type ([Neosoul](taggingv8-defs-subgenresegmentsv1-properties-neosoul.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-neosoul-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-neosoul-anyof-1.md "check type definition")

### soul



`soul`

* is optional

* Type: merged type ([Soul](taggingv8-defs-subgenresegmentsv1-properties-soul.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-soul.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/soul")

#### soul Type

merged type ([Soul](taggingv8-defs-subgenresegmentsv1-properties-soul.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-soul-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-soul-anyof-1.md "check type definition")

### bigBandSwing



`bigBandSwing`

* is optional

* Type: merged type ([Bigbandswing](taggingv8-defs-subgenresegmentsv1-properties-bigbandswing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bigbandswing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/bigBandSwing")

#### bigBandSwing Type

merged type ([Bigbandswing](taggingv8-defs-subgenresegmentsv1-properties-bigbandswing.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bigbandswing-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bigbandswing-anyof-1.md "check type definition")

### bop



`bop`

* is optional

* Type: merged type ([Bop](taggingv8-defs-subgenresegmentsv1-properties-bop.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bop.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/bop")

#### bop Type

merged type ([Bop](taggingv8-defs-subgenresegmentsv1-properties-bop.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bop-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-bop-anyof-1.md "check type definition")

### contemporaryJazz



`contemporaryJazz`

* is optional

* Type: merged type ([Contemporaryjazz](taggingv8-defs-subgenresegmentsv1-properties-contemporaryjazz.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporaryjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/contemporaryJazz")

#### contemporaryJazz Type

merged type ([Contemporaryjazz](taggingv8-defs-subgenresegmentsv1-properties-contemporaryjazz.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporaryjazz-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-contemporaryjazz-anyof-1.md "check type definition")

### easyListening



`easyListening`

* is optional

* Type: merged type ([Easylistening](taggingv8-defs-subgenresegmentsv1-properties-easylistening.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-easylistening.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/easyListening")

#### easyListening Type

merged type ([Easylistening](taggingv8-defs-subgenresegmentsv1-properties-easylistening.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-easylistening-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-easylistening-anyof-1.md "check type definition")

### fusion



`fusion`

* is optional

* Type: merged type ([Fusion](taggingv8-defs-subgenresegmentsv1-properties-fusion.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-fusion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/fusion")

#### fusion Type

merged type ([Fusion](taggingv8-defs-subgenresegmentsv1-properties-fusion.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-fusion-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-fusion-anyof-1.md "check type definition")

### latinJazz



`latinJazz`

* is optional

* Type: merged type ([Latinjazz](taggingv8-defs-subgenresegmentsv1-properties-latinjazz.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-latinjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/latinJazz")

#### latinJazz Type

merged type ([Latinjazz](taggingv8-defs-subgenresegmentsv1-properties-latinjazz.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-latinjazz-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-latinjazz-anyof-1.md "check type definition")

### smoothJazz



`smoothJazz`

* is optional

* Type: merged type ([Smoothjazz](taggingv8-defs-subgenresegmentsv1-properties-smoothjazz.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-smoothjazz.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/smoothJazz")

#### smoothJazz Type

merged type ([Smoothjazz](taggingv8-defs-subgenresegmentsv1-properties-smoothjazz.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-smoothjazz-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-smoothjazz-anyof-1.md "check type definition")

### country



`country`

* is optional

* Type: merged type ([Country](taggingv8-defs-subgenresegmentsv1-properties-country.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-country.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/country")

#### country Type

merged type ([Country](taggingv8-defs-subgenresegmentsv1-properties-country.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-country-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-country-anyof-1.md "check type definition")

### folk



`folk`

* is optional

* Type: merged type ([Folk](taggingv8-defs-subgenresegmentsv1-properties-folk.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-folk.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreSegmentsV1/properties/folk")

#### folk Type

merged type ([Folk](taggingv8-defs-subgenresegmentsv1-properties-folk.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-folk-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenresegmentsv1-properties-folk-anyof-1.md "check type definition")

## Definitions group SubgenreTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group SubgenreV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1"}
```

| Property                | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                       |
| :---------------------- | :----- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-8) | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrev1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/segments") |
| [scores](#scores-5)     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrev1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/scores")     |
| [tags](#tags-7)         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrev1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/tags")         |

### segments



`segments`

* is optional

* Type: merged type ([Details](taggingv8-defs-subgenrev1-properties-segments.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrev1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/segments")

#### segments Type

merged type ([Details](taggingv8-defs-subgenrev1-properties-segments.md))

any of

* [SubgenreSegmentsV1](taggingv8-defs-subgenresegmentsv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrev1-properties-segments-anyof-1.md "check type definition")

### scores



`scores`

* is optional

* Type: merged type ([Details](taggingv8-defs-subgenrev1-properties-scores.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrev1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/scores")

#### scores Type

merged type ([Details](taggingv8-defs-subgenrev1-properties-scores.md))

any of

* [SubgenreScoresV1](taggingv8-defs-subgenrescoresv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrev1-properties-scores-anyof-1.md "check type definition")

### tags



`tags`

* is optional

* Type: merged type ([Tags](taggingv8-defs-subgenrev1-properties-tags.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrev1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/tags")

#### tags Type

merged type ([Tags](taggingv8-defs-subgenrev1-properties-tags.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenrev1-properties-tags-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrev1-properties-tags-anyof-1.md "check type definition")

## Definitions group TimeSignatureTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group TimeSignatureV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureV1"}
```

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                       |
| :-------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [tag](#tag-3)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-timesignaturev1-properties-timesignaturetagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureV1/properties/tag") |
| [confidence](#confidence-2) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-timesignaturev1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureV1/properties/confidence")   |

### tag



`tag`

* is required

* Type: `string` ([TimeSignatureTagsV1](taggingv8-defs-timesignaturev1-properties-timesignaturetagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-timesignaturev1-properties-timesignaturetagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureV1/properties/tag")

#### tag Type

`string` ([TimeSignatureTagsV1](taggingv8-defs-timesignaturev1-properties-timesignaturetagsv1.md))

#### tag Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | :---------- |
| `"3_4"` |             |
| `"4_4"` |             |

### confidence



`confidence`

* is required

* Type: `number` ([Confidence](taggingv8-defs-timesignaturev1-properties-confidence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-timesignaturev1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureV1/properties/confidence")

#### confidence Type

`number` ([Confidence](taggingv8-defs-timesignaturev1-properties-confidence.md))

#### confidence Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## Definitions group Timestamps15sV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/Timestamps15sV1"}
```

| Property                  | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                     |
| :------------------------ | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [timestamps](#timestamps) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-timestamps15sv1-properties-timestamps.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/Timestamps15sV1/properties/timestamps") |

### timestamps



`timestamps`

* is required

* Type: `integer[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-timestamps15sv1-properties-timestamps.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/Timestamps15sV1/properties/timestamps")

#### timestamps Type

`integer[]`

## Definitions group ValenceArousalScoresV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalScoresV1"}
```

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                             |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [valence](#valence) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalscoresv1-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalScoresV1/properties/valence") |
| [arousal](#arousal) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalscoresv1-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalScoresV1/properties/arousal") |

### valence



`valence`

* is required

* Type: `number` ([Valence](taggingv8-defs-valencearousalscoresv1-properties-valence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalscoresv1-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalScoresV1/properties/valence")

#### valence Type

`number` ([Valence](taggingv8-defs-valencearousalscoresv1-properties-valence.md))

#### valence Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `-1`

### arousal



`arousal`

* is required

* Type: `number` ([Arousal](taggingv8-defs-valencearousalscoresv1-properties-arousal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalscoresv1-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalScoresV1/properties/arousal")

#### arousal Type

`number` ([Arousal](taggingv8-defs-valencearousalscoresv1-properties-arousal.md))

#### arousal Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `-1`

## Definitions group ValenceArousalSegmentsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalSegmentsV1"}
```

| Property              | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                 |
| :-------------------- | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [valence](#valence-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalsegmentsv1-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalSegmentsV1/properties/valence") |
| [arousal](#arousal-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalsegmentsv1-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalSegmentsV1/properties/arousal") |

### valence



`valence`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalsegmentsv1-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalSegmentsV1/properties/valence")

#### valence Type

`number[]`

### arousal



`arousal`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalsegmentsv1-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalSegmentsV1/properties/arousal")

#### arousal Type

`number[]`

## Definitions group ValenceArousalV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1"}
```

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                     |
| :-------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-9)           | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/segments")                               |
| [scores](#scores-6)               | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalscoresv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/scores")                                   |
| [energyLevel](#energylevel)       | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalv1-properties-energyleveltagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/energyLevel")       |
| [energyChanges](#energychanges)   | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalv1-properties-energychangestagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/energyChanges")   |
| [emotionProfile](#emotionprofile) | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalv1-properties-emotionprofiletagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/emotionProfile") |
| [emotionChanges](#emotionchanges) | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalv1-properties-emotionchangestagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/emotionChanges") |

### segments



`segments`

* is required

* Type: `object` ([ValenceArousalSegmentsV1](taggingv8-defs-valencearousalsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/segments")

#### segments Type

`object` ([ValenceArousalSegmentsV1](taggingv8-defs-valencearousalsegmentsv1.md))

### scores



`scores`

* is required

* Type: `object` ([ValenceArousalScoresV1](taggingv8-defs-valencearousalscoresv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalscoresv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/scores")

#### scores Type

`object` ([ValenceArousalScoresV1](taggingv8-defs-valencearousalscoresv1.md))

### energyLevel



`energyLevel`

* is required

* Type: `string` ([EnergyLevelTagsV1](taggingv8-defs-valencearousalv1-properties-energyleveltagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalv1-properties-energyleveltagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/energyLevel")

#### energyLevel Type

`string` ([EnergyLevelTagsV1](taggingv8-defs-valencearousalv1-properties-energyleveltagsv1.md))

#### energyLevel Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"low"`     |             |
| `"medium"`  |             |
| `"high"`    |             |
| `"varying"` |             |

### energyChanges



`energyChanges`

* is required

* Type: `string` ([EnergyChangesTagsV1](taggingv8-defs-valencearousalv1-properties-energychangestagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalv1-properties-energychangestagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/energyChanges")

#### energyChanges Type

`string` ([EnergyChangesTagsV1](taggingv8-defs-valencearousalv1-properties-energychangestagsv1.md))

#### energyChanges Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"low"`    |             |
| `"medium"` |             |
| `"high"`   |             |

### emotionProfile



`emotionProfile`

* is required

* Type: `string` ([EmotionProfileTagsV1](taggingv8-defs-valencearousalv1-properties-emotionprofiletagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalv1-properties-emotionprofiletagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/emotionProfile")

#### emotionProfile Type

`string` ([EmotionProfileTagsV1](taggingv8-defs-valencearousalv1-properties-emotionprofiletagsv1.md))

#### emotionProfile Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"negative"` |             |
| `"neutral"`  |             |
| `"positive"` |             |
| `"varying"`  |             |

### emotionChanges



`emotionChanges`

* is required

* Type: `string` ([EmotionChangesTagsV1](taggingv8-defs-valencearousalv1-properties-emotionchangestagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalv1-properties-emotionchangestagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/emotionChanges")

#### emotionChanges Type

`string` ([EmotionChangesTagsV1](taggingv8-defs-valencearousalv1-properties-emotionchangestagsv1.md))

#### emotionChanges Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"low"`    |             |
| `"medium"` |             |
| `"high"`   |             |

## Definitions group VocalPresenceTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalPresenceTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group VocalScoresV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1"}
```

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                     |
| :---------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [female](#female)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalscoresv1-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/female")             |
| [male](#male)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalscoresv1-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/male")                 |
| [instrumental](#instrumental) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalscoresv1-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/instrumental") |

### female



`female`

* is required

* Type: `number` ([Female](taggingv8-defs-vocalscoresv1-properties-female.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalscoresv1-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/female")

#### female Type

`number` ([Female](taggingv8-defs-vocalscoresv1-properties-female.md))

#### female Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### male



`male`

* is required

* Type: `number` ([Male](taggingv8-defs-vocalscoresv1-properties-male.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalscoresv1-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/male")

#### male Type

`number` ([Male](taggingv8-defs-vocalscoresv1-properties-male.md))

#### male Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### instrumental



`instrumental`

* is required

* Type: `number` ([Instrumental](taggingv8-defs-vocalscoresv1-properties-instrumental.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalscoresv1-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/instrumental")

#### instrumental Type

`number` ([Instrumental](taggingv8-defs-vocalscoresv1-properties-instrumental.md))

#### instrumental Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## Definitions group VocalSegmentsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1"}
```

| Property                        | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                         |
| :------------------------------ | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [female](#female-1)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/female")             |
| [male](#male-1)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/male")                 |
| [instrumental](#instrumental-1) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/instrumental") |

### female



`female`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/female")

#### female Type

`number[]`

### male



`male`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/male")

#### male Type

`number[]`

### instrumental



`instrumental`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/instrumental")

#### instrumental Type

`number[]`

## Definitions group VocalTagsV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalTagsV1"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group VocalV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1"}
```

| Property                                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                             |
| :------------------------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments-10)                          | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/segments")                                         |
| [scores](#scores-7)                               | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/scores")                                 |
| [tags](#tags-8)                                   | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/tags")                                     |
| [vocalPresence](#vocalpresence)                   | Merged   | Optional | cannot be null | [TaggingV8](taggingv8-defs-vocalv1-properties-vocalpresence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/vocalPresence")                   |
| [predominantVocalGender](#predominantvocalgender) | Merged   | Optional | cannot be null | [TaggingV8](taggingv8-defs-vocalv1-properties-predominantvocalgender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/predominantVocalGender") |

### segments



`segments`

* is required

* Type: `object` ([VocalSegmentsV1](taggingv8-defs-vocalsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/segments")

#### segments Type

`object` ([VocalSegmentsV1](taggingv8-defs-vocalsegmentsv1.md))

### scores



`scores`

* is required

* Type: merged type ([Details](taggingv8-defs-vocalv1-properties-scores.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/scores")

#### scores Type

merged type ([Details](taggingv8-defs-vocalv1-properties-scores.md))

any of

* [VocalScoresV1](taggingv8-defs-vocalscoresv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-vocalv1-properties-scores-anyof-1.md "check type definition")

### tags



`tags`

* is required

* Type: merged type ([Tags](taggingv8-defs-vocalv1-properties-tags.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/tags")

#### tags Type

merged type ([Tags](taggingv8-defs-vocalv1-properties-tags.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-vocalv1-properties-tags-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-vocalv1-properties-tags-anyof-1.md "check type definition")

### vocalPresence



`vocalPresence`

* is optional

* Type: merged type ([Details](taggingv8-defs-vocalv1-properties-vocalpresence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalv1-properties-vocalpresence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/vocalPresence")

#### vocalPresence Type

merged type ([Details](taggingv8-defs-vocalv1-properties-vocalpresence.md))

any of

* [VocalPresenceTagsV1](taggingv8-defs-vocalv1-properties-vocalpresence-anyof-vocalpresencetagsv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-vocalv1-properties-vocalpresence-anyof-1.md "check type definition")

### predominantVocalGender



`predominantVocalGender`

* is optional

* Type: merged type ([Details](taggingv8-defs-vocalv1-properties-predominantvocalgender.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalv1-properties-predominantvocalgender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/predominantVocalGender")

#### predominantVocalGender Type

merged type ([Details](taggingv8-defs-vocalv1-properties-predominantvocalgender.md))

any of

* [PredominantVocalGenderTagsV1](taggingv8-defs-vocalv1-properties-predominantvocalgender-anyof-predominantvocalgendertagsv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-vocalv1-properties-predominantvocalgender-anyof-1.md "check type definition")

## Definitions group VoiceoverV1

Reference this group by using

```json
{"$ref":"https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VoiceoverV1"}
```

| Property                                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                               |
| :------------------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [voiceoverDegree](#voiceoverdegree)         | `number`  | Required | cannot be null | [TaggingV8](taggingv8-defs-voiceoverv1-properties-voiceoverdegree.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VoiceoverV1/properties/voiceoverDegree")         |
| [isVoiceoverDominant](#isvoiceoverdominant) | `boolean` | Required | cannot be null | [TaggingV8](taggingv8-defs-voiceoverv1-properties-isvoiceoverdominant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VoiceoverV1/properties/isVoiceoverDominant") |

### voiceoverDegree



`voiceoverDegree`

* is required

* Type: `number` ([Voiceoverdegree](taggingv8-defs-voiceoverv1-properties-voiceoverdegree.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-voiceoverv1-properties-voiceoverdegree.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VoiceoverV1/properties/voiceoverDegree")

#### voiceoverDegree Type

`number` ([Voiceoverdegree](taggingv8-defs-voiceoverv1-properties-voiceoverdegree.md))

#### voiceoverDegree Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### isVoiceoverDominant



`isVoiceoverDominant`

* is required

* Type: `boolean` ([Isvoiceoverdominant](taggingv8-defs-voiceoverv1-properties-isvoiceoverdominant.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-voiceoverv1-properties-isvoiceoverdominant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VoiceoverV1/properties/isVoiceoverDominant")

#### isVoiceoverDominant Type

`boolean` ([Isvoiceoverdominant](taggingv8-defs-voiceoverv1-properties-isvoiceoverdominant.md))
