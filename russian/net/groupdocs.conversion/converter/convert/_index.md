---
title: Convert
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Преобразует исходный документ. Сохраняет весь преобразованный документ.
type: docs
weight: 20
url: /ru/net/groupdocs.conversion/converter/convert/
---
## Convert(SaveDocumentStream, ConvertOptions) {#convert_3}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SaveDocumentStream | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) {#convert_1}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SaveDocumentStream | Делегат, сохраняющий преобразованный документ в поток. |
| documentCompleted | ConvertedDocumentStream | Делегат, который получает преобразованный поток документов. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertOptionsProvider) {#convert_2}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SaveDocumentStream | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptionsProvider | ConvertOptionsProvider | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) {#convert}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SaveDocumentStream | Делегат, сохраняющий преобразованный документ в поток. |
| documentCompleted | ConvertedDocumentStream | Делегат, который получает преобразованный поток документов. |
| convertOptionsProvider | ConvertOptionsProvider | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptions) {#convert_7}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) {#convert_5}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Делегат, сохраняющий преобразованный документ в поток. |
| documentCompleted | ConvertedDocumentStream | Делегат, который получает преобразованный поток документов. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptionsProvider) {#convert_6}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptionsProvider | ConvertOptionsProvider | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) {#convert_4}

Преобразует исходный документ. Сохраняет весь преобразованный документ.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Делегат, сохраняющий преобразованный документ в поток. |
| documentCompleted | ConvertedDocumentStream | Делегат, который получает преобразованный поток документов. |
| convertOptionsProvider | ConvertOptionsProvider | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
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

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptions) {#convert_11}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(SavePageStream document, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SavePageStream | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptions) {#convert_9}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SavePageStream | Делегат, сохраняющий преобразованную страницу документа в поток. |
| documentCompleted | ConvertedPageStream | Делегат, который получает преобразованный поток страниц документа. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptionsProvider) {#convert_10}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SavePageStream | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptionsProvider | ConvertOptionsProvider | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) {#convert_8}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SavePageStream | Делегат, сохраняющий преобразованную страницу документа в поток. |
| documentCompleted | ConvertedPageStream | Делегат, который получает преобразованный поток страниц документа. |
| convertOptionsProvider | ConvertOptionsProvider | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptions) {#convert_15}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SavePageStreamForFileType | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) {#convert_13}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SavePageStreamForFileType | Делегат, сохраняющий преобразованную страницу документа в поток. |
| documentCompleted | ConvertedPageStream | Делегат, который получает преобразованный поток страниц документа. |
| convertOptions | ConvertOptions | Параметры преобразования, специфичные для желаемого целевого типа файла. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptionsProvider) {#convert_14}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(SavePageStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SavePageStreamForFileType | Делегат, сохраняющий преобразованный документ в поток. |
| convertOptionsProvider | ConvertOptionsProvider | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) {#convert_12}

Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SavePageStreamForFileType | Делегат, сохраняющий преобразованную страницу документа в поток. |
| documentCompleted | ConvertedPageStream | Делегат, который получает преобразованный поток страниц документа. |
| convertOptionsProvider | ConvertOptionsProvider | Конвертировать поставщик опций. Будет вызываться для каждого преобразования, чтобы предоставить определенные параметры преобразования в желаемый тип целевого документа. |

### Примечания

**Учить больше**

* Подробнее о базовых сценариях преобразования документов: [Как преобразовать документ в 3 шага](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Варианты использования преобразования, дополнительные настройки и настройки: [Конвертировать документ с дополнительными настройками](https://docs.groupdocs.com/display/conversionnet/Converting)

### Смотрите также

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* пространство имен [GroupDocs.Conversion](../../converter)
* сборка [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
