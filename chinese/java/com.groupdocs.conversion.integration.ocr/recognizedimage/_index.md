---
title: "RecognizedImage"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "表示从图像中提取的文本，作为其识别过程的结果。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

表示从图像中提取的文本，作为其识别过程的结果。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | 使用一组已识别的行初始化该类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [EMPTY](#EMPTY) | 空的已识别图像 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getLines()](#getLines--) | 获取文档中识别的文本行及其片段。 |
|
|  | [getText()](#getText--) | 获取结构化文本的文本等价物 |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


使用一组已识别的行初始化该类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 行 | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | 一个 IEnumerable（例如列表或数组），包含已识别的行 |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


空的已识别图像


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


获取文档中识别的文本行及其片段。


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


获取结构化文本的文本等价物


**Returns:**
java.lang.String
