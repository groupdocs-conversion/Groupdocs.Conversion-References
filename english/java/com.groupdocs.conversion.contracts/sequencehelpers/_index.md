---
title: SequenceHelpers
second_title: GroupDocs.Conversion for Java API Reference
description: 
type: docs
weight: 16
url: /java/com.groupdocs.conversion.contracts/sequencehelpers/
---
**Inheritance:**
java.lang.Object
```
public class SequenceHelpers
```
## Constructors

| Constructor | Description |
| --- | --- |
| [SequenceHelpers()](#SequenceHelpers--) |  |
## Methods

| Method | Description |
| --- | --- |
| [<TSource>sequenceEqual(System.Collections.Generic.IGenericEnumerable<TSource> first, System.Collections.Generic.IGenericEnumerable<TSource> second)](#-TSource-sequenceEqual-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--) |  |
| [<TSource,TAccumulate>aggregate(System.Collections.Generic.IGenericEnumerable<TSource> source, TAccumulate seed, BiFunction<TAccumulate,TSource,TAccumulate> func)](#-TSource-TAccumulate-aggregate-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--TAccumulate-java.util.function.BiFunction-TAccumulate-TSource-TAccumulate--) |  |
| [<TSource,TAccumulate,TResult>aggregate(System.Collections.Generic.IGenericEnumerable<TSource> source, TAccumulate seed, BiFunction<TAccumulate,TSource,TAccumulate> func, Func1<TAccumulate,TResult> resultSelector)](#-TSource-TAccumulate-TResult-aggregate-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--TAccumulate-java.util.function.BiFunction-TAccumulate-TSource-TAccumulate--com.groupdocs.conversion.contracts.Func1-TAccumulate-TResult--) |  |
| [<TSource>reverse(System.Collections.Generic.IGenericEnumerable<TSource> source)](#-TSource-reverse-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--) |  |
| [reverse(Object[] source)](#reverse-java.lang.Object---) |  |
| [<TSource>concat(System.Collections.Generic.IGenericEnumerable<TSource> first, System.Collections.Generic.IGenericEnumerable<TSource> second)](#-TSource-concat-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--) |  |
| [concat(List l1, List l2)](#concat-java.util.List-java.util.List-) |  |
| [<TSource>concat(List<TSource>[] collections)](#-TSource-concat-java.util.List-TSource----) |  |
| [<TSource>firstOrDefault(List<TSource> source)](#-TSource-firstOrDefault-java.util.List-TSource--) |  |
| [<TSource>firstOrDefault(List<TSource> source, Func1<TSource,Boolean> predicate)](#-TSource-firstOrDefault-java.util.List-TSource--com.groupdocs.conversion.contracts.Func1-TSource-java.lang.Boolean--) |  |
### SequenceHelpers() {#SequenceHelpers--}
```
public SequenceHelpers()
```


### <TSource>sequenceEqual(System.Collections.Generic.IGenericEnumerable<TSource> first, System.Collections.Generic.IGenericEnumerable<TSource> second) {#-TSource-sequenceEqual-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--}
```
public static boolean <TSource>sequenceEqual(System.Collections.Generic.IGenericEnumerable<TSource> first, System.Collections.Generic.IGenericEnumerable<TSource> second)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<TSource> |  |
| second | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<TSource> |  |

**Returns:**
boolean
### <TSource,TAccumulate>aggregate(System.Collections.Generic.IGenericEnumerable<TSource> source, TAccumulate seed, BiFunction<TAccumulate,TSource,TAccumulate> func) {#-TSource-TAccumulate-aggregate-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--TAccumulate-java.util.function.BiFunction-TAccumulate-TSource-TAccumulate--}
```
public static TAccumulate <TSource,TAccumulate>aggregate(System.Collections.Generic.IGenericEnumerable<TSource> source, TAccumulate seed, BiFunction<TAccumulate,TSource,TAccumulate> func)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<TSource> |  |
| seed | TAccumulate |  |
| func | java.util.function.BiFunction<TAccumulate,TSource,TAccumulate> |  |

**Returns:**
TAccumulate
### <TSource,TAccumulate,TResult>aggregate(System.Collections.Generic.IGenericEnumerable<TSource> source, TAccumulate seed, BiFunction<TAccumulate,TSource,TAccumulate> func, Func1<TAccumulate,TResult> resultSelector) {#-TSource-TAccumulate-TResult-aggregate-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--TAccumulate-java.util.function.BiFunction-TAccumulate-TSource-TAccumulate--com.groupdocs.conversion.contracts.Func1-TAccumulate-TResult--}
```
public static TResult <TSource,TAccumulate,TResult>aggregate(System.Collections.Generic.IGenericEnumerable<TSource> source, TAccumulate seed, BiFunction<TAccumulate,TSource,TAccumulate> func, Func1<TAccumulate,TResult> resultSelector)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<TSource> |  |
| seed | TAccumulate |  |
| func | java.util.function.BiFunction<TAccumulate,TSource,TAccumulate> |  |
| resultSelector | com.groupdocs.conversion.contracts.Func1<TAccumulate,TResult> |  |

**Returns:**
TResult
### <TSource>reverse(System.Collections.Generic.IGenericEnumerable<TSource> source) {#-TSource-reverse-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--}
```
public static System.Collections.Generic.IGenericEnumerable<TSource> <TSource>reverse(System.Collections.Generic.IGenericEnumerable<TSource> source)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<TSource> |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<TSource>
### reverse(Object[] source) {#reverse-java.lang.Object---}
```
public static Object[] reverse(Object[] source)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.Object[] |  |

**Returns:**
java.lang.Object[]
### <TSource>concat(System.Collections.Generic.IGenericEnumerable<TSource> first, System.Collections.Generic.IGenericEnumerable<TSource> second) {#-TSource-concat-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--com.aspose.ms.System.Collections.Generic.IGenericEnumerable-TSource--}
```
public static System.Collections.Generic.IGenericEnumerable<TSource> <TSource>concat(System.Collections.Generic.IGenericEnumerable<TSource> first, System.Collections.Generic.IGenericEnumerable<TSource> second)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<TSource> |  |
| second | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<TSource> |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<TSource>
### concat(List l1, List l2) {#concat-java.util.List-java.util.List-}
```
public static List concat(List l1, List l2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l1 | java.util.List |  |
| l2 | java.util.List |  |

**Returns:**
java.util.List
### <TSource>concat(List<TSource>[] collections) {#-TSource-concat-java.util.List-TSource----}
```
public static List<TSource> <TSource>concat(List<TSource>[] collections)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| collections | java.util.List<TSource>[] |  |

**Returns:**
java.util.List<TSource>
### <TSource>firstOrDefault(List<TSource> source) {#-TSource-firstOrDefault-java.util.List-TSource--}
```
public static TSource <TSource>firstOrDefault(List<TSource> source)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.util.List<TSource> |  |

**Returns:**
TSource
### <TSource>firstOrDefault(List<TSource> source, Func1<TSource,Boolean> predicate) {#-TSource-firstOrDefault-java.util.List-TSource--com.groupdocs.conversion.contracts.Func1-TSource-java.lang.Boolean--}
```
public static TSource <TSource>firstOrDefault(List<TSource> source, Func1<TSource,Boolean> predicate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.util.List<TSource> |  |
| predicate | com.groupdocs.conversion.contracts.Func1<TSource,java.lang.Boolean> |  |

**Returns:**
TSource
