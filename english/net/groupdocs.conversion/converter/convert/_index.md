---
title: Convert
second_title: GroupDocs.Conversion for .NET API Reference
description: Converts source document. Saves the whole converted document.
type: docs
weight: 20
url: /net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| targetStreamProvider | Func`2 | The delegate that saves converted document to a stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |
| cancellationToken | CancellationToken | The cancellation token. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |
| documentCompleted | Action`1 | Delegate that receives the converted document stream. Signature: `Action<ConvertedContext>`. The [`ConvertedContext`](../../convertedcontext) parameter contains the converted document stream and metadata. |
| cancellationToken | CancellationToken | The cancellation token. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegate that provides the stream to save the converted document. Signature: `Func<SaveContext, Stream>`. The [`SaveContext`](../../savecontext) parameter contains information about the save operation. |
| convertOptionsProvider | Func`2 | Delegate that provides conversion options. Signature: `Func<ConvertContext, ConvertOptions>`. The [`ConvertContext`](../../convertcontext) parameter contains information about the conversion operation. |
| cancellationToken | CancellationToken | The cancellation token. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegate that provides conversion options. Signature: `Func<ConvertContext, ConvertOptions>`. The [`ConvertContext`](../../convertcontext) parameter contains information about the conversion operation. |
| documentCompleted | Action`1 | Delegate that receives the converted document stream. Signature: `Action<ConvertedContext>`. The [`ConvertedContext`](../../convertedcontext) parameter contains the converted document stream and metadata. |
| cancellationToken | CancellationToken | The cancellation token. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |
| cancellationToken | CancellationToken | The cancellation token. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegate that provides a stream for saving each converted page. Signature: `Func<SavePageContext, Stream>`. The [`SavePageContext`](../../savepagecontext) parameter contains page number and document information. |
| convertOptionsProvider | Func`2 | Delegate that provides conversion options. Signature: `Func<ConvertContext, ConvertOptions>`. The [`ConvertContext`](../../convertcontext) parameter contains information about the conversion operation. |
| cancellationToken | CancellationToken | The cancellation token. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegate that provides a stream for saving each converted page. Signature: `Func<SavePageContext, Stream>`. The [`SavePageContext`](../../savepagecontext) parameter contains page number and document information. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |
| cancellationToken | CancellationToken | The cancellation token. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Delegate that receives each converted page. Signature: `Action<ConvertedPageContext>`. The [`ConvertedPageContext`](../../convertedpagecontext) parameter contains page number, stream, source file name, and target file type. |
| convertOptions | Action`1 | The convert options specific to desired target file type. |
| cancellationToken | CancellationToken | The cancellation token. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegate that provides conversion options. Signature: `Func<ConvertContext, ConvertOptions>`. The [`ConvertContext`](../../convertcontext) parameter contains information about the conversion operation. |
| documentCompleted | Action`1 | Delegate that receives each converted page. Signature: `Action<ConvertedPageContext>`. The [`ConvertedPageContext`](../../convertedpagecontext) parameter contains page number, stream, source file name, and target file type. |
| cancellationToken | CancellationToken | The cancellation token. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
