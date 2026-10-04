---
title: "FontSubstitutionContext"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Beskriver en enskild teckensnittssubstitution som inträffade vid inläsning eller rendering av ett källdokument. Instanser skickas till OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted."
type: docs
weight: 250
url: /sv/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

Beskriver en enskild teckensnittssubstitution som inträffade vid inläsning eller rendering av ett källdokument. Instanser skickas till [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted).

```csharp
public sealed class FontSubstitutionContext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | Skapar ett nytt [`FontSubstitutionContext`](../fontsubstitutioncontext). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | Namnet på teckensnittet som refereras av källdokumentet men som inte är tillgängligt för konverteringspipeline. |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | Substitutionsmeddelandet exakt som rapporterats av konverteringspipeline, ordagrant och utan tolkning. För dokument som exponerar teckensnittsnamn strukturellt kan detta vara `null` (använd [`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname)); för andra innehåller det den fullständiga människoläsbara beskrivningen, som namnger både det saknade och det ersättande teckensnittet. |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | Filnamnet på källdokumentet som konverteras. När källan tillhandahölls som en ström som inte är en FileStream, innehåller detta en genererad identifierare istället för ett riktigt filnamn. |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | Namnet på teckensnittet som används som ersättning. Kan vara `null` för dokument vars motor rapporterar substitutionen endast som beskrivande text — i så fall läs [`Reason`](./reason). |

### Se även

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
