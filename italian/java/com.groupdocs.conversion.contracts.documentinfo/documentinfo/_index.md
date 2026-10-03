---
title: "DocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Fornisce l'implementazione di base per il recupero di informazioni polimorfiche sul documento"
type: docs
weight: 16
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Fornisce l'implementazione di base per il recupero di informazioni polimorfiche sul documento

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPropertyNames()](#getPropertyNames--) | {@inheritDoc} |
|
|  | [getProperty(String propertyName)](#getProperty-java.lang.String-) | {@inheritDoc} |
|
|  | [getPagesCount()](#getPagesCount--) | {@inheritDoc} |
|
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [getSize()](#getSize--) | {@inheritDoc} |
|
|  | [getCreationDate()](#getCreationDate--) | {@inheritDoc} |
|
### getPropertyNames() {#getPropertyNames--}
```
public List<String> getPropertyNames()
```


Elenco di tutte le proprietà che possono essere ottenute per le informazioni del documento corrente


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Ottieni il valore per una proprietà fornita come chiave


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Conteggio delle pagine del documento.


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Formato del documento


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Dimensione del documento in byte


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Data di creazione del documento


**Returns:**
java.util.Date
