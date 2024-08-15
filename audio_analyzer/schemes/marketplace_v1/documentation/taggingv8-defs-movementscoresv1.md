# MovementScoresV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementV1/properties/scores
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## scores Type

`object` ([MovementScoresV1](taggingv8-defs-movementscoresv1.md))

# scores Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                         |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bouncing](#bouncing)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-bouncing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/bouncing")       |
| [driving](#driving)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-driving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/driving")         |
| [flowing](#flowing)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-flowing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/flowing")         |
| [groovy](#groovy)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-groovy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/groovy")           |
| [nonrhythmic](#nonrhythmic) | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-nonrhythmic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/nonrhythmic") |
| [pulsing](#pulsing)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-pulsing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/pulsing")         |
| [robotic](#robotic)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-robotic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/robotic")         |
| [running](#running)         | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-running.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/running")         |
| [steady](#steady)           | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-steady.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/steady")           |
| [stomping](#stomping)       | `number` | Required | cannot be null | [TaggingV8](taggingv8-defs-movementscoresv1-properties-stomping.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/stomping")       |

## bouncing



`bouncing`

* is required

* Type: `number` ([Bouncing](taggingv8-defs-movementscoresv1-properties-bouncing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-bouncing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/bouncing")

### bouncing Type

`number` ([Bouncing](taggingv8-defs-movementscoresv1-properties-bouncing.md))

### bouncing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## driving



`driving`

* is required

* Type: `number` ([Driving](taggingv8-defs-movementscoresv1-properties-driving.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-driving.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/driving")

### driving Type

`number` ([Driving](taggingv8-defs-movementscoresv1-properties-driving.md))

### driving Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## flowing



`flowing`

* is required

* Type: `number` ([Flowing](taggingv8-defs-movementscoresv1-properties-flowing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-flowing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/flowing")

### flowing Type

`number` ([Flowing](taggingv8-defs-movementscoresv1-properties-flowing.md))

### flowing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## groovy



`groovy`

* is required

* Type: `number` ([Groovy](taggingv8-defs-movementscoresv1-properties-groovy.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-groovy.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/groovy")

### groovy Type

`number` ([Groovy](taggingv8-defs-movementscoresv1-properties-groovy.md))

### groovy Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## nonrhythmic



`nonrhythmic`

* is required

* Type: `number` ([Nonrhythmic](taggingv8-defs-movementscoresv1-properties-nonrhythmic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-nonrhythmic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/nonrhythmic")

### nonrhythmic Type

`number` ([Nonrhythmic](taggingv8-defs-movementscoresv1-properties-nonrhythmic.md))

### nonrhythmic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## pulsing



`pulsing`

* is required

* Type: `number` ([Pulsing](taggingv8-defs-movementscoresv1-properties-pulsing.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-pulsing.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/pulsing")

### pulsing Type

`number` ([Pulsing](taggingv8-defs-movementscoresv1-properties-pulsing.md))

### pulsing Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## robotic



`robotic`

* is required

* Type: `number` ([Robotic](taggingv8-defs-movementscoresv1-properties-robotic.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-robotic.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/robotic")

### robotic Type

`number` ([Robotic](taggingv8-defs-movementscoresv1-properties-robotic.md))

### robotic Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## running



`running`

* is required

* Type: `number` ([Running](taggingv8-defs-movementscoresv1-properties-running.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-running.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/running")

### running Type

`number` ([Running](taggingv8-defs-movementscoresv1-properties-running.md))

### running Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## steady



`steady`

* is required

* Type: `number` ([Steady](taggingv8-defs-movementscoresv1-properties-steady.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-steady.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/steady")

### steady Type

`number` ([Steady](taggingv8-defs-movementscoresv1-properties-steady.md))

### steady Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## stomping



`stomping`

* is required

* Type: `number` ([Stomping](taggingv8-defs-movementscoresv1-properties-stomping.md))

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-movementscoresv1-properties-stomping.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/MovementScoresV1/properties/stomping")

### stomping Type

`number` ([Stomping](taggingv8-defs-movementscoresv1-properties-stomping.md))

### stomping Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`
