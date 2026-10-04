---
title: "GetPossibleConversions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Hämtar möjliga konverteringar för källdokumentet."
type: docs
weight: 50
url: /sv/net/groupdocs.conversion/converter/getpossibleconversions/
---
## GetPossibleConversions()

Hämtar möjliga konverteringar för källdokumentet.

```csharp
public PossibleConversions GetPossibleConversions()
```

### Returvärde

Möjliga konverteringar som [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Anmärkningar

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Se även

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetPossibleConversions(string)

Hämtar stödjade konverteringar för angiven dokumentändelse

```csharp
public static PossibleConversions GetPossibleConversions(string extension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filändelse | String | Dokumentfiländelse |

### Returvärde

Möjliga konverteringar för den angivna filändelsen som [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Anmärkningar

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Exempel

Converter.GetPossibleConversions(".docx")

Converter.GetPossibleConversions("docx")

### Se även

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
