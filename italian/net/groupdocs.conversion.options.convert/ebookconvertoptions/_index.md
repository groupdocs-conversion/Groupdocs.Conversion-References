---
title: EBookConvertOptions
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Opzioni per la conversione nel tipo di file EBook.
type: docs
weight: 1500
url: /it/net/groupdocs.conversion.options.convert/ebookconvertoptions/
---
## EBookConvertOptions class

Opzioni per la conversione nel tipo di file EBook.

```csharp
public class EBookConvertOptions : CommonConvertOptions<EBookFileType>, 
    IPageOrientationConvertOptions, IPageSizeConvertOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EBookConvertOptions](ebookconvertoptions)() | Inizializza una nuova istanza di[`EBookConvertOptions`](../ebookconvertoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Il tipo di file desiderato in cui deve essere convertito il documento di input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Il tipo di file desiderato in cui deve essere convertito il documento di input. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Il numero di pagina da cui iniziare la conversione. |
| [PageOrientation](../../groupdocs.conversion.options.convert/ebookconvertoptions/pageorientation) { get; set; } | Orientamento della pagina desiderato dopo la conversione |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | L'elenco degli indici delle pagine da convertire. Dovrebbe essere specificato per convertire pagine specifiche. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Numero di pagine da convertire a partire da`Numero di pagina` . |
| [PageSize](../../groupdocs.conversion.options.convert/ebookconvertoptions/pagesize) { get; set; } | Dimensione pagina desiderata dopo la conversione |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opzioni specifiche filigrana |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona l'istanza delle opzioni correnti. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funge da funzione hash predefinita. |

### Guarda anche

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [EBookFileType](../../groupdocs.conversion.filetypes/ebookfiletype)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* spazio dei nomi [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->