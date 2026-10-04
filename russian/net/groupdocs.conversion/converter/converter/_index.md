---
title: "Converter"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Инициализирует новый экземпляр класса Convertergroupdocs.conversion/converter."
type: docs
weight: 10
url: /ru/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Инициализирует новый экземпляр класса [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Метод, который возвращает читаемый поток. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *sourceStreamProvider* равен null. |

### Примечания

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### См. также

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Инициализирует новый экземпляр класса [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Метод, который возвращает читаемый поток. |
| settings | Func`1 | Настройки Converter. |

### Примечания

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### См. также

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

Инициализирует новый экземпляр класса [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Метод, который возвращает читаемый поток. |
| loadOptions | Func`2 | Делегат, который предоставляет параметры загрузки для документа. Подпись: `Func<LoadContext, LoadOptions>`. Параметр [`LoadContext`](../../loadcontext) содержит информацию о загружаемом документе. |
| settings | Func`1 | Настройки Converter. |

### Примечания

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### См. также

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Инициализирует новый экземпляр класса [`Converter`](../../converter) с явными событиями конвертации.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Метод, который возвращает читаемый поток. |
| loadOptions | Func`2 | Делегат, предоставляющий параметры загрузки документа. |
| settings | Func`1 | Настройки Converter. |
| events | Func`1 | Делегат, предоставляющий агрегированные [`ConversionEvents`](../../conversionevents), зарегистрированные на время жизни конвертера. |

### См. также

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Инициализирует новый экземпляр класса [`Converter`](../../converter) с явными событиями конвертации.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Метод, который возвращает читаемый поток. |
| settings | Func`1 | Настройки Converter. |
| events | Func`1 | Делегат, предоставляющий агрегированные [`ConversionEvents`](../../conversionevents), зарегистрированные на время жизни конвертера. |

### См. также

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

Инициализирует новый экземпляр класса [`Converter`](../../converter).

```csharp
public Converter(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу исходного документа. |

### Примечания

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### См. также

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

Инициализирует новый экземпляр класса [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу исходного документа. |
| settings | Func`1 | Настройки Converter. |

### Примечания

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### См. также

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

Инициализирует новый экземпляр класса [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу исходного документа. |
| loadOptions | Func`2 | Делегат, который предоставляет параметры загрузки для документа. Подпись: `Func<LoadContext, LoadOptions>`. Параметр [`LoadContext`](../../loadcontext) содержит информацию о загружаемом документе. |
| settings | Func`1 | Настройки Converter. |

### Примечания

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### См. также

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Инициализирует новый экземпляр класса [`Converter`](../../converter) с явными событиями конвертации.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу исходного документа. |
| loadOptions | Func`2 | Делегат, предоставляющий параметры загрузки документа. |
| settings | Func`1 | Настройки Converter. |
| events | Func`1 | Делегат, предоставляющий агрегированные [`ConversionEvents`](../../conversionevents), зарегистрированные на время жизни конвертера. |

### См. также

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Инициализирует новый экземпляр класса [`Converter`](../../converter) с явными событиями конвертации.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу исходного документа. |
| settings | Func`1 | Настройки Converter. |
| events | Func`1 | Делегат, предоставляющий агрегированные [`ConversionEvents`](../../conversionevents), зарегистрированные на время жизни конвертера. |

### См. также

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
