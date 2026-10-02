---
title: "PersonalStorageLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات التخزين الشخصي."
type: docs
weight: 28
url: /ar/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

خيارات تحميل مستندات التخزين الشخصي.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | يقوم بإنشاء مثيل جديد للفئة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFolder()](#getFolder--) | المجلد الذي سيتم معالجته. القيمة الافتراضية هي Inbox |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | تعيين المجلد الذي سيتم معالجته |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} المالك لن يتم تحويله |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


يقوم بإنشاء مثيل جديد للفئة.


### getFolder() {#getFolder--}
```
public String getFolder()
```


المجلد الذي سيتم معالجته. القيمة الافتراضية هي Inbox


**Returns:**
java.lang.String - المجلد الذي سيتم معالجته

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


تعيين المجلد الذي سيتم معالجته


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مجلد | java.lang.String | مجلد |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


يحصل على خيار للتحكم فيما إذا كان يجب تحويل حاوية المستندات نفسها. المالك لن يتم تحويله


**Returns:**
منطقي
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


خيار للتحكم فيما إذا كان يجب تحويل المستندات المملوكة في حاوية المستندات


**Returns:**
منطقي
### getDepth() {#getDepth--}
```
public int getDepth()
```


خيار للتحكم بعدد المستويات في العمق التي يتم فيها إجراء التحويل


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| depth | int |  |

