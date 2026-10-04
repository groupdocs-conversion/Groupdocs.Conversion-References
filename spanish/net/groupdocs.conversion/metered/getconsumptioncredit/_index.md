---
title: "GetConsumptionCredit"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Obtiene el recuento de créditos consumidos."
type: docs
weight: 30
url: /es/net/groupdocs.conversion/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Obtiene el recuento de créditos consumidos.

```csharp
public static decimal GetConsumptionCredit()
```

### Ejemplos

El siguiente ejemplo muestra cómo obtener el recuento de créditos consumidos.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Ver también

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
