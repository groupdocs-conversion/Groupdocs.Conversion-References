---
title: "Convert"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder."
type: docs
weight: 20
url: /tr/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Dönüştürülmüş belgeyi bir akışa kaydeden temsilci. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Açıklamalar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca Bakınız

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |
| documentCompleted | Action`1 | Dönüştürülmüş belge akışını alan temsilci. İmza: `Action<ConvertedContext>`. [`ConvertedContext`](../../convertedcontext) parametresi, dönüştürülmüş belge akışını ve meta verileri içerir. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Açıklamalar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca Bakınız

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Dönüştürülmüş belgeyi kaydetmek için akışı sağlayan temsilci. İmza: `Func<SaveContext, Stream>`. [`SaveContext`](../../savecontext) parametresi, kaydetme işlemi hakkında bilgi içerir. |
| convertOptionsProvider | Func`2 | Dönüştürme seçeneklerini sağlayan temsilci. İmza: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) parametresi, dönüştürme işlemi hakkında bilgi içerir. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Açıklamalar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca Bakınız

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Dönüştürme seçeneklerini sağlayan temsilci. İmza: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) parametresi, dönüştürme işlemi hakkında bilgi içerir. |
| documentCompleted | Action`1 | Dönüştürülmüş belge akışını alan temsilci. İmza: `Action<ConvertedContext>`. [`ConvertedContext`](../../convertedcontext) parametresi, dönüştürülmüş belge akışını ve meta verileri içerir. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Açıklamalar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca Bakınız

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Kaynak belgeyi dönüştürür. Dönüştürülmüş belgenin tamamını kaydeder.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Kaynak belgenin dosya yolu. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Açıklamalar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca Bakınız

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Her dönüştürülmüş sayfayı kaydetmek için bir akış sağlayan temsilci. İmza: `Func<SavePageContext, Stream>`. [`SavePageContext`](../../savepagecontext) parametresi, sayfa numarası ve belge bilgilerini içerir. |
| convertOptionsProvider | Func`2 | Dönüştürme seçeneklerini sağlayan temsilci. İmza: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) parametresi, dönüştürme işlemi hakkında bilgi içerir. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Açıklamalar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca Bakınız

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Her dönüştürülmüş sayfayı kaydetmek için bir akış sağlayan temsilci. İmza: `Func<SavePageContext, Stream>`. [`SavePageContext`](../../savepagecontext) parametresi, sayfa numarası ve belge bilgilerini içerir. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Açıklamalar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca Bakınız

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Her dönüştürülmüş sayfayı alan temsilci. İmza: `Action<ConvertedPageContext>`. [`ConvertedPageContext`](../../convertedpagecontext) parametresi, sayfa numarasını, akışı, kaynak dosya adını ve hedef dosya türünü içerir. |
| convertOptions | Action`1 | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Açıklamalar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca Bakınız

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Kaynak belgeyi dönüştürür. Dönüştürülmüş belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Dönüştürme seçeneklerini sağlayan temsilci. İmza: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) parametresi, dönüştürme işlemi hakkında bilgi içerir. |
| documentCompleted | Action`1 | Her dönüştürülmüş sayfayı alan temsilci. İmza: `Action<ConvertedPageContext>`. [`ConvertedPageContext`](../../convertedpagecontext) parametresi, sayfa numarasını, akışı, kaynak dosya adını ve hedef dosya türünü içerir. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Açıklamalar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca Bakınız

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
