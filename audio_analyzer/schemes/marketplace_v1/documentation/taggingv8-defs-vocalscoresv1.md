# VocalScoresV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalV1/properties/scores/anyOf/0
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## 0 Type

`object` ([VocalScoresV1](taggingv8-defs-vocalscoresv1.md))

# 0 Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                     |
| :---------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [female](#female)             | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalscoresv1-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/female")             |
| [male](#male)                 | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalscoresv1-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/male")                 |
| [instrumental](#instrumental) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-vocalscoresv1-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/instrumental") |

## female



`female`

* is required

* Type: `number` ([Female](taggingv8-defs-vocalscoresv1-properties-female.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalscoresv1-properties-female.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/female")

### female Type

`number` ([Female](taggingv8-defs-vocalscoresv1-properties-female.md))

### female Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## male



`male`

* is required

* Type: `number` ([Male](taggingv8-defs-vocalscoresv1-properties-male.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalscoresv1-properties-male.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/male")

### male Type

`number` ([Male](taggingv8-defs-vocalscoresv1-properties-male.md))

### male Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## instrumental



`instrumental`

* is required

* Type: `number` ([Instrumental](taggingv8-defs-vocalscoresv1-properties-instrumental.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-vocalscoresv1-properties-instrumental.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VocalScoresV1/properties/instrumental")

### instrumental Type

`number` ([Instrumental](taggingv8-defs-vocalscoresv1-properties-instrumental.md))

### instrumental Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`
