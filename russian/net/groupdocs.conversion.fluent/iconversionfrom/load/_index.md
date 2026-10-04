---
title: "Загрузить"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Установить имя файла исходного документа"
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

Установить имя файла исходного документа

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Исходный документ |

### См. также

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Установить массив исходных документов

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String[] | Набор исходных документов |

### См. также

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Установить поток исходного документа

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Поставщик потока исходного документа |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Если проверка настроек конвертера не удалась, будет выброшено это исключение |

### См. также

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Установить массив потоков исходных документов

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Поставщик потоков исходного документа |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Если проверка настроек конвертера не удалась, будет выброшено это исключение |

### См. также

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
