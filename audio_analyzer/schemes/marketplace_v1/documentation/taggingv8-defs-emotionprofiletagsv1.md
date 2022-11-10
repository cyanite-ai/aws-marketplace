# EmotionProfileTagsV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/emotionProfile
```



| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## emotionProfile Type

`string` ([EmotionProfileTagsV1](taggingv8-defs-emotionprofiletagsv1.md))

## emotionProfile Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"negative"` |             |
| `"neutral"`  |             |
| `"positive"` |             |
| `"varying"`  |             |
