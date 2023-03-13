---
title: FontFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i documenti Font Include i seguenti tipi Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Ulteriori informazioni sui formati dei caratteriQuihttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /it/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Definisce i documenti Font Include i seguenti tipi: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Ulteriori informazioni sui formati dei caratteri[Qui](https://docs.fileformat.com/font/) .

```csharp
public sealed class FontFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FontFileType](fontfiletype)() | Costruttore di serializzazione |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Un file con estensione .cff è un formato di font compatto ed è anche noto come PostScript Type 1 o CIDFont. CFF funge da contenitore per memorizzare più caratteri insieme in una singola unità nota come FontSet. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Un file con estensione .eot è un font OpenType incorporato in un documento. Questi sono utilizzati principalmente in file Web come una pagina Web. È stato creato da Microsoft ed è supportato dai prodotti Microsoft, incluso il file .pps di presentazione PowerPoint. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Un file con estensione .otf fa riferimento al formato di carattere OpenType. Il formato dei caratteri OTF è più scalabile ed estende le funzionalità esistenti dei formati TTF per la tipografia digitale. Sviluppato da Microsoft e Adobe, OTF combina le caratteristiche dei formati di font PostScript e TrueType. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Un file con estensione .ttf rappresenta file di font basati sulla tecnologia dei font delle specifiche TrueType. È stato inizialmente progettato e lanciato da Apple Computer, Inc per Mac OS ed è stato successivamente adottato da Microsoft per Windows OS. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | I caratteri di tipo 1 sono una tecnologia Adobe obsoleta che era ampiamente utilizzata nel software di pubblicazione basato su desktop e nelle stampanti che potevano utilizzare PostScript. Sebbene i caratteri di tipo 1 non siano supportati in molte piattaforme moderne, browser Web e sistemi operativi mobili, sono ancora supportati in alcuni dei sistemi operativi. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Un file con estensione .woff è un file di font Web basato sul Web Open Font Format (WOFF). Ha un contenitore compresso specifico per il formato basato sui tipi di carattere TrueType (.TTF) o OpenType (.OTT). Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Un file con estensione .woff è un file di font Web basato sul Web Open Font Format (WOFF). Ha un contenitore compresso specifico per il formato basato sui tipi di carattere TrueType (.TTF) o OpenType (.OTT). Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/font/woff/) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
