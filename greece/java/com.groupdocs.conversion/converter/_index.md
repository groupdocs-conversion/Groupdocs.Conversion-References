---
title: "Μετατροπέας"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία μετατροπής εγγράφων."
type: docs
weight: 10
url: /el/java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία μετατροπής εγγράφων.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Converter()](#Converter--) | Αρχικοποιεί νέα παρουσία της κλάσης για ρυθμίσεις άνετης μετατροπής. |
|
|  | [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
|  | [Converter(String filePath)](#Converter-java.lang.String-) | Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) |  |
|  | [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Αρχικοποιεί νέα παρουσία της κλάσης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
|  | [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Μετατρέπει το πηγαίο έγγραφο. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Μετατρέπει το πηγαίο έγγραφο. |
|
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
|  | [getDocumentInfo()](#getDocumentInfo--) | Λαμβάνει πληροφορίες πηγής εγγράφου - αριθμός σελίδων και άλλες ιδιότητες εγγράφου ειδικές για τον τύπο αρχείου. |
|
|  | [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Ελέγχει αν το πηγαίο έγγραφο είναι προστατευμένο με κωδικό. |
|
|  | [getPossibleConversions()](#getPossibleConversions--) | Λαμβάνει πιθανές μετατροπές για το πηγαίο έγγραφο. |
|
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Αποκτά όλες τις υποστηριζόμενες μετατροπές **Μάθετε περισσότερα** Μάθετε περισσότερα για τις υποστηριζόμενες μετατροπές: [Πλήρης λίστα υποστηριζόμενων μετατροπών](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Μάθετε περισσότερα για τις διαθέσιμες μετατροπές: [Πώς να λάβετε υποστηριζόμενες μετατροπές σε κώδικα](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Αποκτά τις υποστηριζόμενες μετατροπές για την παρεχόμενη επέκταση εγγράφου Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Μάθετε περισσότερα** Μάθετε περισσότερα για τις υποστηριζόμενες μετατροπές: [Πλήρης λίστα υποστηριζόμενων μετατροπών](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Μάθετε περισσότερα για τις διαθέσιμες μετατροπές: [Πώς να λάβετε υποστηριζόμενες μετατροπές σε κώδικα](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [dispose()](#dispose--) | Απελευθερώνει πόρους. |
|
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Αρχικοποιεί νέα παρουσία της κλάσης για ρυθμίσεις άνετης μετατροπής. Παράδειγμα χρήσης άνετης μετατροπής: `
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


Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter).


**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.util.function.Supplier<java.io.InputStream> | προμηθευτής ροής εισόδου. |
|

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.util.function.Supplier<java.io.InputStream> | Ένας προμηθευτής ροής εισόδου. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ένας προμηθευτής ρυθμίσεων Converter. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.util.function.Supplier<java.io.InputStream> | Ένας προμηθευτής ροής εισόδου. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Ένας προμηθευτής επιλογών φόρτωσης. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.util.function.Supplier<java.io.InputStream> | Ένας προμηθευτής ροής εισόδου. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Ένας προμηθευτής επιλογών φόρτωσης εγγράφου. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ένας προμηθευτής ρυθμίσεων Converter. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Αρχικοποιεί νέα παρουσία της κλάσης. **Learn more** Περισσότερα για το πώς να φορτώνετε και να μετατρέπετε έγγραφα που αποθηκεύονται σε FTP, Amazon S3 Storage, Windows Azure ή οποιαδήποτε άλλη αποθήκη τρίτου μέρους: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Περισσότερα για τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.util.function.Supplier<java.io.InputStream> | Ένας προμηθευτής ροής εισόδου. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Η συνάρτηση που επιστρέφει τις επιλογές φόρτωσης εγγράφου. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


Αρχικοποιεί νέα παρουσία της κλάσης. **Learn more** Περισσότερα για το πώς να φορτώνετε και να μετατρέπετε έγγραφα που αποθηκεύονται σε FTP, Amazon S3 Storage, Windows Azure ή οποιαδήποτε άλλη αποθήκη τρίτου μέρους: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Περισσότερα για τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.util.function.Supplier<java.io.InputStream> | Ένας προμηθευτής που επιστρέφει αναγνώσιμη ροή. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Μια συνάρτηση που επιστρέφει τις επιλογές φόρτωσης εγγράφου. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης. **Learn more** Περισσότερα για το πώς να φορτώνετε και να μετατρέπετε έγγραφα που αποθηκεύονται σε FTP, Amazon S3 Storage, Windows Azure ή οποιαδήποτε άλλη αποθήκη τρίτου μέρους: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Περισσότερα για τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.util.function.Supplier<java.io.InputStream> | Ένας προμηθευτής που επιστρέφει αναγνώσιμη ροή. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Μια συνάρτηση που επιστρέφει τις επιλογές φόρτωσης εγγράφου. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ένας προμηθευτής ρυθμίσεων Converter. |
|

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
|

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ένας προμηθευτής ρυθμίσεων Converter. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Ο προμηθευτής επιλογών φόρτωσης. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Ο προμηθευτής επιλογών φόρτωσης εγγράφου. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ο προμηθευτής ρυθμίσεων Converter. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Αρχικοποιεί νέα παρουσία της κλάσης. **Learn more** Περισσότερα για το πώς να φορτώνετε και να μετατρέπετε έγγραφα που αποθηκεύονται σε FTP, Amazon S3 Storage, Windows Azure ή οποιαδήποτε άλλη αποθήκη τρίτου μέρους: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Περισσότερα για τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Η συνάρτηση επιλογών φόρτωσης εγγράφου. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) |  |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης. **Learn more** Περισσότερα για το πώς να φορτώνετε και να μετατρέπετε έγγραφα που αποθηκεύονται σε FTP, Amazon S3 Storage, Windows Azure ή οποιαδήποτε άλλη αποθήκη τρίτου μέρους: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Περισσότερα για τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Η συνάρτηση επιλογών φόρτωσης εγγράφου. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Ο προμηθευτής ρυθμίσεων Converter. |
|

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| προμηθευτής | java.lang.String |  |
| έκδοση | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Ο προμηθευτής ροής εξόδου. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Οι επιλογές μετατροπής συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | προμηθευτής ροής εξόδου |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | ο αντιπρόσωπος που λαμβάνει τη ροή του μετατρεπόμενου εγγράφου. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | οι επιλογές μετατροπής συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
|

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Ο προμηθευτής ροής εξόδου. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Πάροχος επιλογών μετατροπής. Θα κληθεί για κάθε μετατροπή ώστε να παρέχει συγκεκριμένες επιλογές μετατροπής για τον επιθυμητό τύπο εγγράφου προορισμού. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Ο προμηθευτής ροής εξόδου. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Ο αντιπρόσωπος που λαμβάνει τη ροή του μετατρεπόμενου εγγράφου. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Πάροχος επιλογών μετατροπής. Θα κληθεί για κάθε μετατροπή ώστε να παρέχει συγκεκριμένες επιλογές μετατροπής για τον επιθυμητό τύπο εγγράφου προορισμού. |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Συνάρτηση ροής εξόδου. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Οι επιλογές μετατροπής συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Συνάρτηση ροής εξόδου |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Ο αντιπρόσωπος που λαμβάνει τη ροή του μετατρεπόμενου εγγράφου |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Οι επιλογές μετατροπής συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Συνάρτηση ροής εξόδου. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Πάροχος επιλογών μετατροπής. Θα κληθεί για κάθε μετατροπή ώστε να παρέχει συγκεκριμένες επιλογές μετατροπής για τον επιθυμητό τύπο εγγράφου προορισμού. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Συνάρτηση ροής εξόδου. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Ο αντιπρόσωπος που λαμβάνει τη ροή του μετατρεπόμενου εγγράφου. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Πάροχος επιλογών μετατροπής. Θα κληθεί για κάθε μετατροπή ώστε να παρέχει συγκεκριμένες επιλογές μετατροπής για τον επιθυμητό τύπο εγγράφου προορισμού. |
|

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Οι επιλογές μετατροπής συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
|

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Η συνάρτηση ροής εξόδου σελίδας. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Οι επιλογές μετατροπής συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Η συνάρτηση ροής εξόδου. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Ο αντιπρόσωπος που λαμβάνει τη ροή σελίδας του μετατρεπόμενου εγγράφου. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Οι επιλογές μετατροπής συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
|

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Η συνάρτηση ροής εξόδου. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Πάροχος επιλογών μετατροπής. Θα κληθεί για κάθε μετατροπή ώστε να παρέχει συγκεκριμένες επιλογές μετατροπής για τον επιθυμητό τύπο εγγράφου προορισμού. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Συνάρτηση ροής εξόδου. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Ο αντιπρόσωπος που λαμβάνει τη ροή σελίδας του μετατρεπόμενου εγγράφου. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Πάροχος επιλογών μετατροπής. Θα κληθεί για κάθε μετατροπή ώστε να παρέχει συγκεκριμένες επιλογές μετατροπής για τον επιθυμητό τύπο εγγράφου προορισμού. |
|

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Μια συνάρτηση ροής εξόδου. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Οι επιλογές μετατροπής συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Μια συνάρτηση ροής εξόδου. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Ο αντιπρόσωπος που λαμβάνει τη ροή σελίδας του μετατρεπόμενου εγγράφου. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Οι επιλογές μετατροπής συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
|

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Μια συνάρτηση ροής εξόδου. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Πάροχος επιλογών μετατροπής. Θα κληθεί για κάθε μετατροπή ώστε να παρέχει συγκεκριμένες επιλογές μετατροπής για τον επιθυμητό τύπο εγγράφου προορισμού. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Μετατρέπει το πηγαίο έγγραφο. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα. **Μάθετε περισσότερα** Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Περιστατικά χρήσης μετατροπής, προχωρημένες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προχωρημένες ρυθμίσεις](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Μια συνάρτηση ροής εξόδου. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Ο αντιπρόσωπος που λαμβάνει τη ροή σελίδας του μετατρεπόμενου εγγράφου. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Πάροχος επιλογών μετατροπής. Θα κληθεί για κάθε μετατροπή ώστε να παρέχει συγκεκριμένες επιλογές μετατροπής για τον επιθυμητό τύπο εγγράφου προορισμού. |
|

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Λαμβάνει πληροφορίες πηγής εγγράφου - αριθμός σελίδων και άλλες ιδιότητες εγγράφου ειδικές για τον τύπο αρχείου.
**Learn more** Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](../https://docs.groupdocs.com/display/conversionnet/Get+document+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info

### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Ελέγχει αν το πηγαίο έγγραφο είναι προστατευμένο με κωδικό.


**Returns:**
boolean - true εάν το έγγραφο είναι προστατευμένο με κωδικό **Μάθετε περισσότερα** Μάθετε περισσότερα για το μετατρεπόμενο έγγραφο - τύπο αρχείου, αριθμό σελίδων, ημερομηνία δημιουργίας και πολλές άλλες ιδιότητες ειδικές για τη μορφή: [Πώς να ελέγξετε αν το έγγραφο είναι προστατευμένο με κωδικό](../https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected)

### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Λαμβάνει πιθανές μετατροπές για το πηγαίο έγγραφο.
**Learn more** Learn more about supported conversions: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Learn more about available conversions: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Αποκτά όλες τις υποστηριζόμενες μετατροπές **Μάθετε περισσότερα** Μάθετε περισσότερα για τις υποστηριζόμενες μετατροπές: [Πλήρης λίστα υποστηριζόμενων μετατροπών](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Μάθετε περισσότερα για τις διαθέσιμες μετατροπές: [Πώς να λάβετε υποστηριζόμενες μετατροπές σε κώδικα](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - υποστηριζόμενες μετατροπές

### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Αποκτά τις υποστηριζόμενες μετατροπές για την παρεχόμενη επέκταση εγγράφου Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx") **Μάθετε περισσότερα** Μάθετε περισσότερα για τις υποστηριζόμενες μετατροπές: [Πλήρης λίστα υποστηριζόμενων μετατροπών](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Μάθετε περισσότερα για τις διαθέσιμες μετατροπές: [Πώς να λάβετε υποστηριζόμενες μετατροπές σε κώδικα](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | επέκταση | java.lang.String | Επέκταση εγγράφου |
|

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### dispose() {#dispose--}
```
public final void dispose()
```


Απελευθερώνει πόρους.


### close() {#close--}
```
public void close()
```




