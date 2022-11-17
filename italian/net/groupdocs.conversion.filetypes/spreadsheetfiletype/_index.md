---
title: SpreadsheetFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i documenti del foglio di calcolo. Include i seguenti tipi di file Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . Ulteriori informazioni sui formati dei fogli di lavoroquihttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 930
url: /it/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Definisce i documenti del foglio di calcolo. Include i seguenti tipi di file: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Ulteriori informazioni sui formati dei fogli di lavoro[qui](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Costruttore di serializzazione |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia di file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina se due istanze di oggetto sono uguali. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Serve come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione di stringa |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | I file con estensione CSV (Comma Separated Values) rappresentano file di testo semplice che contengono record di dati con valori separati da virgola. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF è l'acronimo di Data Interchange Format che viene utilizzato per importare/esportare i dati dei fogli di calcolo tra diverse applicazioni. Questi includono Microsoft Excel, OpenOffice Calc, StarCalc e molti altri. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Foglio di calcolo OpenDocument Flat XML |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | I file con estensione .numbers sono classificati come file di tipo foglio di calcolo, ecco perché sono simili ai file .xlsx; ma i file di Numbers vengono creati utilizzando il software per fogli di calcolo Apple iWork Numbers. Ulteriori informazioni su questo formato di file[qui](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | I file con estensione ODS rappresentano il formato del documento OpenDocument Spreadsheet che è modificabile dall'utente. I dati vengono archiviati all'interno del file ODF in righe e colonne. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Modello foglio di calcolo OpenDocument |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Un formato basato su XML utilizzato da OpenOffice e StarOffice |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Un formato di file con valori separati da tabulazioni (TSV) rappresenta i dati separati da tabulazioni in formato testo normale. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | Formato documento Xlam |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS rappresenta il formato file binario di Excel. Tali file possono essere creati da Microsoft Excel e da altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | Il formato file XLSB specifica il formato file binario di Excel, che è una raccolta di record e strutture che specificano il contenuto della cartella di lavoro di Excel. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM è un tipo di file di foglio elettronico che supporta le macro. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX è un formato noto per i documenti Microsoft Excel introdotto da Microsoft con il rilascio di Microsoft Office 2007. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | I file con estensione .XLT sono file modello creati con Microsoft Excel, un'applicazione per fogli di calcolo che fa parte della suite Microsoft Office. Microsoft Office 97-2003 supportava la creazione di nuovi file XLT e l'apertura di questi. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | L'estensione file XLTM rappresenta i file generati da Microsoft Excel come file modello con attivazione macro. I file XLTM sono simili a XLTX nella struttura diversa da quella successiva non supporta la creazione di file modello con macro. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | Il file XLTX rappresenta il modello Microsoft Excel basato sulle specifiche del formato file Office OpenXML. Viene utilizzato per creare un file modello standard che può essere utilizzato per generare file XLSX che presentano le stesse impostazioni specificate nel file XLTX. Ulteriori informazioni su questo formato file[qui](https://wiki.fileformat.com/spreadsheet/xltx) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
