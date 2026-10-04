---
title: "Convert"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Конвертирует исходный документ. Сохраняет весь преобразованный документ."
type: docs
weight: 20
url: /ru/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Конвертирует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Делегат, который сохраняет преобразованный документ в поток. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для требуемого типа целевого файла. |
| cancellationToken | CancellationToken | Токен отмены. |

### Примечания

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### См. также

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Конвертирует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для требуемого типа целевого файла. |
| documentCompleted | Action`1 | Делегат, который получает поток преобразованного документа. Подпись: `Action<ConvertedContext>`. Параметр [`ConvertedContext`](../../convertedcontext) содержит поток преобразованного документа и метаданные. |
| cancellationToken | CancellationToken | Токен отмены. |

### Примечания

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### См. также

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Конвертирует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Делегат, который предоставляет поток для сохранения преобразованного документа. Подпись: `Func<SaveContext, Stream>`. Параметр [`SaveContext`](../../savecontext) содержит информацию о операции сохранения. |
| convertOptionsProvider | Func`2 | Делегат, который предоставляет параметры преобразования. Подпись: `Func<ConvertContext, ConvertOptions>`. Параметр [`ConvertContext`](../../convertcontext) содержит информацию о операции преобразования. |
| cancellationToken | CancellationToken | Токен отмены. |

### Примечания

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### См. также

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Конвертирует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Делегат, который предоставляет параметры преобразования. Подпись: `Func<ConvertContext, ConvertOptions>`. Параметр [`ConvertContext`](../../convertcontext) содержит информацию о операции преобразования. |
| documentCompleted | Action`1 | Делегат, который получает поток преобразованного документа. Подпись: `Action<ConvertedContext>`. Параметр [`ConvertedContext`](../../convertedcontext) содержит поток преобразованного документа и метаданные. |
| cancellationToken | CancellationToken | Токен отмены. |

### Примечания

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### См. также

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Конвертирует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу исходного документа. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для требуемого типа целевого файла. |
| cancellationToken | CancellationToken | Токен отмены. |

### Примечания

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### См. также

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Конвертирует исходный документ. Сохраняет преобразованный документ постранично.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Делегат, который предоставляет поток для сохранения каждой преобразованной страницы. Подпись: `Func<SavePageContext, Stream>`. Параметр [`SavePageContext`](../../savepagecontext) содержит номер страницы и информацию о документе. |
| convertOptionsProvider | Func`2 | Делегат, который предоставляет параметры преобразования. Подпись: `Func<ConvertContext, ConvertOptions>`. Параметр [`ConvertContext`](../../convertcontext) содержит информацию о операции преобразования. |
| cancellationToken | CancellationToken | Токен отмены. |

### Примечания

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### См. также

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Конвертирует исходный документ. Сохраняет преобразованный документ постранично.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Делегат, который предоставляет поток для сохранения каждой преобразованной страницы. Подпись: `Func<SavePageContext, Stream>`. Параметр [`SavePageContext`](../../savepagecontext) содержит номер страницы и информацию о документе. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для требуемого типа целевого файла. |
| cancellationToken | CancellationToken | Токен отмены. |

### Примечания

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### См. также

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Конвертирует исходный документ. Сохраняет преобразованный документ постранично.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Делегат, который получает каждую преобразованную страницу. Подпись: `Action<ConvertedPageContext>`. Параметр [`ConvertedPageContext`](../../convertedpagecontext) содержит номер страницы, поток, имя исходного файла и тип целевого файла. |
| convertOptions | Action`1 | Параметры преобразования, специфичные для требуемого типа целевого файла. |
| cancellationToken | CancellationToken | Токен отмены. |

### Примечания

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### См. также

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Конвертирует исходный документ. Сохраняет преобразованный документ постранично.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Делегат, который предоставляет параметры преобразования. Подпись: `Func<ConvertContext, ConvertOptions>`. Параметр [`ConvertContext`](../../convertcontext) содержит информацию о операции преобразования. |
| documentCompleted | Action`1 | Делегат, который получает каждую преобразованную страницу. Подпись: `Action<ConvertedPageContext>`. Параметр [`ConvertedPageContext`](../../convertedpagecontext) содержит номер страницы, поток, имя исходного файла и тип целевого файла. |
| cancellationToken | CancellationToken | Токен отмены. |

### Примечания

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### См. также

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
