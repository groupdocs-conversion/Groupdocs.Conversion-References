---
title: WordProcessingFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define archivos de procesamiento de texto que contienen información del usuario en formato de texto sin formato o de texto enriquecido. Un formato de archivo de texto sin formato contiene texto sin formato y no se pueden aplicar configuraciones de fuente o página etc. Por el contrario un formato de archivo de texto enriquecido permite opciones de formato como la configuración del tipo de fuente estilos negrita cursiva subrayado etc. márgenes de página encabezados viñetas y números y varias otras funciones de formato. Incluye los siguientes tipos de archivo Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi./wordprocessingfiletype/mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log./wordprocessingfiletype/log . Obtenga más información sobre los formatos de procesamiento de textosaquíhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 960
url: /es/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Define archivos de procesamiento de texto que contienen información del usuario en formato de texto sin formato o de texto enriquecido. Un formato de archivo de texto sin formato contiene texto sin formato y no se pueden aplicar configuraciones de fuente o página, etc. Por el contrario, un formato de archivo de texto enriquecido permite opciones de formato como la configuración del tipo de fuente, estilos (negrita, cursiva, subrayado, etc.), márgenes de página, encabezados, viñetas y números, y varias otras funciones de formato. Incluye los siguientes tipos de archivo: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`Mobi`](./mobi) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . [`Log`](./log) . Obtenga más información sobre los formatos de procesamiento de textos[aquí](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Constructor de serialización |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descripción del tipo de archivo |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | La extensión del archivo |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | El archivo family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato de archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Azw3](../../groupdocs.conversion.filetypes/wordprocessingfiletype/azw3) | AZW3, también conocido como Kindle Format 8 (KF8), es la versión modificada del formato de archivo digital de libros electrónicos AZW desarrollado para dispositivos Amazon Kindle. El formato es una mejora de los archivos AZW más antiguos y se usa en dispositivos Kindle Fire solo con compatibilidad con versiones anteriores para el formato de archivo anterior, es decir, MOBI y AZW. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Los archivos con extensión .doc representan documentos generados por Microsoft Word u otros documentos de procesamiento de texto en formato de archivo binario. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | Los archivos DOCM son documentos generados por Microsoft Word 2007 o superior con la capacidad de ejecutar macros. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX es un formato muy conocido para documentos de Microsoft Word. Introducido a partir de 2007 con el lanzamiento de Microsoft Office 2007, la estructura de este nuevo formato de documento se cambió de binario simple a una combinación de XML y archivos binarios. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Los archivos con la extensión .DOT son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de más archivos DOC o DOCX. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Un archivo con extensión DOTM representa un archivo de plantilla creado con Microsoft Word 2007 o superior. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Los archivos con extensión DOTX son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de más archivos DOCX. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Log](../../groupdocs.conversion.filetypes/wordprocessingfiletype/log) | Un archivo con extensión .LOG representa un documento de texto que contiene texto plano en forma de líneas. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Los archivos de texto creados con los dialectos del idioma Markdown se guardan con la extensión de archivo .MD o .MARKDOWN. Los archivos MD se guardan en formato de texto sin formato que utiliza el lenguaje Markdown, que también incluye símbolos de texto en línea, que definen cómo se puede formatear un texto, como sangrías, formato de tablas, fuentes y encabezados. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/wordprocessingfiletype/mobi) | El formato de archivo MOBI es uno de los formatos de archivo de libros electrónicos más utilizados. El formato es una mejora del antiguo formato OEB (Open Ebook Format) y se utilizó como formato patentado para Mobipocket Reader. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/ebook/mobi) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | Los archivos ODT son un tipo de documentos creados con aplicaciones de procesamiento de textos que se basan en el formato de archivo de texto OpenDocument. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Los archivos con extensión OTT representan documentos de plantilla generados por aplicaciones de conformidad con el formato estándar OpenDocument de OASIS. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Presentado y documentado por Microsoft, el formato de texto enriquecido (RTF) representa un método de codificación de texto y gráficos con formato para su uso dentro de las aplicaciones. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Sql](../../groupdocs.conversion.filetypes/wordprocessingfiletype/sql) | Un archivo con extensión .SQL representa un documento de texto que contiene sql. |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Un archivo con extensión .TXT representa un documento de texto que contiene texto plano en forma de líneas. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/txt) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
