---
title: WordProcessingConvertOptions
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Optionen für die Konvertierung in den Dateityp WordProcessing.
type: docs
weight: 2000
url: /de/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Optionen für die Konvertierung in den Dateityp WordProcessing.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Initialisiert eine neue Instanz von[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | Gewünschte Seiten-DPI nach Konvertierung. Die Standardauflösung ist: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Der gewünschte Dateityp, in den das Eingabedokument konvertiert werden soll. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Gewünschte Seitenhöhe nach Konvertierung. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Gewünschter unterer Rand der Seite in Pixel nach der Konvertierung. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Gewünschter linker Seitenrand in Pixel nach der Konvertierung. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Gewünschter rechter Seitenrand in Pixel nach der Konvertierung. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Gewünschter oberer Seitenrand in Pixel nach der Konvertierung. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Die Seitenzahl, ab der die Konvertierung beginnen soll. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Gewünschte Seitenausrichtung nach Konvertierung |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Die Liste der zu konvertierenden Seitenindizes. Sollte angegeben werden, um bestimmte Seiten zu konvertieren. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Anzahl der zu konvertierenden Seiten ab`Seitennummer` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Gewünschte Seitengröße nach Konvertierung |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Legen Sie diese Eigenschaft fest, wenn Sie das konvertierte Dokument mit einem Passwort schützen möchten. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Erkennungsmodus beim Konvertieren von pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | RTF-spezifische Konvertierungsoptionen |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Wasserzeichenspezifische Optionen |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Gewünschte Seitenbreite nach Konvertierung. |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Gibt die Zoomstufe in Prozent an. Der Standardwert ist 100. Der Standardzoom wird bis Microsoft Word 2010 unterstützt. Ab Microsoft Word 2013 ist der Standardzoom nicht mehr auf Dokument eingestellt, sondern scheint den Zoomfaktor des zuletzt geöffneten Dokuments zu verwenden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klont die aktuelle Optionsinstanz. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hash-Funktion. |

### Siehe auch

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* namensraum [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
