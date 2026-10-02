---
title: "Converter"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية تحويل المستند."
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

يمثل الفئة الرئيسية التي تتحكم في عملية تحويل المستند.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Converter()](#Converter--) | يقوم بإنشاء مثيل جديد للفئة لإعداد التحويل السلس. |
|
|  | [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة. |
|
|  | [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | يقوم بإنشاء مثيل جديد للفئة. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | يقوم بإنشاء مثيل جديد للفئة. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | يقوم بإنشاء مثيل جديد للفئة. |
|
|  | [Converter(String filePath)](#Converter-java.lang.String-) | يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة. |
|
|  | [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة. |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة. |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة. |
|
|  | [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | يقوم بإنشاء مثيل جديد للفئة. |
|
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) |  |
|  | [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | يقوم بإنشاء مثيل جديد للفئة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
|  | [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | يقوم بتحويل المستند المصدر. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | يقوم بتحويل المستند المصدر. |
|
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
|  | [getDocumentInfo()](#getDocumentInfo--) | يحصل على معلومات المستند المصدر - عدد الصفحات وغيرها من خصائص المستند المحددة لنوع الملف. |
|
|  | [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | يتحقق مما إذا كان المستند المصدر محميًا بكلمة مرور. |
|
|  | [getPossibleConversions()](#getPossibleConversions--) | يحصل على التحويلات الممكنة للمستند المصدر. |
|
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | يحصل على جميع التحويلات المدعومة **اعرف المزيد** اعرف المزيد حول التحويلات المدعومة: [القائمة الكاملة للتحويلات المدعومة](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) اعرف المزيد حول التحويلات المتاحة: [كيفية الحصول على التحويلات المدعومة في الكود](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | يحصل على التحويلات المدعومة للامتداد المستند المقدم Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **اعرف المزيد** اعرف المزيد حول التحويلات المدعومة: [القائمة الكاملة للتحويلات المدعومة](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) اعرف المزيد حول التحويلات المتاحة: [كيفية الحصول على التحويلات المدعومة في الكود](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [dispose()](#dispose--) | يطلق الموارد. |
|
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


يقوم بإنشاء مثيل جديد للفئة لإعداد التحويل السلس. مثال على استخدام التحويل السلس: `
var converter = new Converter();
` `
converter
`
.Load("")`
`
.ConvertTo("")`
`
.Convert();
` `
converter
`
.WithSettings(() => new ConverterSettings())`
`
.Load("").WithOptions(new PdfLoadOptions())`
`
.ConvertTo("").WithOptions(new PdfConvertOptions())`
`
.OnConversionCompleted(convertedDocumentStream => { })`
`
.Convert();
` `
converter
`
.Load("").WithOptions(new PdfLoadOptions())`
`
.ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())`
`
.OnConversionCompleted((number, stream) => {})`
`
.Convert();
` `
converter.Load("").GetPossibleConversions();`
`
converter.Load("").GetDocumentInfo();`
`
converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();`
`
converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();`
`
`


### Converter(Supplier<InputStream> document) {#Converter-java.util.function.Supplier-java.io.InputStream--}
```
public Converter(Supplier<InputStream> document)
```


يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة.


**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.util.function.Supplier<java.io.InputStream> | مورد تدفق الإدخال. |
|

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.util.function.Supplier<java.io.InputStream> | مورد تدفق الإدخال. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | مورد إعدادات المحول. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.util.function.Supplier<java.io.InputStream> | مورد تدفق الإدخال. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | مورد خيارات التحميل. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.util.function.Supplier<java.io.InputStream> | مورد تدفق الإدخال. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | مورد خيارات تحميل المستند. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | مورد إعدادات المحول. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


يُنشئ مثيلًا جديدًا من الفئة. **Learn more** المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP، Amazon S3 Storage، Windows Azure أو أي تخزين طرف ثالث آخر: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) المزيد حول خيارات تحميل المستندات اعتمادًا على نوع الملف: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.util.function.Supplier<java.io.InputStream> | مورد تدفق الإدخال. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | الدالة التي تُعيد خيارات تحميل المستند. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


يُنشئ مثيلًا جديدًا من الفئة. **Learn more** المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP، Amazon S3 Storage، Windows Azure أو أي تخزين طرف ثالث آخر: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) المزيد حول خيارات تحميل المستندات اعتمادًا على نوع الملف: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.util.function.Supplier<java.io.InputStream> | مورد يُعيد تدفقًا قابلاً للقراءة. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | دالة تُعيد خيارات تحميل المستند. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


يُنشئ مثيلًا جديدًا من الفئة. **Learn more** المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP، Amazon S3 Storage، Windows Azure أو أي تخزين طرف ثالث آخر: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) المزيد حول خيارات تحميل المستندات اعتمادًا على نوع الملف: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.util.function.Supplier<java.io.InputStream> | مورد يُعيد تدفقًا قابلاً للقراءة. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | دالة تُعيد خيارات تحميل المستند. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | مورد إعدادات المحول. |
|

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسار الملف | java.lang.String | مسار الملف إلى المستند المصدر. |
|

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسار الملف | java.lang.String | مسار الملف إلى المستند المصدر. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | مورد إعدادات المحول. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسار الملف | java.lang.String | مسار الملف إلى المستند المصدر. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | مورد خيارات التحميل. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


يقوم بإنشاء مثيل جديد لـ [Converter](../../com.groupdocs.conversion/converter) الفئة.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسار الملف | java.lang.String | مسار الملف إلى المستند المصدر. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | مورد خيارات تحميل المستند. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | مورد إعدادات المحول. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


يُنشئ مثيلًا جديدًا من الفئة. **Learn more** المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP، Amazon S3 Storage، Windows Azure أو أي تخزين طرف ثالث آخر: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) المزيد حول خيارات تحميل المستندات اعتمادًا على نوع الملف: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسار الملف | java.lang.String | مسار الملف إلى المستند المصدر. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | دالة خيارات تحميل المستند. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مسار الملف | java.lang.String |  |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) |  |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مسار الملف | java.lang.String |  |
| loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


يُنشئ مثيلًا جديدًا من الفئة. **Learn more** المزيد حول كيفية تحميل وتحويل المستندات المخزنة في FTP، Amazon S3 Storage، Windows Azure أو أي تخزين طرف ثالث آخر: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) المزيد حول خيارات تحميل المستندات اعتمادًا على نوع الملف: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسار الملف | java.lang.String | مسار الملف إلى المستند المصدر. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | دالة خيارات تحميل المستند. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | مورد إعدادات المحول. |
|

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المورد | java.lang.String |  |
| الإصدار | java.lang.String |  |
| عنوان المواصفة | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


يحوّل المستند المصدر. يحفظ المستند المحوَّل بالكامل.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | مورد تدفق الإخراج. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | خيارات التحويل المحددة لنوع الملف الهدف المطلوب. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول بالكامل. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | مورد تدفق الإخراج |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | الوكيل الذي يتلقى تدفق المستند المحول. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | خيارات التحويل المحددة لنوع الملف الهدف المطلوب. |
|

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول بالكامل. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | مورد تدفق الإخراج. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | مزود خيارات التحويل. سيتم استدعاؤه لكل عملية تحويل لتوفير خيارات تحويل محددة لنوع المستند الهدف المطلوب. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول بالكامل. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | مورد تدفق الإخراج. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | الوكيل الذي يتلقى تدفق المستند المحول. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | مزود خيارات التحويل. سيتم استدعاؤه لكل عملية تحويل لتوفير خيارات تحويل محددة لنوع المستند الهدف المطلوب. |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول بالكامل. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | دالة تدفق الإخراج. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | خيارات التحويل المحددة لنوع الملف الهدف المطلوب. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول بالكامل. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | دالة تدفق الإخراج |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | الوكيل الذي يتلقى تدفق المستند المحول |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | خيارات التحويل المحددة لنوع الملف الهدف المطلوب |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول بالكامل. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | دالة تدفق الإخراج. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | مزود خيارات التحويل. سيتم استدعاؤه لكل عملية تحويل لتوفير خيارات تحويل محددة لنوع المستند الهدف المطلوب. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول بالكامل. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | دالة تدفق الإخراج. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | الوكيل الذي يتلقى تدفق المستند المحول. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | مزود خيارات التحويل. سيتم استدعاؤه لكل عملية تحويل لتوفير خيارات تحويل محددة لنوع المستند الهدف المطلوب. |
|

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


يحوّل المستند المصدر. يحفظ المستند المحوَّل بالكامل.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسار الملف | java.lang.String | مسار الملف إلى المستند المصدر. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | خيارات التحويل المحددة لنوع الملف الهدف المطلوب. |
|

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول صفحة بصفحة.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | دالة تدفق إخراج الصفحة. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | خيارات التحويل المحددة لنوع الملف الهدف المطلوب. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول صفحة بصفحة. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | دالة تدفق الإخراج. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | الوكيل الذي يتلقى تدفق صفحة المستند المحول. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | خيارات التحويل المحددة لنوع الملف الهدف المطلوب. |
|

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول صفحة بصفحة. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | دالة تدفق الإخراج. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | مزود خيارات التحويل. سيتم استدعاؤه لكل عملية تحويل لتوفير خيارات تحويل محددة لنوع المستند الهدف المطلوب. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول صفحة بصفحة. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | دالة تدفق الإخراج. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | الوكيل الذي يتلقى تدفق صفحة المستند المحول. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | مزود خيارات التحويل. سيتم استدعاؤه لكل عملية تحويل لتوفير خيارات تحويل محددة لنوع المستند الهدف المطلوب. |
|

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول صفحة بصفحة. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | دالة تدفق إخراج. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | خيارات التحويل المحددة لنوع الملف الهدف المطلوب. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول صفحة بصفحة. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | دالة تدفق إخراج. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | الوكيل الذي يتلقى تدفق صفحة المستند المحول. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | خيارات التحويل المحددة لنوع الملف الهدف المطلوب. |
|

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول صفحة بصفحة. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | دالة تدفق إخراج. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | مزود خيارات التحويل. سيتم استدعاؤه لكل عملية تحويل لتوفير خيارات تحويل محددة لنوع المستند الهدف المطلوب. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


يقوم بتحويل المستند المصدر. يحفظ المستند المحول صفحة بصفحة. **Learn more** المزيد حول سيناريوهات تحويل المستند الأساسية: [كيفية تحويل المستند في 3 خطوات](../https://docs.groupdocs.com/display/conversionnet/Convert+document) حالات الاستخدام للتحويل، الإعدادات المتقدمة والتخصيصات: [تحويل المستند بإعدادات متقدمة](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | دالة تدفق إخراج. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | الوكيل الذي يتلقى تدفق صفحة المستند المحول. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | مزود خيارات التحويل. سيتم استدعاؤه لكل عملية تحويل لتوفير خيارات تحويل محددة لنوع المستند الهدف المطلوب. |
|

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


يحصل على معلومات المستند المصدر - عدد الصفحات وغيرها من خصائص المستند المحددة لنوع الملف.
**Learn more** Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](../https://docs.groupdocs.com/display/conversionnet/Get+document+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info

### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


يتحقق مما إذا كان المستند المصدر محميًا بكلمة مرور.


**Returns:**
boolean - true إذا كان المستند محميًا بكلمة مرور **Learn more** المزيد حول المستند المحول - نوع الملف، عدد الصفحات، تاريخ الإنشاء والعديد من الخصائص الخاصة بالتنسيق: [كيفية التحقق مما إذا كان المستند محميًا بكلمة مرور](../https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected)

### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


يحصل على التحويلات الممكنة للمستند المصدر.
**Learn more** Learn more about supported conversions: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Learn more about available conversions: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


يحصل على جميع التحويلات المدعومة **اعرف المزيد** اعرف المزيد حول التحويلات المدعومة: [القائمة الكاملة للتحويلات المدعومة](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) اعرف المزيد حول التحويلات المتاحة: [كيفية الحصول على التحويلات المدعومة في الكود](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - التحويلات المدعومة

### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


يحصل على التحويلات المدعومة للامتداد المستند المقدم Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **اعرف المزيد** اعرف المزيد حول التحويلات المدعومة: [القائمة الكاملة للتحويلات المدعومة](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) اعرف المزيد حول التحويلات المتاحة: [كيفية الحصول على التحويلات المدعومة في الكود](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | امتداد | java.lang.String | امتداد المستند |
|

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### dispose() {#dispose--}
```
public final void dispose()
```


يطلق الموارد.


### close() {#close--}
```
public void close()
```




