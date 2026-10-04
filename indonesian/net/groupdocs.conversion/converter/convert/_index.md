---
title: "Konversi"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi."
type: docs
weight: 20
url: /id/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegasi yang menyimpan dokumen yang dikonversi ke aliran. |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk tipe file target yang diinginkan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Catatan

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat Juga

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk tipe file target yang diinginkan. |
| documentCompleted | Action`1 | Delegasi yang menerima aliran dokumen yang dikonversi. Signature: `Action<ConvertedContext>`. Parameter [`ConvertedContext`](../../convertedcontext) berisi aliran dokumen yang dikonversi dan metadata. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Catatan

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat Juga

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegasi yang menyediakan aliran untuk menyimpan dokumen yang dikonversi. Signature: `Func<SaveContext, Stream>`. Parameter [`SaveContext`](../../savecontext) berisi informasi tentang operasi penyimpanan. |
| convertOptionsProvider | Func`2 | Delegasi yang menyediakan opsi konversi. Signature: `Func<ConvertContext, ConvertOptions>`. Parameter [`ConvertContext`](../../convertcontext) berisi informasi tentang operasi konversi. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Catatan

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat Juga

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegasi yang menyediakan opsi konversi. Signature: `Func<ConvertContext, ConvertOptions>`. Parameter [`ConvertContext`](../../convertcontext) berisi informasi tentang operasi konversi. |
| documentCompleted | Action`1 | Delegasi yang menerima aliran dokumen yang dikonversi. Signature: `Action<ConvertedContext>`. Parameter [`ConvertedContext`](../../convertedcontext) berisi aliran dokumen yang dikonversi dan metadata. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Catatan

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat Juga

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang telah dikonversi.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file ke dokumen sumber. |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk tipe file target yang diinginkan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Catatan

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat Juga

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman per halaman.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegasi yang menyediakan aliran untuk menyimpan setiap halaman yang dikonversi. Signature: `Func<SavePageContext, Stream>`. Parameter [`SavePageContext`](../../savepagecontext) berisi nomor halaman dan informasi dokumen. |
| convertOptionsProvider | Func`2 | Delegasi yang menyediakan opsi konversi. Signature: `Func<ConvertContext, ConvertOptions>`. Parameter [`ConvertContext`](../../convertcontext) berisi informasi tentang operasi konversi. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Catatan

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat Juga

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman per halaman.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegasi yang menyediakan aliran untuk menyimpan setiap halaman yang dikonversi. Signature: `Func<SavePageContext, Stream>`. Parameter [`SavePageContext`](../../savepagecontext) berisi nomor halaman dan informasi dokumen. |
| convertOptions | ConvertOptions | Opsi konversi khusus untuk tipe file target yang diinginkan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Catatan

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat Juga

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman per halaman.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Delegasi yang menerima setiap halaman yang dikonversi. Signature: `Action<ConvertedPageContext>`. Parameter [`ConvertedPageContext`](../../convertedpagecontext) berisi nomor halaman, aliran, nama file sumber, dan tipe file target. |
| convertOptions | Action`1 | Opsi konversi khusus untuk tipe file target yang diinginkan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Catatan

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat Juga

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Mengonversi dokumen sumber. Menyimpan dokumen yang dikonversi halaman per halaman.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegasi yang menyediakan opsi konversi. Signature: `Func<ConvertContext, ConvertOptions>`. Parameter [`ConvertContext`](../../convertcontext) berisi informasi tentang operasi konversi. |
| documentCompleted | Action`1 | Delegasi yang menerima setiap halaman yang dikonversi. Signature: `Action<ConvertedPageContext>`. Parameter [`ConvertedPageContext`](../../convertedpagecontext) berisi nomor halaman, aliran, nama file sumber, dan tipe file target. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Catatan

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Lihat Juga

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
