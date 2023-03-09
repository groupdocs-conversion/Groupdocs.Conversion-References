---
title: WordProcessingConvertOptions
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Opties voor conversie naar WordProcessingbestandstype.
type: docs
weight: 2000
url: /nl/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Opties voor conversie naar WordProcessing-bestandstype.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Initialiseert nieuw exemplaar van[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | Gewenste pagina-DPI na conversie. De standaardresolutie is: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Gewenste paginahoogte na conversie. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Gewenste ondermarge pagina in pixels na conversie. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Gewenste pagina linkermarge in pixels na conversie. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Gewenste pagina rechtermarge in pixels na conversie. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Gewenste bovenmarge pagina in pixels na conversie. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Het paginanummer vanaf waar de conversie moet worden gestart. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Gewenste pagina-oriëntatie na conversie |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | De lijst met pagina-indexen die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Aantal pagina's om vanaf te converteren`Paginanummer` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Gewenst paginaformaat na conversie |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Herkenningsmodus bij het converteren van pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | RTF-specifieke conversieopties |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Watermerkspecifieke opties |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Gewenste paginabreedte na conversie. |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Specificeert het zoomniveau in procenten. Standaard is 100. Standaard zoom wordt ondersteund tot Microsoft Word 2010. Vanaf Microsoft Word 2013 is standaard zoom niet langer ingesteld op document, maar lijkt de zoomfactor te gebruiken van het laatst geopende document. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Kloont de huidige optie-instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* naamruimte [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
