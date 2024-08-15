# MovementTagsV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/tags/items
```



| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## items Type

`string` ([MovementTagsV1](taggingv8-defs-movementtagsv1.md))

## items Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"bouncing"`    |             |
| `"driving"`     |             |
| `"flowing"`     |             |
| `"groovy"`      |             |
| `"nonrhythmic"` |             |
| `"pulsing"`     |             |
| `"robotic"`     |             |
| `"running"`     |             |
| `"steady"`      |             |
| `"stomping"`    |             |