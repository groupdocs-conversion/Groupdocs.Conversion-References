---
title: "GetPossibleConversions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "获取源文档的可能转换。"
type: docs
weight: 50
url: /zh/net/groupdocs.conversion/converter/getpossibleconversions/
---
## GetPossibleConversions()

获取源文档的可能转换。

```csharp
public PossibleConversions GetPossibleConversions()
```

### 返回值

可能的转换为 [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions)。

### 备注

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### 另见

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetPossibleConversions(string)

获取提供的文档扩展名支持的转换

```csharp
public static PossibleConversions GetPossibleConversions(string extension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| extension | String | 文档扩展名 |

### 返回值

指定扩展名的可能转换为 [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions)。

### 备注

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### 示例

Converter.GetPossibleConversions(".docx")

Converter.GetPossibleConversions("docx")

### 另见

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
