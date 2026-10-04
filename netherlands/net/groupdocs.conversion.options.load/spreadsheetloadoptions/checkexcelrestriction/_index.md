---
title: "CheckExcelRestriction"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Of de beperkingen van een Excel‑bestand moeten worden gecontroleerd wanneer de gebruiker cellen of gerelateerde objecten wijzigt. Bijvoorbeeld, Excel staat niet toe dat een tekenreeks langer dan 32 KB wordt ingevoerd. Wanneer u een waarde langer dan 32 KB invoert en deze eigenschap is true, krijgt u een Exception. Als deze eigenschap false is, accepteren we uw ingevoerde tekenreeks als de celwaarde, zodat u later de volledige tekenreeks kunt exporteren naar andere bestandsformaten zoals CSV. Als u echter een waarde hebt ingesteld die ongeldig is voor het Excel‑bestandsformaat, mag u het werkboek later niet opslaan als Excel‑bestand. Anders kan er een onverwachte fout optreden in het gegenereerde Excel‑bestand."
type: docs
weight: 40
url: /nl/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

Of de beperkingen van een Excel‑bestand worden gecontroleerd wanneer de gebruiker gerelateerde objecten van cellen wijzigt. Bijvoorbeeld, Excel staat niet toe dat een tekenreeks langer dan 32 KB wordt ingevoerd. Wanneer u een waarde langer dan 32 KB invoert, krijgt u een Exception als deze eigenschap waar is. Als deze eigenschap onwaar is, accepteren we uw ingevoerde tekenreeks als de celwaarde, zodat u later de volledige tekenreeks kunt exporteren naar andere bestandsformaten zoals CSV. Als u echter een waarde instelt die ongeldig is voor het Excel‑formaat, moet u het werkboek later niet opslaan als Excel‑bestand. Anders kan er een onverwachte fout optreden in het gegenereerde Excel‑bestand.

```csharp
public bool CheckExcelRestriction { get; set; }
```

### Zie ook

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
