---
title: "SetMeteredKey"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Aktiverar produkten med mätade nycklar."
type: docs
weight: 20
url: /sv/net/groupdocs.conversion/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Aktiverar produkten med mätade nycklar.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | String | Den offentliga nyckeln. |
| privateKey | String | Den privata nyckeln. |

### Exempel

Följande exempel visar hur man aktiverar produkten med Metered-nycklar.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Se även

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
