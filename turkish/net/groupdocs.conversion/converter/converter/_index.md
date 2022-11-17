---
title: Converter
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Yeni örneğini başlatırConvertergroupdocs.conversion/converter sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(Func<Stream> document)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Okunabilir akış döndüren yöntem. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | ne zaman atıldı*document* boş. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Okunabilir akış döndüren yöntem. |
| settings | Func`1 | Dönüştürücü ayarları. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Okunabilir akış döndüren yöntem. |
| loadOptions | Func`1 | Belge yükleme seçeneklerini döndüren yöntemler. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Okunabilir akış döndüren yöntem. |
| loadOptions | Func`1 | Belge yükleme seçeneklerini döndüren yöntemler. |
| settings | Func`1 | Dönüştürücü ayarları. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Okunabilir akış döndüren yöntem. |
| loadOptions | Func`2 | Belge yükleme seçeneklerini döndüren yöntemler. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Okunabilir akış döndüren yöntem. |
| loadOptions | Func`2 | Belge yükleme seçeneklerini döndüren yöntemler. |
| settings | Func`1 | Dönüştürücü ayarları. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Kaynak belgeye giden dosya yolu. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Kaynak belgeye giden dosya yolu. |
| settings | Func`1 | Dönüştürücü ayarları. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Kaynak belgeye giden dosya yolu. |
| loadOptions | Func`1 | Belge yükleme seçeneklerini döndüren yöntemler. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Kaynak belgeye giden dosya yolu. |
| loadOptions | Func`1 | Belge yükleme seçeneklerini döndüren yöntemler. |
| settings | Func`1 | Dönüştürücü ayarları. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Kaynak belgeye giden dosya yolu. |
| loadOptions | Func`2 | Belge yükleme seçeneklerini döndüren yöntemler. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Yeni örneğini başlatır[`Converter`](../../converter) sınıf.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Kaynak belgeye giden dosya yolu. |
| loadOptions | Func`2 | Belge yükleme seçeneklerini döndüren yöntemler. |
| settings | Func`1 | Dönüştürücü ayarları. |

### Notlar

**Daha fazla bilgi edin**

* FTP, Amazon S3 Storage, Windows Azure veya başka herhangi bir üçüncü taraf depolama alanında depolanan belgelerin nasıl yükleneceği ve dönüştürüleceği hakkında daha fazla bilgi: [Farklı kaynaklardan belge yükleniyor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Dosya türüne bağlı belge yükleme seçenekleri hakkında daha fazla bilgi: [Farklı belge türleri için yükleme seçenekleri](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca bakınız

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Yeni örneğini başlatır[`Converter`](../../converter) akıcı dönüştürme kurulumu için sınıf.

```csharp
public Converter()
```

### Notlar

Örnek akıcı dönüştürme kullanımı:

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

### Ayrıca bakınız

* class [Converter](../../converter)
* ad alanı [GroupDocs.Conversion](../../converter)
* toplantı [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
