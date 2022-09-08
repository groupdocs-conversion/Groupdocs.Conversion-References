---
title: Convert
second_title: GroupDocs.Conversion for .NET API Reference
description: Converts source document. Saves the whole converted document.
type: docs
weight: 20
url: /net/groupdocs.conversion/converter/convert/
---
## Convert(SaveDocumentStream, ConvertOptions) {#convert_3}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SaveDocumentStream | The delegate that saves converted document to a stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) {#convert_1}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SaveDocumentStream | The delegate that saves converted document to a stream. |
| documentCompleted | ConvertedDocumentStream | The delegate that receive converted document stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertOptionsProvider) {#convert_2}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SaveDocumentStream | The delegate that saves converted document to a stream. |
| convertOptionsProvider | ConvertOptionsProvider | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) {#convert}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SaveDocumentStream | The delegate that saves converted document to a stream. |
| documentCompleted | ConvertedDocumentStream | The delegate that receive converted document stream. |
| convertOptionsProvider | ConvertOptionsProvider | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptions) {#convert_7}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | The delegate that saves converted document to a stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) {#convert_5}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | The delegate that saves converted document to a stream. |
| documentCompleted | ConvertedDocumentStream | The delegate that receive converted document stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptionsProvider) {#convert_6}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | The delegate that saves converted document to a stream. |
| convertOptionsProvider | ConvertOptionsProvider | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) {#convert_4}

Converts source document. Saves the whole converted document.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | The delegate that saves converted document to a stream. |
| documentCompleted | ConvertedDocumentStream | The delegate that receive converted document stream. |
| convertOptionsProvider | ConvertOptionsProvider | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
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

## Convert(SavePageStream, ConvertOptions) {#convert_11}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(SavePageStream document, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SavePageStream | The delegate that saves converted document to a stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptions) {#convert_9}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SavePageStream | The delegate that saves converted document page to a stream. |
| documentCompleted | ConvertedPageStream | The delegate that receive converted document page stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptionsProvider) {#convert_10}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SavePageStream | The delegate that saves converted document to a stream. |
| convertOptionsProvider | ConvertOptionsProvider | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) {#convert_8}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SavePageStream | The delegate that saves converted document page to a stream. |
| documentCompleted | ConvertedPageStream | The delegate that receive converted document page stream. |
| convertOptionsProvider | ConvertOptionsProvider | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptions) {#convert_15}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SavePageStreamForFileType | The delegate that saves converted document to a stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) {#convert_13}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SavePageStreamForFileType | The delegate that saves converted document page to a stream. |
| documentCompleted | ConvertedPageStream | The delegate that receive converted document page stream. |
| convertOptions | ConvertOptions | The convert options specific to desired target file type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptionsProvider) {#convert_14}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(SavePageStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SavePageStreamForFileType | The delegate that saves converted document to a stream. |
| convertOptionsProvider | ConvertOptionsProvider | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) {#convert_12}

Converts source document. Saves the converted document page by page.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | SavePageStreamForFileType | The delegate that saves converted document page to a stream. |
| documentCompleted | ConvertedPageStream | The delegate that receive converted document page stream. |
| convertOptionsProvider | ConvertOptionsProvider | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### Remarks

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### See Also

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
