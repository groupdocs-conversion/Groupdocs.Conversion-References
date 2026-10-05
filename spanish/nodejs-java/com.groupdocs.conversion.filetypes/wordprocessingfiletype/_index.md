---
title: "WordProcessingFileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define archivos de procesamiento de texto que contienen información del usuario en texto plano o formato de texto enriquecido."
type: docs
weight: 28
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Define los archivos de procesamiento de texto que contienen información del usuario en texto plano o formato de texto enriquecido. Un formato de archivo de texto plano contiene texto sin formato y no se pueden aplicar fuentes ni configuraciones de página, etc. En contraste, un formato de texto enriquecido permite opciones de formato como establecer tipos de fuentes, estilos (negrita, cursiva, subrayado, etc.), márgenes de página, encabezados, viñetas y numeración, y varias otras características de formato. Incluye los siguientes tipos de archivo: [Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Doc), [Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Docm), [Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Docx), [Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Dot), [Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Dotm), [Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Dotx), [Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Odt), [Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Ott), [Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Rtf), [Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Txt), [Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\\#Md), Obtenga más información sobre los formatos de procesamiento de texto [here][].


[here]: https://wiki.fileformat.com/word-processing
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordProcessingFileType()](#WordProcessingFileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Doc](#Doc) | Los archivos con extensión .doc representan documentos generados por Microsoft Word u otros documentos de procesamiento de texto en formato de archivo binario. |
| [Docm](#Docm) | Los archivos DOCM son documentos generados por Microsoft Word 2007 o versiones posteriores con la capacidad de ejecutar macros. |
| [Docx](#Docx) | DOCX es un formato bien conocido para documentos de Microsoft Word. |
| [Dot](#Dot) | Los archivos con extensión .DOT son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de futuros archivos DOC o DOCX. |
| [Dotm](#Dotm) | Un archivo con extensión DOTM representa una plantilla creada con Microsoft Word 2007 o versiones posteriores. |
| [Dotx](#Dotx) | Los archivos con extensión DOTX son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de futuros archivos DOCX. |
| [Rtf](#Rtf) | Introducido y documentado por Microsoft, el Rich Text Format (RTF) representa un método de codificación de texto formateado y gráficos para su uso dentro de aplicaciones. |
| [Odt](#Odt) | Los archivos ODT son un tipo de documentos creados con aplicaciones de procesamiento de texto que se basan en el formato de archivo OpenDocument Text. |
| [Ott](#Ott) | Los archivos con extensión OTT representan documentos de plantilla generados por aplicaciones en cumplimiento con el formato estándar OpenDocument de OASIS. |
| [Txt](#Txt) | Un archivo con extensión .TXT representa un documento de texto que contiene texto plano en forma de líneas. |
| [Md](#Md) | Los archivos de texto creados con dialectos del lenguaje Markdown se guardan con la extensión de archivo .MD o .MARKDOWN. |
| [Ml](#Ml) | Archivo Ml |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


Constructor de serialización

### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


Los archivos con extensión .doc representan documentos generados por Microsoft Word u otros documentos de procesamiento de texto en formato de archivo binario. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


Los archivos DOCM son documentos generados por Microsoft Word 2007 o versiones posteriores con la capacidad de ejecutar macros. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX es un formato bien conocido para documentos de Microsoft Word. Introducido a partir de 2007 con el lanzamiento de Microsoft Office 2007, la estructura de este nuevo formato de documento cambió de binario puro a una combinación de archivos XML y binarios. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/word-processing/docx

### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


Los archivos con extensión .DOT son archivos de plantilla creados por Microsoft Word para tener configuraciones predefinidas para la generación de futuros archivos DOC o DOCX. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/word-processing/dot

### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


Un archivo con extensión DOTM representa un archivo de plantilla creado con Microsoft Word 2007 o superior. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


Los archivos con extensión DOTX son archivos de plantilla creados por Microsoft Word para tener configuraciones predefinidas para la generación de futuros archivos DOCX. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Introducido y documentado por Microsoft, el Rich Text Format (RTF) representa un método de codificación de texto formateado y gráficos para su uso en aplicaciones. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


Los archivos ODT son un tipo de documentos creados con aplicaciones de procesamiento de texto basadas en el formato OpenDocument Text File. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/word-processing/odt

### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


Los archivos con extensión OTT representan documentos de plantilla generados por aplicaciones en cumplimiento con el formato estándar OpenDocument de OASIS. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/word-processing/ott

### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


Un archivo con extensión .TXT representa un documento de texto que contiene texto plano en forma de líneas. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/word-processing/txt

### Md {#Md}
```
public static final WordProcessingFileType Md
```


Los archivos de texto creados con dialectos del lenguaje Markdown se guardan con la extensión de archivo .MD o .MARKDOWN. Los archivos MD se guardan en formato de texto plano que utiliza el lenguaje Markdown, el cual también incluye símbolos de texto en línea, definiendo cómo se puede formatear un texto, como sangrías, formato de tablas, fuentes y encabezados. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/word-processing/md

### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Archivo Ml

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
```


Opciones de conversión predeterminadas preparadas para el tipo de archivo

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
