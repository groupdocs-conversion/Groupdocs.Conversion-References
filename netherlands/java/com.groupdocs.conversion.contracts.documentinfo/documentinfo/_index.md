---
title: "DocumentInfo"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Biedt basisimplementatie voor het ophalen van polymorfe documentinformatie"
type: docs
weight: 16
url: /nl/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Biedt basisimplementatie voor het ophalen van polymorfe documentinformatie

## Methoden

| Methode | Beschrijving |
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


Lijst van alle eigenschappen die opgehaald kunnen worden voor de huidige documentinfo


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Haal de waarde op voor een eigenschap die als sleutel wordt opgegeven


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Aantal pagina's in het document.


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Documentformaat


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Documentgrootte in bytes


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Aanmaakdatum van het document


**Returns:**
java.util.Date
