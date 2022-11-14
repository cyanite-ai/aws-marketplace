# Untitled object in marketplace\_v1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [marketplace\_v1.schema.json\*](../schema/marketplace_v1.schema.json "open original schema") |

## voice\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-voice_v8.md))

# voice\_v8 Properties

| Property                                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                  |
| :------------------------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [tags](#tags)                                     | `array`  | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/tags")                                     |
| [mean](#mean)                                     | `object` | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-mean.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/mean")                                     |
| [segments](#segments)                             | `object` | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/segments")                             |
| [voicePresenceProfile](#voicepresenceprofile)     | `string` | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-voicepresenceprofile.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/voicePresenceProfile")     |
| [predominantVoiceGender](#predominantvoicegender) | `string` | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-predominantvoicegender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/predominantVoiceGender") |

## tags



`tags`

*   is required

*   Type: `string[]`

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/tags")

### tags Type

`string[]`

## mean



`mean`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-voice_v8-properties-mean.md))

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-mean.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/mean")

### mean Type

`object` ([Details](marketplace_v1-properties-analysis-properties-voice_v8-properties-mean.md))

## segments



`segments`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments.md))

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/segments")

### segments Type

`object` ([Details](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments.md))

## voicePresenceProfile



`voicePresenceProfile`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-voicepresenceprofile.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/voicePresenceProfile")

### voicePresenceProfile Type

`string`

## predominantVoiceGender



`predominantVoiceGender`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-voice_v8-properties-predominantvoicegender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/voice_v8/properties/predominantVoiceGender")

### predominantVoiceGender Type

`string`
