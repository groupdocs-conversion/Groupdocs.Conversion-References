---
title: "DocumentInfo"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Tillhandahåller grundimplementation för att hämta polymorf dokumentinformation"
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Tillhandahåller grundimplementation för att hämta polymorf dokumentinformation
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPropertyNames()](#getPropertyNames--) | \\{@inheritDoc\\} |
| [getProperty(String propertyName)](#getProperty-java.lang.String-) | \\{@inheritDoc\\} |
| [getPagesCount()](#getPagesCount--) | \\{@inheritDoc\\} |
| [getFormat()](#getFormat--) | \\{@inheritDoc\\} |
| [getSize()](#getSize--) | \\{@inheritDoc\\} |
| [getCreationDate()](#getCreationDate--) | \\{@inheritDoc\\} |
### getPropertyNames() {#getPropertyNames--}
```
public List<String> getPropertyNames()
```


Lista över alla egenskaper som kan hämtas för den aktuella dokumentinformationen

**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Hämta värde för en egenskap som anges som nyckel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Antal sidor i dokumentet.

**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Dokumentformat

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Dokumentstorlek i byte

**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Dokumentets skapelsedatum

**Returns:**
java.util.Date
