---
title: "GetPossibleConversions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Ottiene le conversioni possibili per il documento sorgente."
type: docs
weight: 50
url: /it/net/groupdocs.conversion/converter/getpossibleconversions/
---
## GetPossibleConversions()

Ottiene le conversioni possibili per il documento sorgente.

```csharp
public PossibleConversions GetPossibleConversions()
```

### Valore restituito

Conversioni possibili come [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Osservazioni

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### IConversionConvertOptions

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetPossibleConversions(string)

Ottiene le conversioni supportate per l'estensione del documento fornita

```csharp
public static PossibleConversions GetPossibleConversions(string extension)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| estensione | String | Estensione del documento |

### Valore restituito

Conversioni possibili per l'estensione specificata come [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Osservazioni

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Esempi

Converter.GetPossibleConversions(".docx")

Converter.GetPossibleConversions("docx")

### IConversionConvertOptions

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
