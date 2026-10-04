---
title: "WordProcessingFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce file di elaborazione testi che contengono informazioni utente in formato testo semplice o rich text. Un formato di file di testo semplice contiene testo non formattato e non è possibile applicare caratteri o impostazioni di pagina, ecc. Al contrario, un formato di file rich text consente opzioni di formattazione come impostare tipi di carattere, stili, grassetto, corsivo, sottolineato, ecc., margini di pagina, intestazioni, elenchi puntati e numerati e diverse altre funzionalità di formattazione. Include i seguenti tipi di file Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. Scopri di più sui formati di elaborazione testi quihttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /it/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Definisce i file di elaborazione testi che contengono informazioni utente in formato testo semplice o testo formattato. Un formato di file di testo semplice contiene testo non formattato e non è possibile applicare impostazioni di carattere o di pagina, ecc. Al contrario, un formato di file di testo formattato consente opzioni di formattazione come impostare il tipo di carattere, gli stili (grassetto, corsivo, sottolineato, ecc.), i margini della pagina, le intestazioni, i punti elenco e i numeri, e diverse altre funzionalità di formattazione. Include i seguenti tipi di file: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Scopri di più sui formati di elaborazione testi [qui](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Costruttore di serializzazione |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia del file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funziona come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione stringa |

## Campi

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | I file con estensione .doc rappresentano documenti generati da Microsoft Word o altri documenti di elaborazione testi in formato binario. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | I file DOCM sono documenti generati da Microsoft Word 2007 o versioni successive con la capacità di eseguire macro. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX è un formato noto per i documenti Microsoft Word. Introdotto nel 2007 con il rilascio di Microsoft Office 2007, la struttura di questo nuovo formato di documento è stata modificata da binario semplice a una combinazione di file XML e binari. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | I file con estensione .DOT sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Un file con estensione DOTM rappresenta un file modello creato con Microsoft Word 2007 o versioni successive. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | I file con estensione DOTX sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word è Office Open XML WordprocessingML memorizzato in un file XML piatto anziché in un pacchetto ZIP. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | I file di testo creati con dialetti del linguaggio Markdown vengono salvati con estensione .MD o .MARKDOWN. I file MD sono salvati in formato testo semplice che utilizza il linguaggio Markdown, che include anche simboli di testo in linea, definendo come un testo può essere formattato, ad esempio rientri, formattazione di tabelle, caratteri e intestazioni. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | I file ODT sono un tipo di documenti creati con applicazioni di elaborazione testi basate sul formato OpenDocument Text. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | I file con estensione OTT rappresentano documenti modello generati da applicazioni conformi al formato standard OpenDocument di OASIS. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Introdotto e documentato da Microsoft, il Rich Text Format (RTF) rappresenta un metodo di codifica di testo formattato e grafica per l'uso all'interno delle applicazioni. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Un file con estensione .TXT rappresenta un documento di testo che contiene testo semplice sotto forma di righe. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/word-processing/txt). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
