---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor het laden van XML-documenten."
type: docs
weight: 45
url: /nl/nodejs-java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Opties voor het laden van XML-documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XmlLoadOptions()](#XmlLoadOptions--) | Initialiseert een nieuwe instantie van de [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXslFoFactory()](#getXslFoFactory--) | XSL-FO documentstroom om XML-FO te converteren met XSL. |
| [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL documentstroom om XML-FO te converteren met XSL. |
| [getXsltFactory()](#getXsltFactory--) | verkrijg XSLT documentstroom om XML te converteren met XSL-transformatie naar HTML. |
| [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | stel XSLT documentstroom in om XML te converteren met XSL-transformatie naar HTML. |
| [isUseAsDataSource()](#isUseAsDataSource--) | Gebruik Xml-document als gegevensbron |
| [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Stel gebruik van Xml-document als gegevensbron in |
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Initialiseert een nieuwe instantie van de [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) klasse.

### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


XSL-FO documentstroom om XML-FO te converteren met XSL.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


XSL documentstroom om XML-FO te converteren met XSL.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


verkrijg XSLT documentstroom om XML te converteren met XSL-transformatie naar HTML.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


stel XSLT documentstroom in om XML te converteren met XSL-transformatie naar HTML.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Gebruik Xml-document als gegevensbron

**Returns:**
boolean - true indien gebruikt
### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Stel gebruik van Xml-document als gegevensbron in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| useAsDataSource | boolean | gebruik Xml-document als gegevensbron |

