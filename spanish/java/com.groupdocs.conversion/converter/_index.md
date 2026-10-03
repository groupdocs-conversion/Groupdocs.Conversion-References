---
title: "Converter"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa la clase principal que controla el proceso de conversión de documentos."
type: docs
weight: 10
url: /es/java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Representa la clase principal que controla el proceso de conversión de documentos.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Converter()](#Converter--) | Inicializa una nueva instancia de la clase para la configuración fluida de la conversión. |
|
|  | [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Inicializa una nueva instancia de la clase. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | Inicializa una nueva instancia de la clase. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inicializa una nueva instancia de la clase. |
|
|  | [Converter(String filePath)](#Converter-java.lang.String-) | Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Inicializa una nueva instancia de la clase. |
|
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) |  |
|  | [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Inicializa una nueva instancia de la clase. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
|  | [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convierte el documento de origen. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convierte el documento de origen. |
|
|  | [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convierte el documento de origen. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convierte el documento de origen. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convierte el documento de origen. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convierte el documento de origen. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convierte el documento de origen. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convierte el documento de origen. |
|
|  | [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convierte el documento de origen. |
|
|  | [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convierte el documento de origen. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convierte el documento de origen. |
|
|  | [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convierte el documento de origen. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convierte el documento de origen. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convierte el documento de origen. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Convierte el documento de origen. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convierte el documento de origen. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Convierte el documento de origen. |
|
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
|  | [getDocumentInfo()](#getDocumentInfo--) | Obtiene información del documento de origen - recuento de páginas y otras propiedades del documento específicas del tipo de archivo. |
|
|  | [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Comprueba si el documento de origen está protegido con contraseña. |
|
|  | [getPossibleConversions()](#getPossibleConversions--) | Obtiene conversiones posibles para el documento de origen. |
|
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Obtiene todas las conversiones compatibles **Aprende más** Obtén más información sobre conversiones compatibles: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Obtén más información sobre conversiones disponibles: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Obtiene las conversiones compatibles para la extensión de documento proporcionada Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Aprende más** Obtén más información sobre conversiones compatibles: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Obtén más información sobre conversiones disponibles: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [dispose()](#dispose--) | Libera los recursos. |
|
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Inicializa una nueva instancia de la clase para la configuración fluida de la conversión. Ejemplo de uso fluido de la conversión: `
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


Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter).


**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | proveedor de flujo de entrada. |
|

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un proveedor de flujo de entrada. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un proveedor de configuraciones del Convertidor. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un proveedor de flujo de entrada. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Un proveedor de opciones de carga. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un proveedor de flujo de entrada. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Un proveedor de opciones de carga del documento. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un proveedor de configuraciones del Convertidor. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Inicializa una nueva instancia de la clase. **Aprende más** Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Más información sobre las opciones de carga de documentos según el tipo de archivo: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un proveedor de flujo de entrada. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | La función que devuelve opciones de carga del documento. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


Inicializa una nueva instancia de la clase. **Aprende más** Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Más información sobre las opciones de carga de documentos según el tipo de archivo: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un proveedor que devuelve un flujo legible. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Una función que devuelve opciones de carga del documento. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Inicializa una nueva instancia de la clase. **Aprende más** Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Más información sobre las opciones de carga de documentos según el tipo de archivo: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.util.function.Supplier<java.io.InputStream> | Un proveedor que devuelve un flujo legible. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Una función que devuelve opciones de carga del documento. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un proveedor de configuraciones del Convertidor. |
|

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo del documento fuente. |
|

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo del documento fuente. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Un proveedor de configuraciones del Convertidor. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo del documento fuente. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | El proveedor de opciones de carga. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Inicializa una nueva instancia de la clase [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo del documento fuente. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | El proveedor de opciones de carga del documento. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | El proveedor de configuraciones del Convertidor. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Inicializa una nueva instancia de la clase. **Aprende más** Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Más información sobre las opciones de carga de documentos según el tipo de archivo: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo del documento fuente. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | La función de opciones de carga del documento. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) |  |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Inicializa una nueva instancia de la clase. **Aprende más** Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Más información sobre las opciones de carga de documentos según el tipo de archivo: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo del documento fuente. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | La función de opciones de carga del documento. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | El proveedor de configuraciones del Convertidor. |
|

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| proveedor | java.lang.String |  |
| versión | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Convierte el documento fuente. Guarda todo el documento convertido.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | El proveedor del flujo de salida. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Convierte el documento fuente. Guarda todo el documento convertido. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | proveedor de flujo de salida |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | el delegado que recibe el flujo del documento convertido. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | las opciones de conversión específicas para el tipo de archivo de destino deseado. |
|

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Convierte el documento fuente. Guarda todo el documento convertido. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | El proveedor del flujo de salida. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Proveedor de opciones de conversión. Será llamado para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Convierte el documento fuente. Guarda todo el documento convertido. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | El proveedor del flujo de salida. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | El delegado que recibe el flujo del documento convertido. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Proveedor de opciones de conversión. Será llamado para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Convierte el documento fuente. Guarda todo el documento convertido. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Función de flujo de salida. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Convierte el documento fuente. Guarda todo el documento convertido. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Función de flujo de salida |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | El delegado que recibe el flujo del documento convertido |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Convierte el documento fuente. Guarda todo el documento convertido. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Función de flujo de salida. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Proveedor de opciones de conversión. Será llamado para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Convierte el documento fuente. Guarda todo el documento convertido. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Función de flujo de salida. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | El delegado que recibe el flujo del documento convertido. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Proveedor de opciones de conversión. Será llamado para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |
|

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Convierte el documento fuente. Guarda todo el documento convertido.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo del documento fuente. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |
|

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Convierte el documento fuente. Guarda el documento convertido página por página.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | La función de flujo de salida de página. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Convierte el documento fuente. Guarda el documento convertido página por página. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | La función de flujo de salida. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | El delegado que recibe el flujo de la página del documento convertido. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |
|

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Convierte el documento fuente. Guarda el documento convertido página por página. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | La función de flujo de salida. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Proveedor de opciones de conversión. Será llamado para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Convierte el documento fuente. Guarda el documento convertido página por página. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Función de flujo de salida. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | El delegado que recibe el flujo de la página del documento convertido. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Proveedor de opciones de conversión. Será llamado para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |
|

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Convierte el documento fuente. Guarda el documento convertido página por página. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Una función de flujo de salida. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Convierte el documento fuente. Guarda el documento convertido página por página. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Una función de flujo de salida. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | El delegado que recibe el flujo de la página del documento convertido. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |
|

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Convierte el documento fuente. Guarda el documento convertido página por página. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Una función de flujo de salida. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Proveedor de opciones de conversión. Será llamado para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Convierte el documento fuente. Guarda el documento convertido página por página. **Learn more** Más sobre escenarios básicos de conversión de documentos: [Cómo convertir un documento en 3 pasos](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuraciones avanzadas](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Una función de flujo de salida. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | El delegado que recibe el flujo de la página del documento convertido. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Proveedor de opciones de conversión. Será llamado para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |
|

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtiene información del documento de origen - recuento de páginas y otras propiedades del documento específicas del tipo de archivo.
**Learn more** Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](../https://docs.groupdocs.com/display/conversionnet/Get+document+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info

### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Comprueba si el documento de origen está protegido con contraseña.


**Returns:**
boolean - true si el documento está protegido con contraseña **Learn more** Más información sobre el documento convertido - tipo de archivo, número de páginas, fecha de creación y muchas otras propiedades específicas del formato: [Cómo verificar si el documento está protegido con contraseña](../https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected)

### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Obtiene conversiones posibles para el documento de origen.
**Learn more** Learn more about supported conversions: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Learn more about available conversions: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Obtiene todas las conversiones compatibles **Aprende más** Obtén más información sobre conversiones compatibles: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Obtén más información sobre conversiones disponibles: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - conversiones compatibles

### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Obtiene las conversiones compatibles para la extensión de documento proporcionada Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Aprende más** Obtén más información sobre conversiones compatibles: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Obtén más información sobre conversiones disponibles: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | Extensión del documento |
|

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### dispose() {#dispose--}
```
public final void dispose()
```


Libera los recursos.


### close() {#close--}
```
public void close()
```




