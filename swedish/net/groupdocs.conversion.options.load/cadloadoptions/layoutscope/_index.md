---
title: "LayoutScope"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Hämtar eller anger vilka ritningsutrymmen som konverteras. Standard är Bothgroupdocs.conversion.options.load/cadlayoutscope/both som inte begränsar konverteringen. Den ignoreras när LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames tillhandahålls eftersom explicita layoutnamn alltid har företräde. Ett null-värde behandlas som Bothgroupdocs.conversion.options.load/cadlayoutscope/both."
type: docs
weight: 80
url: /sv/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

Hämtar eller anger vilka ritningsutrymmen som konverteras. Standard är [`Both`](../../cadlayoutscope/both), vilket inte begränsar konverteringen. Den ignoreras när [`LayoutNames`](../layoutnames) tillhandahålls, eftersom explicita layoutnamn alltid har företräde. Ett `null`-värde behandlas som [`Both`](../../cadlayoutscope/both).

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### Anmärkningar

Ett omfång som inte väljer någon av de blad som en ritning erbjuder får konverteringen att misslyckas med ett [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) som namnger omfånget och de blad som finns, snarare än att rendera de utrymmen som omfånget uteslöt. En ritning som inte erbjuder något blad alls påverkas inte och konverteras fortfarande som en enhet. Respekteras inte vid konvertering till PDF/UA-1, av den anledning som anges på [`LayoutNames`](../layoutnames).

### Se även

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
