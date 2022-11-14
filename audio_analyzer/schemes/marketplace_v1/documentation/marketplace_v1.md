# marketplace\_v1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json
```

This schema describes the json object returned by the Cyanite Audio Analyzer for version marketplace\_v1.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [marketplace\_v1.schema.json](../schema/marketplace_v1.schema.json "open original schema") |

## marketplace\_v1 Type

`object` ([marketplace\_v1](marketplace_v1.md))

# marketplace\_v1 Properties

| Property                                                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                          |
| :-------------------------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [version](#version)                                       | `string`  | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-version.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/version")                                       |
| [analysis](#analysis)                                     | `object`  | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-analysis.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis")                                     |
| [representativeSegmentIndex](#representativesegmentindex) | `integer` | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-representativesegmentindex.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/representativeSegmentIndex") |
| [timestamps](#timestamps)                                 | `array`   | Required | cannot be null | [marketplace\_v1](marketplace_v1-properties-timestamps.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/timestamps")                                 |

## version



`version`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-version.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/version")

### version Type

`string`

## analysis



`analysis`

*   is required

*   Type: `object` ([Details](marketplace_v1-properties-analysis.md))

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-analysis.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/analysis")

### analysis Type

`object` ([Details](marketplace_v1-properties-analysis.md))

## representativeSegmentIndex



`representativeSegmentIndex`

*   is required

*   Type: `integer`

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-representativesegmentindex.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/representativeSegmentIndex")

### representativeSegmentIndex Type

`integer`

## timestamps



`timestamps`

*   is required

*   Type: `integer[]`

*   cannot be null

*   defined in: [marketplace\_v1](marketplace_v1-properties-timestamps.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/marketplace_v1.schema.json#/properties/timestamps")

### timestamps Type

`integer[]`
