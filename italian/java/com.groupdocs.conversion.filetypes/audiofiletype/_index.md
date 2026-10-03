---
title: "AudioFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce documenti audio. Include i seguenti tipi          Scopri di più sui formati audio qui."
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

Definisce documenti audio. Include i seguenti tipi: , , , , , , , , , Scopri di più sui formati audio [qui](../https://docs.fileformat.com/audio/).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [AudioFileType()](#AudioFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Mp3](#Mp3) | I file con estensione .mp3 sono formati di file audio codificati digitalmente, basati formalmente su MPEG-1 Audio Layer III o MPEG-2 Audio Layer III. |
|
|  | [Aac](#Aac) | AAC (Advanced Audio Coding) si riferisce a uno standard di codifica audio digitale che rappresenta i file audio basati su compressione audio con perdita. |
|
|  | [Aiff](#Aiff) | Il formato AIFF (Audio Interchange File Format) è un formato audio non compresso sviluppato da Apple nel 1998, ma basato su EA IFF 85. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/aiff/). |
|
|  | [Flac](#Flac) | FLAC (Free Lossless Audio Codec) è un formato di codifica audio a compressione lossless sviluppato dalla Xiph.Org Foundation. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/flac/). |
|
|  | [M4a](#M4a) | Il formato M4A è un file audio creato utilizzando l'AAC (Advanced Audio Coding), noto per la compressione con perdita. |
|
|  | [Wma](#Wma) | Un file con estensione .wma rappresenta un file audio salvato nel formato Advanced Systems Format (ASF). |
|
|  | [Ac3](#Ac3) | Un file con estensione .ac3 è un file Audio Codec 3, introdotto da Dolby Laboratories. |
|
|  | [Ogg](#Ogg) | OGG è un file audio compresso Ogg Vorbis salvato con l'estensione .ogg. |
|
|  | [Wav](#Wav) | WAV, noto per WAVE (Waveform Audio File Format), è un sottoinsieme della specifica Resource Interchange File Format (RIFF) di Microsoft\\u2019s per la memorizzazione di file audio digitali. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


Costruttore di serializzazione


### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


I file con estensione .mp3 sono formati di file audio codificati digitalmente, basati formalmente su MPEG-1 Audio Layer III o MPEG-2 Audio Layer III. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/mp3/).


### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) si riferisce a uno standard di codifica audio digitale che rappresenta file audio basati su compressione audio con perdita. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/aac/).


### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


Il formato AIFF (Audio Interchange File Format) è un formato audio non compresso sviluppato da Apple nel 1998, ma basato su EA IFF 85. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/aiff/).


### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC (Free Lossless Audio Codec) è un formato di codifica audio a compressione lossless sviluppato dalla Xiph.Org Foundation. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/flac/).


### M4a {#M4a}
```
public static final AudioFileType M4a
```


Il formato M4A è un file audio creato utilizzando l'AAC (Advanced Audio Coding), noto per la compressione con perdita. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/m4a/).


### Wma {#Wma}
```
public static final AudioFileType Wma
```


Un file con estensione .wma rappresenta un file audio salvato nel formato Advanced Systems Format (ASF). Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/wma/).


### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


Un file con estensione .ac3 è un file Audio Codec 3, introdotto da Dolby Laboratories. È un formato audio che può contenere fino a sei canali di uscita audio. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/ac3/).


### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG è un file audio compresso Ogg Vorbis salvato con l'estensione .ogg. I file OGG sono usati per memorizzare dati audio e possono includere informazioni su artista, traccia e metadati. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/ogg/).


### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, noto per WAVE (Waveform Audio File Format), è un sottoinsieme della specifica Resource Interchange File Format (RIFF) di Microsoft\\u2019s per la memorizzazione di file audio digitali. Scopri di più su questo formato [qui](../https://docs.fileformat.com/audio/ogg/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite preparate per il tipo di file di origine


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opzioni di conversione predefinite preparate per il tipo di file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
