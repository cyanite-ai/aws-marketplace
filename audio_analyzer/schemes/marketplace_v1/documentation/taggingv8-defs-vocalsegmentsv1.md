# VocalSegmentsV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/segments
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## segments Type

`object` ([VocalSegmentsV1](taggingv8-defs-vocalsegmentsv1.md))

# segments Properties

| Property                      | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                         |
| :---------------------------- | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [female](#female)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/female")             |
| [male](#male)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/male")                 |
| [instrumental](#instrumental) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/instrumental") |

## female



`female`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/female")

### female Type

`number[]`

## male



`male`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/male")

### male Type

`number[]`

## instrumental



`instrumental`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalsegmentsv1-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalSegmentsV1/properties/instrumental")

### instrumental Type

`number[]`
