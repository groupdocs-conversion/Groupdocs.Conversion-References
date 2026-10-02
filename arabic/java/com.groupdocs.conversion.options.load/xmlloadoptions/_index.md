---
title: "خيارات تحميل Xml"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات XML."
type: docs
weight: 41
url: /ar/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

خيارات تحميل مستندات XML.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | يُهيئ نسخة جديدة من الفئة [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | تيار مستند XSL-FO لتحويل XML-FO باستخدام XSL. |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | تيار مستند XSL لتحويل XML-FO باستخدام XSL. |
|
|  | [getXsltFactory()](#getXsltFactory--) | احصل على تيار مستند XSLT لتحويل XML عبر إجراء تحويل XSL إلى HTML. |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | حدد تيار مستند XSLT لتحويل XML عبر إجراء تحويل XSL إلى HTML. |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | استخدم مستند Xml كمصدر بيانات |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | اضبط استخدام مستند Xml كمصدر بيانات |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


يُهيئ نسخة جديدة من الفئة [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions).


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


تيار مستند XSL-FO لتحويل XML-FO باستخدام XSL.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


تيار مستند XSL لتحويل XML-FO باستخدام XSL.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


احصل على تيار مستند XSLT لتحويل XML عبر إجراء تحويل XSL إلى HTML.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


حدد تيار مستند XSLT لتحويل XML عبر إجراء تحويل XSL إلى HTML.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


استخدم مستند Xml كمصدر بيانات


**Returns:**
boolean - صحيح إذا تم الاستخدام

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


اضبط استخدام مستند Xml كمصدر بيانات


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | useAsDataSource | منطقي | استخدم مستند Xml كمصدر بيانات |
|

