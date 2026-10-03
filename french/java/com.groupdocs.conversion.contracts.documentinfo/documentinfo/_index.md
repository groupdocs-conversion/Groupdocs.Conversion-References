---
title: "DocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Fournit une implémentation de base pour récupérer les informations polymorphes du document"
type: docs
weight: 16
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Fournit une implémentation de base pour récupérer les informations polymorphes du document

## Méthodes

| Méthode | Description |
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


Liste de toutes les propriétés pouvant être obtenues pour les informations du document actuel


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Obtenir la valeur d'une propriété fournie comme clé


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Nombre de pages du document.


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


Format du document


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


Taille du document en octets


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Date de création du document


**Returns:**
java.util.Date
