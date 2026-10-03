---
title: "XmlLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour le chargement des documents XML."
type: docs
weight: 41
url: /fr/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Options pour le chargement des documents XML.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | Initialise une nouvelle instance de la classe [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | Flux de document XSL-FO pour convertir XML-FO en utilisant XSL. |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Flux de document XSL pour convertir XML-FO en utilisant XSL. |
|
|  | [getXsltFactory()](#getXsltFactory--) | Obtenir le flux de document XSLT pour convertir XML en effectuant une transformation XSL vers HTML. |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Définir le flux de document XSLT pour convertir XML en effectuant une transformation XSL vers HTML. |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | Utiliser le document Xml comme source de données |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Définir l'utilisation du document Xml comme source de données |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Initialise une nouvelle instance de la classe [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions).


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


Flux de document XSL-FO pour convertir XML-FO en utilisant XSL.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


Flux de document XSL pour convertir XML-FO en utilisant XSL.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


Obtenir le flux de document XSLT pour convertir XML en effectuant une transformation XSL vers HTML.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


Définir le flux de document XSLT pour convertir XML en effectuant une transformation XSL vers HTML.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Utiliser le document Xml comme source de données


**Returns:**
booléen - vrai si utilisé

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Définir l'utilisation du document Xml comme source de données


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | useAsDataSource | booléen | utiliser le document Xml comme source de données |
|

