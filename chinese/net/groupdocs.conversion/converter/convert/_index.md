---
title: Convert
second_title: GroupDocs.Conversion for .NET API 参考
description: 转换源文档保存整个转换后的文档
type: docs
weight: 20
url: /zh/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 将转换后的文档保存到流中的委托。 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 将转换后的文档保存到流中的委托。 |
| documentCompleted | Action`2 | 接收转换文档流的委托. 文件内容流文件名 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 将转换后的文档保存到流中的委托。 |
| convertOptionsProvider | Func`3 | 转换选项提供者。将为每个转换调用以提供特定的转换选项到所需的目标文档类型。 文件名文件的类型 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 将转换后的文档保存到流中的委托。 |
| documentCompleted | Action`2 | 接收转换文档流的委托. 文件内容流文件名 |
| convertOptionsProvider | Func`3 | 转换选项提供者。将为每个转换调用以提供特定的转换选项到所需的目标文档类型。 文件名文件的类型 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`2 | 将转换后的文档保存到流中的委托。 源文件的类型 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`2 | 将转换后的文档保存到流中的委托。 源文件的类型 |
| documentCompleted | Action`2 | 接收转换文档流的委托. 文件内容流文件名 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`2 | 将转换后的文档保存到流中的委托。 源文件的类型 |
| convertOptionsProvider | Func`3 | 转换选项提供者。将为每个转换调用以提供特定的转换选项到所需的目标文档类型。 文件名文件的类型 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

转换源文档。保存整个转换后的文档。

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`2 | 将转换后的文档保存到流中的委托。 源文件的类型 |
| documentCompleted | Action`2 | 接收转换文档流的委托. 文件内容流文件名 |
| convertOptionsProvider | Func`3 | 转换选项提供者。将为每个转换调用以提供特定的转换选项到所需的目标文档类型。 文件名文件的类型 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
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

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`2 | 将转换后的文档保存到流中的委托。 页码 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`2 | 将转换后的文档页面保存到流中的委托。 页码 |
| documentCompleted | Action`3 | 接收转换文档页面流的委托. 页码文件内容流文件名 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`2 | 将转换后的文档保存到流中的委托。 页码 |
| convertOptionsProvider | Func`3 | 转换选项提供者。将为每个转换调用以提供特定的转换选项到所需的目标文档类型。 文件名文件的类型 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`2 | 将转换后的文档页面保存到流中的委托。 页码 |
| documentCompleted | Action`3 | 接收转换文档页面流的委托. 页码文件内容流文件名 |
| convertOptionsProvider | Func`3 | 转换选项提供者。将为每个转换调用以提供特定的转换选项到所需的目标文档类型。 文件名文件的类型 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`3 | 将转换后的文档保存到流中的委托。 页码 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`3 | 将转换后的文档页面保存到流中的委托。 页码文件类型 |
| documentCompleted | Action`3 | 接收转换文档页面流的委托. 页码文件内容流文件名 |
| convertOptions | ConvertOptions | 特定于所需目标文件类型的转换选项。 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`3 | 将转换后的文档保存到流中的委托。 页码文件类型 |
| convertOptionsProvider | Func`3 | 转换选项提供者。将为每个转换调用以提供特定的转换选项到所需的目标文档类型。 文件名文件的类型 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

转换源文档。逐页保存转换后的文档。

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`3 | 将转换后的文档页面保存到流中的委托。 页码文件类型 |
| documentCompleted | Action`3 | 接收转换文档页面流的委托. 页码文件内容流文件名 |
| convertOptionsProvider | Func`3 | 转换选项提供者。将为每个转换调用以提供特定的转换选项到所需的目标文档类型。 文件名文件的类型 |

### 评论

**了解更多**

* 更多文档转换基本场景： [如何通过 3 个步骤转换文档](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 转换用例、高级设置和自定义： [使用高级设置转换文档](https://docs.groupdocs.com/display/conversionnet/Converting)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
