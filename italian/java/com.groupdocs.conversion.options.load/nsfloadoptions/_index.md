---
title: "NsfLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Nsf."
type: docs
weight: 25
url: /it/java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Opzioni per il caricamento dei documenti Nsf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) |  |
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### NsfLoadOptions() {#NsfLoadOptions--}
```
public NsfLoadOptions()
```


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ottiene l'opzione per controllare se il contenitore dei documenti stesso deve essere convertito


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

