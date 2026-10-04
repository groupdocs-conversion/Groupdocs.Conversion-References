---
title: "ConvertTo"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Spara konverterat dokument som fil"
type: docs
weight: 20
url: /sv/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

Spara konverterat dokument som fil

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Konverterat dokument |

### Returvärde

Alternativ eller hanterarinställningsgränssnitt för att fortsätta konverteringsbyggnad

### Se även

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

Spara konverterat dokument som ström

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Konverterad dokumentströmleverantör Sparkontext |

### Returvärde

Alternativ eller hanterarinställningsgränssnitt för att fortsätta konverteringsbyggnad

### Se även

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
