---
title: "DiagramLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Diagram."
type: docs
weight: 15
url: /it/java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Opzioni per il caricamento dei documenti Diagram.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DiagramLoadOptions()](#DiagramLoadOptions--) | Inizializza una nuova istanza della classe [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Font predefinito per il documento Diagram. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Font predefinito per il documento Diagram. |
|
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Inizializza una nuova istanza della classe [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions).


### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Font predefinito per il documento Diagram. Il font seguente verrà utilizzato se un font è mancante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Font predefinito per il documento Diagram. Il font seguente verrà utilizzato se un font è mancante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

