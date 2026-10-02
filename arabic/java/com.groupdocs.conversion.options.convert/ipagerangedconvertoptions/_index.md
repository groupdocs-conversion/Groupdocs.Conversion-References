---
title: "IPageRangedConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل خيارات التحويل التي تدعم تحويل قائمة محددة من الصفحات"
type: docs
weight: 52
url: /ar/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

يمثل خيارات التحويل التي تدعم تحويل قائمة محددة من الصفحات

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPages()](#getPages--) | يحصل على قائمة مؤشرات الصفحات التي سيتم تحويلها. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | يضبط قائمة مؤشرات الصفحات التي سيتم تحويلها. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


يحصل على قائمة فهارس الصفحات التي سيتم تحويلها. يجب تحديدها لتحويل صفحات محددة.


**Returns:**
java.util.List<java.lang.Integer> - قائمة مؤشرات الصفحات التي سيتم تحويلها. يجب تحديدها لتحويل صفحات محددة.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


يضبط قائمة فهارس الصفحات التي سيتم تحويلها. يجب تحديدها لتحويل صفحات محددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | قائمة مؤشرات الصفحات التي سيتم تحويلها. يجب تحديدها لتحويل صفحات محددة. |
|

