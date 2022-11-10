# MovementV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/movement
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## movement Type

`object` ([MovementV1](taggingv8-defs-movementv1.md))

# movement Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                               |
| :-------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/segments")     |
| [scores](#scores)     | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/scores")         |
| [tags](#tags)         | `array`  | Required | cannot be null | [TaggingV8](taggingv8-defs-movementv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/tags") |

## segments



`segments`

* is required

* Type: `object` ([MovementSegmentsV1](taggingv8-defs-movementsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/segments")

### segments Type

`object` ([MovementSegmentsV1](taggingv8-defs-movementsegmentsv1.md))

## scores



`scores`

* is required

* Type: `object` ([MovementScoresV1](taggingv8-defs-movementscoresv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/scores")

### scores Type

`object` ([MovementScoresV1](taggingv8-defs-movementscoresv1.md))

## tags



`tags`

* is required

* Type: `string[]` ([MovementTagsV1](taggingv8-defs-movementtagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/tags")

### tags Type

`string[]` ([MovementTagsV1](taggingv8-defs-movementtagsv1.md))
