---
title: Converter
second_title: GroupDocs.Conversion for Java API Reference
description: Represents main class that controls document conversion process.
type: docs
weight: 10
url: /java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Represents main class that controls document conversion process.
## Constructors

| Constructor | Description |
| --- | --- |
| [Converter()](#Converter--) | Initializes new instance of  class for fluent conversion setup. |
| [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class. |
| [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class. |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class. |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class. |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initializes new instance of  class. |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initializes new instance of  class. |
| [Converter(String filePath)](#Converter-java.lang.String-) | Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class. |
| [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class. |
| [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class. |
| [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class. |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initializes new instance of  class. |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initializes new instance of  class. |
## Methods

| Method | Description |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
| [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converts source document. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converts source document. |
| [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converts source document. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converts source document. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converts source document. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converts source document. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converts source document. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converts source document. |
| [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converts source document. |
| [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converts source document. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converts source document. |
| [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converts source document. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converts source document. |
| [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converts source document. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converts source document. |
| [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converts source document. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converts source document. |
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
| [getDocumentInfo()](#getDocumentInfo--) | Gets source document info - pages count and other document properties specific to the file type. |
| [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Checks is source document is password protected |
| [getPossibleConversions()](#getPossibleConversions--) | Gets possible conversions for the source document. |
| [getAllPossibleConversions()](#getAllPossibleConversions--) | Gets all supported conversions **Learn more**Learn more about supported conversions: [Full list of supported conversions][]Learn more about available conversions: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
| [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Gets supported conversions for provided document extension Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**Learn more**Learn more about supported conversions: [Full list of supported conversions][]Learn more about available conversions: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
| [dispose()](#dispose--) | Releases resources. |
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Initializes new instance of  class for fluent conversion setup.  Sample fluent conversion usage: `var converter = new Converter();` `converter .Load("") .ConvertTo("") .Convert();` `converter .WithSettings(() => new ConverterSettings()) .Load("").WithOptions(new PdfLoadOptions()) .ConvertTo("").WithOptions(new PdfConvertOptions()) .OnConversionCompleted(convertedDocumentStream => { }) .Convert();` `converter .Load("").WithOptions(new PdfLoadOptions()) .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions()) .OnConversionCompleted((number, stream) => {}) .Convert();` `converter.Load("").GetPossibleConversions(); converter.Load("").GetDocumentInfo(); converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions(); converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();`

### Converter(Supplier<InputStream> document) {#Converter-java.util.function.Supplier-java.io.InputStream--}
```
public Converter(Supplier<InputStream> document)
```


Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | input stream supplier. |

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | A Converter settings supplier. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | A load options supplier. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | A document load options supplier. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | A Converter settings supplier. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Initializes new instance of  class.**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | An input stream supplier. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | The function that return document load options. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


Initializes new instance of  class.**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.util.function.Supplier<java.io.InputStream> | A supplier that returns readable stream. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | A function that returns document load options. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | A Converter settings supplier. |

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to the source document. |

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to the source document. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | A Converter settings supplier. |

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to the source document. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | The load options supplier. |

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initializes new instance of [Converter](../../com.groupdocs.conversion/converter) class.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to the source document. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | The document load options supplier. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | The Converter settings supplier. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Initializes new instance of  class.**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to the source document. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | The document load options function. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


Initializes new instance of  class.**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to the source document. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | The document load options function. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | The Converter settings supplier. |

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vendor | java.lang.String |  |
| version | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Converts source document. Saves the whole converted document.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | The output stream supplier. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Converts source document. Saves the whole converted document. **Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | output stream supplier |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | the delegate that receive converted document stream. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | the convert options specific to desired target file type. |

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Converts source document. Saves the whole converted document.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | The output stream supplier. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converts source document. Saves the whole converted document.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | The output stream supplier. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | The delegate that receive converted document stream. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Converts source document. Saves the whole converted document.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Output stream function. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Converts source document. Saves the whole converted document.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Output stream function |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | The delegate that receive converted document stream |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type |

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Converts source document. Saves the whole converted document.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Output stream function. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converts source document. Saves the whole converted document.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Output stream function. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | The delegate that receive converted document stream. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Converts source document. Saves the whole converted document.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to the source document. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Converts source document. Saves the converted document page by page.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | The page output stream function. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Converts source document. Saves the converted document page by page. **Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | The output stream function. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | The delegate that receive converted document page stream. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Converts source document. Saves the converted document page by page.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | The output stream function. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converts source document. Saves the converted document page by page.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Output stream function. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | The delegate that receive converted document page stream. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Converts source document. Saves the converted document page by page.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | An output stream function. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Converts source document. Saves the converted document page by page.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | An output stream function. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | The delegate that receive converted document page stream. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Converts source document. Saves the converted document page by page.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | An output stream function. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converts source document. Saves the converted document page by page.**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | An output stream function. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | The delegate that receive converted document page stream. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider. Will be called for each conversion to provide specific convert options to desired target document type. |

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gets source document info - pages count and other document properties specific to the file type.

**Learn more**Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info][]


[How to get document info]: https://docs.groupdocs.com/display/conversionnet/Get+document+info

**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info
### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Checks is source document is password protected

**Returns:**
boolean - true if document is password protected **Learn more**Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to check is the document password protected][]


[How to check is the document password protected]: https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected
### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Gets possible conversions for the source document.

**Learn more**Learn more about supported conversions: [Full list of supported conversions][]Learn more about available conversions: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Gets all supported conversions **Learn more**Learn more about supported conversions: [Full list of supported conversions][]Learn more about available conversions: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - supported conversions
### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Gets supported conversions for provided document extension Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**Learn more**Learn more about supported conversions: [Full list of supported conversions][]Learn more about available conversions: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | Document extension |

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### dispose() {#dispose--}
```
public final void dispose()
```


Releases resources.

### close() {#close--}
```
public void close()
```




