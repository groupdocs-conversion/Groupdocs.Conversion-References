---
title: Converter
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Инициализирует новый экземплярConvertergroupdocs.conversion/converter класс.
type: docs
weight: 10
url: /ru/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(Func<Stream> document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Метод, который возвращает читаемый поток. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*document* нулевой. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Метод, который возвращает читаемый поток. |
| settings | Func`1 | Настройки конвертера. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Метод, который возвращает читаемый поток. |
| loadOptions | Func`1 | Методы, возвращающие параметры загрузки документа. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Метод, который возвращает читаемый поток. |
| loadOptions | Func`1 | Методы, возвращающие параметры загрузки документа. |
| settings | Func`1 | Настройки конвертера. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Метод, который возвращает читаемый поток. |
| loadOptions | Func`2 | Методы, возвращающие параметры загрузки документа. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Func`1 | Метод, который возвращает читаемый поток. |
| loadOptions | Func`2 | Методы, возвращающие параметры загрузки документа. |
| settings | Func`1 | Настройки конвертера. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к исходному документу. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к исходному документу. |
| settings | Func`1 | Настройки конвертера. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к исходному документу. |
| loadOptions | Func`1 | Методы, возвращающие параметры загрузки документа. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к исходному документу. |
| loadOptions | Func`1 | Методы, возвращающие параметры загрузки документа. |
| settings | Func`1 | Настройки конвертера. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к исходному документу. |
| loadOptions | Func`2 | Методы, возвращающие параметры загрузки документа. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Инициализирует новый экземпляр[`Converter`](../../converter) класс.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к исходному документу. |
| loadOptions | Func`2 | Методы, возвращающие параметры загрузки документа. |
| settings | Func`1 | Настройки конвертера. |

### Примечания

**Учить больше**

* Подробнее о том, как загружать и преобразовывать документы, хранящиеся на FTP, в хранилище Amazon S3, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Подробнее о параметрах загрузки документов в зависимости от типа файла: [Параметры загрузки для разных типов документов](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Смотрите также

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Инициализирует новый экземпляр[`Converter`](../../converter) класс для быстрой настройки преобразования.

```csharp
public Converter()
```

### Примечания

Пример использования свободного преобразования:

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

### Смотрите также

* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
