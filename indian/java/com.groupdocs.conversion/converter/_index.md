---
title: "कनवर्टर"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "डॉक्यूमेंट कन्वर्ज़न प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

डॉक्यूमेंट कन्वर्ज़न प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Converter()](#Converter--) | फ़्लुएंट कनवर्ज़न सेटअप के लिए क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(String filePath)](#Converter-java.lang.String-) | क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) |  |
|  | [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
|  | [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | स्रोत दस्तावेज़ को कनवर्ट करता है। |
|
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
|  | [getDocumentInfo()](#getDocumentInfo--) | स्रोत दस्तावेज़ की जानकारी प्राप्त करता है - पृष्ठों की गिनती और फ़ाइल प्रकार के विशिष्ट अन्य दस्तावेज़ गुण। |
|
|  | [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | जाँचता है कि स्रोत दस्तावेज़ पासवर्ड से सुरक्षित है या नहीं। |
|
|  | [getPossibleConversions()](#getPossibleConversions--) | स्रोत दस्तावेज़ के लिए संभावित रूपांतरण प्राप्त करता है। |
|
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | सभी समर्थित रूपांतरण प्राप्त करता है **Learn more** समर्थित रूपांतरणों के बारे में अधिक जानें: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) उपलब्ध रूपांतरणों के बारे में अधिक जानें: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | प्रदान किए गए दस्तावेज़ एक्सटेंशन के लिए समर्थित रूपांतरण प्राप्त करता है Converter.GetPossibleConversions(\".docx\") Converter.GetPossibleConversions(\"docx\") **Learn more** समर्थित रूपांतरणों के बारे में अधिक जानें: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) उपलब्ध रूपांतरणों के बारे में अधिक जानें: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [dispose()](#dispose--) | संसाधनों को रिलीज़ करता है। |
|
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


फ़्लुएंट कनवर्ज़न सेटअप के लिए क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। फ़्लुएंट कनवर्ज़न उपयोग का उदाहरण: `
var converter = new Converter();
` `
converter
`
.Load(\"\")`
`
.ConvertTo(\"\")`
`
.Convert();
` `
converter
`
.WithSettings(() => new ConverterSettings())`
`
.Load(\"\").WithOptions(new PdfLoadOptions())`
`
.ConvertTo(\"\").WithOptions(new PdfConvertOptions())`
`
.OnConversionCompleted(convertedDocumentStream => { })`
`
.Convert();
` `
converter
`
.Load(\"\").WithOptions(new PdfLoadOptions())`
`
.ConvertByPageTo((number => new FileStream(\"\", FileMode.Create))).WithOptions(new PdfConvertOptions())`
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


क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है।


**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.util.function.Supplier<java.io.InputStream> | इनपुट स्ट्रीम सप्लायर। |
|

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है।
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.util.function.Supplier<java.io.InputStream> | एक इनपुट स्ट्रीम सप्लायर। |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | एक Converter सेटिंग्स सप्लायर। |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है।
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.util.function.Supplier<java.io.InputStream> | एक इनपुट स्ट्रीम सप्लायर। |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | एक लोड विकल्प सप्लायर। |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है।
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.util.function.Supplier<java.io.InputStream> | एक इनपुट स्ट्रीम सप्लायर। |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | एक दस्तावेज़ लोड विकल्प सप्लायर। |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | एक Converter सेटिंग्स सप्लायर। |
|

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। **Learn more** FTP, Amazon S3 Storage, Windows Azure या किसी अन्य थर्ड-पार्टी स्टोरेज में संग्रहीत दस्तावेज़ों को लोड और कनवर्ट करने के बारे में अधिक जानकारी: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड विकल्पों के बारे में अधिक जानकारी: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.util.function.Supplier<java.io.InputStream> | एक इनपुट स्ट्रीम सप्लायर। |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | फ़ंक्शन जो दस्तावेज़ लोड विकल्प लौटाता है। |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। **Learn more** FTP, Amazon S3 Storage, Windows Azure या किसी अन्य थर्ड-पार्टी स्टोरेज में संग्रहीत दस्तावेज़ों को लोड और कनवर्ट करने के बारे में अधिक जानकारी: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड विकल्पों के बारे में अधिक जानकारी: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.util.function.Supplier<java.io.InputStream> | एक सप्लायर जो पढ़ने योग्य स्ट्रीम लौटाता है। |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | एक फ़ंक्शन जो दस्तावेज़ लोड विकल्प लौटाता है। |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। **Learn more** FTP, Amazon S3 Storage, Windows Azure या किसी अन्य थर्ड-पार्टी स्टोरेज में संग्रहीत दस्तावेज़ों को लोड और कनवर्ट करने के बारे में अधिक जानकारी: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड विकल्पों के बारे में अधिक जानकारी: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.util.function.Supplier<java.io.InputStream> | एक सप्लायर जो पढ़ने योग्य स्ट्रीम लौटाता है। |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | एक फ़ंक्शन जो दस्तावेज़ लोड विकल्प लौटाता है। |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | एक Converter सेटिंग्स सप्लायर। |
|

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है।
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का फ़ाइल पथ। |
|

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है।
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का फ़ाइल पथ। |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | एक Converter सेटिंग्स सप्लायर। |
|

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है।
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का फ़ाइल पथ। |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | लोड विकल्प सप्लायर। |
|

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


क्लास [Converter](../../com.groupdocs.conversion/converter) का नया इंस्टेंस इनिशियलाइज़ करता है।
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का फ़ाइल पथ। |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | दस्तावेज़ लोड विकल्प सप्लायर। |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Converter सेटिंग्स सप्लायर। |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। **Learn more** FTP, Amazon S3 Storage, Windows Azure या किसी अन्य थर्ड-पार्टी स्टोरेज में संग्रहीत दस्तावेज़ों को लोड और कनवर्ट करने के बारे में अधिक जानकारी: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड विकल्पों के बारे में अधिक जानकारी: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का फ़ाइल पथ। |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | दस्तावेज़ लोड विकल्प फ़ंक्शन। |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) |  |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। **Learn more** FTP, Amazon S3 Storage, Windows Azure या किसी अन्य थर्ड-पार्टी स्टोरेज में संग्रहीत दस्तावेज़ों को लोड और कनवर्ट करने के बारे में अधिक जानकारी: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) फ़ाइल प्रकार पर निर्भर दस्तावेज़ लोड विकल्पों के बारे में अधिक जानकारी: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का फ़ाइल पथ। |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | दस्तावेज़ लोड विकल्प फ़ंक्शन। |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Converter सेटिंग्स सप्लायर। |
|

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विक्रेता | java.lang.String |  |
| संस्करण | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


स्रोत दस्तावेज़ को कनवर्ट करता है। पूरे परिवर्तित दस्तावेज़ को सहेजता है।
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | आउटपुट स्ट्रीम सप्लायर। |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। पूरी रूपांतरित दस्तावेज़ को सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | आउटपुट स्ट्रीम सप्लायर |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | वह डेलीगेट जो रूपांतरित दस्तावेज़ स्ट्रीम प्राप्त करता है। |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
|

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। पूरी रूपांतरित दस्तावेज़ को सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | आउटपुट स्ट्रीम सप्लायर। |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | रूपांतरण विकल्प प्रदाता। प्रत्येक रूपांतरण के लिए कॉल किया जाएगा ताकि वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान किए जा सकें। |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। पूरी रूपांतरित दस्तावेज़ को सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | आउटपुट स्ट्रीम सप्लायर। |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | वह डेलीगेट जो रूपांतरित दस्तावेज़ स्ट्रीम प्राप्त करता है। |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | रूपांतरण विकल्प प्रदाता। प्रत्येक रूपांतरण के लिए कॉल किया जाएगा ताकि वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान किए जा सकें। |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। पूरी रूपांतरित दस्तावेज़ को सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। पूरी रूपांतरित दस्तावेज़ को सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | आउटपुट स्ट्रीम फ़ंक्शन |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | वह डेलीगेट जो रूपांतरित दस्तावेज़ स्ट्रीम प्राप्त करता है |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। पूरी रूपांतरित दस्तावेज़ को सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | रूपांतरण विकल्प प्रदाता। प्रत्येक रूपांतरण के लिए कॉल किया जाएगा ताकि वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान किए जा सकें। |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। पूरी रूपांतरित दस्तावेज़ को सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | वह डेलीगेट जो रूपांतरित दस्तावेज़ स्ट्रीम प्राप्त करता है। |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | रूपांतरण विकल्प प्रदाता। प्रत्येक रूपांतरण के लिए कॉल किया जाएगा ताकि वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान किए जा सकें। |
|

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


स्रोत दस्तावेज़ को कनवर्ट करता है। पूरे परिवर्तित दस्तावेज़ को सहेजता है।
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | स्रोत दस्तावेज़ का फ़ाइल पथ। |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
|

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है।
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | पृष्ठ आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | वह डेलीगेट जो रूपांतरित दस्तावेज़ पृष्ठ स्ट्रीम प्राप्त करता है। |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
|

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | रूपांतरण विकल्प प्रदाता। प्रत्येक रूपांतरण के लिए कॉल किया जाएगा ताकि वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान किए जा सकें। |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | वह डेलीगेट जो रूपांतरित दस्तावेज़ पृष्ठ स्ट्रीम प्राप्त करता है। |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | रूपांतरण विकल्प प्रदाता। प्रत्येक रूपांतरण के लिए कॉल किया जाएगा ताकि वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान किए जा सकें। |
|

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | एक आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | एक आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | वह डेलीगेट जो रूपांतरित दस्तावेज़ पृष्ठ स्ट्रीम प्राप्त करता है। |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | वांछित लक्ष्य फ़ाइल प्रकार के लिए विशिष्ट रूपांतरण विकल्प। |
|

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | एक आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | रूपांतरण विकल्प प्रदाता। प्रत्येक रूपांतरण के लिए कॉल किया जाएगा ताकि वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान किए जा सकें। |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


स्रोत दस्तावेज़ को रूपांतरित करता है। रूपांतरित दस्तावेज़ को पृष्ठ दर पृष्ठ सहेजता है। **Learn more** दस्तावेज़ रूपांतरण के बुनियादी परिदृश्यों के बारे में अधिक: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) रूपांतरण उपयोग मामलों, उन्नत सेटिंग्स और अनुकूलन: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | एक आउटपुट स्ट्रीम फ़ंक्शन। |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | वह डेलीगेट जो रूपांतरित दस्तावेज़ पृष्ठ स्ट्रीम प्राप्त करता है। |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | रूपांतरण विकल्प प्रदाता। प्रत्येक रूपांतरण के लिए कॉल किया जाएगा ताकि वांछित लक्ष्य दस्तावेज़ प्रकार के लिए विशिष्ट रूपांतरण विकल्प प्रदान किए जा सकें। |
|

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


स्रोत दस्तावेज़ की जानकारी प्राप्त करता है - पृष्ठों की गिनती और फ़ाइल प्रकार के विशिष्ट अन्य दस्तावेज़ गुण।
**Learn more** Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](../https://docs.groupdocs.com/display/conversionnet/Get+document+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info

### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


जाँचता है कि स्रोत दस्तावेज़ पासवर्ड से सुरक्षित है या नहीं।


**Returns:**
boolean - true यदि दस्तावेज़ पासवर्ड संरक्षित है **Learn more** रूपांतरित दस्तावेज़ के बारे में अधिक - फ़ाइल प्रकार, पृष्ठों की संख्या, निर्माण तिथि और कई अन्य फ़ॉर्मेट-विशिष्ट गुण: [How to check is the document password protected](../https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected)

### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


स्रोत दस्तावेज़ के लिए संभावित रूपांतरण प्राप्त करता है।
**Learn more** Learn more about supported conversions: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Learn more about available conversions: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


सभी समर्थित रूपांतरण प्राप्त करता है **Learn more** समर्थित रूपांतरणों के बारे में अधिक जानें: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) उपलब्ध रूपांतरणों के बारे में अधिक जानें: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - समर्थित रूपांतरण

### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


प्रदान किए गए दस्तावेज़ एक्सटेंशन के लिए समर्थित रूपांतरण प्राप्त करता है Converter.GetPossibleConversions(\".docx\") Converter.GetPossibleConversions(\"docx\") **Learn more** समर्थित रूपांतरणों के बारे में अधिक जानें: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) उपलब्ध रूपांतरणों के बारे में अधिक जानें: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | extension | java.lang.String | दस्तावेज़ विस्तार |
|

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### dispose() {#dispose--}
```
public final void dispose()
```


संसाधनों को रिलीज़ करता है।


### close() {#close--}
```
public void close()
```




