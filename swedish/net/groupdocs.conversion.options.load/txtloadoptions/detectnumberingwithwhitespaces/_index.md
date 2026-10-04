---
title: "DetectNumberingWithWhitespaces"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Tillåter att ange hur numrerade listobjekt identifieras när ett vanligt textdokument konverteras. Standardvärdet är true."
type: docs
weight: 30
url: /sv/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

Tillåter att ange hur numrerade listobjekt identifieras när ett vanligt textdokument konverteras. Standardvärdet är true.

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### Anmärkningar

Om detta alternativ är satt till false, upptäcker listigenkänningsalgoritmen listparagrafer när listnummer avslutas med antingen punkt, högra hakparentes eller punktlistsymboler (såsom \"•\", \"*\", \"-\" eller \"o\").

Om detta alternativ är satt till true, används mellanslag också som avgränsare för listnummer: listigenkänningsalgoritmen för arabiskt nummerformat (1., 1.1.2.) använder både mellanslag och punkt (\".\")-symboler.

### Se även

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
