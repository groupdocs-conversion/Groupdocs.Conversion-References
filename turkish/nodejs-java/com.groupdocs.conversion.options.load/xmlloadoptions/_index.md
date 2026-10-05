---
title: "XmlLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "XML belgelerini yükleme seçenekleri."
type: docs
weight: 45
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

XML belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmlLoadOptions()](#XmlLoadOptions--) | Yeni bir [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) sınıf örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getXslFoFactory()](#getXslFoFactory--) | XSL kullanarak XML-FO'yu dönüştürmek için XSL-FO belge akışı. |
| [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL kullanarak XML-FO'yu dönüştürmek için XSL belge akışı. |
| [getXsltFactory()](#getXsltFactory--) | XSL dönüşümüyle XML'i HTML'ye dönüştürmek için XSLT belge akışını al. |
| [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XML'i XSL dönüşümüyle HTML'ye dönüştürmek için XSLT belge akışını ayarla. |
| [isUseAsDataSource()](#isUseAsDataSource--) | Xml belgesini veri kaynağı olarak kullan. |
| [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Xml belgesini veri kaynağı olarak kullanmayı ayarla. |
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Yeni bir [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) sınıf örneği başlatır.

### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


XSL kullanarak XML-FO'yu dönüştürmek için XSL-FO belge akışı.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


XSL kullanarak XML-FO'yu dönüştürmek için XSL belge akışı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


XSL dönüşümüyle XML'i HTML'ye dönüştürmek için XSLT belge akışını al.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


XML'i XSL dönüşümüyle HTML'ye dönüştürmek için XSLT belge akışını ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Xml belgesini veri kaynağı olarak kullan.

**Returns:**
boolean - kullanılıyorsa true
### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Xml belgesini veri kaynağı olarak kullanmayı ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| useAsDataSource | boolean | Xml belgesini veri kaynağı olarak kullan. |

