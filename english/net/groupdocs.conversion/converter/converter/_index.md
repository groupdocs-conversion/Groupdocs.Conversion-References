---
title: Converter
second_title: GroupDocs.Conversion for .NET API Reference
description: Initializes new instance of Convertergroupdocs.conversion/converter class.
type: docs
weight: 10
url: /net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | The method that returns readable stream. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *sourceStreamProvider* is null. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | The method that returns readable stream. |
| settings | Func`1 | The Converter settings. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | The method that returns readable stream. |
| loadOptions | Func`2 | Delegate that provides load options for the document. Signature: `Func<LoadContext, LoadOptions>`. The [`LoadContext`](../../loadcontext) parameter contains information about the document being loaded. |
| settings | Func`1 | The Converter settings. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_3}

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
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_4}

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
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_5}

Initializes new instance of [`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | Func`2 | Delegate that provides load options for the document. Signature: `Func<LoadContext, LoadOptions>`. The [`LoadContext`](../../loadcontext) parameter contains information about the document being loaded. |
| settings | Func`1 | The Converter settings. |

### Remarks

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### See Also

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
