---
title: Convert
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Преобразует исходный документ. Сохраняет весь преобразованный документ.
type: docs
weight: 20
url: /ru/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Делегат, сохраняющий преобразованный документ в поток. |
| documentCompleted | Action`2 | Делегат, который получает преобразованный поток документов. Поток содержимого файлаИмя файла |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptionsProvider | Func`3 | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. Имя файлаТип файла |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Делегат, сохраняющий преобразованный документ в поток. |
| documentCompleted | Action`2 | Делегат, который получает преобразованный поток документов. Поток содержимого файлаИмя файла |
| convertOptionsProvider | Func`3 | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. Имя файлаТип файла |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`2 | Делегат, сохраняющий преобразованный документ в поток. Тип исходного файла |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`2 | Делегат, сохраняющий преобразованный документ в поток. Тип исходного файла |
| documentCompleted | Action`2 | Делегат, который получает преобразованный поток документов. Поток содержимого файлаИмя файла |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`2 | Делегат, сохраняющий преобразованный документ в поток. Тип исходного файла |
| convertOptionsProvider | Func`3 | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. Имя файлаТип файла |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`2 | Делегат, сохраняющий преобразованный документ в поток. Тип исходного файла |
| documentCompleted | Action`2 | Делегат, который получает преобразованный поток документов. Поток содержимого файлаИмя файла |
| convertOptionsProvider | Func`3 | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. Имя файлаТип файла |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к исходному документу. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`2 | Делегат, сохраняющий преобразованный документ в поток. Номер страницы |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`2 | Делегат, сохраняющий преобразованную страницу документа в поток. Номер страницы |
| documentCompleted | Action`3 | Делегат, который получает преобразованный поток страниц документа. Номер страницыПоток содержимого файлаИмя файла |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`2 | Делегат, сохраняющий преобразованный документ в поток. Номер страницы |
| convertOptionsProvider | Func`3 | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. Имя файлаТип файла |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`2 | Делегат, сохраняющий преобразованную страницу документа в поток. Номер страницы |
| documentCompleted | Action`3 | Делегат, который получает преобразованный поток страниц документа. Номер страницыПоток содержимого файлаИмя файла |
| convertOptionsProvider | Func`3 | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. Имя файлаТип файла |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`3 | Делегат, сохраняющий преобразованный документ в поток. Номер страницы |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`3 | Делегат, сохраняющий преобразованную страницу документа в поток. Номер страницыТип файла |
| documentCompleted | Action`3 | Делегат, который получает преобразованный поток страниц документа. Номер страницыПоток содержимого файлаИмя файла |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`3 | Делегат, сохраняющий преобразованный документ в поток. Номер страницыТип файла |
| convertOptionsProvider | Func`3 | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. Имя файлаТип файла |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`3 | Делегат, сохраняющий преобразованную страницу документа в поток. Номер страницыТип файла |
| documentCompleted | Action`3 | Делегат, который получает преобразованный поток страниц документа. Номер страницыПоток содержимого файлаИмя файла |
| convertOptionsProvider | Func`3 | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. Имя файлаТип файла |

### Примечания

**Узнать больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
