---
title: "TextLine"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "表示从图像中提取的文本，作为其识别过程的结果。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

表示从图像中提取的文本，作为其识别过程的结果。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | 初始化一个新的文本行实例，该行由 OCR 引擎从图像中提取。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFragments()](#getFragments--) | 获取一组文本片段数组，例如在该行中识别的符号和单词。 |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


初始化一个新的文本行实例，该行由 OCR 引擎从图像中提取。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 片段 | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | 初始文本片段集合 |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


获取一组文本片段数组，例如在该行中识别的符号和单词。


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
