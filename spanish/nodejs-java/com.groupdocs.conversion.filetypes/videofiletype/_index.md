---
title: "VideoFileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define documentos de video Incluye los siguientes tipos        Obtén más información sobre los formatos de video aquí."
type: docs
weight: 26
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Define documentos de video Incluye los siguientes tipos: , , , , , , , Obtenga más información sobre los formatos de video [aquí][].


[here]: https://docs.fileformat.com/video/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VideoFileType()](#VideoFileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Mp4](#Mp4) | MP4 (abreviatura de MPEG-4 Parte 14) es un formato de archivo basado en ISO/IEC 14496-12:2004 que se basa en QuickTime File Format pero especifica formalmente el soporte para Descriptores de Objeto Inicial (IOD) y otras características MPEG. |
| [Avi](#Avi) | El formato de archivo AVI es un contenedor multimedia de audio y video que fue introducido por Microsoft. |
| [Flv](#Flv) | FLV (Flash Video) es un formato de contenedor de archivo con la extensión .flv. |
| [Mkv](#Mkv) | MKV (Matroska Video) es un contenedor multimedia similar a los formatos MOV y AVI, pero admite más de una pista de audio y subtítulos en el mismo archivo. |
| [Mov](#Mov) | MOV o el formato de archivo QuickTime es un contenedor multimedia desarrollado por Apple: contiene una o más pistas, cada pista almacena un tipo particular de datos, por ejemplo. |
| [Webm](#Webm) | Un archivo con extensión .webm es un archivo de video basado en el formato de archivo abierto y libre de regalías WebM. |
| [Wmv](#Wmv) | Windows Media Video es el formato de video comprimido desarrollado por Microsoft. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Constructor de serialización

### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (abreviatura de MPEG-4 Parte 14) es un formato de archivo basado en ISO/IEC 14496-12:2004 que se basa en QuickTime File Format pero especifica formalmente el soporte para Descriptores de Objeto Inicial (IOD) y otras características MPEG. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/video/mp4/

### Avi {#Avi}
```
public static final VideoFileType Avi
```


El formato de archivo AVI es un contenedor multimedia de audio y video que fue introducido por Microsoft. Contiene los datos de audio y video creados y comprimidos usando varios códecs (Codificadores/Decodificadores) como XVid y DivX. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/video/avi/

### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) es un formato de contenedor de archivo con la extensión .flv. FLV se utiliza para entregar contenido de audio/video a través de internet mediante Adobe Flash Player o Adobe Air. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/video/flv/

### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) es un contenedor multimedia similar a los formatos MOV y AVI, pero admite más de una pista de audio y subtítulos en el mismo archivo. Un archivo MKV es el formato de contenedor multimedia Matroska utilizado para video. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/video/mkv/

### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV o el formato de archivo QuickTime es un contenedor multimedia desarrollado por Apple: contiene una o más pistas, cada pista almacena un tipo particular de datos, por ejemplo Video, Audio, texto, etc. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/video/mov/

### Webm {#Webm}
```
public static final VideoFileType Webm
```


Un archivo con extensión .webm es un archivo de video basado en el formato de archivo abierto y libre de regalías WebM. Ha sido diseñado para compartir video en la web y define la estructura del contenedor de archivo, incluidos los formatos de video y audio. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/video/webm//

### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video es el formato de video comprimido desarrollado por Microsoft. Después de la estandarización por la Society of Motion Picture and Television Engineers (SMPTE), WMV ahora se considera un formato estándar abierto. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/video/wmv/

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
