---
title: "GetConsumptionQuantity"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Obtiene la cantidad de MB procesados."
type: docs
weight: 40
url: /es/net/groupdocs.conversion/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Obtiene la cantidad de MB procesados.

```csharp
public static decimal GetConsumptionQuantity()
```

### Ejemplos

El siguiente ejemplo muestra cómo obtener la cantidad de MB procesados.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Ver también

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
