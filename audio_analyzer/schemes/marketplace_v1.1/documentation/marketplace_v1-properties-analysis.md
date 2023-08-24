# Untitled object in marketplace\_v1.1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [marketplace\_v1.1.schema.json\*](../schema/marketplace_v1.1.schema.json "open original schema") |

## analysis Type

`object` ([Details](marketplace_v1-properties-analysis.md))

# analysis Properties

| Property                                             | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                  |
| :--------------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [genre\_v8](#genre_v8)                               | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-genre_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/genre_v8")                               |
| [mood\_v8](#mood_v8)                                 | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-mood_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/mood_v8")                                 |
| [moodAdvanced\_v8](#moodadvanced_v8)                 | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-moodadvanced_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/moodAdvanced_v8")                 |
| [character\_v8](#character_v8)                       | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-character_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/character_v8")                       |
| [movement\_v8](#movement_v8)                         | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-movement_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/movement_v8")                         |
| [instruments\_v8](#instruments_v8)                   | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-instruments_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/instruments_v8")                   |
| [voice\_v8](#voice_v8)                               | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voice_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voice_v8")                               |
| [valenceArousal\_v8](#valencearousal_v8)             | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-valencearousal_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/valenceArousal_v8")             |
| [musicalEra\_v8](#musicalera_v8)                     | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-musicalera_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/musicalEra_v8")                     |
| [musicalFeatures\_v8](#musicalfeatures_v8)           | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-musicalfeatures_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/musicalFeatures_v8")           |
| [voiceover\_v8](#voiceover_v8)                       | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voiceover_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voiceover_v8")                       |
| [transformerCaption\_v8](#transformercaption_v8)     | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-transformercaption_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/transformerCaption_v8")     |
| [transformerGenreTags\_v8](#transformergenretags_v8) | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-transformergenretags_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/transformerGenreTags_v8") |
| [augmentedKeywords\_v8](#augmentedkeywords_v8)       | `object` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-augmentedkeywords_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/augmentedKeywords_v8")       |

## genre\_v8



`genre_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-genre_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-genre_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/genre_v8")

### genre\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-genre_v8.md))

## mood\_v8



`mood_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-mood_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-mood_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/mood_v8")

### mood\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-mood_v8.md))

## moodAdvanced\_v8



`moodAdvanced_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-moodadvanced_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-moodadvanced_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/moodAdvanced_v8")

### moodAdvanced\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-moodadvanced_v8.md))

## character\_v8



`character_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-character_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-character_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/character_v8")

### character\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-character_v8.md))

## movement\_v8



`movement_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-movement_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-movement_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/movement_v8")

### movement\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-movement_v8.md))

## instruments\_v8



`instruments_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-instruments_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-instruments_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/instruments_v8")

### instruments\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-instruments_v8.md))

## voice\_v8



`voice_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-voice_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voice_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voice_v8")

### voice\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-voice_v8.md))

## valenceArousal\_v8



`valenceArousal_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-valencearousal_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-valencearousal_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/valenceArousal_v8")

### valenceArousal\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-valencearousal_v8.md))

## musicalEra\_v8



`musicalEra_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-musicalera_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-musicalera_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/musicalEra_v8")

### musicalEra\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-musicalera_v8.md))

## musicalFeatures\_v8



`musicalFeatures_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-musicalfeatures_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-musicalfeatures_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/musicalFeatures_v8")

### musicalFeatures\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-musicalfeatures_v8.md))

## voiceover\_v8



`voiceover_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-voiceover_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voiceover_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voiceover_v8")

### voiceover\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-voiceover_v8.md))

## transformerCaption\_v8



`transformerCaption_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-transformercaption_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-transformercaption_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/transformerCaption_v8")

### transformerCaption\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-transformercaption_v8.md))

## transformerGenreTags\_v8



`transformerGenreTags_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-transformergenretags_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-transformergenretags_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/transformerGenreTags_v8")

### transformerGenreTags\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-transformergenretags_v8.md))

## augmentedKeywords\_v8



`augmentedKeywords_v8`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-augmentedkeywords_v8.md))

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-augmentedkeywords_v8.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/augmentedKeywords_v8")

### augmentedKeywords\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-augmentedkeywords_v8.md))
