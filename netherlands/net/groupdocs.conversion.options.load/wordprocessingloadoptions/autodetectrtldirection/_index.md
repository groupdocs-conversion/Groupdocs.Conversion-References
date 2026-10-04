---
title: "AutoDetectRtlDirection"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Wanneer true, zullen standaardparagrafen en runs waarvan de tekst overwegend righttoleft is, hun bidi‑vlaggen laten repareren vóór conversie. Dit komt overeen met de heuristiek die Microsoft Word en LibreOffice toepassen en lost de weergave van Arabisch/Hebreeuw‑documenten op die door generators, met name Google Docs, worden geproduceerd en OOXML zonder ltwbidi/gt en met ltwrtl wval0/gt op runs die alleen RTL‑script bevatten, uit. Stel in op false om de strikte OOXML‑interpretatie van de bron‑markup te behouden."
type: docs
weight: 20
url: /nl/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

Wanneer true (standaard), zullen alinea's en runs waarvan de tekst overwegend van rechts naar links is, hun bidi‑vlaggen laten repareren vóór conversie. Dit komt overeen met de heuristiek die Microsoft Word en LibreOffice toepassen en corrigeert de weergave van Arabische/Hebreeuwse documenten die door generators (met name Google Docs) worden geproduceerd en OOXML uitzenden zonder &lt;w:bidi/&gt; en met &lt;w:rtl w:val=\"0\"/&gt; op runs die alleen RTL‑script bevatten. Stel in op false om de strikte OOXML‑interpretatie van de bron‑markup te behouden.

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### Zie ook

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
