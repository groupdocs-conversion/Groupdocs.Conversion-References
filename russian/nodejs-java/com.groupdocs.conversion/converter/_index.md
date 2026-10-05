---
title: "Converter"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Представляет основной класс, который управляет процессом конвертации документов."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Представляет основной класс, который управляет процессом конвертации документов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Converter()](#Converter--) | Инициализирует новый экземпляр класса для настройки конвертации в стиле fluent. |
| [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter). |
| [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter). |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter). |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter). |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Инициализирует новый экземпляр класса. |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Инициализирует новый экземпляр класса. |
| [Converter(String filePath)](#Converter-java.lang.String-) | Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter). |
| [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter). |
| [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter). |
| [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter). |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Инициализирует новый экземпляр класса. |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Инициализирует новый экземпляр класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
| [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Преобразует исходный документ. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Преобразует исходный документ. |
| [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Преобразует исходный документ. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Преобразует исходный документ. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Преобразует исходный документ. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Преобразует исходный документ. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Преобразует исходный документ. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Преобразует исходный документ. |
| [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Преобразует исходный документ. |
| [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Преобразует исходный документ. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Преобразует исходный документ. |
| [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Преобразует исходный документ. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Преобразует исходный документ. |
| [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Преобразует исходный документ. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Преобразует исходный документ. |
| [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Преобразует исходный документ. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Преобразует исходный документ. |
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
| [getDocumentInfo()](#getDocumentInfo--) | Получает информацию об исходном документе — количество страниц и другие свойства документа, специфичные для типа файла. |
| [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Проверяет, защищён ли исходный документ паролем. |
| [getPossibleConversions()](#getPossibleConversions--) | Получает возможные конвертации для исходного документа. |
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Получает все поддерживаемые конвертации **Узнать больше**Подробнее о поддерживаемых конвертациях: [Полный список поддерживаемых конвертаций][]Подробнее о доступных конвертациях: [Как получить поддерживаемые конвертации в коде][] |


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Получает поддерживаемые конвертации для указанного расширения документа Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**Узнать больше**Подробнее о поддерживаемых конвертациях: [Полный список поддерживаемых конвертаций][]Подробнее о доступных конвертациях: [Как получить поддерживаемые конвертации в коде][] |


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
| [dispose()](#dispose--) | Освобождает ресурсы. |
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Инициализирует новый экземпляр класса для настройки конвертации в стиле fluent.  Пример использования fluent конвертации: `var converter = new Converter();` `converter .Load(\"\") .ConvertTo(\"\") .Convert();` `converter .WithSettings(() => new ConverterSettings()) .Load(\"\").WithOptions(new PdfLoadOptions()) .ConvertTo(\"\").WithOptions(new PdfConvertOptions()) .OnConversionCompleted(convertedDocumentStream => { }) .Convert();` `converter .Load(\"\").WithOptions(new PdfLoadOptions()) .ConvertByPageTo((number => new FileStream(\"\", FileMode.Create))).WithOptions(new PdfConvertOptions()) .OnConversionCompleted((number, stream) => {}) .Convert();` `converter.Load(\"\").GetPossibleConversions(); converter.Load(\"\").GetDocumentInfo(); converter.Load(\"\").WithOptions(new PdfLoadOptions()).GetPossibleConversions(); converter.Load(\"\").WithOptions(new PdfLoadOptions()).GetDocumentInfo();`

### Converter(Supplier<InputStream> document) {#Converter-java.util.function.Supplier-java.io.InputStream--}
```
public Converter(Supplier<InputStream> document)
```


Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter).

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | java.util.function.Supplier<java.io.InputStream> | поставщик входного потока. |

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter).

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | java.util.function.Supplier<java.io.InputStream> | Поставщик входного потока. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Поставщик настроек конвертера. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter).

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | java.util.function.Supplier<java.io.InputStream> | Поставщик входного потока. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Поставщик параметров загрузки. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter).

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | java.util.function.Supplier<java.io.InputStream> | Поставщик входного потока. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Поставщик параметров загрузки документа. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Поставщик настроек конвертера. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Инициализирует новый экземпляр класса.**Узнать больше**Подробнее о том, как загружать и конвертировать документы, хранящиеся на FTP, Amazon S3 Storage, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников][]Подробнее о параметрах загрузки документов, зависящих от типа файла: [Параметры загрузки для разных типов документов][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | java.util.function.Supplier<java.io.InputStream> | Поставщик входного потока. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Функция, возвращающая параметры загрузки документа. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


Инициализирует новый экземпляр класса.**Узнать больше**Подробнее о том, как загружать и конвертировать документы, хранящиеся на FTP, Amazon S3 Storage, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников][]Подробнее о параметрах загрузки документов, зависящих от типа файла: [Параметры загрузки для разных типов документов][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | java.util.function.Supplier<java.io.InputStream> | Поставщик, возвращающий читаемый поток. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Функция, возвращающая параметры загрузки документа. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Поставщик настроек конвертера. |

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter).

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу исходного документа. |

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter).

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу исходного документа. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Поставщик настроек конвертера. |

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter).

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу исходного документа. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Поставщик параметров загрузки. |

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Инициализирует новый экземпляр класса [Converter](../../com.groupdocs.conversion/converter).

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу исходного документа. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Поставщик параметров загрузки документа. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Поставщик настроек конвертера. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Инициализирует новый экземпляр класса.**Узнать больше**Подробнее о том, как загружать и конвертировать документы, хранящиеся на FTP, Amazon S3 Storage, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников][]Подробнее о параметрах загрузки документов, зависящих от типа файла: [Параметры загрузки для разных типов документов][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу исходного документа. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Функция параметров загрузки документа. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


Инициализирует новый экземпляр класса.**Узнать больше**Подробнее о том, как загружать и конвертировать документы, хранящиеся на FTP, Amazon S3 Storage, Windows Azure или любом другом стороннем хранилище: [Загрузка документа из разных источников][]Подробнее о параметрах загрузки документов, зависящих от типа файла: [Параметры загрузки для разных типов документов][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу исходного документа. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Функция параметров загрузки документа. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Поставщик настроек конвертера. |

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vendor | java.lang.String |  |
| version | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Конвертирует исходный документ. Сохраняет весь преобразованный документ.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Поставщик выходного потока. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Параметры конвертации, специфичные для требуемого типа целевого файла. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Конвертирует исходный документ. Сохраняет весь преобразованный документ. **Узнать больше**Подробнее о базовых сценариях конвертации документов: [Как конвертировать документ в 3 шага][]Случаи использования конвертации, расширенные настройки и кастомизация: [Конвертировать документ с расширенными настройками][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | поставщик выходного потока |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | делегат, получающий поток преобразованного документа. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | параметры конвертации, специфичные для требуемого типа целевого файла. |

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Преобразует исходный документ. Сохраняет полностью преобразованный документ.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Поставщик выходного потока. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Поставщик параметров конвертации. Будет вызываться для каждой конвертации, чтобы предоставить конкретные параметры конвертации для требуемого типа целевого документа. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Преобразует исходный документ. Сохраняет полностью преобразованный документ.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Поставщик выходного потока. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Делегат, получающий поток преобразованного документа. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Поставщик параметров конвертации. Будет вызываться для каждой конвертации, чтобы предоставить конкретные параметры конвертации для требуемого типа целевого документа. |

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Преобразует исходный документ. Сохраняет полностью преобразованный документ.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Функция вывода потока. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Параметры конвертации, специфичные для требуемого типа целевого файла. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Преобразует исходный документ. Сохраняет полностью преобразованный документ.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Функция вывода потока |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Делегат, получающий поток преобразованного документа |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Параметры конвертации, специфичные для требуемого типа целевого файла |

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Преобразует исходный документ. Сохраняет полностью преобразованный документ.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Функция вывода потока. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Поставщик параметров конвертации. Будет вызываться для каждой конвертации, чтобы предоставить конкретные параметры конвертации для требуемого типа целевого документа. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Преобразует исходный документ. Сохраняет полностью преобразованный документ.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Функция вывода потока. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Делегат, получающий поток преобразованного документа. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Поставщик параметров конвертации. Будет вызываться для каждой конвертации, чтобы предоставить конкретные параметры конвертации для требуемого типа целевого документа. |

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Конвертирует исходный документ. Сохраняет весь преобразованный документ.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу исходного документа. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Параметры конвертации, специфичные для требуемого типа целевого файла. |

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Преобразует исходный документ. Сохраняет преобразованный документ постранично.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Функция вывода потока страницы. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Параметры конвертации, специфичные для требуемого типа целевого файла. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Преобразует исходный документ. Сохраняет преобразованный документ постранично. **Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Функция вывода потока. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Делегат, получающий поток страницы преобразованного документа. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Параметры конвертации, специфичные для требуемого типа целевого файла. |

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Преобразует исходный документ. Сохраняет преобразованный документ постранично.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Функция вывода потока. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Поставщик параметров конвертации. Будет вызываться для каждой конвертации, чтобы предоставить конкретные параметры конвертации для требуемого типа целевого документа. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Преобразует исходный документ. Сохраняет преобразованный документ постранично.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Функция вывода потока. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Делегат, получающий поток страницы преобразованного документа. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Поставщик параметров конвертации. Будет вызываться для каждой конвертации, чтобы предоставить конкретные параметры конвертации для требуемого типа целевого документа. |

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Преобразует исходный документ. Сохраняет преобразованный документ постранично.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Функция вывода потока. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Параметры конвертации, специфичные для требуемого типа целевого файла. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Преобразует исходный документ. Сохраняет преобразованный документ постранично.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Функция вывода потока. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Делегат, получающий поток страницы преобразованного документа. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Параметры конвертации, специфичные для требуемого типа целевого файла. |

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Преобразует исходный документ. Сохраняет преобразованный документ постранично.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Функция вывода потока. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Поставщик параметров конвертации. Будет вызываться для каждой конвертации, чтобы предоставить конкретные параметры конвертации для требуемого типа целевого документа. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Преобразует исходный документ. Сохраняет преобразованный документ постранично.**Learn more**Больше о базовых сценариях конвертации документов: [How to convert document in 3 steps][]Сценарии использования конвертации, расширенные настройки и кастомизация: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Функция вывода потока. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Делегат, получающий поток страницы преобразованного документа. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Поставщик параметров конвертации. Будет вызываться для каждой конвертации, чтобы предоставить конкретные параметры конвертации для требуемого типа целевого документа. |

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Получает информацию об исходном документе — количество страниц и другие свойства документа, специфичные для типа файла.

**Learn more**Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info][]


[How to get document info]: https://docs.groupdocs.com/display/conversionnet/Get+document+info

**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info
### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Проверяет, защищён ли исходный документ паролем.

**Returns:**
boolean — true, если документ защищён паролем **Learn more**Узнайте больше о преобразованном документе — тип файла, количество страниц, дата создания и многие другие свойства, специфичные для формата: [How to check is the document password protected][]


[How to check is the document password protected]: https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected
### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Получает возможные конвертации для исходного документа.

**Learn more**Learn more about supported conversions: [Full list of supported conversions][]Learn more about available conversions: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Получает все поддерживаемые конвертации **Узнать больше**Подробнее о поддерживаемых конвертациях: [Полный список поддерживаемых конвертаций][]Подробнее о доступных конвертациях: [Как получить поддерживаемые конвертации в коде][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> — поддерживаемые конверсии
### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Получает поддерживаемые конвертации для указанного расширения документа Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**Узнать больше**Подробнее о поддерживаемых конвертациях: [Полный список поддерживаемых конвертаций][]Подробнее о доступных конвертациях: [Как получить поддерживаемые конвертации в коде][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | java.lang.String | Расширение документа |

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает ресурсы.

### close() {#close--}
```
public void close()
```




