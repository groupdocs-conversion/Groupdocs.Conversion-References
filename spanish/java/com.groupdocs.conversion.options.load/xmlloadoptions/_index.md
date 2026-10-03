---
title: "XmlLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos XML."
type: docs
weight: 41
url: /es/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Opciones para cargar documentos XML.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | Inicializa una nueva instancia de la clase [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | Secuencia de documento XSL-FO para convertir XML-FO usando XSL. |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Secuencia de documento XSL para convertir XML-FO usando XSL. |
|
|  | [getXsltFactory()](#getXsltFactory--) | Obtener secuencia de documento XSLT para convertir XML realizando transformación XSL a HTML. |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Establecer secuencia de documento XSLT para convertir XML realizando transformación XSL a HTML. |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | Usar documento Xml como fuente de datos |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Establecer documento Xml como fuente de datos |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Inicializa una nueva instancia de la clase [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions).


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


Secuencia de documento XSL-FO para convertir XML-FO usando XSL.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


Secuencia de documento XSL para convertir XML-FO usando XSL.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


Obtener secuencia de documento XSLT para convertir XML realizando transformación XSL a HTML.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


Establecer secuencia de documento XSLT para convertir XML realizando transformación XSL a HTML.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Usar documento Xml como fuente de datos


**Returns:**
boolean - verdadero si se usa

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Establecer documento Xml como fuente de datos


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | useAsDataSource | booleano | usar documento Xml como fuente de datos |
|

