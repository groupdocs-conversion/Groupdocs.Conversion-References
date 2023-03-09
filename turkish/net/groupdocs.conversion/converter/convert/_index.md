---
title: Convert
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.
type: docs
weight: 20
url: /tr/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
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

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| documentCompleted | Action`2 | Dönüştürülen belge akışını alan temsilci. Dosya içerik akışıDosyanın adı |
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

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| convertOptionsProvider | Func`3 | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. Dosyanın adıdosyanın türü |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. |
| documentCompleted | Action`2 | Dönüştürülen belge akışını alan temsilci. Dosya içerik akışıDosyanın adı |
| convertOptionsProvider | Func`3 | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. Dosyanın adıdosyanın türü |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`2 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. Kaynak dosyanın türü |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`2 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. Kaynak dosyanın türü |
| documentCompleted | Action`2 | Dönüştürülen belge akışını alan temsilci. Dosya içerik akışıDosyanın adı |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`2 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. Kaynak dosyanın türü |
| convertOptionsProvider | Func`3 | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. Dosyanın adıdosyanın türü |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Kaynak belgeyi dönüştürür. Dönüştürülen belgenin tamamını kaydeder.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`2 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. Kaynak dosyanın türü |
| documentCompleted | Action`2 | Dönüştürülen belge akışını alan temsilci. Dosya içerik akışıDosyanın adı |
| convertOptionsProvider | Func`3 | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. Dosyanın adıdosyanın türü |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
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

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`2 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. Sayfa numarası |
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

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`2 | Dönüştürülen belge sayfasını bir akışa kaydeden temsilci. Sayfa numarası |
| documentCompleted | Action`3 | Dönüştürülen belge sayfası akışını alan temsilci. Sayfa numarasıDosya içerik akışıDosyanın adı |
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

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`2 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. Sayfa numarası |
| convertOptionsProvider | Func`3 | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. Dosyanın adıdosyanın türü |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`2 | Dönüştürülen belge sayfasını bir akışa kaydeden temsilci. Sayfa numarası |
| documentCompleted | Action`3 | Dönüştürülen belge sayfası akışını alan temsilci. Sayfa numarasıDosya içerik akışıDosyanın adı |
| convertOptionsProvider | Func`3 | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. Dosyanın adıdosyanın türü |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`3 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. Sayfa numarası |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`3 | Dönüştürülen belge sayfasını bir akışa kaydeden temsilci. Sayfa numarasıDosya tipi |
| documentCompleted | Action`3 | Dönüştürülen belge sayfası akışını alan temsilci. Sayfa numarasıDosya içerik akışıDosyanın adı |
| convertOptions | ConvertOptions | İstenen hedef dosya türüne özel dönüştürme seçenekleri. |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`3 | Dönüştürülen belgeyi bir akışa kaydeden temsilci. Sayfa numarasıDosya tipi |
| convertOptionsProvider | Func`3 | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. Dosyanın adıdosyanın türü |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Kaynak belgeyi dönüştürür. Dönüştürülen belgeyi sayfa sayfa kaydeder.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`3 | Dönüştürülen belge sayfasını bir akışa kaydeden temsilci. Sayfa numarasıDosya tipi |
| documentCompleted | Action`3 | Dönüştürülen belge sayfası akışını alan temsilci. Sayfa numarasıDosya içerik akışıDosyanın adı |
| convertOptionsProvider | Func`3 | Seçenekler sağlayıcısını dönüştürün. İstenen hedef belge türüne özel dönüştürme seçenekleri sağlamak için her dönüştürme için çağrılacaktır. Dosyanın adıdosyanın türü |

### Notlar

**Daha fazla bilgi edin**

* Belge dönüştürme temel senaryoları hakkında daha fazla bilgi: [3 adımda belge nasıl dönüştürülür](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Dönüşüm kullanım durumları, gelişmiş ayarlar ve özelleştirmeler: [Belgeyi gelişmiş ayarlarla dönüştürün](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
