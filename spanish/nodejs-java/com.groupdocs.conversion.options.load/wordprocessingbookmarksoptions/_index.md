---
title: "WordProcessingBookmarksOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para manejar marcadores en WordProcessing"
type: docs
weight: 43
url: /es/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

Opciones para manejar marcadores en WordProcessing
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Especifica el nivel predeterminado en el esquema del documento en el que se mostrarán los marcadores de Word. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Especifica el nivel predeterminado en el esquema del documento en el que se mostrarán los marcadores de Word. |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Especifica cuántos niveles de encabezados (párrafos formateados con los estilos de Encabezado) incluir en el esquema del documento. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Especifica cuántos niveles de encabezados (párrafos formateados con los estilos de Encabezado) incluir en el esquema del documento. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Especifica cuántos niveles del esquema del documento se mostrarán expandidos al visualizar el archivo. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Especifica cuántos niveles del esquema del documento se mostrarán expandidos al visualizar el archivo. |
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


Especifica el nivel predeterminado en el esquema del documento en el que se mostrarán los marcadores de Word. Predeterminado es 0. Rango válido es de 0 a 9.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


Especifica el nivel predeterminado en el esquema del documento en el que se mostrarán los marcadores de Word. Predeterminado es 0. Rango válido es de 0 a 9.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


Especifica cuántos niveles de encabezados (párrafos formateados con los estilos de Encabezado) incluir en el esquema del documento. Predeterminado es 0. Rango válido es de 0 a 9.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


Especifica cuántos niveles de encabezados (párrafos formateados con los estilos de Encabezado) incluir en el esquema del documento. Predeterminado es 0. Rango válido es de 0 a 9.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


Especifica cuántos niveles del esquema del documento se mostrarán expandidos al visualizar el archivo. Predeterminado es 0. Rango válido es de 0 a 9. Nota: esta opción no funcionará al guardar en XPS.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


Especifica cuántos niveles del esquema del documento se mostrarán expandidos al visualizar el archivo. Predeterminado es 0. Rango válido es de 0 a 9. Nota: esta opción no funcionará al guardar en XPS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

