---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar kalkylbladsdokument."
type: docs
weight: 25
url: /sv/nodejs-java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

Definierar kalkylbladsdokument. Inkluderar följande filtyper: [Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Csv), [Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Fods), [Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Ods), [Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Ots), [Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Tsv), [Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlam), [Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xls), [Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlsb), [Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlsm), [Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlsx), [Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlt), [Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xltm), [Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xltx). Läs mer om kalkylbladsformat [här][].


[here]: https://wiki.fileformat.com/spreadsheet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SpreadsheetFileType()](#SpreadsheetFileType--) | Serialiseringskonstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Xls](#Xls) | XLS representerar Excel Binary File Format. |
| [Xlsx](#Xlsx) | XLSX är ett välkänt format för Microsoft Excel-dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. |
| [Xlsm](#Xlsm) | XLSM är en typ av kalkylbladsfiler som stödjer makron. |
| [Xlsb](#Xlsb) | XLSB-filformatet specificerar Excel Binary File Format, som är en samling av poster och strukturer som specificerar innehållet i en Excel-arbetsbok. |
| [Ods](#Ods) | Filer med ODS‑tillägg står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. |
| [Ots](#Ots) | En fil med .ots‑tillägg är en OpenDocument Spreadsheet Template‑fil som skapas med Calc‑programvaran som ingår i Apache OpenOffice. |
| [Xltx](#Xltx) | XLTX-filen representerar Microsoft Excel Template som är baserad på specifikationerna för Office OpenXML‑filformatet. |
| [Xlt](#Xlt) | Filer med .XLT‑tillägg är mallfiler som skapats med Microsoft Excel, vilket är ett kalkylprogram som ingår i Microsoft Office‑sviten. |
| [Xltm](#Xltm) | XLTM-filändelsen representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. |
| [Tsv](#Tsv) | Ett Tab-separerat värde (TSV)-filformat representerar data som är separerad med tabbar i vanligt textformat. |
| [Xlam](#Xlam) | XLAM är en makroaktiverad tilläggsfil som används för att lägga till nya funktioner i kalkylblad. |
| [Csv](#Csv) | Filer med CSV (Comma Separated Values)-ändelse representerar vanliga textfiler som innehåller dataposter med kommaseparerade värden. |
| [Fods](#Fods) | En fil med .fods-ändelse är en typ av OpenDocument Spreadsheet-dokumentformat som lagrar data i rader och kolumner. |
| [Dif](#Dif) | DIF står för Data Interchange Format som används för att importera/exportera kalkylbladsdata mellan olika program. |
| [Sxc](#Sxc) | Filformatet SXC (Sun XML Calc) tillhör en kontorssvit som heter OpenOffice.org. |
| [Numbers](#Numbers) | Filerna med .numbers-ändelse klassificeras som kalkylbladsfiltyp, det är därför de liknar .xlsx-filerna; men Numbers-filerna skapas med Apples iWork Numbers-kalkylbladsprogram. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


Serialiseringskonstruktor

### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX är ett välkänt format för Microsoft Excel-dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM är en typ av kalkylbladsfiler som stödjer makron. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


XLSB-filformatet specificerar Excel Binary File Format, vilket är en samling av poster och strukturer som specificerar innehållet i en Excel-arbetsbok. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


Filer med ODS-ändelse står för OpenDocument Spreadsheet Document-format som är redigerbart av användaren. Data lagras i ODF-filen i rader och kolumner. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


En fil med .ots-ändelse är en OpenDocument Spreadsheet Template-fil som skapas med Calc-programvaran som ingår i Apache OpenOffice. Calc-programvaran är liknande Excel som finns i Microsoft Office. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


XLTX-filen representerar Microsoft Excel-mall som är baserad på Office OpenXML-filformatspecifikationerna. Den används för att skapa en standardmallfil som kan användas för att generera XLSX-filer som har samma inställningar som specificeras i XLTX-filen. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


Filer med .XLT-ändelse är mallfiler skapade med Microsoft Excel, som är ett kalkylprogram som ingår i Microsoft Office-sviten. Microsoft Office 97-2003 stödde att skapa nya XLT-filer samt att öppna dem. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


XLTM-filändelsen representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. XLTM-filer är liknande XLTX i struktur förutom att den senare inte stödjer att skapa mallfiler med makron. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Ett Tab-separerat värde (TSV)-filformat representerar data som är separerad med tabbar i vanligt textformat. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM är en makroaktiverad tilläggsfil som används för att lägga till nya funktioner i kalkylblad. Ett tillägg är ett kompletterande program som kör extra kod och ger ytterligare funktionalitet för kalkylblad. Läs mer om detta filformat [here][]


[here]: https://docs.fileformat.com/spreadsheet/xlam/

### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


Filer med CSV (Comma Separated Values)-ändelse representerar rena textfiler som innehåller dataposter med kommaseparerade värden. Läs mer om detta filformat [here][]


[here]: https://wiki.fileformat.com/spreadsheet/csv

### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


En fil med .fods‑ändelse är en typ av OpenDocument Spreadsheet-dokumentformat som lagrar data i rader och kolumner. Formatet specificeras som en del av ODF 1.2‑specifikationerna som publiceras och underhålls av OASIS. Läs mer om detta filformat [here][]


[here]: https://wiki.fileformat.com/spreadsheet/fods

### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF står för Data Interchange Format och används för att importera/exportera kalkylbladsdata mellan olika program. Dessa inkluderar Microsoft Excel, OpenOffice Calc, StarCalc och många andra. Läs mer om detta filformat [here][]


[here]: https://wiki.fileformat.com/spreadsheet/dif

### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


Filformatet SXC (Sun XML Calc) tillhör kontorssviten som heter OpenOffice.org. Detta format hanterar generellt användarnas kalkylbladsbehov eftersom det är ett XML‑baserat kalkylbladsfilformat. SXC‑formatet stöder formler, funktioner, makron och diagram samt DataPilot. Läs mer om detta filformat [here][]


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


Filer med .numbers‑ändelse klassificeras som kalkylbladsfiltyp, vilket är varför de liknar .xlsx‑filer; men Numbers‑filer skapas med Apples iWork Numbers‑kalkylbladsprogram. Läs mer om detta filformat [here][]


[here]: https://docs.fileformat.com/spreadsheet/numbers

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Förberedda standardalternativ för konvertering för filtypen

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
