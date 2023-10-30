---
title: Convert
second_title: GroupDocs.Conversion for .NET API Reference
description: Converts source document. Saves the whole converted document.
type: docs
weight: 20
url: /net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The delegate that saves converted document to a stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;string, FileType, Stream&gt;, ConvertOptions) {#convert_1}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<Stream> document, Action<string, FileType, Stream> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The delegate that saves converted document to a stream. |
| documentCompleted | Action`3 | The delegate that receive converted document stream. The name of the source fileThe target file typeThe converted file content stream |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The delegate that saves converted document to a stream. |
| convertOptionsProvider | Func`3 | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. The name of the fileThe type of the file |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;string, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<Stream> document, Action<string, FileType, Stream> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The delegate that saves converted document to a stream. |
| documentCompleted | Action`3 | The delegate that receive converted document stream. The name of the source fileThe target file typeThe converted file content stream |
| convertOptionsProvider | Func`3 | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. The name of the fileThe type of the file |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`2 | The delegate that saves converted document to a stream. The type of the converted file |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;string, FileType, Stream&gt;, ConvertOptions) {#convert_5}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Action<string, FileType, Stream> documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`2 | The delegate that saves converted document to a stream. The type of the target file |
| documentCompleted | Action`3 | The delegate that receive converted document stream. The name of the source fileThe target file typeThe converted file content stream |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`2 | The delegate that saves converted document to a stream. The type of the source file |
| convertOptionsProvider | Func`3 | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. The name of the fileThe type of the file |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;string, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Action<string, FileType, Stream> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`2 | The delegate that saves converted document to a stream. The type of the source file |
| documentCompleted | Action`3 | The delegate that receive converted document stream. The name of the source fileThe target file typeThe converted file content stream |
| convertOptionsProvider | Func`3 | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. The name of the fileThe type of the file |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`2 | The delegate that saves converted document to a stream. Page number |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;string, FileType, int, Stream&gt;, ConvertOptions) {#convert_9}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<int, Stream> document, 
    Action<string, FileType, int, Stream> documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`2 | The delegate that saves converted document page to a stream. Page number |
| documentCompleted | Action`4 | The delegate that receive converted document page stream. The name of the source fileThe target file typePage numberThe converted file content stream |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`2 | The delegate that saves converted document to a stream. Page number |
| convertOptionsProvider | Func`3 | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. The name of the fileThe type of the file |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;string, FileType, int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<int, Stream> document, 
    Action<string, FileType, int, Stream> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`2 | The delegate that saves converted document page to a stream. Page number |
| documentCompleted | Action`4 | The delegate that receive converted document page stream. The name of the source fileThe target file typePage numberThe converted file content stream |
| convertOptionsProvider | Func`3 | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. The name of the fileThe type of the file |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`3 | The delegate that saves converted document to a stream. Page number |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;string, FileType, int, Stream&gt;, ConvertOptions) {#convert_13}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<string, FileType, int, Stream> documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`3 | The delegate that saves converted document page to a stream. Page numberFile type |
| documentCompleted | Action`4 | The delegate that receive converted document page stream. The name of the source fileThe target file typePage numberThe converted file content stream |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`3 | The delegate that saves converted document to a stream. Page numberFile type |
| convertOptionsProvider | Func`3 | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. The name of the fileThe type of the file |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;string, FileType, int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<string, FileType, int, Stream> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`3 | The delegate that saves converted document page to a stream. Page numberFile type |
| documentCompleted | Action`4 | The delegate that receive converted document page stream. The name of the source fileThe target file typePage numberThe converted file content stream |
| convertOptionsProvider | Func`3 | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. The name of the fileThe type of the file |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
