---
title: WordProcessingFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i file di elaborazione testi che contengono informazioni utente in formato testo normale o RTF. Un formato di file di testo semplice contiene testo non formattato e non è possibile applicare impostazioni di carattere o pagina ecc. Al contrario un formato di file di testo ricco consente opzioni di formattazione come limpostazione del tipo di carattere gli stili grassetto corsivo sottolineato ecc. i margini della pagina i titoli i punti elenco e i numeri e molte altre funzionalità di formattazione. Include i seguenti tipi di file Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log . Ulteriori informazioni sui formati di elaborazione testiQuihttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 1090
url: /it/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Definisce i file di elaborazione testi che contengono informazioni utente in formato testo normale o RTF. Un formato di file di testo semplice contiene testo non formattato e non è possibile applicare impostazioni di carattere o pagina ecc. Al contrario, un formato di file di testo ricco consente opzioni di formattazione come l'impostazione del tipo di carattere, gli stili (grassetto, corsivo, sottolineato, ecc.), i margini della pagina, i titoli, i punti elenco e i numeri e molte altre funzionalità di formattazione. Include i seguenti tipi di file: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , Mobi , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . Log . Ulteriori informazioni sui formati di elaborazione testi[Qui](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Costruttore di serializzazione |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determina se due istanze di oggetto sono uguali. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funge da funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione di stringa |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | I file con estensione .doc rappresentano documenti generati da Microsoft Word o altri documenti di elaborazione testi in formato di file binario. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | I file DOCM sono documenti generati da Microsoft Word 2007 o versioni successive con la possibilità di eseguire macro. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX è un formato ben noto per i documenti di Microsoft Word. Introdotto a partire dal 2007 con il rilascio di Microsoft Office 2007, la struttura di questo nuovo formato di documento è stata modificata da semplice binario a una combinazione di XML e file binari. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | I file con estensione .DOT sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Un file con estensione DOTM rappresenta un file modello creato con Microsoft Word 2007 o versioni successive. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | I file con estensione DOTX sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | I file di testo creati con i dialetti della lingua Markdown vengono salvati con estensione file .MD o .MARKDOWN. I file MD vengono salvati in un formato di testo normale che utilizza il linguaggio Markdown che include anche simboli di testo in linea, definendo come un testo può essere formattato come rientri, formattazione della tabella, caratteri e intestazioni. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | I file ODT sono tipi di documenti creati con applicazioni di elaborazione testi basate sul formato OpenDocument Text File. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | I file con estensione OTT rappresentano documenti modello generati da applicazioni conformi al formato standard OpenDocument di OASIS. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Introdotto e documentato da Microsoft, il Rich Text Format (RTF) rappresenta un metodo di codifica di testo e grafica formattati per l'utilizzo all'interno delle applicazioni. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Un file con estensione .TXT rappresenta un documento di testo che contiene testo semplice sotto forma di righe. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/word-processing/txt) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
