---
title: "MemoryCache"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Comportamiento de caché en memoria."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

Comportamiento de caché en memoria. Significa que la caché se almacena en la memoria **Aprende más**Más información sobre la caché y la optimización del rendimiento del proceso de conversión: [Resultados de caché de conversión][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MemoryCache()](#MemoryCache--) | Crea una nueva instancia de la clase MemoryCache |
## Métodos

| Método | Descripción |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Inserta una entrada en la caché. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Obtiene la entrada asociada a esta clave si está presente. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Devuelve todas las claves que coinciden con el filtro. |
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


Crea una nueva instancia de la clase MemoryCache

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Inserta una entrada en la caché.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | Un identificador único para la entrada de caché. |
| valor | java.lang.Object | El objeto a insertar. |

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Obtiene la entrada asociada a esta clave si está presente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | Una clave que identifica la entrada solicitada. |

**Returns:**
java.lang.Object - El valor localizado o null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Devuelve todas las claves que coinciden con el filtro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filtro | java.lang.String | El filtro a usar. |

**Returns:**
java.lang.Iterable<java.lang.String> - Claves que coinciden con el filtro.
