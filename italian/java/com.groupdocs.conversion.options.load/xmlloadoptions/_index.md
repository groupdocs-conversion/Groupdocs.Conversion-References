---
title: "XmlLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti XML."
type: docs
weight: 41
url: /it/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Opzioni per il caricamento dei documenti XML.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | Inizializza una nuova istanza della classe [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | Flusso di documento XSL-FO per convertire XML-FO usando XSL. |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Flusso di documento XSL per convertire XML-FO usando XSL. |
|
|  | [getXsltFactory()](#getXsltFactory--) | ottieni il flusso di documento XSLT per convertire XML eseguendo la trasformazione XSL in HTML. |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | imposta il flusso di documento XSLT per convertire XML eseguendo la trasformazione XSL in HTML. |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | Usa il documento Xml come origine dati |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Imposta l'uso del documento Xml come origine dati |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Inizializza una nuova istanza della classe [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions).


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


Flusso di documento XSL-FO per convertire XML-FO usando XSL.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


Flusso di documento XSL per convertire XML-FO usando XSL.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


ottieni il flusso di documento XSLT per convertire XML eseguendo la trasformazione XSL in HTML.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


imposta il flusso di documento XSLT per convertire XML eseguendo la trasformazione XSL in HTML.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Usa il documento Xml come origine dati


**Returns:**
boolean - true se utilizzato

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Imposta l'uso del documento Xml come origine dati


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | useAsDataSource | booleano | usa il documento Xml come origine dati |
|

