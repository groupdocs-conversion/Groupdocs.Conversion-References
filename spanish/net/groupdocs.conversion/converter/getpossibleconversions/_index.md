---
title: "GetPossibleConversions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Obtiene conversiones posibles para el documento fuente."
type: docs
weight: 50
url: /es/net/groupdocs.conversion/converter/getpossibleconversions/
---
## GetPossibleConversions()

Obtiene conversiones posibles para el documento fuente.

```csharp
public PossibleConversions GetPossibleConversions()
```

### Valor de retorno

Conversiones posibles como [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Observaciones

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Ver también

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetPossibleConversions(string)

Obtiene las conversiones compatibles para la extensión de documento proporcionada

```csharp
public static PossibleConversions GetPossibleConversions(string extension)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extensión | String | Extensión del documento |

### Valor de retorno

Conversiones posibles para la extensión especificada como [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Observaciones

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Ejemplos

Converter.GetPossibleConversions(".docx")

Converter.GetPossibleConversions("docx")

### Ver también

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
