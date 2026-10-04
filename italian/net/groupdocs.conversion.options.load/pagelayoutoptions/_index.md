---
title: "PageLayoutOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Descrive le modalità di layout della pagina durante il caricamento di documenti web."
type: docs
weight: 2720
url: /it/net/groupdocs.conversion.options.load/pagelayoutoptions/
---
## PageLayoutOptions class

Descrive le modalità di layout della pagina durante il caricamento di documenti web.

```csharp
public class PageLayoutOptions : FlagsEnumeration
```

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina se due istanze di oggetti sono uguali. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funziona come funzione hash predefinita. |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | Verifica se il flag corrente contiene il flag specificato. |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | Verifica se il flag corrente contiene il valore specificato. |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | Converte l'oggetto corrente in una stringa. |
| [operator &#x7C;](../../groupdocs.conversion.options.load/pagelayoutoptions/op_bitwiseor) | Combina due flag [`PageLayoutOptions`](../pagelayoutoptions) usando l'OR bitwise. |

## Campi

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static readonly [None](../../groupdocs.conversion.options.load/pagelayoutoptions/none) | Valore predefinito |
| static readonly [ScaleToPageHeight](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopageheight) | Questo flag indica che il contenuto del documento sarà scalato per adattarsi all'altezza della prima pagina. Tutto il contenuto del documento sarà posizionato su un'unica pagina. |
| static readonly [ScaleToPageWidth](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopagewidth) | Indica che il contenuto del documento sarà scalato per adattarsi alla pagina in cui la differenza tra la larghezza disponibile della pagina e il contenuto sovrapposto è massima. |

### IConversionConvertOptions

* class [FlagsEnumeration](../../groupdocs.conversion.contracts/flagsenumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
