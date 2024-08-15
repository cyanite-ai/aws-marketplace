# InstrumentV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/instrument
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## instrument Type

`object` ([InstrumentV1](taggingv8-defs-instrumentv1.md))

# instrument Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                   |
| :-------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [segments](#segments) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/segments")     |
| [presence](#presence) | `object` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentpresencev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/presence")     |
| [tags](#tags)         | `array`  | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/tags") |

## segments



`segments`

* is required

* Type: `object` ([InstrumentSegmentsV1](taggingv8-defs-instrumentsegmentsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/segments")

### segments Type

`object` ([InstrumentSegmentsV1](taggingv8-defs-instrumentsegmentsv1.md))

## presence



`presence`

* is required

* Type: `object` ([InstrumentPresenceV1](taggingv8-defs-instrumentpresencev1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentpresencev1.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/presence")

### presence Type

`object` ([InstrumentPresenceV1](taggingv8-defs-instrumentpresencev1.md))

## tags



`tags`

* is required

* Type: `string[]` ([InstrumentTagsV1](taggingv8-defs-instrumenttagsv1.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentv1-properties-tags.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/tags")

### tags Type

`string[]` ([InstrumentTagsV1](taggingv8-defs-instrumenttagsv1.md))
