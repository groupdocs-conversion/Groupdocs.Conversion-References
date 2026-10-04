---
title: "SetMeteredKey"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Attiva il prodotto con chiavi Metered."
type: docs
weight: 20
url: /it/net/groupdocs.conversion/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Attiva il prodotto con chiavi Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| publicKey | String | La chiave pubblica. |
| privateKey | String | La chiave privata. |

### Esempi

L'esempio seguente dimostra come attivare il prodotto con Metered keys.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### IConversionConvertOptions

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
