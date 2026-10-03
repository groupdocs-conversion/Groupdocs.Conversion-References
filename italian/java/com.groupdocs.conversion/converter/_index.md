---
title: "Converter"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta la classe principale che controlla il processo di conversione dei documenti."
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Rappresenta la classe principale che controlla il processo di conversione dei documenti.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Converter()](#Converter--) | Inizializza una nuova istanza della classe per la configurazione fluida della conversione. |
|
|  | [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Inizializza una nuova istanza della classe. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | Inizializza una nuova istanza della classe. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inizializza una nuova istanza della classe. |
|
|  | [Converter(String filePath)](#Converter-java.lang.String-) | Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Inizializza una nuova istanza della classe. |
|
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) |  |
|  | [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inizializza una nuova istanza della classe. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
|  | [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converte il documento di origine. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converte il documento di origine. |
|
|  | [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converte il documento di origine. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converte il documento di origine. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converte il documento di origine. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converte il documento di origine. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converte il documento di origine. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converte il documento di origine. |
|
|  | [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converte il documento di origine. |
|
|  | [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converte il documento di origine. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converte il documento di origine. |
|
|  | [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converte il documento di origine. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converte il documento di origine. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converte il documento di origine. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Converte il documento di origine. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converte il documento di origine. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Converte il documento di origine. |
|
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
|  | [getDocumentInfo()](#getDocumentInfo--) | Ottiene le informazioni del documento sorgente - conteggio delle pagine e altre proprietà del documento specifiche del tipo di file. |
|
|  | [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Verifica se il documento di origine è protetto da password. |
|
|  | [getPossibleConversions()](#getPossibleConversions--) | Ottiene le conversioni possibili per il documento sorgente. |
|
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Ottiene tutte le conversioni supportate **Scopri di più** Scopri di più sulle conversioni supportate: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Scopri di più sulle conversioni disponibili: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Ottiene le conversioni supportate per l'estensione del documento fornita Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Scopri di più** Scopri di più sulle conversioni supportate: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Scopri di più sulle conversioni disponibili: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [dispose()](#dispose--) | Rilascia le risorse. |
|
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Inizializza una nuova istanza della classe per la configurazione fluida della conversione. Esempio di utilizzo fluido della conversione: `
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


Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter).


**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | fornitore di flusso di input. |
|

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un fornitore di flusso di input. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un fornitore delle impostazioni del Converter. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un fornitore di flusso di input. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Un fornitore delle opzioni di caricamento. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un fornitore di flusso di input. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Un fornitore delle opzioni di caricamento del documento. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un fornitore delle impostazioni del Converter. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Inizializza una nuova istanza della classe. **Learn more** Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro archivio di terze parti: [Caricamento di documenti da diverse fonti](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Opzioni di caricamento per diversi tipi di documento](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un fornitore di flusso di input. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | La funzione che restituisce le opzioni di caricamento del documento. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


Inizializza una nuova istanza della classe. **Learn more** Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro archivio di terze parti: [Caricamento di documenti da diverse fonti](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Opzioni di caricamento per diversi tipi di documento](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un fornitore che restituisce un flusso leggibile. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Una funzione che restituisce le opzioni di caricamento del documento. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Inizializza una nuova istanza della classe. **Learn more** Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro archivio di terze parti: [Caricamento di documenti da diverse fonti](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Opzioni di caricamento per diversi tipi di documento](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un fornitore che restituisce un flusso leggibile. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Una funzione che restituisce le opzioni di caricamento del documento. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un fornitore delle impostazioni del Converter. |
|

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file del documento di origine. |
|

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file del documento di origine. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un fornitore delle impostazioni del Converter. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file del documento di origine. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Il fornitore delle opzioni di caricamento. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Inizializza una nuova istanza della classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file del documento di origine. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Il fornitore delle opzioni di caricamento del documento. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Il fornitore delle impostazioni del Converter. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Inizializza una nuova istanza della classe. **Learn more** Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro archivio di terze parti: [Caricamento di documenti da diverse fonti](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Opzioni di caricamento per diversi tipi di documento](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file del documento di origine. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | La funzione delle opzioni di caricamento del documento. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) |  |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Inizializza una nuova istanza della classe. **Learn more** Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro archivio di terze parti: [Caricamento di documenti da diverse fonti](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Opzioni di caricamento per diversi tipi di documento](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file del documento di origine. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | La funzione delle opzioni di caricamento del documento. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Il fornitore delle impostazioni del Converter. |
|

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fornitore | java.lang.String |  |
| versione | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Converte il documento di origine. Salva l'intero documento convertito.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Il fornitore del flusso di output. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Converte il documento sorgente. Salva l'intero documento convertito. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | fornitore del flusso di output |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | il delegato che riceve il flusso del documento convertito. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
|

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Converte il documento sorgente. Salva l'intero documento convertito. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Il fornitore del flusso di output. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fornitore di opzioni di conversione. Verrà chiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converte il documento sorgente. Salva l'intero documento convertito. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Il fornitore del flusso di output. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Il delegato che riceve il flusso del documento convertito. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fornitore di opzioni di conversione. Verrà chiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Converte il documento sorgente. Salva l'intero documento convertito. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Funzione del flusso di output. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Converte il documento sorgente. Salva l'intero documento convertito. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Funzione del flusso di output |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Il delegato che riceve il flusso del documento convertito |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Converte il documento sorgente. Salva l'intero documento convertito. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Funzione del flusso di output. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fornitore di opzioni di conversione. Verrà chiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converte il documento sorgente. Salva l'intero documento convertito. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Funzione del flusso di output. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Il delegato che riceve il flusso del documento convertito. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fornitore di opzioni di conversione. Verrà chiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. |
|

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Converte il documento di origine. Salva l'intero documento convertito.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file del documento di origine. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
|

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Converte il documento sorgente. Salva il documento convertito pagina per pagina.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | La funzione del flusso di output della pagina. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Converte il documento sorgente. Salva il documento convertito pagina per pagina. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | La funzione del flusso di output. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Il delegato che riceve il flusso della pagina del documento convertito. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
|

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Converte il documento sorgente. Salva il documento convertito pagina per pagina. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | La funzione del flusso di output. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fornitore di opzioni di conversione. Verrà chiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converte il documento sorgente. Salva il documento convertito pagina per pagina. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Funzione del flusso di output. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Il delegato che riceve il flusso della pagina del documento convertito. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fornitore di opzioni di conversione. Verrà chiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. |
|

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Converte il documento sorgente. Salva il documento convertito pagina per pagina. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Una funzione del flusso di output. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Converte il documento sorgente. Salva il documento convertito pagina per pagina. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Una funzione del flusso di output. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Il delegato che riceve il flusso della pagina del documento convertito. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
|

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Converte il documento sorgente. Salva il documento convertito pagina per pagina. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Una funzione del flusso di output. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fornitore di opzioni di conversione. Verrà chiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Converte il documento sorgente. Salva il documento convertito pagina per pagina. **Scopri di più** Ulteriori informazioni sui casi base di conversione dei documenti: [Come convertire un documento in 3 passaggi](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casi d'uso della conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Una funzione del flusso di output. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Il delegato che riceve il flusso della pagina del documento convertito. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fornitore di opzioni di conversione. Verrà chiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. |
|

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Ottiene le informazioni del documento sorgente - conteggio delle pagine e altre proprietà del documento specifiche del tipo di file.
**Learn more** Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](../https://docs.groupdocs.com/display/conversionnet/Get+document+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info

### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Verifica se il documento di origine è protetto da password.


**Returns:**
boolean - true se il documento è protetto da password **Scopri di più** Ulteriori informazioni sul documento convertito - tipo di file, conteggio pagine, data di creazione e molte altre proprietà specifiche del formato: [Come verificare se il documento è protetto da password](../https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected)

### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Ottiene le conversioni possibili per il documento sorgente.
**Learn more** Learn more about supported conversions: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Learn more about available conversions: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Ottiene tutte le conversioni supportate **Scopri di più** Scopri di più sulle conversioni supportate: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Scopri di più sulle conversioni disponibili: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - conversioni supportate

### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Ottiene le conversioni supportate per l'estensione del documento fornita Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Scopri di più** Scopri di più sulle conversioni supportate: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Scopri di più sulle conversioni disponibili: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | Estensione del documento |
|

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia le risorse.


### close() {#close--}
```
public void close()
```




