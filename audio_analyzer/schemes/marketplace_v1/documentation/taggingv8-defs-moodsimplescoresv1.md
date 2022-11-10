# MoodSimpleScoresV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleV1/properties/scores/anyOf/0
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## 0 Type

`object` ([MoodSimpleScoresV1](taggingv8-defs-moodsimplescoresv1.md))

# 0 Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                           |
| :------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [aggressive](#aggressive) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/aggressive") |
| [calm](#calm)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/calm")             |
| [chill](#chill)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-chill.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/chill")           |
| [dark](#dark)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/dark")             |
| [energetic](#energetic)   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/energetic")   |
| [epic](#epic)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/epic")             |
| [happy](#happy)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/happy")           |
| [romantic](#romantic)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/romantic")     |
| [sad](#sad)               | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/sad")               |
| [scary](#scary)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/scary")           |
| [sexy](#sexy)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/sexy")             |
| [ethereal](#ethereal)     | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/ethereal")     |
| [uplifting](#uplifting)   | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/uplifting")   |

## aggressive



`aggressive`

* is required

* Type: `number` ([Aggressive](taggingv8-defs-moodsimplescoresv1-properties-aggressive.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-aggressive.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/aggressive")

### aggressive Type

`number` ([Aggressive](taggingv8-defs-moodsimplescoresv1-properties-aggressive.md))

### aggressive Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## calm



`calm`

* is required

* Type: `number` ([Calm](taggingv8-defs-moodsimplescoresv1-properties-calm.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-calm.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/calm")

### calm Type

`number` ([Calm](taggingv8-defs-moodsimplescoresv1-properties-calm.md))

### calm Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## chill



`chill`

* is required

* Type: `number` ([Chill](taggingv8-defs-moodsimplescoresv1-properties-chill.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-chill.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/chill")

### chill Type

`number` ([Chill](taggingv8-defs-moodsimplescoresv1-properties-chill.md))

### chill Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## dark



`dark`

* is required

* Type: `number` ([Dark](taggingv8-defs-moodsimplescoresv1-properties-dark.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-dark.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/dark")

### dark Type

`number` ([Dark](taggingv8-defs-moodsimplescoresv1-properties-dark.md))

### dark Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## energetic



`energetic`

* is required

* Type: `number` ([Energetic](taggingv8-defs-moodsimplescoresv1-properties-energetic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-energetic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/energetic")

### energetic Type

`number` ([Energetic](taggingv8-defs-moodsimplescoresv1-properties-energetic.md))

### energetic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## epic



`epic`

* is required

* Type: `number` ([Epic](taggingv8-defs-moodsimplescoresv1-properties-epic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-epic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/epic")

### epic Type

`number` ([Epic](taggingv8-defs-moodsimplescoresv1-properties-epic.md))

### epic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## happy



`happy`

* is required

* Type: `number` ([Happy](taggingv8-defs-moodsimplescoresv1-properties-happy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-happy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/happy")

### happy Type

`number` ([Happy](taggingv8-defs-moodsimplescoresv1-properties-happy.md))

### happy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## romantic



`romantic`

* is required

* Type: `number` ([Romantic](taggingv8-defs-moodsimplescoresv1-properties-romantic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-romantic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/romantic")

### romantic Type

`number` ([Romantic](taggingv8-defs-moodsimplescoresv1-properties-romantic.md))

### romantic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## sad



`sad`

* is required

* Type: `number` ([Sad](taggingv8-defs-moodsimplescoresv1-properties-sad.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-sad.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/sad")

### sad Type

`number` ([Sad](taggingv8-defs-moodsimplescoresv1-properties-sad.md))

### sad Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## scary



`scary`

* is required

* Type: `number` ([Scary](taggingv8-defs-moodsimplescoresv1-properties-scary.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-scary.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/scary")

### scary Type

`number` ([Scary](taggingv8-defs-moodsimplescoresv1-properties-scary.md))

### scary Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## sexy



`sexy`

* is required

* Type: `number` ([Sexy](taggingv8-defs-moodsimplescoresv1-properties-sexy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-sexy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/sexy")

### sexy Type

`number` ([Sexy](taggingv8-defs-moodsimplescoresv1-properties-sexy.md))

### sexy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## ethereal



`ethereal`

* is required

* Type: `number` ([Ethereal](taggingv8-defs-moodsimplescoresv1-properties-ethereal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-ethereal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/ethereal")

### ethereal Type

`number` ([Ethereal](taggingv8-defs-moodsimplescoresv1-properties-ethereal.md))

### ethereal Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## uplifting



`uplifting`

* is required

* Type: `number` ([Uplifting](taggingv8-defs-moodsimplescoresv1-properties-uplifting.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-moodsimplescoresv1-properties-uplifting.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MoodSimpleScoresV1/properties/uplifting")

### uplifting Type

`number` ([Uplifting](taggingv8-defs-moodsimplescoresv1-properties-uplifting.md))

### uplifting Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`
