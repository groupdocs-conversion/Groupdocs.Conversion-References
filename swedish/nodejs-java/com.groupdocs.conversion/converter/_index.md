---
title: "Converter"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Representerar huvudklassen som styr dokumentkonverteringsprocessen."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Representerar huvudklassen som styr dokumentkonverteringsprocessen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Converter()](#Converter--) | Initierar en ny instans av  klassen för flytande konverteringsinställning. |
| [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen. |
| [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen. |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen. |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen. |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initierar en ny instans av  klassen. |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initierar en ny instans av  klassen. |
| [Converter(String filePath)](#Converter-java.lang.String-) | Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen. |
| [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen. |
| [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen. |
| [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen. |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Initierar en ny instans av  klassen. |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Initierar en ny instans av  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
| [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konverterar källdokumentet. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konverterar källdokumentet. |
| [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konverterar källdokumentet. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konverterar källdokumentet. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konverterar källdokumentet. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konverterar källdokumentet. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konverterar källdokumentet. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konverterar källdokumentet. |
| [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konverterar källdokumentet. |
| [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konverterar källdokumentet. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konverterar källdokumentet. |
| [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konverterar källdokumentet. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konverterar källdokumentet. |
| [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konverterar källdokumentet. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Konverterar källdokumentet. |
| [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konverterar källdokumentet. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Konverterar källdokumentet. |
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
| [getDocumentInfo()](#getDocumentInfo--) | Hämtar information om källdokumentet – sidantal och andra dokumentegenskaper som är specifika för filtypen. |
| [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Kontrollerar om källdokumentet är lösenordsskyddat. |
| [getPossibleConversions()](#getPossibleConversions--) | Hämtar möjliga konverteringar för källdokumentet. |
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Hämtar alla stödda konverteringar **Läs mer**Läs mer om stödda konverteringar: [Full list of supported conversions][]Läs mer om tillgängliga konverteringar: [How to get supported conversions in code][] |


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Hämtar stödda konverteringar för angiven dokumentändelse Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**Läs mer**Läs mer om stödda konverteringar: [Full list of supported conversions][]Läs mer om tillgängliga konverteringar: [How to get supported conversions in code][] |


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
| [dispose()](#dispose--) | Frigör resurser. |
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Initierar en ny instans av  klass för flytande konverteringsinställning.  Exempel på flytande konverteringsanvändning: `var converter = new Converter();` `converter .Load(\"\") .ConvertTo(\"\") .Convert();` `converter .WithSettings(() => new ConverterSettings()) .Load(\"\").WithOptions(new PdfLoadOptions()) .ConvertTo(\"\").WithOptions(new PdfConvertOptions()) .OnConversionCompleted(convertedDocumentStream => { }) .Convert();` `converter .Load(\"\").WithOptions(new PdfLoadOptions()) .ConvertByPageTo((number => new FileStream(\"\", FileMode.Create))).WithOptions(new PdfConvertOptions()) .OnConversionCompleted((number, stream) => {}) .Convert();` `converter.Load(\"\").GetPossibleConversions(); converter.Load(\"\").GetDocumentInfo(); converter.Load(\"\").WithOptions(new PdfLoadOptions()).GetPossibleConversions(); converter.Load(\"\").WithOptions(new PdfLoadOptions()).GetDocumentInfo();`

### Converter(Supplier<InputStream> document) {#Converter-java.util.function.Supplier-java.io.InputStream--}
```
public Converter(Supplier<InputStream> document)
```


Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | java.util.function.Supplier<java.io.InputStream> | leverantör av inmatningsström. |

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | java.util.function.Supplier<java.io.InputStream> | En leverantör av inmatningsström. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | En leverantör av Converter-inställningar. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | java.util.function.Supplier<java.io.InputStream> | En leverantör av inmatningsström. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | En leverantör av laddningsalternativ. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | java.util.function.Supplier<java.io.InputStream> | En leverantör av inmatningsström. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | En leverantör av dokumentets laddningsalternativ. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | En leverantör av Converter-inställningar. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Initierar en ny instans av  klass.**Learn more**Mer om hur man laddar och konverterar dokument som lagras på FTP, Amazon S3 Storage, Windows Azure eller någon annan tredjepartslagring: [Loading document from different sources][]Mer om dokumentladdningsalternativ beroende på filtyp: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | java.util.function.Supplier<java.io.InputStream> | En leverantör av inmatningsström. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Funktionen som returnerar dokumentets laddningsalternativ. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


Initierar en ny instans av  klass.**Learn more**Mer om hur man laddar och konverterar dokument som lagras på FTP, Amazon S3 Storage, Windows Azure eller någon annan tredjepartslagring: [Loading document from different sources][]Mer om dokumentladdningsalternativ beroende på filtyp: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | java.util.function.Supplier<java.io.InputStream> | En leverantör som returnerar läsbar ström. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | En funktion som returnerar dokumentets laddningsalternativ. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | En leverantör av Converter-inställningar. |

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen till källdokumentet. |

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen till källdokumentet. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | En leverantör av Converter-inställningar. |

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen till källdokumentet. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Leverantören av laddningsalternativ. |

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Initierar en ny instans av [Converter](../../com.groupdocs.conversion/converter) klassen.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen till källdokumentet. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Leverantören av dokumentets laddningsalternativ. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Leverantören av Converter-inställningar. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Initierar en ny instans av  klass.**Learn more**Mer om hur man laddar och konverterar dokument som lagras på FTP, Amazon S3 Storage, Windows Azure eller någon annan tredjepartslagring: [Loading document from different sources][]Mer om dokumentladdningsalternativ beroende på filtyp: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen till källdokumentet. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Funktionen för dokumentets laddningsalternativ. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


Initierar en ny instans av  klass.**Learn more**Mer om hur man laddar och konverterar dokument som lagras på FTP, Amazon S3 Storage, Windows Azure eller någon annan tredjepartslagring: [Loading document from different sources][]Mer om dokumentladdningsalternativ beroende på filtyp: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen till källdokumentet. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Funktionen för dokumentets laddningsalternativ. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Leverantören av Converter-inställningar. |

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vendor | java.lang.String |  |
| version | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Konverterar källdokumentet. Sparar hela det konverterade dokumentet.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Leverantören av utdataström. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De konverteringsalternativen som är specifika för önskad målfiltyp. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Konverterar källdokumentet. Sparar hela det konverterade dokumentet. **Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | leverantör av utdataflöde |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | delegaten som tar emot det konverterade dokumentflödet. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | de konverteringsalternativen som är specifika för önskad målfiltyp. |

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Konverterar källdokumentet. Sparar hela det konverterade dokumentet.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Leverantören av utdataström. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Leverantör av konverteringsalternativ. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ för önskad mål dokumenttyp. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Konverterar källdokumentet. Sparar hela det konverterade dokumentet.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Leverantören av utdataström. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Delegaten som tar emot det konverterade dokumentflödet. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Leverantör av konverteringsalternativ. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ för önskad mål dokumenttyp. |

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Konverterar källdokumentet. Sparar hela det konverterade dokumentet.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Funktion för utdataflöde. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De konverteringsalternativen som är specifika för önskad målfiltyp. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Konverterar källdokumentet. Sparar hela det konverterade dokumentet.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Funktion för utdataflöde |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Delegaten som tar emot det konverterade dokumentflödet |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De konverteringsalternativen som är specifika för önskad målfiltyp |

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Konverterar källdokumentet. Sparar hela det konverterade dokumentet.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Funktion för utdataflöde. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Leverantör av konverteringsalternativ. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ för önskad mål dokumenttyp. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Konverterar källdokumentet. Sparar hela det konverterade dokumentet.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Funktion för utdataflöde. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Delegaten som tar emot det konverterade dokumentflödet. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Leverantör av konverteringsalternativ. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ för önskad mål dokumenttyp. |

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Konverterar källdokumentet. Sparar hela det konverterade dokumentet.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen till källdokumentet. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De konverteringsalternativen som är specifika för önskad målfiltyp. |

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Funktionen för sidans utdataflöde. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De konverteringsalternativen som är specifika för önskad målfiltyp. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida. **Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Funktionen för utdataflöde. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Delegaten som tar emot det konverterade dokumentets sidström. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De konverteringsalternativen som är specifika för önskad målfiltyp. |

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Funktionen för utdataflöde. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Leverantör av konverteringsalternativ. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ för önskad mål dokumenttyp. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Funktion för utdataflöde. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Delegaten som tar emot det konverterade dokumentets sidström. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Leverantör av konverteringsalternativ. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ för önskad mål dokumenttyp. |

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | En funktion för utdataflöde. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De konverteringsalternativen som är specifika för önskad målfiltyp. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | En funktion för utdataflöde. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Delegaten som tar emot det konverterade dokumentets sidström. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | De konverteringsalternativen som är specifika för önskad målfiltyp. |

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | En funktion för utdataflöde. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Leverantör av konverteringsalternativ. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ för önskad mål dokumenttyp. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.**Learn more**Mer om grundläggande scenarier för dokumentkonvertering: [How to convert document in 3 steps][]Användningsfall för konvertering, avancerade inställningar och anpassningar: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | En funktion för utdataflöde. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Delegaten som tar emot det konverterade dokumentets sidström. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Leverantör av konverteringsalternativ. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ för önskad mål dokumenttyp. |

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Hämtar information om källdokumentet – sidantal och andra dokumentegenskaper som är specifika för filtypen.

**Learn more**Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info][]


[How to get document info]: https://docs.groupdocs.com/display/conversionnet/Get+document+info

**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info
### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Kontrollerar om källdokumentet är lösenordsskyddat.

**Returns:**
boolean - true om dokumentet är lösenordsskyddat **Learn more**Läs mer om det konverterade dokumentet - filtyp, sidantal, skapandedatum och många andra format‑specifika egenskaper: [How to check is the document password protected][]


[How to check is the document password protected]: https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected
### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Hämtar möjliga konverteringar för källdokumentet.

**Learn more**Learn more about supported conversions: [Full list of supported conversions][]Learn more about available conversions: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Hämtar alla stödda konverteringar **Läs mer**Läs mer om stödda konverteringar: [Full list of supported conversions][]Läs mer om tillgängliga konverteringar: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - stödda konverteringar
### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Hämtar stödda konverteringar för angiven dokumentändelse Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**Läs mer**Läs mer om stödda konverteringar: [Full list of supported conversions][]Läs mer om tillgängliga konverteringar: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filändelse | java.lang.String | Dokumentfiländelse |

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### dispose() {#dispose--}
```
public final void dispose()
```


Frigör resurser.

### close() {#close--}
```
public void close()
```




