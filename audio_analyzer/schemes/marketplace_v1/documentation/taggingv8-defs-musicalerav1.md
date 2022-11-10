# MusicalEraV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/musicalEra
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## musicalEra Type

`object` ([MusicalEraV1](taggingv8-defs-musicalerav1.md))

# musicalEra Properties

| Property                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                             |
| :---------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [exactYear](#exactyear) | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-musicalerav1-properties-exactyear.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraV1/properties/exactYear") |
| [tag](#tag)             | `string`  | Required | cannot be null | [TaggingV8](taggingv8-defs-musicaleratagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraV1/properties/tag")                        |

## exactYear



`exactYear`

* is required

* Type: `integer` ([Exactyear](taggingv8-defs-musicalerav1-properties-exactyear.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-musicalerav1-properties-exactyear.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraV1/properties/exactYear")

### exactYear Type

`integer` ([Exactyear](taggingv8-defs-musicalerav1-properties-exactyear.md))

### exactYear Constraints

**maximum**: the value of this number must smaller than or equal to: `2022`

**minimum**: the value of this number must greater than or equal to: `1950`

## tag



`tag`

* is required

* Type: `string` ([MusicalEraTagsV1](taggingv8-defs-musicaleratagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-musicaleratagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MusicalEraV1/properties/tag")

### tag Type

`string` ([MusicalEraTagsV1](taggingv8-defs-musicaleratagsv1.md))

### tag Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                   | Explanation |
| :---------------------- | :---------- |
| `"earlyMid1950s"`       |             |
| `"midLate1950s"`        |             |
| `"late1950sEarly1960s"` |             |
| `"earlyMid1960s"`       |             |
| `"midLate1960s"`        |             |
| `"late1960sEarly1970s"` |             |
| `"earlyMid1970s"`       |             |
| `"midLate1970s"`        |             |
| `"late1970sEarly1980s"` |             |
| `"earlyMid1980s"`       |             |
| `"midLate1980s"`        |             |
| `"late1980sEarly1990s"` |             |
| `"earlyMid1990s"`       |             |
| `"midLate1990s"`        |             |
| `"late1990sEarly2000s"` |             |
| `"earlyMid2000s"`       |             |
| `"midLate2000s"`        |             |
| `"late2000sEarly2010s"` |             |
| `"contemporary"`        |             |
