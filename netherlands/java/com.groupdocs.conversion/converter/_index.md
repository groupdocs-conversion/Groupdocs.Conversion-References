---
title: "Converter"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Stelt de hoofdklasse voor die het documentconversieproces beheert."
type: docs
weight: 10
url: /nl/java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Stelt de hoofdklasse voor die het documentconversieproces beheert.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Converter()](#Converter--) | Initialiseert een nieuwe instantie van de klasse voor een vloeiende conversie‑configuratie. |
|
|  | [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse. |
|
|  | [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initialiseert een nieuwe instantie van de klasse. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | Initialiseert een nieuwe instantie van de klasse. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialiseert een nieuwe instantie van de klasse. |
|
|  | [Converter(String filePath)](#Converter-java.lang.String-) | Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse. |
|
|  | [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse. |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse. |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse. |
|
|  | [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initialiseert een nieuwe instantie van de klasse. |
|
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) |  |
|  | [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialiseert een nieuwe instantie van de klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
|  | [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converteert brondocument. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converteert brondocument. |
|
|  | [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converteert brondocument. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converteert brondocument. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converteert brondocument. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converteert brondocument. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converteert brondocument. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converteert brondocument. |
|
|  | [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converteert brondocument. |
|
|  | [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converteert brondocument. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converteert brondocument. |
|
|  | [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converteert brondocument. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converteert brondocument. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converteert brondocument. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converteert brondocument. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converteert brondocument. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converteert brondocument. |
|
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
|  | [getDocumentInfo()](#getDocumentInfo--) | Haalt informatie over brondocument op - paginatelling en andere documenteigenschappen specifiek voor het bestandstype. |
|
|  | [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Controleert of het brondocument met een wachtwoord is beveiligd |
|
|  | [getPossibleConversions()](#getPossibleConversions--) | Haalt mogelijke conversies voor het brondocument op. |
|
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Haalt alle ondersteunde conversies op **Meer info** Meer informatie over ondersteunde conversies: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Meer informatie over beschikbare conversies: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Haalt ondersteunde conversies op voor de opgegeven documentextensie Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Meer info** Meer informatie over ondersteunde conversies: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Meer informatie over beschikbare conversies: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [dispose()](#dispose--) | Vrijgeeft bronnen. |
|
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Initialiseert een nieuwe instantie van de klasse voor een vloeiende conversie‑configuratie. Voorbeeld van vloeiend conversiegebruik: `
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


Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse.


**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | leverancier van invoerstroom. |
|

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Een leverancier van invoerstroom. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Een leverancier van Converter-instellingen. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Een leverancier van invoerstroom. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Een leverancier van laadopties. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Een leverancier van invoerstroom. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Een leverancier van documentlaadopties. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Een leverancier van Converter-instellingen. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Initialiseert een nieuw exemplaar van de klasse. **Learn more** Meer informatie over hoe documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of een andere opslag van derden te laden en te converteren: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Meer over documentlaadopties afhankelijk van het bestandstype: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Een leverancier van invoerstroom. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | De functie die documentlaadopties retourneert. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


Initialiseert een nieuw exemplaar van de klasse. **Learn more** Meer informatie over hoe documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of een andere opslag van derden te laden en te converteren: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Meer over documentlaadopties afhankelijk van het bestandstype: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Een leverancier die een leesbare stroom retourneert. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Een functie die documentlaadopties retourneert. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Initialiseert een nieuw exemplaar van de klasse. **Learn more** Meer informatie over hoe documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of een andere opslag van derden te laden en te converteren: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Meer over documentlaadopties afhankelijk van het bestandstype: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Een leverancier die een leesbare stroom retourneert. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Een functie die documentlaadopties retourneert. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Een leverancier van Converter-instellingen. |
|

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad naar het brondocument. |
|

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad naar het brondocument. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Een leverancier van Converter-instellingen. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad naar het brondocument. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | De leverancier van laadopties. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initialiseert een nieuwe instantie van de [Converter](../../com.groupdocs.conversion/converter) klasse.
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad naar het brondocument. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | De leverancier van documentlaadopties. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | De leverancier van Converter-instellingen. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Initialiseert een nieuw exemplaar van de klasse. **Learn more** Meer informatie over hoe documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of een andere opslag van derden te laden en te converteren: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Meer over documentlaadopties afhankelijk van het bestandstype: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad naar het brondocument. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | De functie voor documentlaadopties. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) |  |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Initialiseert een nieuw exemplaar van de klasse. **Learn more** Meer informatie over hoe documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of een andere opslag van derden te laden en te converteren: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Meer over documentlaadopties afhankelijk van het bestandstype: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad naar het brondocument. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | De functie voor documentlaadopties. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | De leverancier van Converter-instellingen. |
|

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| leverancier | java.lang.String |  |
| versie | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Converteert het brondocument. Slaat het volledige geconverteerde document op.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | De output stream leverancier. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De conversieopties specifiek voor het gewenste doelbestandstype. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Converteert brondocument. Slaat het volledige geconverteerde document op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | output stream leverancier |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | de delegate die de geconverteerde documentstroom ontvangt. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | de conversieopties specifiek voor het gewenste doelbestandstype. |
|

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Converteert brondocument. Slaat het volledige geconverteerde document op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | De output stream leverancier. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Conversieoptiesprovider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te leveren voor het gewenste doeldocumenttype. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converteert brondocument. Slaat het volledige geconverteerde document op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | De output stream leverancier. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | De delegate die de geconverteerde documentstroom ontvangt. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Conversieoptiesprovider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te leveren voor het gewenste doeldocumenttype. |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Converteert brondocument. Slaat het volledige geconverteerde document op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Output stream functie. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De conversieopties specifiek voor het gewenste doelbestandstype. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Converteert brondocument. Slaat het volledige geconverteerde document op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Output stream functie |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | De delegate die de geconverteerde documentstroom ontvangt |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De conversieopties specifiek voor het gewenste doelbestandstype |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Converteert brondocument. Slaat het volledige geconverteerde document op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Output stream functie. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Conversieoptiesprovider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te leveren voor het gewenste doeldocumenttype. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converteert brondocument. Slaat het volledige geconverteerde document op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Output stream functie. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | De delegate die de geconverteerde documentstroom ontvangt. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Conversieoptiesprovider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te leveren voor het gewenste doeldocumenttype. |
|

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Converteert het brondocument. Slaat het volledige geconverteerde document op.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad naar het brondocument. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De conversieopties specifiek voor het gewenste doelbestandstype. |
|

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | De pagina-outputstreamfunctie. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De conversieopties specifiek voor het gewenste doelbestandstype. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | De output stream functie. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | De delegate die de geconverteerde documentpagina-stroom ontvangt. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De conversieopties specifiek voor het gewenste doelbestandstype. |
|

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | De output stream functie. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Conversieoptiesprovider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te leveren voor het gewenste doeldocumenttype. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Output stream functie. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | De delegate die de geconverteerde documentpagina-stroom ontvangt. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Conversieoptiesprovider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te leveren voor het gewenste doeldocumenttype. |
|

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Een output stream functie. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De conversieopties specifiek voor het gewenste doelbestandstype. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Een output stream functie. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | De delegate die de geconverteerde documentpagina-stroom ontvangt. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De conversieopties specifiek voor het gewenste doelbestandstype. |
|

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Een output stream functie. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Conversieoptiesprovider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te leveren voor het gewenste doeldocumenttype. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. **Meer info** Meer over basisscenario's voor documentconversie: [Hoe een document te converteren in 3 stappen](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversiegebruikssituaties, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Een output stream functie. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | De delegate die de geconverteerde documentpagina-stroom ontvangt. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Conversieoptiesprovider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te leveren voor het gewenste doeldocumenttype. |
|

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Haalt informatie over brondocument op - paginatelling en andere documenteigenschappen specifiek voor het bestandstype.
**Learn more** Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](../https://docs.groupdocs.com/display/conversionnet/Get+document+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info

### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Controleert of het brondocument met een wachtwoord is beveiligd


**Returns:**
boolean - true als document met wachtwoord beveiligd is **Meer info** Meer informatie over het geconverteerde document - bestandstype, paginatelling, aanmaakdatum en vele andere formatspecifieke eigenschappen: [Hoe te controleren of het document met wachtwoord beveiligd is](../https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected)

### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Haalt mogelijke conversies voor het brondocument op.
**Learn more** Learn more about supported conversions: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Learn more about available conversions: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Haalt alle ondersteunde conversies op **Meer info** Meer informatie over ondersteunde conversies: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Meer informatie over beschikbare conversies: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - ondersteunde conversies

### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Haalt ondersteunde conversies op voor de opgegeven documentextensie Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Meer info** Meer informatie over ondersteunde conversies: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Meer informatie over beschikbare conversies: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | Documentextensie |
|

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### dispose() {#dispose--}
```
public final void dispose()
```


Vrijgeeft bronnen.


### close() {#close--}
```
public void close()
```




