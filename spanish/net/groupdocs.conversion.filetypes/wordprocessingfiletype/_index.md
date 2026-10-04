---
title: "WordProcessingFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define archivos de procesamiento de texto que contienen información del usuario en formato de texto plano o texto enriquecido. Un formato de archivo de texto plano contiene texto sin formato y no se pueden aplicar fuentes, configuraciones de página, etc. En contraste, un formato de archivo de texto enriquecido permite opciones de formato como establecer tipos de fuentes, estilos, negrita, cursiva, subrayado, etc., márgenes de página, encabezados, viñetas y numeración, y varias otras características de formato. Incluye los siguientes tipos de archivo Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt Md./wordprocessingfiletype/md. Obtén más información sobre los formatos de procesamiento de texto aquíhttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /es/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Define los archivos de procesamiento de texto que contienen información del usuario en formato de texto plano o formato de texto enriquecido. Un formato de archivo de texto plano contiene texto sin formato y no se pueden aplicar fuentes ni configuraciones de página, etc. En contraste, un formato de texto enriquecido permite opciones de formato como establecer tipos de fuentes, estilos (negrita, cursiva, subrayado, etc.), márgenes de página, encabezados, viñetas y numeración, y varias otras características de formato. Incluye los siguientes tipos de archivo: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Obtén más información sobre los formatos de procesamiento de texto [aquí](https://wiki.fileformat.com/word-processing).

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
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La familia del archivo |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato del archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Los archivos con extensión .doc representan documentos generados por Microsoft Word u otros documentos de procesamiento de texto en formato binario. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | Los archivos DOCM son documentos generados por Microsoft Word 2007 o versiones superiores con la capacidad de ejecutar macros. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX es un formato bien conocido para documentos de Microsoft Word. Introducido a partir de 2007 con el lanzamiento de Microsoft Office 2007, la estructura de este nuevo formato de documento cambió de binario plano a una combinación de archivos XML y binarios. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Los archivos con extensión .DOT son archivos plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de futuros archivos DOC o DOCX. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Un archivo con extensión DOTM representa un archivo plantilla creado con Microsoft Word 2007 o versiones superiores. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Los archivos con extensión DOTX son archivos plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de futuros archivos DOCX. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word es Office Open XML WordprocessingML almacenado en un archivo XML plano en lugar de un paquete ZIP. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Los archivos de texto creados con dialectos del lenguaje Markdown se guardan con la extensión .MD o .MARKDOWN. Los archivos MD se guardan en formato de texto plano que utiliza el lenguaje Markdown, que también incluye símbolos de texto en línea, definiendo cómo se puede formatear un texto, como sangrías, formato de tablas, fuentes y encabezados. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | Los archivos ODT son un tipo de documentos creados con aplicaciones de procesamiento de texto que se basan en el formato de archivo OpenDocument Text. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Los archivos con extensión OTT representan documentos plantilla generados por aplicaciones en cumplimiento con el formato estándar OpenDocument de OASIS. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Introducido y documentado por Microsoft, el Formato de Texto Enriquecido (RTF) representa un método de codificación de texto formateado y gráficos para su uso dentro de aplicaciones. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Un archivo con extensión .TXT representa un documento de texto que contiene texto plano en forma de líneas. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/txt). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
