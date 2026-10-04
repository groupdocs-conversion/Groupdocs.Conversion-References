---
title: "GroupDocs.Conversion.Options.Convert"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "El espacio de nombres proporciona clases para especificar opciones adicionales para el proceso de conversión de documentos."
type: docs
weight: 130
url: /es/net/groupdocs.conversion.options.convert/
---
El espacio de nombres proporciona clases para especificar opciones adicionales para el proceso de conversión de documentos.

## Clases

| Clase | Descripción |
| --- | --- |
| [AudioConvertOptions](./audioconvertoptions) | Opciones para la conversión al tipo Audio. |
| [CadConvertOptions](./cadconvertoptions) | Opciones para la conversión al tipo Cad. |
| [CommonConvertOptions&lt;TFileType&gt;](./commonconvertoptions-1) | Clase abstracta genérica de opciones comunes de conversión. |
| [CompressionConvertOptions](./compressionconvertoptions) | Opciones para la conversión al tipo de archivo Compresión. |
| [ConvertOptions](./convertoptions) | La clase general de opciones de conversión. |
| [ConvertOptions&lt;TFileType&gt;](./convertoptions-1) | Clase abstracta genérica de opciones de conversión. |
| [DiagramConvertOptions](./diagramconvertoptions) | Opciones para la conversión al tipo de archivo Diagrama. |
| [EBookConvertOptions](./ebookconvertoptions) | Opciones para la conversión al tipo de archivo Libro electrónico. |
| [EmailConvertOptions](./emailconvertoptions) | Opciones para la conversión al tipo de archivo Correo electrónico. |
| [FinanceConvertOptions](./financeconvertoptions) | Opciones para la conversión al tipo financiero. |
| [Font](./font) | Configuración de fuente |
| [FontConvertOptions](./fontconvertoptions) | Opciones para la conversión al tipo de fuente. |
| [GisConvertOptions](./gisconvertoptions) | Opciones para la conversión al tipo GIS. |
| [ImageConvertOptions](./imageconvertoptions) | Opciones para la conversión al tipo de archivo Imagen. |
| [ImageFlipModes](./imageflipmodes) | Describe los modos de volteo de imagen. |
| [JpegOptions](./jpegoptions) | Opciones para la conversión al tipo de archivo Jpeg. |
| [JpgColorModes](./jpgcolormodes) | Describe la enumeración de modos de color Jpg. |
| [JpgCompressionMethods](./jpgcompressionmethods) | Describe los modos de compresión Jpg |
| [MarkdownImageSavingArgs](./markdownimagesavingargs) | Argumentos pasados a [`ImageSaving`](../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving). |
| [MarkdownOptions](./markdownoptions) | Opciones para la conversión al tipo de archivo markdown. |
| [NoConvertOptions](./noconvertoptions) | Clase de opción de conversión especial, que instruye al convertidor a copiar el documento fuente sin ningún procesamiento |
| [PageDescriptionLanguageConvertOptions](./pagedescriptionlanguageconvertoptions) | Opciones para la conversión al tipo de archivo de lenguaje de descripciones de página. |
| [PageOrientation](./pageorientation) | Especifica la orientación de la página |
| [PageResizeMode](./pageresizemode) | Especifica cómo debe escalarse el contenido cuando se cambia el tamaño de la página |
| [PdfConvertOptions](./pdfconvertoptions) | Opciones para la conversión al tipo de archivo Pdf. |
| [PdfDirection](./pdfdirection) | Describe la dirección del texto Pdf. |
| [PdfDocumentInfo](./pdfdocumentinfo) | Representa la información meta del documento PDF. |
| [PdfFontSubsetStrategy](./pdffontsubsetstrategy) | Especifica la estrategia de subconjunto de fuentes |
| [PdfFormats](./pdfformats) | Describe la enumeración de formatos PDF. |
| [PdfFormattingOptions](./pdfformattingoptions) | Define las opciones de formato PDF. |
| [PdfOptimizationOptions](./pdfoptimizationoptions) | Define las opciones de optimización PDF. |
| [PdfOptions](./pdfoptions) | Opciones para la conversión al tipo de archivo Pdf. |
| [PdfPageLayout](./pdfpagelayout) | Describe el diseño de página PDF. |
| [PdfPageMode](./pdfpagemode) | Describe el modo de página PDF |
| [PdfRecognitionMode](./pdfrecognitionmode) | Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto. |
| [PresentationConvertOptions](./presentationconvertoptions) | Describe las opciones de conversión al tipo de archivo de presentación. |
| [ProjectManagementConvertOptions](./projectmanagementconvertoptions) | Opciones de conversión al tipo de archivo de gestión de proyectos. |
| [PsdColorModes](./psdcolormodes) | Define la enumeración de modos de color PSD. |
| [PsdCompressionMethods](./psdcompressionmethods) | Describe los métodos de compresión PSD. |
| [PsdOptions](./psdoptions) | Opciones para convertir al tipo de archivo PSD. |
| [Rotation](./rotation) | Describe la enumeración de rotación de página |
| [RtfOptions](./rtfoptions) | Opciones de conversión al tipo de archivo RTF. |
| [SpreadsheetConvertOptions](./spreadsheetconvertoptions) | Opciones de conversión al tipo de archivo de hoja de cálculo. |
| [ThreeDConvertOptions](./threedconvertoptions) | Opciones de conversión al tipo 3D. |
| [TiffCompressionMethods](./tiffcompressionmethods) | Describe la enumeración de métodos de compresión TIFF. |
| [TiffOptions](./tiffoptions) | Opciones de conversión al tipo de archivo TIFF. |
| [VideoConvertOptions](./videoconvertoptions) | Opciones de conversión al tipo de video. |
| [WatermarkImageOptions](./watermarkimageoptions) | Opciones para establecer marca de agua en el documento convertido |
| [WatermarkOptions](./watermarkoptions) | Opciones para establecer marca de agua en el documento convertido |
| [WatermarkTextOptions](./watermarktextoptions) | Opciones para establecer marca de agua de texto en el documento convertido |
| [WebConvertOptions](./webconvertoptions) | Opciones de conversión al tipo de archivo web. |
| [WebpOptions](./webpoptions) | Opciones de conversión al tipo de archivo WebP. |
| [WordProcessingConvertOptions](./wordprocessingconvertoptions) | Opciones de conversión al tipo de archivo de procesamiento de texto. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IConvertOptions](./iconvertoptions) | Representa opciones de conversión |
| [IDpiConvertOptions](./idpiconvertoptions) | Representa opciones de conversión que admiten configuraciones DPI (puntos por pulgada). |
| [IMarkdownImageSavingCallback](./imarkdownimagesavingcallback) | Gestiona el procesamiento personalizado de imágenes al guardar en Markdown. Se invoca una vez por imagen; modifique [`MarkdownImageSavingArgs`](../groupdocs.conversion.options.convert/markdownimagesavingargs) para controlar el URI incrustado en la salida Markdown y/o redirigir dónde se escriben los bytes de la imagen. |
| [IPagedConvertOptions](./ipagedconvertoptions) | Representa opciones de conversión que permiten limitar la conversión especificando la página inicial y la cantidad de páginas. |
| [IPageRangedConvertOptions](./ipagerangedconvertoptions) | Representa opciones de conversión que admiten la conversión de una lista específica de páginas. |
| [IPasswordConvertOptions](./ipasswordconvertoptions) | Representa opciones de conversión que admiten la protección con contraseña para documentos convertidos. |
| [IPdfRecognitionModeOptions](./ipdfrecognitionmodeoptions) | Representa opciones de conversión que controlan el modo de reconocimiento al convertir desde PDF. |
| [IUsePdfConvertOptions](./iusepdfconvertoptions) | Representa opciones que admiten la conversión a PDF si es necesario. |
| [IWatermarkedConvertOptions](./iwatermarkedconvertoptions) | Representa opciones de conversión que permiten que la salida de la conversión tenga una marca de agua. |
| [IZoomConvertOptions](./izoomconvertoptions) | Representa opciones de conversión que permiten realizar la conversión con opciones de zoom. |

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
