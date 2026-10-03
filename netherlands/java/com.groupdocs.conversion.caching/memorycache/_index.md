---
title: "MemoryCache"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Geheugencache-gedrag."
type: docs
weight: 11
url: /nl/java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

Geheugencachinggedrag. Betekent dat de cache in het geheugen wordt opgeslagen **Meer info** Meer over caching en het optimaliseren van de prestaties van het conversieproces: [Caching conversion results](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [MemoryCache()](#MemoryCache--) | Maakt een nieuw exemplaar van de MemoryCache-klasse |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Voegt een cache‑item toe aan de cache. |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Haalt het item op dat aan deze sleutel is gekoppeld, indien aanwezig. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Retourneert alle sleutels die overeenkomen met het filter. |
|
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


Maakt een nieuw exemplaar van de MemoryCache-klasse


### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Voegt een cache‑item toe aan de cache.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | sleutel | java.lang.String | Een unieke identificatie voor het cache‑item. |
|
|  | waarde | java.lang.Object | Het object om in te voegen. |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Haalt het item op dat aan deze sleutel is gekoppeld, indien aanwezig.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | sleutel | java.lang.String | Een sleutel die het gevraagde item identificeert. |
|

**Returns:**
java.lang.Object - De gevonden waarde of null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Retourneert alle sleutels die overeenkomen met het filter.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filter | java.lang.String | Het filter om te gebruiken. |
|

**Returns:**
java.lang.Iterable<java.lang.String> - Sleutels die overeenkomen met het filter.

