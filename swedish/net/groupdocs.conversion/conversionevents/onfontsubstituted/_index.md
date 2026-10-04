---
title: "OnFontSubstituted"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Avfyras när ett teckensnitt som refereras i källdokumentet inte är tillgängligt och ersätts antingen av en kundtillhandahållen FontSubstitutegroupdocs.conversion.contracts/fontsubstitute‑regel, av det konfigurerade standardteckensnittet eller av konverteringspipeline‑ns interna reserv."
type: docs
weight: 80
url: /sv/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

Avfyras när ett teckensnitt som refereras i källdokumentet inte är tillgängligt och ersätts (antingen av en kundtillhandahållen [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute)-regel, av det konfigurerade standardteckensnittet eller av konverteringspipeline‑ns interna reserv).

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### Anmärkningar

Händelsen dedupliceras per `(SourceFileName, OriginalFontName)` inom ett enda `Converter.Convert(...)`‑anrop — prenumeranter får högst en avisering per saknat teckensnitt per källdokument. Avfyras synkront på konverteringstråden. Aviseras inte för bildkonverteringar.

För presentationsdokument upptäcks teckensnittsersättning endast på Windows, eftersom motorn löser det genom plattforms‑specifik teckensnittsmatchning som inte är tillgänglig på andra operativsystem.

### Se även

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
