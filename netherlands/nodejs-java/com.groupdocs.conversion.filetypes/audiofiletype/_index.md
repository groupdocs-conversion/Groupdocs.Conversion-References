---
title: "AudioFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert audiobestanden. Bevat de volgende types          Meer informatie over audioformaten hier."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

Definieert audiobestanden. Bevat de volgende types: , , , , , , , , , Meer informatie over audioformaten [hier][].


[here]: https://docs.fileformat.com/audio/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AudioFileType()](#AudioFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Mp3](#Mp3) | Bestanden met de .mp3-extensie zijn digitaal gecodeerde bestandsformaten voor audiobestanden die formeel gebaseerd zijn op MPEG-1 Audio Layer III of MPEG-2 Audio Layer III. |
| [Aac](#Aac) | AAC (Advanced Audio Coding) verwijst naar een digitale audiocodeerstandaard die audiobestanden vertegenwoordigt op basis van verliesgevende audiocompressie. |
|  | [Aiff](#Aiff) | De AIFF (Audio Interchange File Format) is een ongecomprimeerd audio‑bestandformaat ontwikkeld door Apple in 1998, maar is gebaseerd op EA IFF 85. Meer informatie over dit bestandsformaat [hier][]. |


[here]: https://docs.fileformat.com/audio/aiff/ |
|  | [Flac](#Flac) | FLAC (Free Lossless Audio Codec) is een verliesloze compressie‑audio‑codeerformaat ontwikkeld door de Xiph.Org Foundation. Meer informatie over dit bestandsformaat [hier][]. |


[here]: https://docs.fileformat.com/audio/flac/ |
| [M4a](#M4a) | Het M4A-bestandsformaat is een audiobestand dat is gemaakt met behulp van de AAC (Advanced Audio Coding), die bekend staat als een verliesgevende compressie. |
| [Wma](#Wma) | Een bestand met de .wma-extensie vertegenwoordigt een audiobestand dat is opgeslagen in het Advanced Systems Format (ASF)-formaat. |
| [Ac3](#Ac3) | Een bestand met een .ac3-extensie is een Audio Codec 3‑bestand, geïntroduceerd door Dolby Laboratories. |
| [Ogg](#Ogg) | OGG is een Ogg Vorbis gecomprimeerd audio‑bestand dat is opgeslagen met de .ogg-extensie. |
| [Wav](#Wav) | WAV, bekend als WAVE (Waveform Audio File Format), is een subset van Microsoft\\u2019s Resource Interchange File Format (RIFF)-specificatie voor het opslaan van digitale audiobestanden. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


Serialisatieconstructor

### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


Bestanden met de .mp3-extensie zijn digitaal gecodeerde bestandsformaten voor audiobestanden die formeel gebaseerd zijn op MPEG-1 Audio Layer III of MPEG-2 Audio Layer III. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/audio/mp3/

### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) verwijst naar een digitale audiocodeerstandaard die audiobestanden vertegenwoordigt op basis van verliesgevende audiocompressie. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/audio/aac/

### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


De AIFF (Audio Interchange File Format) is een ongecomprimeerd audio‑bestandformaat ontwikkeld door Apple in 1998, maar is gebaseerd op EA IFF 85. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/audio/aiff/

### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC (Free Lossless Audio Codec) is een verliesloze compressie‑audio‑codeerformaat ontwikkeld door de Xiph.Org Foundation. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/audio/flac/

### M4a {#M4a}
```
public static final AudioFileType M4a
```


Het M4A-bestandsformaat is een audiobestand dat is gemaakt met behulp van de AAC (Advanced Audio Coding), die bekend staat als een verliesgevende compressie. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/audio/m4a/

### Wma {#Wma}
```
public static final AudioFileType Wma
```


Een bestand met de .wma-extensie vertegenwoordigt een audiobestand dat is opgeslagen in het Advanced Systems Format (ASF)-formaat. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/audio/wma/

### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


Een bestand met een .ac3-extensie is een Audio Codec 3‑bestand, geïntroduceerd door Dolby Laboratories. Het is een audio‑formaat dat tot zes kanalen audio‑output kan bevatten. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/audio/ac3/

### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG is een Ogg Vorbis gecomprimeerd audio‑bestand dat is opgeslagen met de .ogg-extensie. OGG‑bestanden worden gebruikt voor het opslaan van audiogegevens en kunnen ook artiest‑ en trackinformatie en metadata bevatten. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/audio/ogg/

### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, bekend als WAVE (Waveform Audio File Format), is een subset van Microsoft\\u2019s Resource Interchange File Format (RIFF)-specificatie voor het opslaan van digitale audiobestanden. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/audio/ogg/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Voorbereide standaard conversie‑opties voor het bestandstype

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
