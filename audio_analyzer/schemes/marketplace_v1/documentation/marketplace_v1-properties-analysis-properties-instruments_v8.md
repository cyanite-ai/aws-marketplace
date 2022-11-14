# Untitled object in marketplace\_v1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/instruments_v8
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [marketplace\_v1.schema.json\*](../schema/marketplace_v1.schema.json "open original schema") |

## instruments\_v8 Type

`object` ([Details](marketplace_v1-properties-analysis-properties-instruments_v8.md))

# instruments\_v8 Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                  |
| :-------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [tags](#tags)         | `array`  | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-instruments_v8-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/instruments_v8/properties/tags")         |
| [segments](#segments) | `object` | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-instruments_v8-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/instruments_v8/properties/segments") |
| [presence](#presence) | `object` | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis-properties-instruments_v8-properties-presence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/instruments_v8/properties/presence") |

## tags



`tags`

*   is required

*   Type: `string[]`

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-instruments_v8-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/instruments_v8/properties/tags")

### tags Type

`string[]`

## segments



`segments`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-instruments_v8-properties-segments.md))

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-instruments_v8-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/instruments_v8/properties/segments")

### segments Type

`object` ([Details](marketplace_v1-properties-analysis-properties-instruments_v8-properties-segments.md))

## presence



`presence`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis-properties-instruments_v8-properties-presence.md))

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis-properties-instruments_v8-properties-presence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis/properties/instruments_v8/properties/presence")

### presence Type

`object` ([Details](marketplace_v1-properties-analysis-properties-instruments_v8-properties-presence.md))
