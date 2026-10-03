---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "检索已处理的 MB 数量。"
type: docs
weight: 40
url: /zh/net/groupdocs.conversion/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

检索已处理的 MB 数量。

```csharp
public static decimal GetConsumptionQuantity()
```

### 示例

以下示例演示如何检索已处理的 MB 数量。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### 另见

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
