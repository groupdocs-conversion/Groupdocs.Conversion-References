---
title: Convert
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.
type: docs
weight: 20
url: /tr/net/groupdocs.conversion/converter/convert/
---
## Convert(SaveDocumentStream, ConvertOptions) {#convert_3}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SaveDocumentStream | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) {#convert_1}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SaveDocumentStream | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| documentCompleted | ConvertedDocumentStream | Dönüştürülen belge akışını alan temsilci. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertOptionsProvider) {#convert_2}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SaveDocumentStream | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| convertOptionsProvider | ConvertOptionsProvider | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) {#convert}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SaveDocumentStream | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| documentCompleted | ConvertedDocumentStream | Dönüştürülen belge akışını alan temsilci. |
| convertOptionsProvider | ConvertOptionsProvider | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptions) {#convert_7}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) {#convert_5}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| documentCompleted | ConvertedDocumentStream | Dönüştürülen belge akışını alan temsilci. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptionsProvider) {#convert_6}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| convertOptionsProvider | ConvertOptionsProvider | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) {#convert_4}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| documentCompleted | ConvertedDocumentStream | Dönüştürülen belge akışını alan temsilci. |
| convertOptionsProvider | ConvertOptionsProvider | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Kaynak belgeye giden dosya yolu. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptions) {#convert_11}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(SavePageStream document, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SavePageStream | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptions) {#convert_9}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SavePageStream | Dönüştürülen belge sayfasını bir akışa kaydeden temsilci. |
| documentCompleted | ConvertedPageStream | Dönüştürülen belge sayfası akışını alan temsilci. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptionsProvider) {#convert_10}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SavePageStream | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| convertOptionsProvider | ConvertOptionsProvider | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) {#convert_8}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SavePageStream | Dönüştürülen belge sayfasını bir akışa kaydeden temsilci. |
| documentCompleted | ConvertedPageStream | Dönüştürülen belge sayfası akışını alan temsilci. |
| convertOptionsProvider | ConvertOptionsProvider | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptions) {#convert_15}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SavePageStreamForFileType | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) {#convert_13}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SavePageStreamForFileType | Dönüştürülen belge sayfasını bir akışa kaydeden temsilci. |
| documentCompleted | ConvertedPageStream | Dönüştürülen belge sayfası akışını alan temsilci. |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptionsProvider) {#convert_14}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(SavePageStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SavePageStreamForFileType | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| convertOptionsProvider | ConvertOptionsProvider | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) {#convert_12}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | SavePageStreamForFileType | Dönüştürülen belge sayfasını bir akışa kaydeden temsilci. |
| documentCompleted | ConvertedPageStream | Dönüştürülen belge sayfası akışını alan temsilci. |
| convertOptionsProvider | ConvertOptionsProvider | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
