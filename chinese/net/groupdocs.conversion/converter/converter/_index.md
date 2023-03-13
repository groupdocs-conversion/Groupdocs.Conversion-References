---
title: Converter
second_title: GroupDocs.Conversion for .NET API 参考
description: 初始化新实例Convertergroupdocs.conversion/converter类.
type: docs
weight: 10
url: /zh/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(Func<Stream> document)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 返回可读流的方法。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*document*一片空白。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 返回可读流的方法。 |
| settings | Func`1 | 转换器设置。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 返回可读流的方法。 |
| loadOptions | Func`1 | 返回文档加载选项的方法。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 返回可读流的方法。 |
| loadOptions | Func`1 | 返回文档加载选项的方法。 |
| settings | Func`1 | 转换器设置。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 返回可读流的方法。 |
| loadOptions | Func`2 | 返回文档加载选项的方法. 源文件的类型 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Func`1 | 返回可读流的方法。 |
| loadOptions | Func`2 | 返回文档加载选项的方法. 源文件的类型 |
| settings | Func`1 | 转换器设置。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| settings | Func`1 | 转换器设置。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| loadOptions | Func`1 | 返回文档加载选项的方法。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| loadOptions | Func`1 | 返回文档加载选项的方法。 |
| settings | Func`1 | 转换器设置。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| loadOptions | Func`2 | 返回文档加载选项的方法. 源文件的类型 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

初始化新实例[`Converter`](../../converter)类.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| loadOptions | Func`2 | 返回文档加载选项的方法. 源文件的类型 |
| settings | Func`1 | 转换器设置。 |

### 评论

**了解更多**

* 有关如何加载和转换存储在 FTP、Amazon S3 存储、Windows Azure 或任何其他第三方存储的文档的更多信息： [从不同来源加载文档](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 有关取决于文件类型的文档加载选项的更多信息： [不同文档类型的加载选项](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 也可以看看

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

初始化新实例[`Converter`](../../converter)流利转换设置类.

```csharp
public Converter()
```

### 评论

示例流畅转换用法：

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

### 也可以看看

* class [Converter](../../converter)
* 命名空间 [GroupDocs.Conversion](../../converter)
* 部件 [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
