---
title: "Classe SpreadsheetFileType"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Definisce i documenti di foglio di calcolo."
type: docs
url: /it/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/
is_root: false
weight: 190
---


## SpreadsheetFileType class

Definisce i documenti di foglio di calcolo.

Include i seguenti tipi di file:
- [`SpreadsheetFileType.csv`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/csv/)
- [`SpreadsheetFileType.fods`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/fods/)
- [`SpreadsheetFileType.ods`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/ods/)
- [`SpreadsheetFileType.ots`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/ots/)
- [`SpreadsheetFileType.tsv`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/tsv/)
- [`SpreadsheetFileType.xlam`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlam/)
- [`SpreadsheetFileType.xls`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xls/)
- [`SpreadsheetFileType.xlsb`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb/)
- [`SpreadsheetFileType.xlsm`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm/)
- [`SpreadsheetFileType.xlsx`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx/)
- [`SpreadsheetFileType.xlt`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlt/)
- [`SpreadsheetFileType.xltm`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xltm/)
- [`SpreadsheetFileType.xltx`](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xltx/)

Scopri di più sui formati di fogli di calcolo su https://wiki.fileformat.com/spreadsheet.

Il tipo SpreadsheetFileType espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/__init__/) | Inizializza un SpreadsheetFileType per la serializzazione. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Confronta l'oggetto corrente con un altro. (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementa il confronto di uguaglianza definito da [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (ereditato da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Ottiene il FileType per l'estensione di file fornita. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Restituisce il FileType per il file_name specificato. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Restituisce il FileType per lo stream di documento fornito. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Fornisce la funzione hash predefinita. (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Rappresentazione stringa del tipo di file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | La descrizione del tipo di file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | L'estensione del file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | La famiglia del file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Il formato del file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [XLS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xls/) | XLS rappresenta il formato Excel Binary File Format. Tali file possono essere creati da Microsoft Excel così come da altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Scopri di più su questo formato di file qui. |
| [XLSX](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx/) | XLSX è un formato noto per i documenti Microsoft Excel introdotto da Microsoft con il rilascio di Microsoft Office 2007. Scopri di più su questo formato di file qui. |
| [XLSM](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm/) | XLSM è un tipo di file di foglio di calcolo che supporta le macro. Scopri di più su questo formato di file qui. |
| [XLSB](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb/) | Il formato file XLSB specifica l'Excel Binary File Format, che è una raccolta di record e strutture che definiscono il contenuto della cartella di lavoro Excel. Scopri di più su questo formato di file qui. |
| [ODS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/ods/) | I file con estensione ODS corrispondono al formato OpenDocument Spreadsheet Document, modificabile dall'utente. I dati sono memorizzati all'interno del file ODF in righe e colonne. Scopri di più su questo formato di file qui. |
| [OTS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/ots/) | Un file con estensione .ots è un file modello OpenDocument Spreadsheet creato con il software Calc incluso in Apache OpenOffice. Il software Calc è simile a Excel disponibile in Microsoft Office. Scopri di più su questo formato di file qui. |
| [XLTX](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xltx/) | Il file XLTX rappresenta un modello di Microsoft Excel basato sulle specifiche del formato file Office OpenXML. Viene utilizzato per creare un file modello standard che può essere impiegato per generare file XLSX che presentano le stesse impostazioni specificate nel file XLTX. Scopri di più su questo formato di file qui. |
| [XLT](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlt/) | I file con estensione .XLT sono file modello creati con Microsoft Excel, che è un'applicazione di foglio di calcolo inclusa nella suite Microsoft Office. Microsoft Office 97-2003 supportava la creazione di nuovi file XLT così come l'apertura di questi. Scopri di più su questo formato di file qui. |
| [XLTM](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xltm/) | L'estensione di file XLTM rappresenta file generati da Microsoft Excel come modelli abilitati alle macro. I file XLTM sono simili a XLTX nella struttura, tranne per il fatto che quest'ultimo non supporta la creazione di modelli con macro. Scopri di più su questo formato di file qui. |
| [TSV](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/tsv/) | Un formato di file Tab-Separated Values (TSV) rappresenta dati separati da tabulazioni in formato di testo semplice. Scopri di più su questo formato di file qui. |
| [XLAM](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/xlam/) | XLAM è un file Macro-Enabled Add-In utilizzato per aggiungere nuove funzioni ai fogli di calcolo. Un Add-In è un programma supplementare che esegue codice aggiuntivo e fornisce funzionalità aggiuntive per i fogli di calcolo. Scopri di più su questo formato di file qui. |
| [CSV](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/csv/) | I file con estensione CSV (Comma Separated Values) rappresentano file di testo semplice che contengono record di dati con valori separati da virgola. Scopri di più su questo formato di file qui. |
| [FODS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/fods/) | Un file con estensione .fods è un tipo di formato documento OpenDocument Spreadsheet che memorizza i dati in righe e colonne. Il formato è specificato come parte delle specifiche ODF 1.2 pubblicate e mantenute da OASIS. Scopri di più su questo formato di file qui. |
| [DIF](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/dif/) | DIF sta per Data Interchange Format ed è usato per importare/esportare dati di fogli di calcolo tra diverse applicazioni. Queste includono Microsoft Excel, OpenOffice Calc, StarCalc e molte altre. Scopri di più su questo formato di file qui. |
| [SXC](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/sxc/) | Il formato di file SXC (Sun XML Calc) appartiene a una suite office chiamata OpenOffice.org. Questo formato soddisfa generalmente le esigenze di foglio di calcolo degli utenti poiché è un formato di file di foglio di calcolo basato su XML. Il formato SXC supporta formule, funzioni, macro e grafici insieme a DataPilot. Scopri di più su questo formato di file qui. |
| [NUMBERS](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/numbers/) | I file con estensione .numbers sono classificati come tipo di file foglio di calcolo, perciò sono simili ai file .xlsx; ma i file Numbers sono creati utilizzando il software di foglio di calcolo Apple iWork Numbers. Scopri di più su questo formato di file qui. |
| [FLAT_OPC](/conversion/python-net/groupdocs.conversion.filetypes/spreadsheetfiletype/flat_opc/) | Flat OPC Excel è Office Open XML SpreadsheetML memorizzato in un file XML piatto invece di un pacchetto ZIP. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo di file sconosciuto (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Vedi anche
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
