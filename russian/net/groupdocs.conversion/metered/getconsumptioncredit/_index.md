---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Получает количество использованных кредитов."
type: docs
weight: 30
url: /ru/net/groupdocs.conversion/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Получает количество использованных кредитов.

```csharp
public static decimal GetConsumptionCredit()
```

### Примеры

Следующий пример демонстрирует, как получить количество использованных кредитов.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
