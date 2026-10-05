---
title: "MemoryCache"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Minnescachningsbeteende."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

Minnescachebeteende. Betyder att cachen lagras i minnet **Learn more**Mer om cachelagring och optimering av konverteringsprocessens prestanda: [Caching conversion results][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MemoryCache()](#MemoryCache--) | Skapar en ny instans av MemoryCache-klassen |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Infogar ett cache-objekt i cachen. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Hämtar posten som är associerad med denna nyckel om den finns. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returnerar alla nycklar som matchar filtret. |
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


Skapar en ny instans av MemoryCache-klassen

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Infogar ett cache-objekt i cachen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | En unik identifierare för cacheposten. |
| value | java.lang.Object | Objektet att infoga. |

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Hämtar posten som är associerad med denna nyckel om den finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | En nyckel som identifierar den begärda posten. |

**Returns:**
java.lang.Object - Det hittade värdet eller null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Returnerar alla nycklar som matchar filtret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filter | java.lang.String | Filtret att använda. |

**Returns:**
java.lang.Iterable<java.lang.String> - Nycklar som matchar filtret.
