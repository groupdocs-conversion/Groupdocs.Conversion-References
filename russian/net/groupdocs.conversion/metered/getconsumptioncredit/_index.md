---
title: GetConsumptionCredit
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Получает количество использованных кредитов.
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

В следующем примере показано, как получить количество использованных кредитов.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Смотрите также

* class [Metered](../../metered)
* пространство имен [GroupDocs.Conversion](../../metered)
* сборка [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
