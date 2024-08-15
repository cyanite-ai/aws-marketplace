# ValenceArousalV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/valenceArousal
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## valenceArousal Type

`object` ([ValenceArousalV1](taggingv8-defs-valencearousalv1.md))

# valenceArousal Properties

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                         |
| :-------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments)             | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/segments")   |
| [scores](#scores)                 | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalscoresv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/scores")       |
| [energyLevel](#energylevel)       | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-energyleveltagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/energyLevel")       |
| [energyChanges](#energychanges)   | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-energychangestagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/energyChanges")   |
| [emotionProfile](#emotionprofile) | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-emotionprofiletagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/emotionProfile") |
| [emotionChanges](#emotionchanges) | `string` | Required | cannot be null | [TaggingV8](taggingv8-defs-emotionchangestagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/emotionChanges") |

## segments



`segments`

* is required

* Type: `object` ([ValenceArousalSegmentsV1](taggingv8-defs-valencearousalsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/segments")

### segments Type

`object` ([ValenceArousalSegmentsV1](taggingv8-defs-valencearousalsegmentsv1.md))

## scores



`scores`

* is required

* Type: `object` ([ValenceArousalScoresV1](taggingv8-defs-valencearousalscoresv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalscoresv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/scores")

### scores Type

`object` ([ValenceArousalScoresV1](taggingv8-defs-valencearousalscoresv1.md))

## energyLevel



`energyLevel`

* is required

* Type: `string` ([EnergyLevelTagsV1](taggingv8-defs-energyleveltagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-energyleveltagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/energyLevel")

### energyLevel Type

`string` ([EnergyLevelTagsV1](taggingv8-defs-energyleveltagsv1.md))

### energyLevel Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"low"`     |             |
| `"medium"`  |             |
| `"high"`    |             |
| `"varying"` |             |

## energyChanges



`energyChanges`

* is required

* Type: `string` ([EnergyChangesTagsV1](taggingv8-defs-energychangestagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-energychangestagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/energyChanges")

### energyChanges Type

`string` ([EnergyChangesTagsV1](taggingv8-defs-energychangestagsv1.md))

### energyChanges Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"low"`    |             |
| `"medium"` |             |
| `"high"`   |             |

## emotionProfile



`emotionProfile`

* is required

* Type: `string` ([EmotionProfileTagsV1](taggingv8-defs-emotionprofiletagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-emotionprofiletagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/emotionProfile")

### emotionProfile Type

`string` ([EmotionProfileTagsV1](taggingv8-defs-emotionprofiletagsv1.md))

### emotionProfile Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"negative"` |             |
| `"neutral"`  |             |
| `"positive"` |             |
| `"varying"`  |             |

## emotionChanges



`emotionChanges`

* is required

* Type: `string` ([EmotionChangesTagsV1](taggingv8-defs-emotionchangestagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-emotionchangestagsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/emotionChanges")

### emotionChanges Type

`string` ([EmotionChangesTagsV1](taggingv8-defs-emotionchangestagsv1.md))

### emotionChanges Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"low"`    |             |
| `"medium"` |             |
| `"high"`   |             |
