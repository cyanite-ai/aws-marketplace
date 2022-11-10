# ValenceArousalScoresV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalV1/properties/scores
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## scores Type

`object` ([ValenceArousalScoresV1](taggingv8-defs-valencearousalscoresv1.md))

# scores Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                             |
| :------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [valence](#valence) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalscoresv1-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalScoresV1/properties/valence") |
| [arousal](#arousal) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-valencearousalscoresv1-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalScoresV1/properties/arousal") |

## valence



`valence`

* is required

* Type: `number` ([Valence](taggingv8-defs-valencearousalscoresv1-properties-valence.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalscoresv1-properties-valence.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalScoresV1/properties/valence")

### valence Type

`number` ([Valence](taggingv8-defs-valencearousalscoresv1-properties-valence.md))

### valence Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `-1`

## arousal



`arousal`

* is required

* Type: `number` ([Arousal](taggingv8-defs-valencearousalscoresv1-properties-arousal.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-valencearousalscoresv1-properties-arousal.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/ValenceArousalScoresV1/properties/arousal")

### arousal Type

`number` ([Arousal](taggingv8-defs-valencearousalscoresv1-properties-arousal.md))

### arousal Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `-1`
