---
title: "GetPossibleConversions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Haalt mogelijke conversies voor het bron‑document op."
type: docs
weight: 50
url: /nl/net/groupdocs.conversion/converter/getpossibleconversions/
---
## GetPossibleConversions()

Haalt mogelijke conversies voor het bron‑document op.

```csharp
public PossibleConversions GetPossibleConversions()
```

### Retourwaarde

Mogelijke conversies als [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Opmerkingen

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Zie ook

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetPossibleConversions(string)

Haalt ondersteunde conversies op voor opgegeven documentextensie

```csharp
public static PossibleConversions GetPossibleConversions(string extension)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extensie | String | Documentextensie |

### Retourwaarde

Mogelijke conversies voor de opgegeven extensie als [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Opmerkingen

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Voorbeelden

Converter.GetPossibleConversions(".docx")

Converter.GetPossibleConversions("docx")

### Zie ook

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
