---
title: "SetMeteredKey"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Активирует продукт с Metered‑ключами."
type: docs
weight: 20
url: /ru/net/groupdocs.conversion/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Активирует продукт с Metered‑ключами.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKey | String | Публичный ключ. |
| privateKey | String | Приватный ключ. |

### Примеры

Следующий пример демонстрирует, как активировать продукт с помощью Metered-ключей.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
