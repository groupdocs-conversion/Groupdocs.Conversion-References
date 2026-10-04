---
title: "SetMeteredKey"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Metered キーで製品を有効化します。"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Metered キーで製品を有効化します。

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| publicKey | String | 公開鍵。 |
| privateKey | String | 秘密鍵。 |

### 例

以下の例は、従量課金キーで製品を有効化する方法を示しています。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### 関連項目

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
