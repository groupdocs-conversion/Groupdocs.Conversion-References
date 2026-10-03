---
title: "Konverter"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt die Hauptklasse dar, die den Dokumentkonvertierungsprozess steuert."
type: docs
weight: 10
url: /de/java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Stellt die Hauptklasse dar, die den Dokumentkonvertierungsprozess steuert.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Converter()](#Converter--) | Initialisiert eine neue Instanz der Klasse für die fluente Konvertierungseinrichtung. |
|
|  | [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initialisiert eine neue Instanz der Klasse. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | Initialisiert eine neue Instanz der Klasse. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialisiert eine neue Instanz der Klasse. |
|
|  | [Converter(String filePath)](#Converter-java.lang.String-) | Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initialisiert eine neue Instanz der Klasse. |
|
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) |  |
|  | [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialisiert eine neue Instanz der Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
|  | [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konvertiert das Quelldokument. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konvertiert das Quelldokument. |
|
|  | [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konvertiert das Quelldokument. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konvertiert das Quelldokument. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konvertiert das Quelldokument. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konvertiert das Quelldokument. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konvertiert das Quelldokument. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konvertiert das Quelldokument. |
|
|  | [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konvertiert das Quelldokument. |
|
|  | [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konvertiert das Quelldokument. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konvertiert das Quelldokument. |
|
|  | [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konvertiert das Quelldokument. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konvertiert das Quelldokument. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konvertiert das Quelldokument. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konvertiert das Quelldokument. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konvertiert das Quelldokument. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konvertiert das Quelldokument. |
|
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
|  | [getDocumentInfo()](#getDocumentInfo--) | Liest Informationen des Quelldokuments - Seitenanzahl und weitere dokumentenspezifische Eigenschaften je nach Dateityp. |
|
|  | [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Überprüft, ob das Quelldokument passwortgeschützt ist. |
|
|  | [getPossibleConversions()](#getPossibleConversions--) | Ermittelt mögliche Konvertierungen für das Quelldokument. |
|
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Ermittelt alle unterstützten Konvertierungen **Erfahren Sie mehr** Erfahren Sie mehr über unterstützte Konvertierungen: [Vollständige Liste der unterstützten Konvertierungen](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Erfahren Sie mehr über verfügbare Konvertierungen: [Wie man unterstützte Konvertierungen im Code abruft](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Ermittelt unterstützte Konvertierungen für die angegebene Dokumenterweiterung Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Erfahren Sie mehr** Erfahren Sie mehr über unterstützte Konvertierungen: [Vollständige Liste der unterstützten Konvertierungen](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Erfahren Sie mehr über verfügbare Konvertierungen: [Wie man unterstützte Konvertierungen im Code abruft](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [dispose()](#dispose--) | Gibt Ressourcen frei. |
|
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Initialisiert eine neue Instanz der Klasse für die fluente Konvertierungseinrichtung. Beispiel für fluente Konvertierungsverwendung: `
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


Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter).


**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.util.function.Supplier<java.io.InputStream> | Input-Stream-Lieferant. |
|

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.util.function.Supplier<java.io.InputStream> | Ein Input-Stream-Lieferant. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ein Konverter-Einstellungs-Lieferant. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.util.function.Supplier<java.io.InputStream> | Ein Input-Stream-Lieferant. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Ein Lieferant für Ladeoptionen. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.util.function.Supplier<java.io.InputStream> | Ein Input-Stream-Lieferant. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Ein Lieferant für Dokument-Ladeoptionen. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ein Konverter-Einstellungs-Lieferant. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Initialisiert eine neue Instanz der Klasse. **Learn more** Mehr darüber, wie Dokumente, die auf FTP, Amazon S3 Storage, Windows Azure oder einem anderen Drittanbieterspeicher gespeichert sind, geladen und konvertiert werden können: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Mehr über dokumentenabhängige Ladeoptionen je nach Dateityp: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.util.function.Supplier<java.io.InputStream> | Ein Input-Stream-Lieferant. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Die Funktion, die Dokument-Ladeoptionen zurückgibt. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


Initialisiert eine neue Instanz der Klasse. **Learn more** Mehr darüber, wie Dokumente, die auf FTP, Amazon S3 Storage, Windows Azure oder einem anderen Drittanbieterspeicher gespeichert sind, geladen und konvertiert werden können: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Mehr über dokumentenabhängige Ladeoptionen je nach Dateityp: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.util.function.Supplier<java.io.InputStream> | Ein Lieferant, der einen lesbaren Stream zurückgibt. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Eine Funktion, die Dokument-Ladeoptionen zurückgibt. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Initialisiert eine neue Instanz der Klasse. **Learn more** Mehr darüber, wie Dokumente, die auf FTP, Amazon S3 Storage, Windows Azure oder einem anderen Drittanbieterspeicher gespeichert sind, geladen und konvertiert werden können: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Mehr über dokumentenabhängige Ladeoptionen je nach Dateityp: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.util.function.Supplier<java.io.InputStream> | Ein Lieferant, der einen lesbaren Stream zurückgibt. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Eine Funktion, die Dokument-Ladeoptionen zurückgibt. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ein Konverter-Einstellungs-Lieferant. |
|

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad zum Quelldokument. |
|

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad zum Quelldokument. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ein Konverter-Einstellungs-Lieferant. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad zum Quelldokument. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Der Anbieter der Ladeoptionen. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initialisiert eine neue Instanz der Klasse [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad zum Quelldokument. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Der Anbieter der Dokument-Ladeoptionen. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Der Anbieter der Konvertereinstellungen. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Initialisiert eine neue Instanz der Klasse. **Learn more** Mehr darüber, wie Dokumente, die auf FTP, Amazon S3 Storage, Windows Azure oder einem anderen Drittanbieterspeicher gespeichert sind, geladen und konvertiert werden können: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Mehr über dokumentenabhängige Ladeoptionen je nach Dateityp: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad zum Quelldokument. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Die Funktion für Dokument-Ladeoptionen. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) |  |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Initialisiert eine neue Instanz der Klasse. **Learn more** Mehr darüber, wie Dokumente, die auf FTP, Amazon S3 Storage, Windows Azure oder einem anderen Drittanbieterspeicher gespeichert sind, geladen und konvertiert werden können: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Mehr über dokumentenabhängige Ladeoptionen je nach Dateityp: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad zum Quelldokument. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Die Funktion für Dokument-Ladeoptionen. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Der Anbieter der Konvertereinstellungen. |
|

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Anbieter | java.lang.String |  |
| Version | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Der Anbieter des Ausgabestreams. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldatentyp spezifisch sind. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. **Learn more** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Ausgabestream-Anbieter |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | der Delegat, der den konvertierten Dokumentenstream empfängt. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | die Konvertierungsoptionen, die für den gewünschten Zieldatentyp spezifisch sind. |
|

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. **Learn more** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Der Anbieter des Ausgabestreams. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Anbieter von Konvertierungsoptionen. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. **Learn more** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Der Anbieter des Ausgabestreams. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Der Delegat, der den konvertierten Dokumentenstream empfängt. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Anbieter von Konvertierungsoptionen. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. **Learn more** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Ausgabestream-Funktion. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldatentyp spezifisch sind. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. **Learn more** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Ausgabestream-Funktion |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Der Delegat, der den konvertierten Dokumentenstream empfängt |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldatentyp spezifisch sind |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. **Learn more** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Ausgabestream-Funktion. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Anbieter von Konvertierungsoptionen. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument. **Learn more** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Ausgabestream-Funktion. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Der Delegat, der den konvertierten Dokumentenstream empfängt. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Anbieter von Konvertierungsoptionen. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |
|

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad zum Quelldokument. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldatentyp spezifisch sind. |
|

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Die Seiten-Ausgabestream-Funktion. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldatentyp spezifisch sind. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. **Mehr erfahren** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [Wie man ein Dokument in 3 Schritten konvertiert](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle der Konvertierung, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Die Ausgabestream-Funktion. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Der Delegat, der den konvertierten Dokumentseiten-Stream empfängt. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldatentyp spezifisch sind. |
|

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. **Mehr erfahren** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [Wie man ein Dokument in 3 Schritten konvertiert](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle der Konvertierung, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Die Ausgabestream-Funktion. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Anbieter von Konvertierungsoptionen. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. **Mehr erfahren** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [Wie man ein Dokument in 3 Schritten konvertiert](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle der Konvertierung, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Ausgabestream-Funktion. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Der Delegat, der den konvertierten Dokumentseiten-Stream empfängt. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Anbieter von Konvertierungsoptionen. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |
|

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. **Mehr erfahren** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [Wie man ein Dokument in 3 Schritten konvertiert](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle der Konvertierung, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Eine Ausgabestream-Funktion. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldatentyp spezifisch sind. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. **Mehr erfahren** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [Wie man ein Dokument in 3 Schritten konvertiert](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle der Konvertierung, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Eine Ausgabestream-Funktion. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Der Delegat, der den konvertierten Dokumentseiten-Stream empfängt. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldatentyp spezifisch sind. |
|

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. **Mehr erfahren** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [Wie man ein Dokument in 3 Schritten konvertiert](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle der Konvertierung, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Eine Ausgabestream-Funktion. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Anbieter von Konvertierungsoptionen. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise. **Mehr erfahren** Mehr über grundlegende Szenarien der Dokumentkonvertierung: [Wie man ein Dokument in 3 Schritten konvertiert](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Anwendungsfälle der Konvertierung, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Eine Ausgabestream-Funktion. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Der Delegat, der den konvertierten Dokumentseiten-Stream empfängt. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Anbieter von Konvertierungsoptionen. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |
|

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Liest Informationen des Quelldokuments - Seitenanzahl und weitere dokumentenspezifische Eigenschaften je nach Dateityp.
**Learn more** Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](../https://docs.groupdocs.com/display/conversionnet/Get+document+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info

### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Überprüft, ob das Quelldokument passwortgeschützt ist.


**Returns:**
boolean - true, wenn das Dokument passwortgeschützt ist **Mehr erfahren** Mehr Informationen über das konvertierte Dokument – Dateityp, Seitenanzahl, Erstellungsdatum und viele weitere formatspezifische Eigenschaften: [Wie man prüft, ob das Dokument passwortgeschützt ist](../https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected)

### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Ermittelt mögliche Konvertierungen für das Quelldokument.
**Learn more** Learn more about supported conversions: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Learn more about available conversions: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Ermittelt alle unterstützten Konvertierungen **Erfahren Sie mehr** Erfahren Sie mehr über unterstützte Konvertierungen: [Vollständige Liste der unterstützten Konvertierungen](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Erfahren Sie mehr über verfügbare Konvertierungen: [Wie man unterstützte Konvertierungen im Code abruft](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - unterstützte Konvertierungen

### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Ermittelt unterstützte Konvertierungen für die angegebene Dokumenterweiterung Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Erfahren Sie mehr** Erfahren Sie mehr über unterstützte Konvertierungen: [Vollständige Liste der unterstützten Konvertierungen](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Erfahren Sie mehr über verfügbare Konvertierungen: [Wie man unterstützte Konvertierungen im Code abruft](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Dokumenterweiterung |
|

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### dispose() {#dispose--}
```
public final void dispose()
```


Gibt Ressourcen frei.


### close() {#close--}
```
public void close()
```




