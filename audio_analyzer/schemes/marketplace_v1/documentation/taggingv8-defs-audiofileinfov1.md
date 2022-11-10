# AudioFileInfoV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/audioFileInfo
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## audioFileInfo Type

`object` ([AudioFileInfoV1](taggingv8-defs-audiofileinfov1.md))

# audioFileInfo Properties

| Property                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                     |
| :------------------------ | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [duration](#duration)     | `number`  | Required | cannot be null | [TaggingV8](taggingv8-defs-audiofileinfov1-properties-duration.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/duration")     |
| [fileSizeB](#filesizeb)   | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-audiofileinfov1-properties-filesizeb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/fileSizeB")   |
| [bitrate](#bitrate)       | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-audiofileinfov1-properties-bitrate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/bitrate")       |
| [samplerate](#samplerate) | `integer` | Required | cannot be null | [TaggingV8](taggingv8-defs-audiofileinfov1-properties-samplerate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/samplerate") |

## duration



`duration`

* is required

* Type: `number` ([Duration](taggingv8-defs-audiofileinfov1-properties-duration.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-audiofileinfov1-properties-duration.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/duration")

### duration Type

`number` ([Duration](taggingv8-defs-audiofileinfov1-properties-duration.md))

## fileSizeB



`fileSizeB`

* is required

* Type: `integer` ([Filesizeb](taggingv8-defs-audiofileinfov1-properties-filesizeb.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-audiofileinfov1-properties-filesizeb.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/fileSizeB")

### fileSizeB Type

`integer` ([Filesizeb](taggingv8-defs-audiofileinfov1-properties-filesizeb.md))

## bitrate



`bitrate`

* is required

* Type: `integer` ([Bitrate](taggingv8-defs-audiofileinfov1-properties-bitrate.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-audiofileinfov1-properties-bitrate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/bitrate")

### bitrate Type

`integer` ([Bitrate](taggingv8-defs-audiofileinfov1-properties-bitrate.md))

## samplerate



`samplerate`

* is required

* Type: `integer` ([Samplerate](taggingv8-defs-audiofileinfov1-properties-samplerate.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-audiofileinfov1-properties-samplerate.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/AudioFileInfoV1/properties/samplerate")

### samplerate Type

`integer` ([Samplerate](taggingv8-defs-audiofileinfov1-properties-samplerate.md))
