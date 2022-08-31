---
title: Converter
second_title: GroupDocs.Conversion for .NET API Reference
description: Initializes new instance of Convertergroupdocs.conversion/converter class.
type: docs
weight: 10
url: /net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The method that returns readable stream. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *document* is null. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The method that returns readable stream. |
| settings | Func`1 | The Converter settings. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The method that returns readable stream. |
| loadOptions | Func`1 | The methods that returns document load options. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The method that returns readable stream. |
| loadOptions | Func`1 | The methods that returns document load options. |
| settings | Func`1 | The Converter settings. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The method that returns readable stream. |
| loadOptions | Func`2 | The methods that returns document load options. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | The method that returns readable stream. |
| loadOptions | Func`2 | The methods that returns document load options. |
| settings | Func`1 | The Converter settings. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| settings | Func`1 | The Converter settings. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | Func`1 | The methods that returns document load options. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | Func`1 | The methods that returns document load options. |
| settings | Func`1 | The Converter settings. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | Func`2 | The methods that returns document load options. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | Func`2 | The methods that returns document load options. |
| settings | Func`1 | The Converter settings. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Initializes new instance of [`Converter`](../../converter) class for fluent conversion setup.

```csharp
public Converter()
```

### Remarks

Sample fluent conversion usage:

```csharp
var converter = new Converter();
```

```csharp
converter
    .Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
converter
    .WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
converter
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
    .OnConversionCompleted((number, stream) => {})
    .Convert();
```

```csharp
converter.Load("").GetPossibleConversions();
converter.Load("").GetDocumentInfo();
converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### See Also

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../converter)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
