---
title: CsvLoadOptions
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Optionen zum Laden von CsvDokumenten.
type: docs
weight: 1860
url: /de/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

Optionen zum Laden von Csv-Dokumenten.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | Initialisiert eine neue Instanz von[`CsvLoadOptions`](../csvloadoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert. Beispielsweise erlaubt Excel keine Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind. Wenn Sie einen Wert eingeben, der länger als 32 KB ist, erhalten Sie eine Ausnahme, wenn diese Eigenschaft wahr ist. Wenn diese Eigenschaft falsch ist, akzeptieren wir Ihren Eingabe-String-Wert als Wert der Zelle, sodass Sie später den vollständigen String-Wert für andere Dateiformate wie CSV ausgeben können. Wenn Sie jedoch einen solchen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist, sollten Sie die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu einem unerwarteten Fehler für die generierte Excel-Datei kommen. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | Gibt an, ob die Zeichenfolge in der Datei in ein Datum konvertiert wird. Standard ist True. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | Gibt an, ob die Zeichenfolge in der Datei in einen numerischen Wert konvertiert wird. Standard ist True. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Konvertieren Sie einen bestimmten Bereich, wenn Sie in ein anderes Format als ein Tabellenkalkulationsformat konvertieren. Beispiel: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Abrufen oder Festlegen der Systemkulturinformationen zum Zeitpunkt des Ladens der Datei |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Standardschriftart für Tabellenkalkulationsdokument. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt. |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | Codierung. Standard ist Encoding.Default. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Bestimmte Schriftarten beim Konvertieren von Tabellendokumenten ersetzen. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Dateityp des Eingabedokuments. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Dateityp des Eingabedokuments. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | Gibt an, ob Text eine Formel ist, wenn er mit "=" beginnt. |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Kommentare ausblenden. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True bedeutet, dass die Datei mehrere Kodierungen enthält. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Wenn OnePagePerSheet wahr ist, wird der Inhalt des Blattes in eine Seite im PDF-Dokument konvertiert. Der Standardwert ist wahr. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Bei True und Konvertierung in PDF wird die Konvertierung für eine bessere Dateigröße als Druckqualität optimiert. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Kennwort festlegen, um den Schutz des geschützten Dokuments aufzuheben. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Trennzeichen einer CSV-Datei. |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Zu konvertierender Blattname |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Gitterlinien beim Konvertieren von Excel-Dateien anzeigen. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Beim Konvertieren von Excel-Dateien ausgeblendete Blätter anzeigen. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Überspringt leere Zeilen und Spalten beim Konvertieren. Standard ist True. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Klont aktuelle Instanz. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hash-Funktion. |

### Siehe auch

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namensraum [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
