---
title: "Convert"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换源文档。保存完整的已转换文档。"
type: docs
weight: 20
url: /zh/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

转换源文档。保存完整的已转换文档。

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 将已转换文档保存到流的委托。 |
| convertOptions | ConvertOptions | 针对所需目标文件类型的转换选项。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 备注

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 另见

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

转换源文档。保存完整的已转换文档。

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOptions | ConvertOptions | 针对所需目标文件类型的转换选项。 |
| documentCompleted | Action`1 | 接收已转换文档流的委托。签名：`Action<ConvertedContext>`。[`ConvertedContext`](../../convertedcontext) 参数包含已转换的文档流和元数据。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 备注

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 另见

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

转换源文档。保存完整的已转换文档。

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 提供用于保存已转换文档的流的委托。签名：`Func<SaveContext, Stream>`。[`SaveContext`](../../savecontext) 参数包含有关保存操作的信息。 |
| convertOptionsProvider | Func`2 | 提供转换选项的委托。签名：`Func<ConvertContext, ConvertOptions>`。[`ConvertContext`](../../convertcontext) 参数包含有关转换操作的信息。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 备注

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 另见

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

转换源文档。保存完整的已转换文档。

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | 提供转换选项的委托。签名：`Func<ConvertContext, ConvertOptions>`。[`ConvertContext`](../../convertcontext) 参数包含有关转换操作的信息。 |
| documentCompleted | Action`1 | 接收已转换文档流的委托。签名：`Action<ConvertedContext>`。[`ConvertedContext`](../../convertedcontext) 参数包含已转换的文档流和元数据。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 备注

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 另见

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

转换源文档。保存完整的已转换文档。

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| convertOptions | ConvertOptions | 针对所需目标文件类型的转换选项。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 备注

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 另见

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

转换源文档。逐页保存已转换的文档。

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 提供用于保存每个已转换页面的流的委托。签名：`Func<SavePageContext, Stream>`。[`SavePageContext`](../../savepagecontext) 参数包含页码和文档信息。 |
| convertOptionsProvider | Func`2 | 提供转换选项的委托。签名：`Func<ConvertContext, ConvertOptions>`。[`ConvertContext`](../../convertcontext) 参数包含有关转换操作的信息。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 备注

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 另见

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

转换源文档。逐页保存已转换的文档。

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 提供用于保存每个已转换页面的流的委托。签名：`Func<SavePageContext, Stream>`。[`SavePageContext`](../../savepagecontext) 参数包含页码和文档信息。 |
| convertOptions | ConvertOptions | 针对所需目标文件类型的转换选项。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 备注

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 另见

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

转换源文档。逐页保存已转换的文档。

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentCompleted | ConvertOptions | 接收每个已转换页面的委托。签名：`Action<ConvertedPageContext>`。[`ConvertedPageContext`](../../convertedpagecontext) 参数包含页码、流、源文件名和目标文件类型。 |
| convertOptions | Action`1 | 针对所需目标文件类型的转换选项。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 备注

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 另见

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

转换源文档。逐页保存已转换的文档。

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | 提供转换选项的委托。签名：`Func<ConvertContext, ConvertOptions>`。[`ConvertContext`](../../convertcontext) 参数包含有关转换操作的信息。 |
| documentCompleted | Action`1 | 接收每个已转换页面的委托。签名：`Action<ConvertedPageContext>`。[`ConvertedPageContext`](../../convertedpagecontext) 参数包含页码、流、源文件名和目标文件类型。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 备注

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 另见

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
