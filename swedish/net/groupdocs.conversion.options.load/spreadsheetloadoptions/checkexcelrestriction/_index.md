---
title: "CheckExcelRestriction"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Om restriktioner för Excel-filen ska kontrolleras när användaren ändrar cellrelaterade objekt. Till exempel tillåter inte Excel att ange ett strängvärde längre än 32 K. När du anger ett värde längre än 32 K får du ett Exception om den här egenskapen är sann. Om egenskapen är falsk accepterar vi ditt inmatade strängvärde som cellvärde så att du senare kan skriva ut det kompletta strängvärdet för andra filformat såsom CSV. Om du däremot har angett ett värde som är ogiltigt för Excel-filformatet bör du inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå oväntade fel i den genererade Excel-filen."
type: docs
weight: 40
url: /sv/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

Anger om restriktioner för Excel‑filen ska kontrolleras när användaren ändrar cellrelaterade objekt. Till exempel tillåter Excel inte att en strängvärde längre än 32 K matas in. När du anger ett värde som är längre än 32 K, får du ett Exception om den här egenskapen är true. Om egenskapen är false accepterar vi ditt inmatade strängvärde som cellens värde så att du senare kan skriva ut hela strängvärdet för andra filformat såsom CSV. Däremot, om du har angett ett värde som är ogiltigt för Excel‑filformatet bör du inte spara arbetsboken som Excel‑filformat senare. Annars kan det uppstå oväntade fel i den genererade Excel‑filen.

```csharp
public bool CheckExcelRestriction { get; set; }
```

### Se även

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
