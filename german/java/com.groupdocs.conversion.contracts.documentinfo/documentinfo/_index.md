---
title: "DocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt die Basisimplementierung zum Abrufen polymorpher Dokumentinformationen bereit"
type: docs
weight: 16
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Stellt die Basisimplementierung zum Abrufen polymorpher Dokumentinformationen bereit

## Methoden

| Methode | Beschreibung |
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


Liste aller Eigenschaften, die für die aktuelle Dokumentinfo abgerufen werden können


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Wert einer als Schlüssel bereitgestellten Eigenschaft abrufen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Anzahl der Dokumentseiten.


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Dokumentenformat


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Dokumentgröße in Bytes


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Erstellungsdatum des Dokuments


**Returns:**
java.util.Date
