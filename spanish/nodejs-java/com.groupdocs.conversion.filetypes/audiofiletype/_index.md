---
title: "AudioFileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define documentos de audio. Incluye los siguientes tipos          Obtenga más información sobre los formatos de audio aquí."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

Define documentos de audio. Incluye los siguientes tipos: , , , , , , , , , Obtenga más información sobre los formatos de audio [aquí][].


[here]: https://docs.fileformat.com/audio/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AudioFileType()](#AudioFileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Mp3](#Mp3) | Los archivos con extensión .mp3 son formatos de archivo codificados digitalmente para archivos de audio que se basan formalmente en MPEG-1 Audio Layer III o MPEG-2 Audio Layer III. |
| [Aac](#Aac) | AAC (Advanced Audio Coding) se refiere a un estándar de codificación de audio digital que representa archivos de audio basados en compresión con pérdida. |
|  | [Aiff](#Aiff) | El AIFF (Audio Interchange File Format) es un formato de archivo de audio sin comprimir desarrollado por Apple en 1998, pero se basa en EA IFF 85. Obtenga más información sobre este formato de archivo [aquí][]. |


[here]: https://docs.fileformat.com/audio/aiff/ |
|  | [Flac](#Flac) | FLAC (Free Lossless Audio Codec) es un formato de codificación de audio con compresión sin pérdida desarrollado por Xiph.Org Foundation. Obtenga más información sobre este formato de archivo [aquí][]. |


[here]: https://docs.fileformat.com/audio/flac/ |
| [M4a](#M4a) | El formato de archivo M4A es un archivo de audio creado usando AAC (Advanced Audio Coding), que se conoce como compresión con pérdida. |
| [Wma](#Wma) | Un archivo con extensión .wma representa un archivo de audio que se guarda en el formato Advanced Systems Format (ASF). |
| [Ac3](#Ac3) | Un archivo con extensión .ac3 es un archivo Audio Codec 3, introducido por Dolby Laboratories. |
| [Ogg](#Ogg) | OGG es un archivo de audio comprimido Ogg Vorbis que se guarda con la extensión .ogg. |
| [Wav](#Wav) | WAV, conocido por WAVE (Waveform Audio File Format), es un subconjunto de la especificación Resource Interchange File Format (RIFF) de Microsoft\u2019s para almacenar archivos de audio digitales. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


Constructor de serialización

### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


Los archivos con extensión .mp3 son formatos de archivo codificados digitalmente para archivos de audio que se basan formalmente en MPEG-1 Audio Layer III o MPEG-2 Audio Layer III. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/audio/mp3/

### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) se refiere a un estándar de codificación de audio digital que representa archivos de audio basados en compresión con pérdida. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/audio/aac/

### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


El AIFF (Audio Interchange File Format) es un formato de archivo de audio sin comprimir desarrollado por Apple en 1998, pero se basa en EA IFF 85. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/audio/aiff/

### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC (Free Lossless Audio Codec) es un formato de codificación de audio con compresión sin pérdida desarrollado por Xiph.Org Foundation. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/audio/flac/

### M4a {#M4a}
```
public static final AudioFileType M4a
```


El formato de archivo M4A es un archivo de audio creado usando AAC (Advanced Audio Coding), que se conoce como compresión con pérdida. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/audio/m4a/

### Wma {#Wma}
```
public static final AudioFileType Wma
```


Un archivo con extensión .wma representa un archivo de audio que se guarda en el formato Advanced Systems Format (ASF). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/audio/wma/

### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


Un archivo con extensión .ac3 es un archivo Audio Codec 3, introducido por Dolby Laboratories. Es un formato de audio que puede contener hasta seis canales de salida de audio. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/audio/ac3/

### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG es un archivo de audio comprimido Ogg Vorbis que se guarda con la extensión .ogg. Los archivos OGG se utilizan para almacenar datos de audio y pueden incluir información de artista y pista, así como metadatos. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/audio/ogg/

### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, conocido por WAVE (Waveform Audio File Format), es un subconjunto de la especificación Resource Interchange File Format (RIFF) de Microsoft\u2019s para almacenar archivos de audio digitales. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/audio/ogg/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opciones de conversión predeterminadas preparadas para el tipo de archivo

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
