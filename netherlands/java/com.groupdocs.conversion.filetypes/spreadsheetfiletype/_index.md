---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert spreadsheet‑documenten."
type: docs
weight: 25
url: /nl/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

Definieert Spreadsheet-documenten. Bevat de volgende bestandstypen:
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
Meer informatie over Spreadsheet-formaten [hier](../https://wiki.fileformat.com/spreadsheet).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | Serialisatieconstructor |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Xls](#Xls) | XLS staat voor het Excel Binary File Format. |
|
|  | [Xlsx](#Xlsx) | XLSX is een bekend formaat voor Microsoft Excel-documenten dat door Microsoft werd geïntroduceerd met de uitgave van Microsoft Office 2007. |
|
|  | [Xlsm](#Xlsm) | XLSM is een type spreadsheetbestanden dat macro's ondersteunt. |
|
|  | [Xlsb](#Xlsb) | XLSB-bestandsformaat specificeert het Excel Binary File Format, een verzameling records en structuren die de inhoud van een Excel-werkmap definiëren. |
|
|  | [Ods](#Ods) | Bestanden met de ODS-extensie staan voor het OpenDocument Spreadsheet Document-formaat dat door de gebruiker bewerkbaar is. |
|
|  | [Ots](#Ots) | Een bestand met de .ots-extensie is een OpenDocument Spreadsheet-sjabloonbestand dat wordt gemaakt met de Calc-toepassing die is inbegrepen in Apache OpenOffice. |
|
|  | [Xltx](#Xltx) | XLTX-bestand vertegenwoordigt een Microsoft Excel-sjabloon dat gebaseerd is op de Office OpenXML-bestandsformaat-specificaties. |
|
|  | [Xlt](#Xlt) | Bestanden met de .XLT-extensie zijn sjabloonbestanden die zijn gemaakt met Microsoft Excel, een spreadsheettoepassing die deel uitmaakt van de Microsoft Office-suite. |
|
|  | [Xltm](#Xltm) | De XLTM-bestandsextensie vertegenwoordigt bestanden die door Microsoft Excel worden gegenereerd als macro-ondersteunde sjabloonbestanden. |
|
|  | [Tsv](#Tsv) | Een Tab-Separated Values (TSV)-bestandformaat vertegenwoordigt gegevens die met tabs gescheiden zijn in een platte-tekstformaat. |
|
|  | [Xlam](#Xlam) | XLAM is een macro-ondersteund add-in-bestand dat wordt gebruikt om nieuwe functies aan spreadsheets toe te voegen. |
|
|  | [Csv](#Csv) | Bestanden met de CSV (Comma Separated Values)-extensie vertegenwoordigen platte-tekstbestanden die gegevensrecords bevatten met door komma's gescheiden waarden. |
|
|  | [Fods](#Fods) | Een bestand met de .fods-extensie is een type OpenDocument Spreadsheet-documentformaat dat gegevens opslaat in rijen en kolommen. |
|
|  | [Dif](#Dif) | DIF staat voor Data Interchange Format, dat wordt gebruikt om spreadsheetgegevens tussen verschillende toepassingen te importeren/exporteren. |
|
|  | [Sxc](#Sxc) | Het bestandsformaat SXC (Sun XML Calc) behoort tot een kantoorsuite genaamd OpenOffice.org. |
|
|  | [Numbers](#Numbers) | De bestanden met .numbers extensie worden geclassificeerd als spreadsheet‑bestandstype, dat\u2019s waarom ze vergelijkbaar zijn met de .xlsx‑bestanden; maar de Numbers‑bestanden worden gemaakt met Apple iWork Numbers‑spreadsheetsoftware. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


Serialisatieconstructor


### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS staat voor Excel Binary File Format. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel evenals andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/xls).


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX is een bekend formaat voor Microsoft Excel-documenten dat door Microsoft werd geïntroduceerd met de uitgave van Microsoft Office 2007.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/xlsx).


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM is een type spreadsheetbestanden dat macro's ondersteunt.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/xlsm).


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


XLSB-bestandsformaat specificeert het Excel Binary File Format, een verzameling records en structuren die de inhoud van een Excel-werkmap definiëren.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/xlsb).


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


Bestanden met de ODS‑extensie staan voor het OpenDocument Spreadsheet‑documentformaat dat door de gebruiker bewerkbaar is. Gegevens worden opgeslagen in het ODF‑bestand in rijen en kolommen.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/ods).


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


Een bestand met de .ots‑extensie is een OpenDocument Spreadsheet‑sjabloonbestand dat wordt gemaakt met de Calc‑toepassingssoftware die is inbegrepen in Apache OpenOffice. De Calc‑toepassingssoftware is vergelijkbaar met Excel die beschikbaar is in Microsoft Office.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/ots).


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


Het XLTX‑bestand vertegenwoordigt een Microsoft Excel‑sjabloon dat gebaseerd is op de Office OpenXML‑bestandsformaatspecificaties. Het wordt gebruikt om een standaard‑sjabloonbestand te maken dat kan worden gebruikt om XLSX‑bestanden te genereren die dezelfde instellingen vertonen als gespecificeerd in het XLTX‑bestand.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/xltx).


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


Bestanden met de .XLT‑extensie zijn sjabloonbestanden die zijn gemaakt met Microsoft Excel, een spreadsheet‑applicatie die deel uitmaakt van de Microsoft Office‑suite. Microsoft Office 97-2003 ondersteunde het maken van nieuwe XLT‑bestanden en het openen ervan.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/xlt).


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


De XLTM‑bestandsextensie staat voor bestanden die door Microsoft Excel worden gegenereerd als macro‑ingeschakelde sjabloonbestanden. XLTM‑bestanden lijken op XLTX in structuur, behalve dat de laatste geen sjabloonbestanden met macro's ondersteunt.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/xltm).


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Een Tab-Separated Values (TSV)-bestandformaat vertegenwoordigt gegevens die met tabs gescheiden zijn in een platte-tekstformaat.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/tsv).


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM is een macro‑ingeschakeld add‑in‑bestand dat wordt gebruikt om nieuwe functies aan spreadsheets toe te voegen. Een add‑in is een aanvullend programma dat extra code uitvoert en extra functionaliteit biedt voor spreadsheets.
Meer informatie over dit bestandsformaat [hier](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


Bestanden met de CSV (Comma Separated Values)-extensie vertegenwoordigen platte-tekstbestanden die gegevensrecords bevatten met door komma's gescheiden waarden.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/csv).


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


Een bestand met de .fods‑extensie is een type OpenDocument Spreadsheet‑documentformaat dat gegevens opslaat in rijen en kolommen. Het formaat is gespecificeerd als onderdeel van de ODF 1.2‑specificaties die zijn gepubliceerd en onderhouden door OASIS. Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/fods).


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF staat voor Data Interchange Format dat wordt gebruikt om spreadsheet‑gegevens te importeren/exporteren tussen verschillende toepassingen. Deze omvatten Microsoft Excel, OpenOffice Calc, StarCalc en vele anderen. Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/dif).


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


Het bestandsformaat SXC (Sun XML Calc) behoort tot een kantoorsuite genaamd OpenOffice.org. Dit formaat behandelt over het algemeen de spreadsheet‑behoeften van gebruikers, aangezien het een op XML gebaseerd spreadsheet‑bestandformaat is. Het SXC‑formaat ondersteunt formules, functies, macro's en grafieken, samen met DataPilot. Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/spreadsheet/sxc).


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


De bestanden met de .numbers extensie worden geclassificeerd als spreadsheet‑bestandstype, daarom lijken ze op de .xlsx‑bestanden; maar de Numbers‑bestanden worden gemaakt met Apple iWork Numbers spreadsheet‑software. Meer informatie over dit bestandsformaat [hier](../https://docs.fileformat.com/spreadsheet/numbers).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Voorbereide standaard conversie‑opties voor het bestandstype


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
