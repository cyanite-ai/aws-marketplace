# ValenceArousalSegmentsV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/segments
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## segments Type

`object` ([ValenceArousalSegmentsV1](taggingv8-defs-valencearousalsegmentsv1.md))

# segments Properties

| Property            | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                 |
| :------------------ | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [valence](#valence) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalsegmentsv1-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalSegmentsV1/properties/valence") |
| [arousal](#arousal) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalsegmentsv1-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalSegmentsV1/properties/arousal") |

## valence



`valence`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalsegmentsv1-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalSegmentsV1/properties/valence")

### valence Type

`number[]`

## arousal



`arousal`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalsegmentsv1-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalSegmentsV1/properties/arousal")

### arousal Type

`number[]`
