---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για τη φόρτωση εγγράφων XML."
type: docs
weight: 41
url: /el/java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Επιλογές για τη φόρτωση εγγράφων XML.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [XmlLoadOptions()](#XmlLoadOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getXslFoFactory()](#getXslFoFactory--) | Ροή εγγράφου XSL-FO για μετατροπή XML-FO χρησιμοποιώντας XSL. |
|
|  | [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Ροή εγγράφου XSL για μετατροπή XML-FO χρησιμοποιώντας XSL. |
|
|  | [getXsltFactory()](#getXsltFactory--) | Λάβετε ροή εγγράφου XSLT για μετατροπή XML εκτελώντας μετασχηματισμό XSL σε HTML. |
|
|  | [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Ορίστε ροή εγγράφου XSLT για μετατροπή XML εκτελώντας μετασχηματισμό XSL σε HTML. |
|
|  | [isUseAsDataSource()](#isUseAsDataSource--) | Χρησιμοποιήστε το έγγραφο Xml ως πηγή δεδομένων |
|
|  | [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Ορίστε τη χρήση του εγγράφου Xml ως πηγή δεδομένων |
|
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions).


### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


Ροή εγγράφου XSL-FO για μετατροπή XML-FO χρησιμοποιώντας XSL.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


Ροή εγγράφου XSL για μετατροπή XML-FO χρησιμοποιώντας XSL.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


Λάβετε ροή εγγράφου XSLT για μετατροπή XML εκτελώντας μετασχηματισμό XSL σε HTML.


**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


Ορίστε ροή εγγράφου XSLT για μετατροπή XML εκτελώντας μετασχηματισμό XSL σε HTML.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Χρησιμοποιήστε το έγγραφο Xml ως πηγή δεδομένων


**Returns:**
boolean - true εάν χρησιμοποιείται

### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Ορίστε τη χρήση του εγγράφου Xml ως πηγή δεδομένων


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | useAsDataSource | boolean | χρησιμοποιήστε το έγγραφο Xml ως πηγή δεδομένων |
|

