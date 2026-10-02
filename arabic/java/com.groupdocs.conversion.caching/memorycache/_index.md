---
title: "MemoryCache"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "سلوك التخزين المؤقت للذاكرة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

سلوك التخزين المؤقت في الذاكرة. يعني أن الذاكرة المؤقتة مخزنة في الذاكرة **Learn more** مزيد من المعلومات حول التخزين المؤقت وتحسين أداء عملية التحويل: [Caching conversion results](../https://docs.groupdocs.com/display/conversionnet/Caching)

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [MemoryCache()](#MemoryCache--) | ينشئ مثيلاً جديدًا من الفئة MemoryCache |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | يدرج إدخالًا في الذاكرة المؤقتة. |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | يحصل على الإدخال المرتبط بهذا المفتاح إذا كان موجودًا. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | يعيد جميع المفاتيح التي تطابق الفلتر. |
|
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


ينشئ مثيلاً جديدًا من الفئة MemoryCache


### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


يدرج إدخالًا في الذاكرة المؤقتة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المفتاح | java.lang.String | معرّف فريد لإدخال الذاكرة المؤقتة. |
|
|  | القيمة | java.lang.Object | الكائن المراد إدراجه. |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


يحصل على الإدخال المرتبط بهذا المفتاح إذا كان موجودًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المفتاح | java.lang.String | مفتاح يحدد الإدخال المطلوب. |
|

**Returns:**
java.lang.Object - القيمة الموجودة أو null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


يعيد جميع المفاتيح التي تطابق الفلتر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الفلتر | java.lang.String | الفلتر للاستخدام. |
|

**Returns:**
java.lang.Iterable<java.lang.String> - المفاتيح التي تطابق الفلتر.

