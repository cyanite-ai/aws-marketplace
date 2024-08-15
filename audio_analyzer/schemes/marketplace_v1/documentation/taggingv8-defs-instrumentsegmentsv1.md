# InstrumentSegmentsV1 Schema

```txt
https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentV1/properties/segments
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [TaggingV8.schema.json\*](../out/TaggingV8.schema.json "open original schema") |

## segments Type

`object` ([InstrumentSegmentsV1](taggingv8-defs-instrumentsegmentsv1.md))

# segments Properties

| Property                                | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                             |
| :-------------------------------------- | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [accordion](#accordion)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-accordion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/accordion")                 |
| [acousticGuitar](#acousticguitar)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-acousticguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/acousticGuitar")       |
| [africanPercussion](#africanpercussion) | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-africanpercussion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/africanPercussion") |
| [asianFlute](#asianflute)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-asianflute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/asianFlute")               |
| [asianStrings](#asianstrings)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-asianstrings.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/asianStrings")           |
| [banjo](#banjo)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-banjo.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/banjo")                         |
| [bassGuitar](#bassguitar)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bassguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bassGuitar")               |
| [bells](#bells)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bells.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bells")                         |
| [bongoConga](#bongoconga)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bongoconga.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bongoConga")               |
| [brass](#brass)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-brass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/brass")                         |
| [celeste](#celeste)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-celeste.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/celeste")                     |
| [cello](#cello)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-cello.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/cello")                         |
| [clarinet](#clarinet)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-clarinet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/clarinet")                   |
| [doubleBass](#doublebass)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-doublebass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/doubleBass")               |
| [drumKit](#drumkit)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-drumkit.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/drumKit")                     |
| [electricGuitar](#electricguitar)       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricGuitar")       |
| [electricOrgan](#electricorgan)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricorgan.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricOrgan")         |
| [electricPiano](#electricpiano)         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricpiano.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricPiano")         |
| [electronicDrums](#electronicdrums)     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electronicdrums.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electronicDrums")     |
| [flute](#flute)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-flute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/flute")                         |
| [frenchHorn](#frenchhorn)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-frenchhorn.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/frenchHorn")               |
| [harp](#harp)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-harp.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/harp")                           |
| [harpsichord](#harpsichord)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-harpsichord.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/harpsichord")             |
| [luteOud](#luteoud)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-luteoud.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/luteOud")                     |
| [mandolin](#mandolin)                   | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-mandolin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/mandolin")                   |
| [marimba](#marimba)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-marimba.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/marimba")                     |
| [oboe](#oboe)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-oboe.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/oboe")                           |
| [churchOrgan](#churchorgan)             | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-churchorgan.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/churchOrgan")             |
| [piano](#piano)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-piano.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/piano")                         |
| [pizzicato](#pizzicato)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-pizzicato.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/pizzicato")                 |
| [saxophone](#saxophone)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-saxophone.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/saxophone")                 |
| [sitar](#sitar)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-sitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/sitar")                         |
| [steelDrums](#steeldrums)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-steeldrums.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/steelDrums")               |
| [strings](#strings)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-strings.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/strings")                     |
| [synth](#synth)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-synth.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/synth")                         |
| [tabla](#tabla)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-tabla.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/tabla")                         |
| [taiko](#taiko)                         | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-taiko.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/taiko")                         |
| [trumpet](#trumpet)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-trumpet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/trumpet")                     |
| [tuba](#tuba)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-tuba.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/tuba")                           |
| [ukulele](#ukulele)                     | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-ukulele.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/ukulele")                     |
| [vibraphone](#vibraphone)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-vibraphone.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/vibraphone")               |
| [violin](#violin)                       | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-violin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/violin")                       |
| [woodwinds](#woodwinds)                 | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-woodwinds.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/woodwinds")                 |
| [glockenspiel](#glockenspiel)           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-glockenspiel.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/glockenspiel")           |
| [percussion](#percussion)               | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-percussion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/percussion")               |
| [bass](#bass)                           | `array` | Required | cannot be null | [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bass")                           |

## accordion



`accordion`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-accordion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/accordion")

### accordion Type

`number[]`

## acousticGuitar



`acousticGuitar`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-acousticguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/acousticGuitar")

### acousticGuitar Type

`number[]`

## africanPercussion



`africanPercussion`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-africanpercussion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/africanPercussion")

### africanPercussion Type

`number[]`

## asianFlute



`asianFlute`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-asianflute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/asianFlute")

### asianFlute Type

`number[]`

## asianStrings



`asianStrings`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-asianstrings.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/asianStrings")

### asianStrings Type

`number[]`

## banjo



`banjo`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-banjo.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/banjo")

### banjo Type

`number[]`

## bassGuitar



`bassGuitar`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bassguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bassGuitar")

### bassGuitar Type

`number[]`

## bells



`bells`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bells.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bells")

### bells Type

`number[]`

## bongoConga



`bongoConga`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bongoconga.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bongoConga")

### bongoConga Type

`number[]`

## brass



`brass`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-brass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/brass")

### brass Type

`number[]`

## celeste



`celeste`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-celeste.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/celeste")

### celeste Type

`number[]`

## cello



`cello`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-cello.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/cello")

### cello Type

`number[]`

## clarinet



`clarinet`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-clarinet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/clarinet")

### clarinet Type

`number[]`

## doubleBass



`doubleBass`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-doublebass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/doubleBass")

### doubleBass Type

`number[]`

## drumKit



`drumKit`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-drumkit.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/drumKit")

### drumKit Type

`number[]`

## electricGuitar



`electricGuitar`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricguitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricGuitar")

### electricGuitar Type

`number[]`

## electricOrgan



`electricOrgan`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricorgan.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricOrgan")

### electricOrgan Type

`number[]`

## electricPiano



`electricPiano`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electricpiano.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electricPiano")

### electricPiano Type

`number[]`

## electronicDrums



`electronicDrums`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-electronicdrums.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/electronicDrums")

### electronicDrums Type

`number[]`

## flute



`flute`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-flute.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/flute")

### flute Type

`number[]`

## frenchHorn



`frenchHorn`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-frenchhorn.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/frenchHorn")

### frenchHorn Type

`number[]`

## harp



`harp`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-harp.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/harp")

### harp Type

`number[]`

## harpsichord



`harpsichord`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-harpsichord.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/harpsichord")

### harpsichord Type

`number[]`

## luteOud



`luteOud`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-luteoud.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/luteOud")

### luteOud Type

`number[]`

## mandolin



`mandolin`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-mandolin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/mandolin")

### mandolin Type

`number[]`

## marimba



`marimba`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-marimba.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/marimba")

### marimba Type

`number[]`

## oboe



`oboe`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-oboe.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/oboe")

### oboe Type

`number[]`

## churchOrgan



`churchOrgan`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-churchorgan.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/churchOrgan")

### churchOrgan Type

`number[]`

## piano



`piano`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-piano.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/piano")

### piano Type

`number[]`

## pizzicato



`pizzicato`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-pizzicato.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/pizzicato")

### pizzicato Type

`number[]`

## saxophone



`saxophone`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-saxophone.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/saxophone")

### saxophone Type

`number[]`

## sitar



`sitar`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-sitar.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/sitar")

### sitar Type

`number[]`

## steelDrums



`steelDrums`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-steeldrums.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/steelDrums")

### steelDrums Type

`number[]`

## strings



`strings`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-strings.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/strings")

### strings Type

`number[]`

## synth



`synth`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-synth.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/synth")

### synth Type

`number[]`

## tabla



`tabla`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-tabla.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/tabla")

### tabla Type

`number[]`

## taiko



`taiko`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-taiko.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/taiko")

### taiko Type

`number[]`

## trumpet



`trumpet`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-trumpet.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/trumpet")

### trumpet Type

`number[]`

## tuba



`tuba`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-tuba.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/tuba")

### tuba Type

`number[]`

## ukulele



`ukulele`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-ukulele.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/ukulele")

### ukulele Type

`number[]`

## vibraphone



`vibraphone`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-vibraphone.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/vibraphone")

### vibraphone Type

`number[]`

## violin



`violin`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-violin.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/violin")

### violin Type

`number[]`

## woodwinds



`woodwinds`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-woodwinds.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/woodwinds")

### woodwinds Type

`number[]`

## glockenspiel



`glockenspiel`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-glockenspiel.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/glockenspiel")

### glockenspiel Type

`number[]`

## percussion



`percussion`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-percussion.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/percussion")

### percussion Type

`number[]`

## bass



`bass`

* is required

* Type: `number[]`

* cannot be null

* defined in: [TaggingV8](taggingv8-defs-instrumentsegmentsv1-properties-bass.md "https://github.com/cyanite-ai/aws-marketplace/blob/main/audio_analyzer/schemes/marketplace_v1/schema/TaggingV8.schema.json#/$defs/InstrumentSegmentsV1/properties/bass")

### bass Type

`number[]`
