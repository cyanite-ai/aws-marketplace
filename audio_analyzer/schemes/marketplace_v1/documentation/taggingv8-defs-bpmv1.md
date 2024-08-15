# BpmV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/bpm
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## bpm Type

`object` ([BpmV1](taggingv8-defs-bpmv1.md))

# bpm Properties

| Property                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                       |
| :------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments)           | `array`   | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/segments")           |
| [segmentsRange](#segmentsrange) | `array`   | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-segmentsrange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/segmentsRange") |
| [tag](#tag)                     | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-tag.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/tag")                     |
| [tagRange](#tagrange)           | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-tagrange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/tagRange")           |
| [confidence](#confidence)       | `number`  | Required | cannot be null | [TaggingV8](taggingv8-defs-bpmv1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/confidence")       |

## segments



`segments`

* is required

* Type: `integer[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-segments.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/segments")

### segments Type

`integer[]`

## segmentsRange



`segmentsRange`

* is required

* Type: `integer[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-segmentsrange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/segmentsRange")

### segmentsRange Type

`integer[]`

## tag



`tag`

* is required

* Type: `integer` ([Tag](taggingv8-defs-bpmv1-properties-tag.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-tag.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/tag")

### tag Type

`integer` ([Tag](taggingv8-defs-bpmv1-properties-tag.md))

### tag Constraints

**maximum**: the value of this number must smaller than or equal to: `285`

**minimum**: the value of this number must greater than or equal to: `30`

## tagRange



`tagRange`

* is required

* Type: `integer` ([Tagrange](taggingv8-defs-bpmv1-properties-tagrange.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-tagrange.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/tagRange")

### tagRange Type

`integer` ([Tagrange](taggingv8-defs-bpmv1-properties-tagrange.md))

### tagRange Constraints

**maximum**: the value of this number must smaller than or equal to: `180`

**minimum**: the value of this number must greater than or equal to: `60`

## confidence



`confidence`

* is required

* Type: `number` ([Confidence](taggingv8-defs-bpmv1-properties-confidence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-bpmv1-properties-confidence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/BpmV1/properties/confidence")

### confidence Type

`number` ([Confidence](taggingv8-defs-bpmv1-properties-confidence.md))

### confidence Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`
