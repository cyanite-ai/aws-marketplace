# MoodAdvancedV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/moodAdvanced
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## moodAdvanced Type

`object` ([MoodAdvancedV1](taggingv8-defs-moodadvancedv1.md))

# moodAdvanced Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                           |
| :-------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/segments")         |
| [scores](#scores)     | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/scores") |
| [tags](#tags)         | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-moodadvancedv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/tags")     |

## segments



`segments`

* is required

* Type: `object` ([MoodAdvancedSegmentsV1](taggingv8-defs-moodadvancedsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/segments")

### segments Type

`object` ([MoodAdvancedSegmentsV1](taggingv8-defs-moodadvancedsegmentsv1.md))

## scores



`scores`

* is required

* Type: merged type ([Details](taggingv8-defs-moodadvancedv1-properties-scores.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/scores")

### scores Type

merged type ([Details](taggingv8-defs-moodadvancedv1-properties-scores.md))

any of

* [MoodAdvancedScoresV1](taggingv8-defs-moodadvancedscoresv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-moodadvancedv1-properties-scores-anyof-1.md "check type definition")

## tags



`tags`

* is required

* Type: merged type ([Tags](taggingv8-defs-moodadvancedv1-properties-tags.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodadvancedv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodAdvancedV1/properties/tags")

### tags Type

merged type ([Tags](taggingv8-defs-moodadvancedv1-properties-tags.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-moodadvancedv1-properties-tags-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-moodadvancedv1-properties-tags-anyof-1.md "check type definition")
