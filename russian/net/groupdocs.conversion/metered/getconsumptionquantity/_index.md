---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Получает объём обработанных мегабайт."
type: docs
weight: 40
url: /ru/net/groupdocs.conversion/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Получает объём обработанных мегабайт.

```csharp
public static decimal GetConsumptionQuantity()
```

### Примеры

Следующий пример демонстрирует, как получить количество обработанных мегабайт.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
