---
title: "AudioFileType"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar ljuddokument. Inkluderar följande typer          Läs mer om ljudformat här."
type: docs
weight: 10
url: /sv/java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

Definierar ljuddokument. Inkluderar följande typer: , , , , , , , , , Läs mer om ljudformat [här](../https://docs.fileformat.com/audio/).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [AudioFileType()](#AudioFileType--) | Serialiseringskonstruktor |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Mp3](#Mp3) | Filer med .mp3‑tillägg är digitalt kodade filformat för ljudfiler som formellt är baserade på MPEG-1 Audio Layer III eller MPEG-2 Audio Layer III. |
|
|  | [Aac](#Aac) | AAC (Advanced Audio Coding) avser en digital ljudkodningsstandard som representerar ljudfiler baserade på förlustkomprimering. |
|
|  | [Aiff](#Aiff) | AIFF (Audio Interchange File Format) är ett okomprimerat ljudfilformat utvecklat av Apple år 1998, men är baserat på EA IFF 85. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/aiff/). |
|
|  | [Flac](#Flac) | FLAC(Free Lossless Audio Codec) är ett förlustfritt komprimeringsformat för ljudkodning som utvecklats av Xiph.Org Foundation. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/flac/). |
|
|  | [M4a](#M4a) | M4A‑filformatet är en ljudfil som skapats med AAC (Advanced Audio Coding), vilket är en förlustkomprimering. |
|
|  | [Wma](#Wma) | En fil med .wma‑extension representerar en ljudfil som sparas i Advanced Systems Format (ASF). |
|
|  | [Ac3](#Ac3) | En fil med .ac3‑extension är en Audio Codec 3‑fil, introducerad av Dolby Laboratories. |
|
|  | [Ogg](#Ogg) | OGG är en Ogg Vorbis‑komprimerad ljudfil som sparas med .ogg‑extensionen. |
|
|  | [Wav](#Wav) | WAV, känt för WAVE (Waveform Audio File Format), är en delmängd av Microsoft\\u2019s Resource Interchange File Format (RIFF)-specifikation för lagring av digitala ljudfiler. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


Serialiseringskonstruktor


### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


Filer med .mp3‑extension är digitalt kodade filformat för ljudfiler som formellt baseras på MPEG‑1 Audio Layer III eller MPEG‑2 Audio Layer III. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/mp3/).


### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) avser en digital ljudkodningsstandard som representerar ljudfiler baserade på förlustkomprimering. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/aac/).


### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


AIFF (Audio Interchange File Format) är ett okomprimerat ljudfilformat utvecklat av Apple år 1998, men är baserat på EA IFF 85. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/aiff/).


### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC(Free Lossless Audio Codec) är ett förlustfritt komprimeringsformat för ljudkodning som utvecklats av Xiph.Org Foundation. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/flac/).


### M4a {#M4a}
```
public static final AudioFileType M4a
```


M4A‑filformatet är en ljudfil skapad med AAC (Advanced Audio Coding), vilket är en förlustkomprimering. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/m4a/).


### Wma {#Wma}
```
public static final AudioFileType Wma
```


En fil med .wma‑extension representerar en ljudfil som sparas i Advanced Systems Format (ASF). Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/wma/).


### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


En fil med .ac3‑extension är en Audio Codec 3‑fil, introducerad av Dolby Laboratories. Det är ett ljudformat som kan innehålla upp till sex kanaler av ljudutgång. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/ac3/).


### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG är en Ogg Vorbis‑komprimerad ljudfil som sparas med .ogg‑extensionen. OGG‑filer används för att lagra ljuddata och kan även innehålla artist‑ och spårinformation samt metadata. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/ogg/).


### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, känt för WAVE (Waveform Audio File Format), är en delmängd av Microsoft\\u2019s Resource Interchange File Format (RIFF)-specifikation för lagring av digitala ljudfiler. Läs mer om detta filformat [här](../https://docs.fileformat.com/audio/ogg/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Förberedda standardalternativ för konvertering för filtypen


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
