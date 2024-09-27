---
title: XmlLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for loading XML documents.
type: docs
weight: 45
url: /nodejs-java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Options for loading XML documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmlLoadOptions()](#XmlLoadOptions--) | Initializes new instance of [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getXslFoFactory()](#getXslFoFactory--) | XSL-FO document stream to convert XML-FO using XSL. |
| [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL document stream to convert XML-FO using XSL. |
| [getXsltFactory()](#getXsltFactory--) | get XSLT document stream to convert XML performing XSL transformation to HTML. |
| [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | set XSLT document stream to convert XML performing XSL transformation to HTML. |
| [isUseAsDataSource()](#isUseAsDataSource--) | Use Xml document as data source |
| [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Set use Xml document as data source |
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Initializes new instance of [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) class.

### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


XSL-FO document stream to convert XML-FO using XSL.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


XSL document stream to convert XML-FO using XSL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


get XSLT document stream to convert XML performing XSL transformation to HTML.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


set XSLT document stream to convert XML performing XSL transformation to HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Use Xml document as data source

**Returns:**
boolean - true if use
### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Set use Xml document as data source

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| useAsDataSource | boolean | use Xml document as data source |

