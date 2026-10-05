---
title: "FileCache"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Filcachningsbeteende."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Filcachebeteende. Betyder att cachen lagras i filsystemet **Learn more**Mer om cachelagring och optimering av konverteringsprocessens prestanda: [Caching conversion results][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Skapar en ny instans av FileCache-klassen |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Infogar ett cache-objekt i cachen. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Hämtar posten som är associerad med denna nyckel om den finns. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returnerar alla nycklar som matchar filtret. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Skapar en ny instans av FileCache-klassen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cachePath | java.lang.String | Relativ eller absolut sökväg där dokumentcachen kommer att lagras |

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
java.lang.Object - Objekt om nyckeln hittades, annars null.
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
