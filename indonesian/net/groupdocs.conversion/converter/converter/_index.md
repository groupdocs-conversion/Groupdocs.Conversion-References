---
title: "Converter"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menginisialisasi instance baru dari kelas Convertergroupdocs.conversion/converter."
type: docs
weight: 10
url: /id/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *sourceStreamProvider* bernilai null. |

### Catatan

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat Juga

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| settings | Func`1 | Pengaturan Converter. |

### Catatan

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat Juga

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | Func`2 | Delegasi yang menyediakan opsi muat untuk dokumen. Signature: `Func<LoadContext, LoadOptions>`. Parameter [`LoadContext`](../../loadcontext) berisi informasi tentang dokumen yang sedang dimuat. |
| settings | Func`1 | Pengaturan Converter. |

### Catatan

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat Juga

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter) dengan peristiwa konversi eksplisit.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | Func`2 | Delegasi yang menyediakan opsi pemuatan untuk dokumen. |
| settings | Func`1 | Pengaturan Converter. |
| events | Func`1 | Delegasi yang menyediakan [`ConversionEvents`](../../conversionevents) teragregasi yang terdaftar selama masa pakai konverter. |

### Lihat Juga

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter) dengan peristiwa konversi eksplisit.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| settings | Func`1 | Pengaturan Converter. |
| events | Func`1 | Delegasi yang menyediakan [`ConversionEvents`](../../conversionevents) teragregasi yang terdaftar selama masa pakai konverter. |

### Lihat Juga

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter).

```csharp
public Converter(string filePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |

### Catatan

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat Juga

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| settings | Func`1 | Pengaturan Converter. |

### Catatan

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat Juga

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| loadOptions | Func`2 | Delegasi yang menyediakan opsi muat untuk dokumen. Signature: `Func<LoadContext, LoadOptions>`. Parameter [`LoadContext`](../../loadcontext) berisi informasi tentang dokumen yang sedang dimuat. |
| settings | Func`1 | Pengaturan Converter. |

### Catatan

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Lihat Juga

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter) dengan peristiwa konversi eksplisit.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| loadOptions | Func`2 | Delegasi yang menyediakan opsi pemuatan untuk dokumen. |
| settings | Func`1 | Pengaturan Converter. |
| events | Func`1 | Delegasi yang menyediakan [`ConversionEvents`](../../conversionevents) teragregasi yang terdaftar selama masa pakai konverter. |

### Lihat Juga

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Menginisialisasi instance baru dari kelas [`Converter`](../../converter) dengan peristiwa konversi eksplisit.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| settings | Func`1 | Pengaturan Converter. |
| events | Func`1 | Delegasi yang menyediakan [`ConversionEvents`](../../conversionevents) teragregasi yang terdaftar selama masa pakai konverter. |

### Lihat Juga

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
