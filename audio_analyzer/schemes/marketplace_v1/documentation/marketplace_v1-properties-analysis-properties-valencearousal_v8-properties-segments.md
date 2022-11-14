# Untitled object in marketplace\_v1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/valenceArousal_v8/properties/segments
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [marketplace\_v1.schema.json\*](../schema/marketplace_v1.schema.json "open original schema") |

## segments Type

`object` ([Details](marketplace_v1-properties-analysis-properties-valencearousal_v8-properties-segments.md))

# segments Properties

| Property            | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                              |
| :------------------ | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [valence](#valence) | `array` | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-valencearousal_v8-properties-segments-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/valenceArousal_v8/properties/segments/properties/valence") |
| [arousal](#arousal) | `array` | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-valencearousal_v8-properties-segments-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/valenceArousal_v8/properties/segments/properties/arousal") |

## valence



`valence`

*   is required

*   Type: `number[]`

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-valencearousal_v8-properties-segments-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/valenceArousal_v8/properties/segments/properties/valence")

### valence Type

`number[]`

## arousal



`arousal`

*   is required

*   Type: `number[]`

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-valencearousal_v8-properties-segments-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/valenceArousal_v8/properties/segments/properties/arousal")

### arousal Type

`number[]`
