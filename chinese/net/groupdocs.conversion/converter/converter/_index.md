---
title: "Converter"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "初始化 Convertergroupdocs.conversion/converter 类的新实例。"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 返回可读流的方法。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *sourceStreamProvider* 为 null 时抛出。 |

### 备注

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 另见

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 返回可读流的方法。 |
| settings | Func`1 | Converter 的设置。 |

### 备注

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 另见

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 返回可读流的方法。 |
| loadOptions | Func`2 | 提供文档加载选项的委托。签名：`Func<LoadContext, LoadOptions>`。[`LoadContext`](../../loadcontext) 参数包含有关正在加载的文档的信息。 |
| settings | Func`1 | Converter 的设置。 |

### 备注

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 另见

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

使用显式转换事件初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 返回可读流的方法。 |
| loadOptions | Func`2 | 提供文档加载选项的委托。 |
| settings | Func`1 | Converter 的设置。 |
| events | Func`1 | 提供为转换器生命周期注册的聚合 [`ConversionEvents`](../../conversionevents) 的委托。 |

### 另见

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

使用显式转换事件初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 返回可读流的方法。 |
| settings | Func`1 | Converter 的设置。 |
| events | Func`1 | 提供为转换器生命周期注册的聚合 [`ConversionEvents`](../../conversionevents) 的委托。 |

### 另见

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |

### 备注

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 另见

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| settings | Func`1 | Converter 的设置。 |

### 备注

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 另见

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| loadOptions | Func`2 | 提供文档加载选项的委托。签名：`Func<LoadContext, LoadOptions>`。[`LoadContext`](../../loadcontext) 参数包含有关正在加载的文档的信息。 |
| settings | Func`1 | Converter 的设置。 |

### 备注

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 另见

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

使用显式转换事件初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| loadOptions | Func`2 | 提供文档加载选项的委托。 |
| settings | Func`1 | Converter 的设置。 |
| events | Func`1 | 提供为转换器生命周期注册的聚合 [`ConversionEvents`](../../conversionevents) 的委托。 |

### 另见

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

使用显式转换事件初始化 [`Converter`](../../converter) 类的新实例。

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 源文档的文件路径。 |
| settings | Func`1 | Converter 的设置。 |
| events | Func`1 | 提供为转换器生命周期注册的聚合 [`ConversionEvents`](../../conversionevents) 的委托。 |

### 另见

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
