---
title: "GetPossibleConversions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ソースドキュメントの可能な変換を取得します。"
type: docs
weight: 50
url: /ja/net/groupdocs.conversion/converter/getpossibleconversions/
---
## GetPossibleConversions()

ソースドキュメントの可能な変換を取得します。

```csharp
public PossibleConversions GetPossibleConversions()
```

### 戻り値

可能な変換は [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions) として表されます。

### 備考

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### 関連項目

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetPossibleConversions(string)

指定されたドキュメント拡張子に対するサポートされている変換を取得します

```csharp
public static PossibleConversions GetPossibleConversions(string extension)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| extension | String | ドキュメント拡張子 |

### 戻り値

指定された拡張子に対する可能な変換は、[`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions) として提供されます。

### 備考

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### 例

Converter.GetPossibleConversions(".docx")

Converter.GetPossibleConversions("docx")

### 関連項目

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
