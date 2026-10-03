---
title: "SetMeteredKey"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "使用计量密钥激活产品。"
type: docs
weight: 20
url: /zh/net/groupdocs.conversion/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

使用计量密钥激活产品。

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | String | 公钥。 |
| privateKey | String | 私钥。 |

### 示例

以下示例演示如何使用计量密钥激活产品。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### 另见

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
