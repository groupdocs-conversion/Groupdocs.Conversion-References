---
title: XmlLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading XML documents.
type: docs
weight: 34
url: /java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.DataLoadOptions](../../com.groupdocs.conversion.options.load/dataloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends DataLoadOptions implements Serializable
```

Options for loading XML documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmlLoadOptions()](#XmlLoadOptions--) | Initializes new instance of [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getXslFoFactory()](#getXslFoFactory--) | XSL document stream to convert XML-FO using XSL. |
| [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL document stream to convert XML-FO using XSL. |
| [isUseAsDataSource()](#isUseAsDataSource--) | Use Xml document as data source |
| [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Set use Xml document as data source |
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Initializes new instance of [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) class.

### getFormat() {#getFormat--}
```
public DataFileType getFormat()
```


Input document file type

**Returns:**
[DataFileType](../../com.groupdocs.conversion.filetypes/datafiletype)
### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


XSL document stream to convert XML-FO using XSL.

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

