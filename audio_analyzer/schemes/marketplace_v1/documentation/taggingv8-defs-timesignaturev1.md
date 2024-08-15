# TimeSignatureV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/timeSignature
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## timeSignature Type

`object` ([TimeSignatureV1](taggingv8-defs-timesignaturev1.md))

# timeSignature Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                     |
| :------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [tag](#tag)               | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-timesignaturetagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureV1/properties/tag")                          |
| [confidence](#confidence) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-timesignaturev1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureV1/properties/confidence") |

## tag



`tag`

* is required

* Type: `string` ([TimeSignatureTagsV1](taggingv8-defs-timesignaturetagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-timesignaturetagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureV1/properties/tag")

### tag Type

`string` ([TimeSignatureTagsV1](taggingv8-defs-timesignaturetagsv1.md))

### tag Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | :---------- |
| `"3_4"` |             |
| `"4_4"` |             |

## confidence



`confidence`

* is required

* Type: `number` ([Confidence](taggingv8-defs-timesignaturev1-properties-confidence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-timesignaturev1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/TimeSignatureV1/properties/confidence")

### confidence Type

`number` ([Confidence](taggingv8-defs-timesignaturev1-properties-confidence.md))

### confidence Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`
