---
title: "SetMeteredKey"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Activa el producto con claves Metered."
type: docs
weight: 20
url: /es/net/groupdocs.conversion/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Activa el producto con claves Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | String | La clave pública. |
| privateKey | String | La clave privada. |

### Ejemplos

El siguiente ejemplo muestra cómo activar el producto con claves Metered.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Ver también

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
