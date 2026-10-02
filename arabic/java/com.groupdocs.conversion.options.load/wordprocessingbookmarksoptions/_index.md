---
title: "WordProcessingBookmarksOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التعامل مع العلامات المرجعية في معالجة النصوص"
type: docs
weight: 39
url: /ar/java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

خيارات التعامل مع العلامات المرجعية في معالجة النصوص

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | يحدد المستوى الافتراضي في مخطط المستند الذي يتم فيه عرض إشارات Word. |
|
|  | [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | يحدد المستوى الافتراضي في مخطط المستند الذي يتم فيه عرض إشارات Word. |
|
|  | [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | يحدد عدد مستويات العناوين (الفقرات المنسقة بأنماط Heading) التي يجب تضمينها في مخطط المستند. |
|
|  | [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | يحدد عدد مستويات العناوين (الفقرات المنسقة بأنماط Heading) التي يجب تضمينها في مخطط المستند. |
|
|  | [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | يحدد عدد المستويات في مخطط المستند التي يجب عرضها موسعة عند عرض الملف. |
|
|  | [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | يحدد عدد المستويات في مخطط المستند التي يجب عرضها موسعة عند عرض الملف. |
|
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


يحدد المستوى الافتراضي في مخطط المستند الذي تُعرض فيه إشارات Word. الافتراضي هو 0. النطاق الصالح هو من 0 إلى 9.


**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


يحدد المستوى الافتراضي في مخطط المستند الذي تُعرض فيه إشارات Word. الافتراضي هو 0. النطاق الصالح هو من 0 إلى 9.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


يحدد عدد مستويات العناوين (الفقرات المنسقة بأنماط Heading) التي يجب تضمينها في مخطط المستند. الافتراضي هو 0. النطاق الصالح هو من 0 إلى 9.


**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


يحدد عدد مستويات العناوين (الفقرات المنسقة بأنماط Heading) التي يجب تضمينها في مخطط المستند. الافتراضي هو 0. النطاق الصالح هو من 0 إلى 9.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


يحدد عدد المستويات في مخطط المستند التي يجب عرضها موسعة عند عرض الملف. الافتراضي هو 0. النطاق الصالح هو من 0 إلى 9. لاحظ أن هذا الخيار لن يعمل عند الحفظ إلى XPS.


**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


يحدد عدد المستويات في مخطط المستند التي يجب عرضها موسعة عند عرض الملف. الافتراضي هو 0. النطاق الصالح هو من 0 إلى 9. لاحظ أن هذا الخيار لن يعمل عند الحفظ إلى XPS.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

