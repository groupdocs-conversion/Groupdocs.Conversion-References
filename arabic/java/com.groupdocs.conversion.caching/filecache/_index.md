---
title: "FileCache"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "سلوك التخزين المؤقت للملفات."
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

سلوك التخزين المؤقت على الملفات. يعني أن الذاكرة المؤقتة مخزنة على نظام الملفات **Learn more** مزيد من المعلومات حول التخزين المؤقت وتحسين أداء عملية التحويل: [Caching conversion results](../https://docs.groupdocs.com/display/conversionnet/Caching)

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة FileCache |
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
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


ينشئ مثيلاً جديدًا من الفئة FileCache


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cachePath | java.lang.String | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة التخزين المؤقت للمستند |
|

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
java.lang.Object - الكائن إذا تم العثور على المفتاح أو null.

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

