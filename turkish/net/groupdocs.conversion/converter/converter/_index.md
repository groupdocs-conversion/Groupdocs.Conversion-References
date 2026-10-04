---
title: "Converter"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Convertergroupdocs.conversion/converter sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

[`Converter`](../../converter) sınıfının yeni bir örneğini başlatır.

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Okunabilir akış döndüren yöntem. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceStreamProvider* null olduğunda fırlatılır. |

### Açıklamalar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca Bakınız

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

[`Converter`](../../converter) sınıfının yeni bir örneğini başlatır.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Okunabilir akış döndüren yöntem. |
| settings | Func`1 | Converter ayarları. |

### Açıklamalar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca Bakınız

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

[`Converter`](../../converter) sınıfının yeni bir örneğini başlatır.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Okunabilir akış döndüren yöntem. |
| loadOptions | Func`2 | Belge için yükleme seçeneklerini sağlayan temsilci. İmza: `Func<LoadContext, LoadOptions>`. [`LoadContext`](../../loadcontext) parametresi, yüklenen belge hakkında bilgi içerir. |
| settings | Func`1 | Converter ayarları. |

### Açıklamalar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca Bakınız

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Yeni bir [`Converter`](../../converter) sınıfının örneğini açık dönüşüm olaylarıyla başlatır.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Okunabilir akış döndüren yöntem. |
| loadOptions | Func`2 | Belge için yükleme seçeneklerini sağlayan temsilci. |
| settings | Func`1 | Converter ayarları. |
| events | Func`1 | Dönüştürücünün ömrü boyunca kaydedilen toplu [`ConversionEvents`](../../conversionevents) sağlayan temsilci. |

### Ayrıca Bakınız

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Yeni bir [`Converter`](../../converter) sınıfının örneğini açık dönüşüm olaylarıyla başlatır.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Okunabilir akış döndüren yöntem. |
| settings | Func`1 | Converter ayarları. |
| events | Func`1 | Dönüştürücünün ömrü boyunca kaydedilen toplu [`ConversionEvents`](../../conversionevents) sağlayan temsilci. |

### Ayrıca Bakınız

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

[`Converter`](../../converter) sınıfının yeni bir örneğini başlatır.

```csharp
public Converter(string filePath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Kaynak belgenin dosya yolu. |

### Açıklamalar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca Bakınız

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

[`Converter`](../../converter) sınıfının yeni bir örneğini başlatır.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Kaynak belgenin dosya yolu. |
| settings | Func`1 | Converter ayarları. |

### Açıklamalar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca Bakınız

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

[`Converter`](../../converter) sınıfının yeni bir örneğini başlatır.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Kaynak belgenin dosya yolu. |
| loadOptions | Func`2 | Belge için yükleme seçeneklerini sağlayan temsilci. İmza: `Func<LoadContext, LoadOptions>`. [`LoadContext`](../../loadcontext) parametresi, yüklenen belge hakkında bilgi içerir. |
| settings | Func`1 | Converter ayarları. |

### Açıklamalar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ayrıca Bakınız

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Yeni bir [`Converter`](../../converter) sınıfının örneğini açık dönüşüm olaylarıyla başlatır.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Kaynak belgenin dosya yolu. |
| loadOptions | Func`2 | Belge için yükleme seçeneklerini sağlayan temsilci. |
| settings | Func`1 | Converter ayarları. |
| events | Func`1 | Dönüştürücünün ömrü boyunca kaydedilen toplu [`ConversionEvents`](../../conversionevents) sağlayan temsilci. |

### Ayrıca Bakınız

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Yeni bir [`Converter`](../../converter) sınıfının örneğini açık dönüşüm olaylarıyla başlatır.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Kaynak belgenin dosya yolu. |
| settings | Func`1 | Converter ayarları. |
| events | Func`1 | Dönüştürücünün ömrü boyunca kaydedilen toplu [`ConversionEvents`](../../conversionevents) sağlayan temsilci. |

### Ayrıca Bakınız

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
