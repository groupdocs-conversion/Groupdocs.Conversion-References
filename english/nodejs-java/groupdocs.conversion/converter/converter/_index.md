---
title: Converter
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: 
type: docs

url: /groupdocs.conversion/converter/converter/
---

## createConverterFromStream (ReadStream document, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, [ConverterSettings](../../convertersettings) settings, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, [LoadOptions](../../loadoptions) loadOptions, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, [LoadOptions](../../loadoptions) loadOptions, [ConverterSettings](../../convertersettings) settings, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, com.groupdocs.conversion.contracts.Func1<com.groupdocs.conversion.filetypes.FileType, com.groupdocs.conversion.options.load.LoadOptions> loadOptions, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, com.groupdocs.conversion.contracts.Func1<com.groupdocs.conversion.filetypes.FileType, com.groupdocs.conversion.options.load.LoadOptions> loadOptions, [ConverterSettings](../../convertersettings) settings, Function callback) function


### Result
Converter


---


## Converter() function
Initializes new instance of  class for fluent conversion setup.
 
 Sample fluent conversion usage:
 
 var converter = new Converter();
 
 
 converter
 .Load("")
 .ConvertTo("")
 .Convert();
 
 
 converter
 .WithSettings(() => new ConverterSettings())
 .Load("").WithOptions(new PdfLoadOptions())
 .ConvertTo("").WithOptions(new PdfConvertOptions())
 .OnConversionCompleted(convertedDocumentStream => { })
 .Convert();
 
 
 converter
 .Load("").WithOptions(new PdfLoadOptions())
 .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
 .OnConversionCompleted((number, stream) => {})
 .Convert();
 
 
 converter.Load("").GetPossibleConversions();
 converter.Load("").GetDocumentInfo();
 converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
 converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
 

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document) function

 Initializes new instance of  Converter class.
 
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | input stream supplier. |

### Result
Converter

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | Thrown when {@code document} is null. |


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  Converter class.
 

 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | A Converter settings supplier. |

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, LoadOptionsProvider loadOptions) function

 Initializes new instance of  Converter class.
 

 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| loadOptions | LoadOptionsProvider | A load options supplier. |

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, LoadOptionsProvider loadOptions, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  Converter class.
 

 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| loadOptions | LoadOptionsProvider | A document load options supplier. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | A Converter settings supplier. |

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, LoadOptionsForFileTypeProvider loadOptions) function
Initializes new instance of  class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| loadOptions | LoadOptionsForFileTypeProvider | The function that return document load options. |

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, LoadOptionsForFileTypeProvider loadOptions, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function
Initializes new instance of  class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | A supplier that returns readable stream. |
| loadOptions | LoadOptionsForFileTypeProvider | A function that returns document load options. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | A Converter settings supplier. |

### Result
Converter


---


## Converter(String filePath) function

 Initializes new instance of  Converter class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |

### Result
Converter


---


## Converter(String filePath, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  Converter class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | A Converter settings supplier. |

### Result
Converter


---


## Converter(String filePath, [ConverterSettings](../../convertersettings) settings) function


### Result
Converter


---


## Converter(String filePath, LoadOptionsProvider loadOptions) function

 Initializes new instance of  Converter class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | LoadOptionsProvider | The load options supplier. |

### Result
Converter


---


## Converter(String filePath, [LoadOptions](../../loadoptions) loadOptions) function


### Result
Converter


---


## Converter(String filePath, LoadOptionsProvider loadOptions, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  Converter class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | LoadOptionsProvider | The document load options supplier. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | The Converter settings supplier. |

### Result
Converter


---


## Converter(String filePath, [LoadOptions](../../loadoptions) loadOptions, [ConverterSettings](../../convertersettings) settings) function


### Result
Converter


---


## Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) function

 Initializes new instance of  class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | LoadOptionsForFileTypeProvider | The document load options function. |

### Result
Converter


---


## Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | LoadOptionsForFileTypeProvider | The document load options function. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | The Converter settings supplier. |

### Result
Converter


---


## createConverterFromStream (ReadStream document, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, [ConverterSettings](../../convertersettings) settings, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, [LoadOptions](../../loadoptions) loadOptions, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, [LoadOptions](../../loadoptions) loadOptions, [ConverterSettings](../../convertersettings) settings, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, com.groupdocs.conversion.contracts.Func1<com.groupdocs.conversion.filetypes.FileType, com.groupdocs.conversion.options.load.LoadOptions> loadOptions, Function callback) function


### Result
Converter


---


## createConverterFromStream (ReadStream document, com.groupdocs.conversion.contracts.Func1<com.groupdocs.conversion.filetypes.FileType, com.groupdocs.conversion.options.load.LoadOptions> loadOptions, [ConverterSettings](../../convertersettings) settings, Function callback) function


### Result
Converter


---


## Converter() function
Initializes new instance of  class for fluent conversion setup.
 
 Sample fluent conversion usage:
 
 var converter = new Converter();
 
 
 converter
 .Load("")
 .ConvertTo("")
 .Convert();
 
 
 converter
 .WithSettings(() => new ConverterSettings())
 .Load("").WithOptions(new PdfLoadOptions())
 .ConvertTo("").WithOptions(new PdfConvertOptions())
 .OnConversionCompleted(convertedDocumentStream => { })
 .Convert();
 
 
 converter
 .Load("").WithOptions(new PdfLoadOptions())
 .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
 .OnConversionCompleted((number, stream) => {})
 .Convert();
 
 
 converter.Load("").GetPossibleConversions();
 converter.Load("").GetDocumentInfo();
 converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
 converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
 

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document) function

 Initializes new instance of  Converter class.
 
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | input stream supplier. |

### Result
Converter

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | Thrown when {@code document} is null. |


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  Converter class.
 

 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | A Converter settings supplier. |

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, LoadOptionsProvider loadOptions) function

 Initializes new instance of  Converter class.
 

 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| loadOptions | LoadOptionsProvider | A load options supplier. |

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, LoadOptionsProvider loadOptions, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  Converter class.
 

 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| loadOptions | LoadOptionsProvider | A document load options supplier. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | A Converter settings supplier. |

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, LoadOptionsForFileTypeProvider loadOptions) function
Initializes new instance of  class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| loadOptions | LoadOptionsForFileTypeProvider | The function that return document load options. |

### Result
Converter


---


## Converter(java.util.function.Supplier<java.io.InputStream> document, LoadOptionsForFileTypeProvider loadOptions, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function
Initializes new instance of  class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | A supplier that returns readable stream. |
| loadOptions | LoadOptionsForFileTypeProvider | A function that returns document load options. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | A Converter settings supplier. |

### Result
Converter


---


## Converter(String filePath) function

 Initializes new instance of  Converter class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |

### Result
Converter


---


## Converter(String filePath, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  Converter class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | A Converter settings supplier. |

### Result
Converter


---


## Converter(String filePath, [ConverterSettings](../../convertersettings) settings) function


### Result
Converter


---


## Converter(String filePath, LoadOptionsProvider loadOptions) function

 Initializes new instance of  Converter class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | LoadOptionsProvider | The load options supplier. |

### Result
Converter


---


## Converter(String filePath, [LoadOptions](../../loadoptions) loadOptions) function


### Result
Converter


---


## Converter(String filePath, LoadOptionsProvider loadOptions, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  Converter class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | LoadOptionsProvider | The document load options supplier. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | The Converter settings supplier. |

### Result
Converter


---


## Converter(String filePath, [LoadOptions](../../loadoptions) loadOptions, [ConverterSettings](../../convertersettings) settings) function


### Result
Converter


---


## Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) function

 Initializes new instance of  class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | LoadOptionsForFileTypeProvider | The document load options function. |

### Result
Converter


---


## Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, [ConverterSettingsProvider](../../convertersettingsprovider) settings) function

 Initializes new instance of  class.
 
 
 Learn more
 
 
 More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage:
 Loading document from different sources
 
 
 More about document loading options dependent on file type:
 Load options for different document types
 
 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to the source document. |
| loadOptions | LoadOptionsForFileTypeProvider | The document load options function. |
| settings | [ConverterSettingsProvider](../../convertersettingsprovider) | The Converter settings supplier. |

### Result
Converter


---


