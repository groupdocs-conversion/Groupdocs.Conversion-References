---
title: "MemoryCache"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "内存缓存行为。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

内存缓存行为。表示缓存存储在内存中 **Learn more** 更多关于缓存以及优化转换过程性能的信息： [Caching conversion results](../https://docs.groupdocs.com/display/conversionnet/Caching)

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [MemoryCache()](#MemoryCache--) | 创建 MemoryCache 类的新实例 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | 向缓存中插入缓存项。 |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | 获取与此键关联的条目（如果存在）。 |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | 返回所有匹配过滤条件的键。 |
|
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


创建 MemoryCache 类的新实例


### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


向缓存中插入缓存项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 键 | java.lang.String | 缓存条目的唯一标识符。 |
|
|  | 值 | java.lang.Object | 要插入的对象。 |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


获取与此键关联的条目（如果存在）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 键 | java.lang.String | 标识请求条目的键。 |
|

**Returns:**
java.lang.Object - 找到的值或 null。

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


返回所有匹配过滤条件的键。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 过滤器 | java.lang.String | 要使用的过滤器。 |
|

**Returns:**
java.lang.Iterable<java.lang.String> - 匹配过滤器的键。

