---
title: "DocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Proporciona una implementación base para recuperar información polimórfica de documentos"
type: docs
weight: 16
url: /es/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

Proporciona una implementación base para recuperar información polimórfica de documentos
## Métodos

| Método | Descripción |
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


Lista de todas las propiedades que se pueden obtener para la información del documento actual

**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


Obtener el valor de una propiedad proporcionada como clave

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


Recuento de páginas del documento.

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


Tamaño del documento en bytes

**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Fecha de creación del documento

**Returns:**
java.util.Date
