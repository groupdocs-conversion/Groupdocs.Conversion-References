---
title: "XmlLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen XML."
type: docs
weight: 41
url: /id/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Opsi untuk memuat dokumen XML.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | Menginisialisasi instance baru dari kelas [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | Aliran dokumen XSL-FO untuk mengonversi XML-FO menggunakan XSL. |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Aliran dokumen XSL untuk mengonversi XML-FO menggunakan XSL. |
|
|  | [getXsltFactory()](#getXsltFactory--) | dapatkan aliran dokumen XSLT untuk mengonversi XML dengan melakukan transformasi XSL ke HTML. |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | atur aliran dokumen XSLT untuk mengonversi XML dengan melakukan transformasi XSL ke HTML. |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | Gunakan dokumen Xml sebagai sumber data |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Atur penggunaan dokumen Xml sebagai sumber data |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Menginisialisasi instance baru dari kelas [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions).


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


Aliran dokumen XSL-FO untuk mengonversi XML-FO menggunakan XSL.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


Aliran dokumen XSL untuk mengonversi XML-FO menggunakan XSL.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


dapatkan aliran dokumen XSLT untuk mengonversi XML dengan melakukan transformasi XSL ke HTML.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


atur aliran dokumen XSLT untuk mengonversi XML dengan melakukan transformasi XSL ke HTML.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Gunakan dokumen Xml sebagai sumber data


**Returns:**
boolean - true jika digunakan

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Atur penggunaan dokumen Xml sebagai sumber data


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | useAsDataSource | boolean | gunakan dokumen Xml sebagai sumber data |
|

