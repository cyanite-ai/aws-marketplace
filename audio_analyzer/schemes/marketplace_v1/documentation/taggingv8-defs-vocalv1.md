# VocalV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/vocal
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## vocal Type

`object` ([VocalV1](taggingv8-defs-vocalv1.md))

# vocal Properties

| Property                                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                             |
| :------------------------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments)                             | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/segments")                                         |
| [scores](#scores)                                 | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/scores")                                 |
| [tags](#tags)                                     | Merged   | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/tags")                                     |
| [vocalPresence](#vocalpresence)                   | Merged   | Optional | cannot be null | [TaggingV8](taggingv8-defs-vocalv1-properties-vocalpresence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/vocalPresence")                   |
| [predominantVocalGender](#predominantvocalgender) | Merged   | Optional | cannot be null | [TaggingV8](taggingv8-defs-vocalv1-properties-predominantvocalgender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/predominantVocalGender") |

## segments



`segments`

* is required

* Type: `object` ([VocalSegmentsV1](taggingv8-defs-vocalsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/segments")

### segments Type

`object` ([VocalSegmentsV1](taggingv8-defs-vocalsegmentsv1.md))

## scores



`scores`

* is required

* Type: merged type ([Details](taggingv8-defs-vocalv1-properties-scores.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalv1-properties-scores.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/scores")

### scores Type

merged type ([Details](taggingv8-defs-vocalv1-properties-scores.md))

any of

* [VocalScoresV1](taggingv8-defs-vocalscoresv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-vocalv1-properties-scores-anyof-1.md "check type definition")

## tags



`tags`

* is required

* Type: merged type ([Tags](taggingv8-defs-vocalv1-properties-tags.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/tags")

### tags Type

merged type ([Tags](taggingv8-defs-vocalv1-properties-tags.md))

any of

* [Untitled array in TaggingV8](taggingv8-defs-vocalv1-properties-tags-anyof-0.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-vocalv1-properties-tags-anyof-1.md "check type definition")

## vocalPresence



`vocalPresence`

* is optional

* Type: merged type ([Details](taggingv8-defs-vocalv1-properties-vocalpresence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalv1-properties-vocalpresence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/vocalPresence")

### vocalPresence Type

merged type ([Details](taggingv8-defs-vocalv1-properties-vocalpresence.md))

any of

* [VocalPresenceTagsV1](taggingv8-defs-vocalpresencetagsv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-vocalv1-properties-vocalpresence-anyof-1.md "check type definition")

## predominantVocalGender



`predominantVocalGender`

* is optional

* Type: merged type ([Details](taggingv8-defs-vocalv1-properties-predominantvocalgender.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalv1-properties-predominantvocalgender.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/predominantVocalGender")

### predominantVocalGender Type

merged type ([Details](taggingv8-defs-vocalv1-properties-predominantvocalgender.md))

any of

* [PredominantVocalGenderTagsV1](taggingv8-defs-predominantvocalgendertagsv1.md "check type definition")

* [Untitled null in TaggingV8](taggingv8-defs-vocalv1-properties-predominantvocalgender-anyof-1.md "check type definition")
