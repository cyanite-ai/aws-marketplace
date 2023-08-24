# Untitled object in marketplace\_v1.1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voice_v8/properties/segments
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [marketplace\_v1.1.schema.json\*](../schema/marketplace_v1.1.schema.json "open original schema") |

## segments Type

`object` ([Details](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments.md))

# segments Properties

| Property                      | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                            |
| :---------------------------- | :------ | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [female](#female)             | `array` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voice_v8/properties/segments/properties/female")             |
| [instrumental](#instrumental) | `array` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voice_v8/properties/segments/properties/instrumental") |
| [male](#male)                 | `array` | Required | cannot be null | [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voice_v8/properties/segments/properties/male")                 |

## female



`female`

*   is required

*   Type: `number[]`

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voice_v8/properties/segments/properties/female")

### female Type

`number[]`

## instrumental



`instrumental`

*   is required

*   Type: `number[]`

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voice_v8/properties/segments/properties/instrumental")

### instrumental Type

`number[]`

## male



`male`

*   is required

*   Type: `number[]`

*   cannot be null

*   defined in: [marketplace\_v1.1](marketplace_v1-properties-analysis-properties-voice_v8-properties-segments-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1.1/schema/marketplace_v1.1.schema.json#/properties/analysis/properties/voice_v8/properties/segments/properties/male")

### male Type

`number[]`
