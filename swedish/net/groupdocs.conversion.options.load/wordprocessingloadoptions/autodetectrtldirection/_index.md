---
title: "AutoDetectRtlDirection"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "När true kommer standardparagrafer och körningar vars text domineras av höger‑till‑vänster att få sina bidi‑flaggor reparerade före konvertering. Detta matchar den heuristik som Microsoft Word och LibreOffice använder och åtgärdar rendering av arabiska/hebreiska dokument som genereras, särskilt av Google Docs, som avger OOXML utan ltwbidi/gt och med ltwrtl wval0/gt på körningar som endast innehåller RTL‑skript. Sätt till false för att bevara en strikt OOXML‑tolkning av källmarkupen."
type: docs
weight: 20
url: /sv/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

När true (standard) repareras bidi-flaggor för stycken och körningar vars text huvudsakligen är från höger till vänster innan konvertering. Detta motsvarar den heuristik som Microsoft Word och LibreOffice använder och åtgärdar rendering av arabiska/hebreiska dokument som genereras av verktyg (särskilt Google Docs) som skapar OOXML utan &lt;w:bidi/&gt; och med &lt;w:rtl w:val="0"/&gt; på körningar som endast innehåller RTL-skript. Ställ in på false för att bevara strikt OOXML‑tolkning av källmarkupen.

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### Se även

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
