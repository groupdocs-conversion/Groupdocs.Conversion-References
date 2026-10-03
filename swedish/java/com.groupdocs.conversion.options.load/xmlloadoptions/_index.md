---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för inläsning av XML-dokument."
type: docs
weight: 41
url: /sv/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Alternativ för inläsning av XML-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | Initierar en ny instans av klassen [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | XSL-FO-dokumentström för att konvertera XML-FO med XSL. |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL-dokumentström för att konvertera XML-FO med XSL. |
|
|  | [getXsltFactory()](#getXsltFactory--) | Hämtar XSLT-dokumentström för att konvertera XML genom XSL-transformation till HTML. |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Ställer in XSLT-dokumentström för att konvertera XML genom XSL-transformation till HTML. |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | Använd Xml-dokument som datakälla |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Ställ in att använda Xml-dokument som datakälla |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Initierar en ny instans av klassen [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions).


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


XSL-FO-dokumentström för att konvertera XML-FO med XSL.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


XSL-dokumentström för att konvertera XML-FO med XSL.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


Hämtar XSLT-dokumentström för att konvertera XML genom XSL-transformation till HTML.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


Ställer in XSLT-dokumentström för att konvertera XML genom XSL-transformation till HTML.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Använd Xml-dokument som datakälla


**Returns:**
boolean - sant om den används

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Ställ in att använda Xml-dokument som datakälla


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | useAsDataSource | boolean | använd Xml-dokument som datakälla |
|

