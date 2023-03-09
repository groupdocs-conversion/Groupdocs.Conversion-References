---
title: Converter
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Menginisialisasi instance baruConvertergroupdocs.conversion/converter kelas.
type: docs
weight: 10
url: /id/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(Func<Stream> document)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*document* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| settings | Func`1 | Pengaturan Konverter. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | Func`1 | Metode yang mengembalikan opsi pemuatan dokumen. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | Func`1 | Metode yang mengembalikan opsi pemuatan dokumen. |
| settings | Func`1 | Pengaturan Konverter. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | Func`2 | Metode yang mengembalikan opsi pemuatan dokumen. Jenis file sumber |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | Func`2 | Metode yang mengembalikan opsi pemuatan dokumen. Jenis file sumber |
| settings | Func`1 | Pengaturan Konverter. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| settings | Func`1 | Pengaturan Konverter. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| loadOptions | Func`1 | Metode yang mengembalikan opsi pemuatan dokumen. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| loadOptions | Func`1 | Metode yang mengembalikan opsi pemuatan dokumen. |
| settings | Func`1 | Pengaturan Konverter. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| loadOptions | Func`2 | Metode yang mengembalikan opsi pemuatan dokumen. Jenis file sumber |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Menginisialisasi instance baru[`Converter`](../../converter) kelas.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| loadOptions | Func`2 | Metode yang mengembalikan opsi pemuatan dokumen. Jenis file sumber |
| settings | Func`1 | Pengaturan Konverter. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara memuat dan mengonversi dokumen yang disimpan di FTP, Penyimpanan Amazon S3, Windows Azure, atau penyimpanan pihak ketiga lainnya: [Memuat dokumen dari berbagai sumber](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Lebih lanjut tentang opsi pemuatan dokumen tergantung pada jenis file: [Muat opsi untuk berbagai jenis dokumen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Menginisialisasi instance baru[`Converter`](../../converter) kelas untuk penyiapan konversi yang lancar.

```csharp
public Converter()
```

### Perkataan

Contoh penggunaan konversi lancar:

```csharp
var converter = new Converter();
```

```csharp
converter
    .Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
converter
    .WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
converter
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
    .OnConversionCompleted((number, stream) => {})
    .Convert();
```

```csharp
converter.Load("").GetPossibleConversions();
converter.Load("").GetDocumentInfo();
converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### Lihat juga

* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
