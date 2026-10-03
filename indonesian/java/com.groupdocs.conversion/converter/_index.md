---
title: "Converter"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili kelas utama yang mengontrol proses konversi dokumen."
type: docs
weight: 10
url: /id/java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

Mewakili kelas utama yang mengontrol proses konversi dokumen.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Converter()](#Converter--) | Menginisialisasi instance baru dari kelas untuk pengaturan konversi yang lancar. |
|
|  | [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Menginisialisasi instance baru dari kelas. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | Menginisialisasi instance baru dari kelas. |
|
|  | [Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Menginisialisasi instance baru dari kelas. |
|
|  | [Converter(String filePath)](#Converter-java.lang.String-) | Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter). |
|
|  | [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Menginisialisasi instance baru dari kelas. |
|
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) |  |
|  | [Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | Menginisialisasi instance baru dari kelas. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
|  | [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Mengonversi dokumen sumber. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Mengonversi dokumen sumber. |
|
|  | [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Mengonversi dokumen sumber. |
|
|  | [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Mengonversi dokumen sumber. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Mengonversi dokumen sumber. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Mengonversi dokumen sumber. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Mengonversi dokumen sumber. |
|
|  | [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Mengonversi dokumen sumber. |
|
|  | [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | Mengonversi dokumen sumber. |
|
|  | [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Mengonversi dokumen sumber. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Mengonversi dokumen sumber. |
|
|  | [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Mengonversi dokumen sumber. |
|
|  | [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Mengonversi dokumen sumber. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | Mengonversi dokumen sumber. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | Mengonversi dokumen sumber. |
|
|  | [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Mengonversi dokumen sumber. |
|
|  | [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Mengonversi dokumen sumber. |
|
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
|  | [getDocumentInfo()](#getDocumentInfo--) | Mendapatkan info dokumen sumber - jumlah halaman dan properti dokumen lainnya yang spesifik untuk tipe file. |
|
|  | [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | Memeriksa apakah dokumen sumber dilindungi kata sandi. |
|
|  | [getPossibleConversions()](#getPossibleConversions--) | Mendapatkan konversi yang memungkinkan untuk dokumen sumber. |
|
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | Mendapatkan semua konversi yang didukung **Learn more** Pelajari lebih lanjut tentang konversi yang didukung: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Pelajari lebih lanjut tentang konversi yang tersedia: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | Mendapatkan konversi yang didukung untuk ekstensi dokumen yang diberikan Converter.GetPossibleConversions(\".docx\") Converter.GetPossibleConversions(\"docx\") **Learn more** Pelajari lebih lanjut tentang konversi yang didukung: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Pelajari lebih lanjut tentang konversi yang tersedia: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions) |
|
|  | [dispose()](#dispose--) | Melepaskan sumber daya. |
|
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


Menginisialisasi instance baru dari kelas untuk pengaturan konversi yang lancar. Contoh penggunaan konversi yang lancar: `
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


Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter).


**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.util.function.Supplier<java.io.InputStream> | pemasok aliran masukan. |
|

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.util.function.Supplier<java.io.InputStream> | Sebuah pemasok aliran masukan. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Sebuah pemasok pengaturan Converter. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.util.function.Supplier<java.io.InputStream> | Sebuah pemasok aliran masukan. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Sebuah pemasok opsi pemuatan. |
|

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.util.function.Supplier<java.io.InputStream> | Sebuah pemasok aliran masukan. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Sebuah pemasok opsi pemuatan dokumen. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Sebuah pemasok pengaturan Converter. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


Menginisialisasi instance baru dari kelas. **Learn more** Selengkapnya tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Amazon S3 Storage, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Selengkapnya tentang opsi pemuatan dokumen yang bergantung pada tipe file: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.util.function.Supplier<java.io.InputStream> | Sebuah pemasok aliran masukan. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Fungsi yang mengembalikan opsi pemuatan dokumen. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


Menginisialisasi instance baru dari kelas. **Learn more** Selengkapnya tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Amazon S3 Storage, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Selengkapnya tentang opsi pemuatan dokumen yang bergantung pada tipe file: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.util.function.Supplier<java.io.InputStream> | Sebuah pemasok yang mengembalikan aliran yang dapat dibaca. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Sebuah fungsi yang mengembalikan opsi pemuatan dokumen. |
|

### Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Menginisialisasi instance baru dari kelas. **Learn more** Selengkapnya tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Amazon S3 Storage, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Selengkapnya tentang opsi pemuatan dokumen yang bergantung pada tipe file: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.util.function.Supplier<java.io.InputStream> | Sebuah pemasok yang mengembalikan aliran yang dapat dibaca. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Sebuah fungsi yang mengembalikan opsi pemuatan dokumen. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Sebuah pemasok pengaturan Converter. |
|

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file ke dokumen sumber. |
|

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file ke dokumen sumber. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Sebuah pemasok pengaturan Converter. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file ke dokumen sumber. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Pemasok opsi pemuatan. |
|

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


Menginisialisasi instance baru dari kelas [Converter](../../com.groupdocs.conversion/converter).
**Learn more** More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) More about document loading options dependent on file type: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file ke dokumen sumber. |
|
|  | loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Pemasok opsi pemuatan dokumen. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Pemasok pengaturan Converter. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


Menginisialisasi instance baru dari kelas. **Learn more** Selengkapnya tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Amazon S3 Storage, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Selengkapnya tentang opsi pemuatan dokumen yang bergantung pada tipe file: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file ke dokumen sumber. |
|
|  | loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Fungsi opsi pemuatan dokumen. |
|

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) |  |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String |  |
| loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

### Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForNameFileTypeStreamProvider loadOptions, ConverterSettingsProvider settings)
```


Menginisialisasi instance baru dari kelas. **Learn more** Selengkapnya tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Amazon S3 Storage, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Loading document from different sources](../https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources) Selengkapnya tentang opsi pemuatan dokumen yang bergantung pada tipe file: [Load options for different document types](../https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file ke dokumen sumber. |
|
|  | loadOptions | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) | Fungsi opsi pemuatan dokumen. |
|
|  | settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Pemasok pengaturan Converter. |
|

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vendor | java.lang.String |  |
| versi | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Penyedia aliran keluaran. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Opsi konversi spesifik untuk tipe file target yang diinginkan. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | penyedia aliran keluaran |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | delegasi yang menerima aliran dokumen yang dikonversi. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | opsi konversi spesifik untuk tipe file target yang diinginkan. |
|

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Penyedia aliran keluaran. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk menyediakan opsi konversi spesifik ke tipe dokumen target yang diinginkan. |
|

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Penyedia aliran keluaran. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Delegasi yang menerima aliran dokumen yang dikonversi. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk menyediakan opsi konversi spesifik ke tipe dokumen target yang diinginkan. |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Fungsi aliran keluaran. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Opsi konversi spesifik untuk tipe file target yang diinginkan. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Fungsi aliran keluaran |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Delegasi yang menerima aliran dokumen yang dikonversi |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Opsi konversi spesifik untuk tipe file target yang diinginkan |
|

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Fungsi aliran keluaran. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk menyediakan opsi konversi spesifik ke tipe dokumen target yang diinginkan. |
|

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Fungsi aliran keluaran. |
|
|  | documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Delegasi yang menerima aliran dokumen yang dikonversi. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk menyediakan opsi konversi spesifik ke tipe dokumen target yang diinginkan. |
|

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file ke dokumen sumber. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Opsi konversi spesifik untuk tipe file target yang diinginkan. |
|

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman demi halaman.
**Learn more** More about document conversion basic scenarios: [How to convert document in 3 steps](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Fungsi aliran keluaran halaman. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Opsi konversi spesifik untuk tipe file target yang diinginkan. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman demi halaman. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Fungsi aliran keluaran. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Delegasi yang menerima aliran halaman dokumen yang dikonversi. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Opsi konversi spesifik untuk tipe file target yang diinginkan. |
|

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman demi halaman. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Fungsi aliran keluaran. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk menyediakan opsi konversi spesifik ke tipe dokumen target yang diinginkan. |
|

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman demi halaman. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Fungsi aliran keluaran. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Delegasi yang menerima aliran halaman dokumen yang dikonversi. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk menyediakan opsi konversi spesifik ke tipe dokumen target yang diinginkan. |
|

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman demi halaman. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Sebuah fungsi aliran keluaran. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Opsi konversi spesifik untuk tipe file target yang diinginkan. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman demi halaman. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Sebuah fungsi aliran keluaran. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Delegasi yang menerima aliran halaman dokumen yang dikonversi. |
|
|  | convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Opsi konversi spesifik untuk tipe file target yang diinginkan. |
|

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman demi halaman. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Sebuah fungsi aliran keluaran. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk menyediakan opsi konversi spesifik ke tipe dokumen target yang diinginkan. |
|

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman demi halaman. **Pelajari lebih lanjut** Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](../https://docs.groupdocs.com/display/conversionnet/Convert+document) Kasus penggunaan konversi, pengaturan lanjutan dan kustomisasi: [Konversi dokumen dengan pengaturan lanjutan](../https://docs.groupdocs.com/display/conversionnet/Converting)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Sebuah fungsi aliran keluaran. |
|
|  | documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Delegasi yang menerima aliran halaman dokumen yang dikonversi. |
|
|  | convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk menyediakan opsi konversi spesifik ke tipe dokumen target yang diinginkan. |
|

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Mendapatkan info dokumen sumber - jumlah halaman dan properti dokumen lainnya yang spesifik untuk tipe file.
**Learn more** Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](../https://docs.groupdocs.com/display/conversionnet/Get+document+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info

### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


Memeriksa apakah dokumen sumber dilindungi kata sandi.


**Returns:**
boolean - true jika dokumen dilindungi kata sandi **Pelajari lebih lanjut** Pelajari lebih lanjut tentang dokumen yang dikonversi - tipe file, jumlah halaman, tanggal pembuatan, dan banyak properti spesifik format lainnya: [Cara memeriksa apakah dokumen dilindungi kata sandi](../https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected)

### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


Mendapatkan konversi yang memungkinkan untuk dokumen sumber.
**Learn more** Learn more about supported conversions: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Learn more about available conversions: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


Mendapatkan semua konversi yang didukung **Learn more** Pelajari lebih lanjut tentang konversi yang didukung: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Pelajari lebih lanjut tentang konversi yang tersedia: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - konversi yang didukung

### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


Mendapatkan konversi yang didukung untuk ekstensi dokumen yang diberikan Converter.GetPossibleConversions(\".docx\") Converter.GetPossibleConversions(\"docx\") **Learn more** Pelajari lebih lanjut tentang konversi yang didukung: [Full list of supported conversions](../https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats) Pelajari lebih lanjut tentang konversi yang tersedia: [How to get supported conversions in code](../https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi dokumen |
|

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions

### dispose() {#dispose--}
```
public final void dispose()
```


Melepaskan sumber daya.


### close() {#close--}
```
public void close()
```




