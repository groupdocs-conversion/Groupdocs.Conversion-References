---
title: "GroupDocs.Conversion.Options.Convert"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "L'espace de noms fournit des classes pour spécifier des options supplémentaires pour le processus de conversion de documents."
type: docs
weight: 130
url: /fr/net/groupdocs.conversion.options.convert/
---
L'espace de noms fournit des classes pour spécifier des options supplémentaires pour le processus de conversion de documents.

## Classes

| Classe | Description |
| --- | --- |
| [AudioConvertOptions](./audioconvertoptions) | Options de conversion vers le type Audio. |
| [CadConvertOptions](./cadconvertoptions) | Options de conversion vers le type Cad. |
| [CommonConvertOptions&lt;TFileType&gt;](./commonconvertoptions-1) | Classe abstraite générique d'options de conversion communes. |
| [CompressionConvertOptions](./compressionconvertoptions) | Options de conversion vers le type de fichier Compression. |
| [ConvertOptions](./convertoptions) | La classe générale d'options de conversion. |
| [ConvertOptions&lt;TFileType&gt;](./convertoptions-1) | Classe abstraite générique d'options de conversion. |
| [DiagramConvertOptions](./diagramconvertoptions) | Options de conversion vers le type de fichier Diagram. |
| [EBookConvertOptions](./ebookconvertoptions) | Options de conversion vers le type de fichier EBook. |
| [EmailConvertOptions](./emailconvertoptions) | Options de conversion vers le type de fichier Email. |
| [FinanceConvertOptions](./financeconvertoptions) | Options de conversion vers le type finance. |
| [Font](./font) | Paramètres de police |
| [FontConvertOptions](./fontconvertoptions) | Options de conversion vers le type de police Font. |
| [GisConvertOptions](./gisconvertoptions) | Options de conversion vers le type GIS. |
| [ImageConvertOptions](./imageconvertoptions) | Options de conversion vers le type de fichier Image. |
| [ImageFlipModes](./imageflipmodes) | Décrit les modes de retournement d'image. |
| [JpegOptions](./jpegoptions) | Options de conversion vers le type de fichier Jpeg. |
| [JpgColorModes](./jpgcolormodes) | Décrit l'énumération des modes de couleur Jpg. |
| [JpgCompressionMethods](./jpgcompressionmethods) | Décrit les modes de compression Jpg |
| [MarkdownImageSavingArgs](./markdownimagesavingargs) | Arguments transmis à [`ImageSaving`](../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving). |
| [MarkdownOptions](./markdownoptions) | Options de conversion vers le type de fichier markdown. |
| [NoConvertOptions](./noconvertoptions) | Classe d'option de conversion spéciale, qui indique au convertisseur de copier le document source sans aucun traitement |
| [PageDescriptionLanguageConvertOptions](./pagedescriptionlanguageconvertoptions) | Options de conversion vers le type de fichier de langage de descriptions de page. |
| [PageOrientation](./pageorientation) | Spécifie l'orientation de la page |
| [PageResizeMode](./pageresizemode) | Spécifie comment le contenu doit être mis à l'échelle lorsque la taille de la page est modifiée |
| [PdfConvertOptions](./pdfconvertoptions) | Options de conversion vers le type de fichier Pdf. |
| [PdfDirection](./pdfdirection) | Décrit la direction du texte Pdf. |
| [PdfDocumentInfo](./pdfdocumentinfo) | Représente les méta-informations du document PDF. |
| [PdfFontSubsetStrategy](./pdffontsubsetstrategy) | Spécifie la stratégie de sous-ensemble de polices |
| [PdfFormats](./pdfformats) | Décrit l'énumération des formats PDF. |
| [PdfFormattingOptions](./pdfformattingoptions) | Définit les options de formatage PDF. |
| [PdfOptimizationOptions](./pdfoptimizationoptions) | Définit les options d'optimisation PDF. |
| [PdfOptions](./pdfoptions) | Options de conversion vers le type de fichier Pdf. |
| [PdfPageLayout](./pdfpagelayout) | Décrit la mise en page PDF. |
| [PdfPageMode](./pdfpagemode) | Décrit le mode de page PDF |
| [PdfRecognitionMode](./pdfrecognitionmode) | Permet de contrôler comment un document PDF est converti en document de traitement de texte. |
| [PresentationConvertOptions](./presentationconvertoptions) | Décrit les options de conversion vers le type de fichier Présentation. |
| [ProjectManagementConvertOptions](./projectmanagementconvertoptions) | Options de conversion vers le type de fichier de gestion de projet. |
| [PsdColorModes](./psdcolormodes) | Définit l'énumération des modes couleur PSD. |
| [PsdCompressionMethods](./psdcompressionmethods) | Décrit les méthodes de compression PSD. |
| [PsdOptions](./psdoptions) | Options de conversion vers le type de fichier PSD. |
| [Rotation](./rotation) | Décrit l'énumération de rotation de page |
| [RtfOptions](./rtfoptions) | Options de conversion vers le type de fichier RTF. |
| [SpreadsheetConvertOptions](./spreadsheetconvertoptions) | Options de conversion vers le type de fichier Feuille de calcul. |
| [ThreeDConvertOptions](./threedconvertoptions) | Options de conversion vers le type 3D. |
| [TiffCompressionMethods](./tiffcompressionmethods) | Décrit l'énumération des méthodes de compression TIFF. |
| [TiffOptions](./tiffoptions) | Options de conversion vers le type de fichier TIFF. |
| [VideoConvertOptions](./videoconvertoptions) | Options de conversion vers le type Vidéo. |
| [WatermarkImageOptions](./watermarkimageoptions) | Options pour définir le filigrane du document converti |
| [WatermarkOptions](./watermarkoptions) | Options pour définir le filigrane du document converti |
| [WatermarkTextOptions](./watermarktextoptions) | Options pour définir le filigrane texte du document converti |
| [WebConvertOptions](./webconvertoptions) | Options de conversion vers le type de fichier Web. |
| [WebpOptions](./webpoptions) | Options de conversion vers le type de fichier WebP. |
| [WordProcessingConvertOptions](./wordprocessingconvertoptions) | Options de conversion vers le type de fichier de traitement de texte. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IConvertOptions](./iconvertoptions) | Représente les options de conversion |
| [IDpiConvertOptions](./idpiconvertoptions) | Représente les options de conversion qui prennent en charge les paramètres DPI (points par pouce). |
| [IMarkdownImageSavingCallback](./imarkdownimagesavingcallback) | Gère le traitement personnalisé des images lors de l'enregistrement au format Markdown. Invoqué une fois par image ; modifiez [`MarkdownImageSavingArgs`](../groupdocs.conversion.options.convert/markdownimagesavingargs) pour contrôler l'URI intégré dans la sortie Markdown et/ou rediriger l'endroit où les octets de l'image sont écrits. |
| [IPagedConvertOptions](./ipagedconvertoptions) | Représente les options de conversion qui permettent de limiter les pages de la conversion en spécifiant la page de départ et le nombre de pages. |
| [IPageRangedConvertOptions](./ipagerangedconvertoptions) | Représente les options de conversion qui prennent en charge la conversion d'une liste spécifique de pages. |
| [IPasswordConvertOptions](./ipasswordconvertoptions) | Représente les options de conversion qui prennent en charge la protection par mot de passe des documents convertis. |
| [IPdfRecognitionModeOptions](./ipdfrecognitionmodeoptions) | Représente les options de conversion qui contrôlent le mode de reconnaissance lors de la conversion depuis un PDF. |
| [IUsePdfConvertOptions](./iusepdfconvertoptions) | Représente les options qui prennent en charge la conversion en PDF si nécessaire. |
| [IWatermarkedConvertOptions](./iwatermarkedconvertoptions) | Implémentation du journaliseur console. |
| [IZoomConvertOptions](./izoomconvertoptions) | Définit les méthodes utilisées pour effectuer la journalisation. |

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
