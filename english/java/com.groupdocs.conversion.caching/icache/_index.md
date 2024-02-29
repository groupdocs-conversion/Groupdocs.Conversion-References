---
title: ICache
second_title: GroupDocs.Conversion for Java API Reference
description: Defines methods required for storing rendered document and document resources u0441ache.
type: docs
weight: 12
url: /java/com.groupdocs.conversion.caching/icache/
---```
public interface ICache
```

Defines methods required for storing rendered document and document resources \\u0441ache.
## Methods

| Method | Description |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Inserts a cache entry into the cache. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Gets the entry associated with this key if present. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returns all keys matching filter. |
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public abstract void set(String key, Object value)
```


Inserts a cache entry into the cache.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A unique identifier for the cache entry. |
| value | java.lang.Object | The object to insert. |

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public abstract Object tryGetValue(String key)
```


Gets the entry associated with this key if present.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A key identifying the requested entry. |

**Returns:**
java.lang.Object - Object if the key was found or else null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public abstract Iterable<String> getKeys(String filter)
```


Returns all keys matching filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String | The filter to use. |

**Returns:**
java.lang.Iterable<java.lang.String> - Keys matching the filter.
