---
title: "PersonalStorageLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti di archiviazione personale."
type: docs
weight: 28
url: /it/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opzioni per il caricamento dei documenti di archiviazione personale.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | Inizializza una nuova istanza della classe. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFolder()](#getFolder--) | Cartella da elaborare Il valore predefinito è Inbox |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | Imposta la cartella da elaborare |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} Il proprietario non verrà convertito |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


Inizializza una nuova istanza della classe.


### getFolder() {#getFolder--}
```
public String getFolder()
```


Cartella da elaborare Il valore predefinito è Inbox


**Returns:**
java.lang.String - Cartella da elaborare

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


Imposta la cartella da elaborare


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | cartella | java.lang.String | cartella |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ottiene l'opzione per controllare se il contenitore dei documenti stesso deve essere convertito Il proprietario non verrà convertito


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


Opzione per controllare quanti livelli di profondità eseguire la conversione


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

