# KeyV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/key
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## key Type

`object` ([KeyV1](taggingv8-defs-keyv1.md))

# key Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                 |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments)     | `array`  | Required | cannot be null | [TaggingV8](taggingv8-defs-keyv1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/segments")     |
| [tag](#tag)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-keytagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/tag")                          |
| [confidence](#confidence) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-keyv1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/confidence") |

## segments



`segments`

* is required

* Type: `string[]` ([KeyTagsV1](taggingv8-defs-keytagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-keyv1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/segments")

### segments Type

`string[]` ([KeyTagsV1](taggingv8-defs-keytagsv1.md))

## tag



`tag`

* is required

* Type: `string` ([KeyTagsV1](taggingv8-defs-keytagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-keytagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/tag")

### tag Type

`string` ([KeyTagsV1](taggingv8-defs-keytagsv1.md))

### tag Constraints

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

## confidence



`confidence`

* is required

* Type: `number` ([Confidence](taggingv8-defs-keyv1-properties-confidence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-keyv1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/KeyV1/properties/confidence")

### confidence Type

`number` ([Confidence](taggingv8-defs-keyv1-properties-confidence.md))

### confidence Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`
