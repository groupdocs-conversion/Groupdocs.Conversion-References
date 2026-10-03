---
title: "MboxLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Mbox."
type: docs
weight: 23
url: /it/java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opzioni per il caricamento dei documenti Mbox.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [MboxLoadOptions()](#MboxLoadOptions--) | Inizializza una nuova istanza della classe. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isConvertOwner()](#isConvertOwner--) | Il proprietario non verrà convertito |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} Predefinito: 3 |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | {@inheritDoc} |
|
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


Inizializza una nuova istanza della classe.


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Il proprietario non verrà convertito


**Returns:**
booleano
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opzione per controllare se i documenti di proprietà nel contenitore dei documenti devono essere convertiti


**Returns:**
booleano
### getDepth() {#getDepth--}
```
public int getDepth()
```


Opzione per controllare quanti livelli di profondità eseguire nella conversione Predefinito: 3


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| depth | int |  |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
