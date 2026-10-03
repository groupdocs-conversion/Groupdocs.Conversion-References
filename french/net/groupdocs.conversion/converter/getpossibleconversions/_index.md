---
title: "GetPossibleConversions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Obtient les conversions possibles pour le document source."
type: docs
weight: 50
url: /fr/net/groupdocs.conversion/converter/getpossibleconversions/
---
## GetPossibleConversions()

Obtient les conversions possibles pour le document source.

```csharp
public PossibleConversions GetPossibleConversions()
```

### Valeur de retour

Conversions possibles en tant que [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Remarques

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Voir aussi

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetPossibleConversions(string)

Obtient les conversions prises en charge pour l'extension de document fournie

```csharp
public static PossibleConversions GetPossibleConversions(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | Extension du document |

### Valeur de retour

Conversions possibles pour l'extension spécifiée en tant que [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Remarques

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Exemples

Converter.GetPossibleConversions(".docx")

Converter.GetPossibleConversions("docx")

### Voir aussi

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
