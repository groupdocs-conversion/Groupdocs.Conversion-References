---
title: "Convertisseur"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente la classe principale qui contrôle le processus de conversion de documents."
type: docs
weight: 10
url: /fr/java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Représente la classe principale qui contrôle le processus de conversion de documents.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Converter()](#Converter--) | Initialise une nouvelle instance de la classe pour la configuration fluide de la conversion. |
|
|  | [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initialise une nouvelle instance de la classe. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | Initialise une nouvelle instance de la classe. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialise une nouvelle instance de la classe. |
|
|  | [Converter(String filePath)](#Converter-java.lang.String-) | Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initialise une nouvelle instance de la classe. |
|
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) |  |
|  | [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initialise une nouvelle instance de la classe. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
|  | [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convertit le document source. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convertit le document source. |
|
|  | [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convertit le document source. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convertit le document source. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convertit le document source. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convertit le document source. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convertit le document source. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convertit le document source. |
|
|  | [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convertit le document source. |
|
|  | [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convertit le document source. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convertit le document source. |
|
|  | [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convertit le document source. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convertit le document source. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convertit le document source. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convertit le document source. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convertit le document source. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convertit le document source. |
|
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
|  | [getDocumentInfo()](#getDocumentInfo--) | Obtient les informations du document source - nombre de pages et autres propriétés du document spécifiques au type de fichier. |
|
|  | [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Vérifie si le document source est protégé par mot de passe |
|
|  | [getPossibleConversions()](#getPossibleConversions--) | Obtient les conversions possibles pour le document source. |
|
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Obtient toutes les conversions prises en charge **En savoir plus** En savoir plus sur les conversions prises en charge : [Liste complète des conversions prises en charge](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) En savoir plus sur les conversions disponibles : [Comment obtenir les conversions prises en charge dans le code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Obtient les conversions prises en charge pour l'extension de document fournie Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **En savoir plus** En savoir plus sur les conversions prises en charge : [Liste complète des conversions prises en charge](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) En savoir plus sur les conversions disponibles : [Comment obtenir les conversions prises en charge dans le code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [dispose()](#dispose--) | Libère les ressources. |
|
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Initialise une nouvelle instance de la classe pour la configuration fluide de la conversion. Exemple d'utilisation fluide de la conversion : `
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


Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter).


**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | fournisseur de flux d'entrée. |
|

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Un fournisseur de flux d'entrée. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un fournisseur de paramètres du Convertisseur. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Un fournisseur de flux d'entrée. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Un fournisseur d'options de chargement. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Un fournisseur de flux d'entrée. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Un fournisseur d'options de chargement du document. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un fournisseur de paramètres du Convertisseur. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Initialise une nouvelle instance de la classe. **Learn more** Plus d'informations sur la façon de charger et de convertir des documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Plus d'informations sur les options de chargement des documents en fonction du type de fichier : [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Un fournisseur de flux d'entrée. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | La fonction qui renvoie les options de chargement du document. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


Initialise une nouvelle instance de la classe. **Learn more** Plus d'informations sur la façon de charger et de convertir des documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Plus d'informations sur les options de chargement des documents en fonction du type de fichier : [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Un fournisseur qui renvoie un flux lisible. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Une fonction qui renvoie les options de chargement du document. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Initialise une nouvelle instance de la classe. **Learn more** Plus d'informations sur la façon de charger et de convertir des documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Plus d'informations sur les options de chargement des documents en fonction du type de fichier : [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.util.function.Supplier<java.io.InputStream> | Un fournisseur qui renvoie un flux lisible. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Une fonction qui renvoie les options de chargement du document. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un fournisseur de paramètres du Convertisseur. |
|

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier du document source. |
|

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier du document source. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un fournisseur de paramètres du Convertisseur. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier du document source. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Le fournisseur d'options de chargement. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initialise une nouvelle instance de la classe [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier du document source. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Le fournisseur d'options de chargement du document. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Le fournisseur de paramètres du Convertisseur. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Initialise une nouvelle instance de la classe. **Learn more** Plus d'informations sur la façon de charger et de convertir des documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Plus d'informations sur les options de chargement des documents en fonction du type de fichier : [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier du document source. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | La fonction d'options de chargement du document. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) |  |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Initialise une nouvelle instance de la classe. **Learn more** Plus d'informations sur la façon de charger et de convertir des documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Plus d'informations sur les options de chargement des documents en fonction du type de fichier : [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier du document source. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | La fonction d'options de chargement du document. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Le fournisseur de paramètres du Convertisseur. |
|

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vendeur | java.lang.String |  |
| version | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Convertit le document source. Enregistre le document complet converti.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Le fournisseur de flux de sortie. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Convertit le document source. Enregistre le document converti complet. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | fournisseur de flux de sortie |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | le délégué qui reçoit le flux du document converti. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | les options de conversion spécifiques au type de fichier cible souhaité. |
|

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Convertit le document source. Enregistre le document converti complet. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Le fournisseur de flux de sortie. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fournisseur d'options de conversion. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Convertit le document source. Enregistre le document converti complet. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Le fournisseur de flux de sortie. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Le délégué qui reçoit le flux du document converti. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fournisseur d'options de conversion. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Convertit le document source. Enregistre le document converti complet. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Fonction de flux de sortie. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Convertit le document source. Enregistre le document converti complet. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Fonction de flux de sortie |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Le délégué qui reçoit le flux du document converti |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Convertit le document source. Enregistre le document converti complet. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Fonction de flux de sortie. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fournisseur d'options de conversion. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Convertit le document source. Enregistre le document converti complet. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Fonction de flux de sortie. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Le délégué qui reçoit le flux du document converti. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fournisseur d'options de conversion. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. |
|

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Convertit le document source. Enregistre le document complet converti.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier du document source. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
|

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Convertit le document source. Enregistre le document converti page par page.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | La fonction de flux de sortie de page. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Convertit le document source. Enregistre le document converti page par page. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | La fonction de flux de sortie. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Le délégué qui reçoit le flux de page du document converti. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
|

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Convertit le document source. Enregistre le document converti page par page. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | La fonction de flux de sortie. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fournisseur d'options de conversion. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Convertit le document source. Enregistre le document converti page par page. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Fonction de flux de sortie. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Le délégué qui reçoit le flux de page du document converti. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fournisseur d'options de conversion. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. |
|

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Convertit le document source. Enregistre le document converti page par page. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Une fonction de flux de sortie. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Convertit le document source. Enregistre le document converti page par page. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Une fonction de flux de sortie. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Le délégué qui reçoit le flux de page du document converti. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
|

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Convertit le document source. Enregistre le document converti page par page. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Une fonction de flux de sortie. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fournisseur d'options de conversion. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Convertit le document source. Enregistre le document converti page par page. **Learn more** Plus d'informations sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Cas d'utilisation de conversion, paramètres avancés et personnalisations : [Convertir le document avec des paramètres avancés](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Une fonction de flux de sortie. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Le délégué qui reçoit le flux de page du document converti. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Fournisseur d'options de conversion. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. |
|

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtient les informations du document source - nombre de pages et autres propriétés du document spécifiques au type de fichier.
**Learn more** Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](../https://docs.groupdocs.com/display/conversionnet/Get+document+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info

### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Vérifie si le document source est protégé par mot de passe


**Returns:**
boolean - true si le document est protégé par mot de passe **Learn more** En savoir plus sur le document converti - type de fichier, nombre de pages, date de création et de nombreuses autres propriétés spécifiques au format : [Comment vérifier si le document est protégé par mot de passe](../https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected)

### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Obtient les conversions possibles pour le document source.
**Learn more** Learn more about supported conversions: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Learn more about available conversions: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Obtient toutes les conversions prises en charge **En savoir plus** En savoir plus sur les conversions prises en charge : [Liste complète des conversions prises en charge](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) En savoir plus sur les conversions disponibles : [Comment obtenir les conversions prises en charge dans le code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - conversions prises en charge

### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Obtient les conversions prises en charge pour l'extension de document fournie Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **En savoir plus** En savoir plus sur les conversions prises en charge : [Liste complète des conversions prises en charge](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) En savoir plus sur les conversions disponibles : [Comment obtenir les conversions prises en charge dans le code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | Extension du document |
|

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### dispose() {#dispose--}
```
public final void dispose()
```


Libère les ressources.


### close() {#close--}
```
public void close()
```




