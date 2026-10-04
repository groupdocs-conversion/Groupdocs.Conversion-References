---
title: "PageSizeOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Metodi"
type: docs
weight: 2990
url: /it/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

Metodi

```csharp
public sealed class PageSizeOptions : ValueObject
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | Costruttore predefinito. Inizializza [`PageSize`](./pagesize) a [`Unset`](../pagesize/unset). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | Altezza pagina in punti da applicare prima della conversione. Quando impostato, [`PageSize`](./pagesize) viene automaticamente modificato in [`Custom`](../pagesize/custom). |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | Implementa [`PageSize`](../pagesize) |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | Larghezza della pagina in punti da applicare prima della conversione. Quando impostata, [`PageSize`](./pagesize) viene automaticamente cambiata in [`Custom`](../pagesize/custom). |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
