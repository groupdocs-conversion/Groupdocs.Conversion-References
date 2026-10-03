---
title: "FontConfigSubstitutionEnabled"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "自动根据系统中的 FontConfig 替换缺失的字体。默认 false。"
type: docs
weight: 120
url: /zh/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled/
---
## WordProcessingLoadOptions.FontConfigSubstitutionEnabled property

基于系统中的 FontConfig 自动替换缺失的字体。默认值：false。

```csharp
public bool FontConfigSubstitutionEnabled { get; set; }
```

### 备注

**Note:** The order of substitution is as follows:

1) 自动根据字体名称替换缺失的字体（如果已启用）。

2) 自动根据 FontConfig 替换缺失的字体（如果已启用）。

3) 根据 FontSubstitutes 替换缺失的字体（如果已设置）。

4) 自动根据 FontInfo 替换缺失的字体（如果已启用）。

5) 根据 DefaultFont 替换缺失的字体（如果已设置）。

### 另见

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
