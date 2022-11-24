---
title: MemoryCache
second_title: GroupDocs.Conversion for Java API Reference
description: Memory caching behaviour.
type: docs
weight: 11
url: /java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

Memory caching behaviour. Means that cache is stored in the memory **Learn more**More about caching and optimizing conversion process performance: [Caching conversion results][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## Constructors

| Constructor | Description |
| --- | --- |
| [MemoryCache()](#MemoryCache--) | Creates new instance of MemoryCache class |
## Methods

| Method | Description |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Inserts a cache entry into the cache. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Gets the entry associated with this key if present. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returns all keys matching filter. |
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


Creates new instance of MemoryCache class

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Inserts a cache entry into the cache.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A unique identifier for the cache entry. |
| value | java.lang.Object | The object to insert. |

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Gets the entry associated with this key if present.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A key identifying the requested entry. |

**Returns:**
java.lang.Object - The located value or null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Returns all keys matching filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String | he filter to use. |

**Returns:**
java.lang.Iterable<java.lang.String> - Keys matching the filter.
