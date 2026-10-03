---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Optionen zum Laden von Spreadsheet-Dokumenten."
type: docs
weight: 2810
url: /de/net/groupdocs.conversion.options.load/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Optionen zum Laden von Spreadsheet-Dokumenten.

```csharp
public class SpreadsheetLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IPageMarginOptions, IPageSizeOptions, 
    IResourceLoadingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Initialisiert eine neue Instanz der Klasse [`SpreadsheetLoadOptions`](../spreadsheetloadoptions). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | Wenn AllColumnsInOnePagePerSheet true ist, wird der gesamte Spalteninhalt eines Blatts nur auf einer Seite im Ergebnis ausgegeben. Die Breite des Papierformats der Seiten­einrichtung wird ungültig sein, während die anderen Einstellungen der Seiten­einrichtung weiterhin wirksam bleiben. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | Passt alle Zeilen beim Konvertieren automatisch an. |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Ob die Beschränkungen der Excel‑Datei geprüft werden, wenn der Benutzer zellbezogene Objekte ändert. Beispielsweise erlaubt Excel nicht, einen Zeichenwert länger als 32 K einzugeben. Wenn Sie einen Wert länger als 32 K eingeben und diese Eigenschaft true ist, erhalten Sie eine Exception. Ist die Eigenschaft false, wird der eingegebene Zeichenwert als Zellwert akzeptiert, sodass Sie später den vollständigen Zeichenwert für andere Dateiformate wie CSV ausgeben können. Wenn Sie jedoch einen Wert festlegen, der für das Excel‑Dateiformat ungültig ist, sollten Sie die Arbeitsmappe später nicht im Excel‑Format speichern. Andernfalls kann es zu unerwarteten Fehlern in der erzeugten Excel‑Datei kommen. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | Entfernt integrierte Metadaten‑Eigenschaften aus dem Dokument. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | Entfernt benutzerdefinierte Metadaten‑Eigenschaften aus dem Dokument. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | Teilt ein Arbeitsblatt in Seiten nach Spalten. Standardwert ist 0, keine Paginierung. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | Implementiert [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). Standard ist false. |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | Implementiert [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner). Standard ist true. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Konvertiert einen bestimmten Bereich, wenn in ein anderes Format als das Tabellenkalkulationsformat konvertiert wird. Beispiel: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Liest oder setzt die System‑Culture‑Information zum Zeitpunkt des Ladens der Datei. |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Standardschriftart für das Tabellenkalkulationsdokument. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | Implementiert [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Standard: 1. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Ersetzt bestimmte Schriftarten beim Konvertieren des Tabellenkalkulationsdokuments. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Dateityp des Eingabedokuments. Ist `null`, bis ein Format festgelegt wurde, daher prüfen Sie auf `null` anstatt gegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) zu vergleichen, was niemals zutrifft. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Dateityp des Eingabedokuments. |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | Gibt an, ob Formelberechnungsfehler ignoriert werden sollen. Der Fehler kann eine nicht unterstützte Funktion, externe Verknüpfungen usw. sein. Standardwert ist false. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | Seitenrand-Einstellungen |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Wenn OnePagePerSheet true ist, wird der Inhalt des Blatts in eine Seite des PDF‑Dokuments konvertiert. Standardwert ist true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Wenn True und in PDF konvertiert wird, ist die Konvertierung für eine kleinere Dateigröße statt Druckqualität optimiert. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Passwort festlegen, um geschütztes Dokument zu entsperren. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | Bestimmt, ob die Dokumentstruktur beim Konvertieren zu PDF erhalten bleiben soll (Standard ist false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | Stellt dar, wie Kommentare mit dem Blatt gedruckt werden. Standardwert ist PrintNoComments. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | Setzt die Schriftarten‑Ordner zurück, bevor das Dokument geladen wird. |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | Teilt ein Arbeitsblatt in Seiten nach Zeilen. Standardwert ist 0, keine Paginierung. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Liste der zu konvertierenden Blattindizes. Die Indizes müssen nullbasiert sein. |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Blattname zum Konvertieren |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Gitternetzlinien beim Konvertieren von Excel-Dateien anzeigen. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Versteckte Blätter beim Konvertieren von Excel-Dateien anzeigen. |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | Seitengröße-Einstellungen |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Überspringt leere Zeilen und Spalten beim Konvertieren. Standard ist True. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | Implementiert [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | Fußzeilen beim Konvertieren von Tabellenkalkulationsdokumenten überspringen. Standard: false. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | Kopfzeilen beim Konvertieren von Tabellenkalkulationsdokumenten überspringen. Standard: false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | Implementiert [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Klont die aktuelle Instanz. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hashfunktion. |

### Siehe auch

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
