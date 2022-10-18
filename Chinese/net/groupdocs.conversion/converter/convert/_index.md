---
title: Convert
second_title: GroupDocs.Conversion for .NET API 参考
description: 转换源文档保存整个转换后的文档
type: docs
weight: 20
url: /zh/net/groupdocs.conversion/converter/convert/
---
## Convert(SaveDocumentStream, ConvertOptions) {#convert_3}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(SaveDocumentStream document, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SaveDocumentStream | 将转换后的文档保存到流的委托。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) {#convert_1}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SaveDocumentStream | 将转换后的文档保存到流的委托。 |
| documentCompleted | ConvertedDocumentStream | 接收转换后的文档流的委托。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertOptionsProvider) {#convert_2}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SaveDocumentStream | 将转换后的文档保存到流的委托。 |
| convertOptionsProvider | ConvertOptionsProvider | 转换选项提供程序。将在每次转换时调用，以向所需的目标文档类型提供特定的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) {#convert}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SaveDocumentStream | 将转换后的文档保存到流的委托。 |
| documentCompleted | ConvertedDocumentStream | 接收转换后的文档流的委托。 |
| convertOptionsProvider | ConvertOptionsProvider | 转换选项提供程序。将在每次转换时调用，以向所需的目标文档类型提供特定的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptions) {#convert_7}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | 将转换后的文档保存到流的委托。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) {#convert_5}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | 将转换后的文档保存到流的委托。 |
| documentCompleted | ConvertedDocumentStream | 接收转换后的文档流的委托。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptionsProvider) {#convert_6}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | 将转换后的文档保存到流的委托。 |
| convertOptionsProvider | ConvertOptionsProvider | 转换选项提供程序。将在每次转换时调用，以向所需的目标文档类型提供特定的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) {#convert_4}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | 将转换后的文档保存到流的委托。 |
| documentCompleted | ConvertedDocumentStream | 接收转换后的文档流的委托。 |
| convertOptionsProvider | ConvertOptionsProvider | 转换选项提供程序。将在每次转换时调用，以向所需的目标文档类型提供特定的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptions) {#convert_11}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(SavePageStream document, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SavePageStream | 将转换后的文档保存到流的委托。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptions) {#convert_9}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SavePageStream | 将转换后的文档页面保存到流的委托。 |
| documentCompleted | ConvertedPageStream | 接收转换后的文档页面流的委托。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptionsProvider) {#convert_10}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SavePageStream | 将转换后的文档保存到流的委托。 |
| convertOptionsProvider | ConvertOptionsProvider | 转换选项提供程序。将在每次转换时调用，以向所需的目标文档类型提供特定的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) {#convert_8}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SavePageStream | 将转换后的文档页面保存到流的委托。 |
| documentCompleted | ConvertedPageStream | 接收转换后的文档页面流的委托。 |
| convertOptionsProvider | ConvertOptionsProvider | 转换选项提供程序。将在每次转换时调用，以向所需的目标文档类型提供特定的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptions) {#convert_15}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SavePageStreamForFileType | 将转换后的文档保存到流的委托。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) {#convert_13}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SavePageStreamForFileType | 将转换后的文档页面保存到流的委托。 |
| documentCompleted | ConvertedPageStream | 接收转换后的文档页面流的委托。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptionsProvider) {#convert_14}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(SavePageStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SavePageStreamForFileType | 将转换后的文档保存到流的委托。 |
| convertOptionsProvider | ConvertOptionsProvider | 转换选项提供程序。将在每次转换时调用，以向所需的目标文档类型提供特定的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) {#convert_12}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | SavePageStreamForFileType | 将转换后的文档页面保存到流的委托。 |
| documentCompleted | ConvertedPageStream | 接收转换后的文档页面流的委托。 |
| convertOptionsProvider | ConvertOptionsProvider | 转换选项提供程序。将在每次转换时调用，以向所需的目标文档类型提供特定的转换选项。 |

### 评论

**学到更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
