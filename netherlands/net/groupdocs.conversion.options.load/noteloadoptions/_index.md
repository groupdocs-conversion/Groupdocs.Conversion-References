---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van One‑documenten."
type: docs
weight: 2680
url: /nl/net/groupdocs.conversion.options.load/noteloadoptions/
---
## NoteLoadOptions class

Opties voor het laden van One‑documenten.

```csharp
public sealed class NoteLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [NoteLoadOptions](noteloadoptions)() | Initialiseert een nieuwe instantie van de [`NoteLoadOptions`](../noteloadoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/noteloadoptions/defaultfont) { get; set; } | Standaardlettertype voor Note-document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/noteloadoptions/fontsubstitutes) { get; set; } | Vervang specifieke lettertypen bij het converteren van een Note-document. |
| [Format](../../groupdocs.conversion.options.load/noteloadoptions/format) { get; } | Invoerdocument bestandstype. Is `null` totdat een formaat is ingesteld, dus test op `null` in plaats van tegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), waaraan het nooit gelijk is. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [Password](../../groupdocs.conversion.options.load/noteloadoptions/password) { get; set; } | Stel wachtwoord in om een beschermd document te ontgrendelen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
