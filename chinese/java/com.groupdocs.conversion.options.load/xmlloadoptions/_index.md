---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载 XML 文档的选项。"
type: docs
weight: 41
url: /zh/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

加载 XML 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | 初始化 [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | XSL-FO 文档流，用于使用 XSL 转换 XML-FO。 |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL 文档流，用于使用 XSL 转换 XML-FO。 |
|
|  | [getXsltFactory()](#getXsltFactory--) | 获取 XSLT 文档流，以使用 XSL 将 XML 转换为 HTML。 |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | 设置 XSLT 文档流，以使用 XSL 将 XML 转换为 HTML。 |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | 使用 Xml 文档作为数据源。 |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | 设置使用 Xml 文档作为数据源 |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


初始化 [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) 类的新实例。


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


XSL-FO 文档流，用于使用 XSL 转换 XML-FO。


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


XSL 文档流，用于使用 XSL 转换 XML-FO。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


获取 XSLT 文档流，以使用 XSL 将 XML 转换为 HTML。


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


设置 XSLT 文档流，以使用 XSL 将 XML 转换为 HTML。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


使用 Xml 文档作为数据源。


**Returns:**
布尔 - 如果使用则为 true

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


设置使用 Xml 文档作为数据源


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | useAsDataSource | 布尔 | 使用 Xml 文档作为数据源 |
|

