# SubgenreV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/subGenre
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## subGenre Type

`object` ([SubgenreV1](taggingv8-defs-subgenrev1.md))

# subGenre Properties

| Property              | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                       |
| :-------------------- | :----- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments) | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrev1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/segments") |
| [scores](#scores)     | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrev1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/scores")     |
| [tags](#tags)         | Merged | Optional | cannot be null | [TaggingV8](taggingv8-defs-subgenrev1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/tags")         |

## segments



`segments`

* is optional

* Type: merged type ([Details](taggingv8-defs-subgenrev1-properties-segments.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrev1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/segments")

### segments Type

merged type ([Details](taggingv8-defs-subgenrev1-properties-segments.md))

any of

* [SubgenreSegmentsV1](taggingv8-defs-subgenresegmentsv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrev1-properties-segments-anyof-1.md "check type definition")

## scores



`scores`

* is optional

* Type: merged type ([Details](taggingv8-defs-subgenrev1-properties-scores.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrev1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/scores")

### scores Type

merged type ([Details](taggingv8-defs-subgenrev1-properties-scores.md))

any of

* [SubgenreScoresV1](taggingv8-defs-subgenrescoresv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrev1-properties-scores-anyof-1.md "check type definition")

## tags



`tags`

* is optional

* Type: merged type ([Tags](taggingv8-defs-subgenrev1-properties-tags.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-subgenrev1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/SubgenreV1/properties/tags")

### tags Type

merged type ([Tags](taggingv8-defs-subgenrev1-properties-tags.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-subgenrev1-properties-tags-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-subgenrev1-properties-tags-anyof-1.md "check type definition")
