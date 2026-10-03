---
title: "FileCache"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Comportamiento de caché de archivos."
type: docs
weight: 10
url: /es/java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Comportamiento de caché en el sistema de archivos. Significa que la caché se almacena en el sistema de archivos **Aprende más** Más sobre caché y la optimización del rendimiento del proceso de conversión: [Resultados de caché de conversión](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | Crea una nueva instancia de la clase FileCache |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Inserta una entrada de caché en la caché. |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Obtiene la entrada asociada a esta clave si está presente. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Devuelve todas las claves que coinciden con el filtro. |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Crea una nueva instancia de la clase FileCache


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cachePath | java.lang.String | Ruta relativa o absoluta donde se almacenará la caché de documentos |
|

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Inserta una entrada de caché en la caché.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | clave | java.lang.String | Un identificador único para la entrada de caché. |
|
|  | valor | java.lang.Object | El objeto a insertar. |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Obtiene la entrada asociada a esta clave si está presente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | clave | java.lang.String | Una clave que identifica la entrada solicitada. |
|

**Returns:**
java.lang.Object - Objeto si la clave se encontró o null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Devuelve todas las claves que coinciden con el filtro.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filtro | java.lang.String | El filtro a usar. |
|

**Returns:**
java.lang.Iterable<java.lang.String> - Claves que coinciden con el filtro.

