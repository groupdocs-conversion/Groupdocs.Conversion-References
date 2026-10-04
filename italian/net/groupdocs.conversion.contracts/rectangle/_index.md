---
title: "Rettangolo"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Rappresenta un rettangolo definito dai suoi bordi per scopi di ritaglio."
type: docs
weight: 580
url: /it/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

Rappresenta un rettangolo definito dai suoi bordi per scopi di ritaglio.

```csharp
public sealed class Rectangle : ValueObject
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | Inizializza una nuova istanza della struct [`Rectangle`](../rectangle) con i bordi specificati. |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | Ottiene il bordo inferiore del rettangolo. |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | Ottiene l'altezza del rettangolo basata sui bordi superiore e inferiore. |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | Ottiene il bordo sinistro del rettangolo. |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | Ottiene il bordo destro del rettangolo. |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | Ottiene il bordo superiore del rettangolo. |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | Ottiene la larghezza del rettangolo basata sui bordi sinistro e destro. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | Crea una versione ritagliata del rettangolo corrente rimuovendo i margini specificati. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | Restituisce una rappresentazione stringa del rettangolo. |

### IConversionConvertOptions

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
