---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von XML-Dokumenten."
type: docs
weight: 41
url: /de/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Optionen zum Laden von XML-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | Initialisiert eine neue Instanz der Klasse [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | XSL-FO-Dokumentstrom zum Konvertieren von XML-FO mit XSL. |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | XSL-Dokumentstrom zum Konvertieren von XML-FO mit XSL. |
|
|  | [getXsltFactory()](#getXsltFactory--) | Ruft XSLT-Dokumentstrom ab, um XML mittels XSL-Transformation nach HTML zu konvertieren. |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Setzt XSLT-Dokumentstrom, um XML mittels XSL-Transformation nach HTML zu konvertieren. |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | Verwende Xml-Dokument als Datenquelle |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Setze die Verwendung des Xml-Dokuments als Datenquelle |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Initialisiert eine neue Instanz der Klasse [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions).


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


XSL-FO-Dokumentstrom zum Konvertieren von XML-FO mit XSL.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


XSL-Dokumentstrom zum Konvertieren von XML-FO mit XSL.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


Ruft XSLT-Dokumentstrom ab, um XML mittels XSL-Transformation nach HTML zu konvertieren.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


Setzt XSLT-Dokumentstrom, um XML mittels XSL-Transformation nach HTML zu konvertieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Verwende Xml-Dokument als Datenquelle


**Returns:**
boolean – true, wenn verwendet

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Setze die Verwendung des Xml-Dokuments als Datenquelle


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | useAsDataSource | boolean | verwende Xml-Dokument als Datenquelle |
|

