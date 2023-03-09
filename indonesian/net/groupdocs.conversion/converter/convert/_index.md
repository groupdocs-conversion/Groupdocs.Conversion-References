---
title: Convert
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.
type: docs
weight: 20
url: /id/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk jenis file target yang diinginkan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. |
| documentCompleted | Action`2 | Delegasi yang menerima aliran dokumen yang dikonversi. Aliran konten fileNama file |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk jenis file target yang diinginkan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. |
| convertOptionsProvider | Func`3 | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk memberikan opsi konversi spesifik ke jenis dokumen target yang diinginkan. Nama fileJenis file |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. |
| documentCompleted | Action`2 | Delegasi yang menerima aliran dokumen yang dikonversi. Aliran konten fileNama file |
| convertOptionsProvider | Func`3 | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk memberikan opsi konversi spesifik ke jenis dokumen target yang diinginkan. Nama fileJenis file |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`2 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. Jenis file sumber |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk jenis file target yang diinginkan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`2 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. Jenis file sumber |
| documentCompleted | Action`2 | Delegasi yang menerima aliran dokumen yang dikonversi. Aliran konten fileNama file |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk jenis file target yang diinginkan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`2 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. Jenis file sumber |
| convertOptionsProvider | Func`3 | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk memberikan opsi konversi spesifik ke jenis dokumen target yang diinginkan. Nama fileJenis file |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`2 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. Jenis file sumber |
| documentCompleted | Action`2 | Delegasi yang menerima aliran dokumen yang dikonversi. Aliran konten fileNama file |
| convertOptionsProvider | Func`3 | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk memberikan opsi konversi spesifik ke jenis dokumen target yang diinginkan. Nama fileJenis file |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk jenis file target yang diinginkan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`2 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. Nomor halaman |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk jenis file target yang diinginkan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`2 | Delegasi yang menyimpan halaman dokumen yang dikonversi ke aliran. Nomor halaman |
| documentCompleted | Action`3 | Delegasi yang menerima aliran halaman dokumen yang dikonversi. Nomor halamanAliran konten fileNama file |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk jenis file target yang diinginkan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`2 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. Nomor halaman |
| convertOptionsProvider | Func`3 | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk memberikan opsi konversi spesifik ke jenis dokumen target yang diinginkan. Nama fileJenis file |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`2 | Delegasi yang menyimpan halaman dokumen yang dikonversi ke aliran. Nomor halaman |
| documentCompleted | Action`3 | Delegasi yang menerima aliran halaman dokumen yang dikonversi. Nomor halamanAliran konten fileNama file |
| convertOptionsProvider | Func`3 | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk memberikan opsi konversi spesifik ke jenis dokumen target yang diinginkan. Nama fileJenis file |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`3 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. Nomor halaman |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk jenis file target yang diinginkan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`3 | Delegasi yang menyimpan halaman dokumen yang dikonversi ke aliran. Nomor halamanJenis berkas |
| documentCompleted | Action`3 | Delegasi yang menerima aliran halaman dokumen yang dikonversi. Nomor halamanAliran konten fileNama file |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk jenis file target yang diinginkan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`3 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. Nomor halamanJenis berkas |
| convertOptionsProvider | Func`3 | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk memberikan opsi konversi spesifik ke jenis dokumen target yang diinginkan. Nama fileJenis file |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`3 | Delegasi yang menyimpan halaman dokumen yang dikonversi ke aliran. Nomor halamanJenis berkas |
| documentCompleted | Action`3 | Delegasi yang menerima aliran halaman dokumen yang dikonversi. Nomor halamanAliran konten fileNama file |
| convertOptionsProvider | Func`3 | Penyedia opsi konversi. Akan dipanggil untuk setiap konversi untuk memberikan opsi konversi spesifik ke jenis dokumen target yang diinginkan. Nama fileJenis file |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang skenario dasar konversi dokumen: [Cara mengonversi dokumen dalam 3 langkah](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Kasus penggunaan konversi, setelan lanjutan, dan penyesuaian: [Konversikan dokumen dengan pengaturan lanjutan](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat juga

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ruang nama [GroupDocs.Conversion](../../converter)
* perakitan [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
