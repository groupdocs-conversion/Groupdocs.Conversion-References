---
title: "XmlLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "XML 문서를 로드하기 위한 옵션."
type: docs
weight: 45
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

XML 문서를 로드하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmlLoadOptions()](#XmlLoadOptions--) | 새 인스턴스를 초기화합니다 [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getXslFoFactory()](#getXslFoFactory--) | XSL을 사용하여 XML-FO를 변환하기 위한 XSL-FO 문서 스트림. |
| [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL을 사용하여 XML-FO를 변환하기 위한 XSL 문서 스트림. |
| [getXsltFactory()](#getXsltFactory--) | XML을 변환하여 HTML로 XSL 변환을 수행하기 위한 XSLT 문서 스트림을 가져옵니다. |
| [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XML을 변환하여 HTML로 XSL 변환을 수행하기 위한 XSLT 문서 스트림을 설정합니다. |
| [isUseAsDataSource()](#isUseAsDataSource--) | Xml 문서를 데이터 소스로 사용합니다 |
| [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Xml 문서를 데이터 소스로 사용하도록 설정합니다 |
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


새 인스턴스를 초기화합니다 [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions) 클래스.

### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


XSL을 사용하여 XML-FO를 변환하기 위한 XSL-FO 문서 스트림.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


XSL을 사용하여 XML-FO를 변환하기 위한 XSL 문서 스트림.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


XML을 변환하여 HTML로 XSL 변환을 수행하기 위한 XSLT 문서 스트림을 가져옵니다.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


XML을 변환하여 HTML로 XSL 변환을 수행하기 위한 XSLT 문서 스트림을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Xml 문서를 데이터 소스로 사용합니다

**Returns:**
boolean - 사용하면 true
### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Xml 문서를 데이터 소스로 사용하도록 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| useAsDataSource | boolean | Xml 문서를 데이터 소스로 사용합니다 |

