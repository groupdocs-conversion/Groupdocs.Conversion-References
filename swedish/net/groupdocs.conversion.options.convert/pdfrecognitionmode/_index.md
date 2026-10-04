---
title: "PdfRecognitionMode"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Gör det möjligt att styra hur ett PDF-dokument konverteras till ett ordbehandlingsdokument."
type: docs
weight: 2160
url: /sv/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

Gör det möjligt att styra hur ett PDF-dokument konverteras till ett ordbehandlingsdokument.

```csharp
public sealed class PdfRecognitionMode : Enumeration
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | Fullständigt igenkänningsläge, motorn utför gruppering och flernivåanalys för att återställa författarens avsikt i det ursprungliga dokumentet och skapa ett maximalt redigerbart dokument. Nackdelen är att utdata‑dokumentet kan se annorlunda ut än den ursprungliga PDF‑filen. |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | Detta läge är snabbt och bra för att maximalt bevara det ursprungliga utseendet på PDF‑filen, men redigerbarheten i det resulterande dokumentet kan vara begränsad. Varje visuellt grupperat textblock i den ursprungliga PDF‑filen konverteras till en textruta i det resulterande dokumentet. Detta uppnår maximal likhet mellan utdata‑dokumentet och den ursprungliga PDF‑filen. Utdata‑dokumentet kommer att se bra ut, men det kommer helt och hållet bestå av textrutor och det kan göra vidare redigering av dokumentet i Microsoft Word ganska svårt. Detta är standardläget. |

### Se även

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
