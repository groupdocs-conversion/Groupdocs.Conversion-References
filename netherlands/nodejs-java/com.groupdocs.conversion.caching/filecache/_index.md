---
title: "FileCache"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Gedrag van bestandscaching."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Bestandscachinggedrag. Betekent dat de cache wordt opgeslagen op het bestandssysteem **Learn more**Meer over caching en het optimaliseren van de prestaties van het conversieproces: [Caching conversion results][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Maakt een nieuw exemplaar van de FileCache-klasse |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Voegt een cache-item toe aan de cache. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Haalt het item op dat aan deze sleutel is gekoppeld, indien aanwezig. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Retourneert alle sleutels die overeenkomen met het filter. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Maakt een nieuw exemplaar van de FileCache-klasse

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cachePath | java.lang.String | Relatief of absoluut pad waar de documentcache wordt opgeslagen |

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Voegt een cache-item toe aan de cache.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Een unieke identifier voor het cache-item. |
| value | java.lang.Object | Het object om in te voegen. |

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Haalt het item op dat aan deze sleutel is gekoppeld, indien aanwezig.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Een sleutel die het aangevraagde item identificeert. |

**Returns:**
java.lang.Object - Object als de sleutel werd gevonden, anders null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Retourneert alle sleutels die overeenkomen met het filter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filter | java.lang.String | Het filter om te gebruiken. |

**Returns:**
java.lang.Iterable<java.lang.String> - Sleutels die overeenkomen met het filter.
