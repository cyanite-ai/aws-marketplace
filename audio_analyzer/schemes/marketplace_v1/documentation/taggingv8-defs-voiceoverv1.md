# VoiceoverV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/properties/voiceover
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## voiceover Type

`object` ([VoiceoverV1](taggingv8-defs-voiceoverv1.md))

# voiceover Properties

| Property                                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                               |
| :------------------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [voiceoverDegree](#voiceoverdegree)         | `number`  | Required | cannot be null | [TaggingV8](taggingv8-defs-voiceoverv1-properties-voiceoverdegree.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VoiceoverV1/properties/voiceoverDegree")         |
| [isVoiceoverDominant](#isvoiceoverdominant) | `boolean` | Required | cannot be null | [TaggingV8](taggingv8-defs-voiceoverv1-properties-isvoiceoverdominant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VoiceoverV1/properties/isVoiceoverDominant") |

## voiceoverDegree



`voiceoverDegree`

* is required

* Type: `number` ([Voiceoverdegree](taggingv8-defs-voiceoverv1-properties-voiceoverdegree.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-voiceoverv1-properties-voiceoverdegree.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VoiceoverV1/properties/voiceoverDegree")

### voiceoverDegree Type

`number` ([Voiceoverdegree](taggingv8-defs-voiceoverv1-properties-voiceoverdegree.md))

### voiceoverDegree Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## isVoiceoverDominant



`isVoiceoverDominant`

* is required

* Type: `boolean` ([Isvoiceoverdominant](taggingv8-defs-voiceoverv1-properties-isvoiceoverdominant.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-voiceoverv1-properties-isvoiceoverdominant.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/VoiceoverV1/properties/isVoiceoverDominant")

### isVoiceoverDominant Type

`boolean` ([Isvoiceoverdominant](taggingv8-defs-voiceoverv1-properties-isvoiceoverdominant.md))
