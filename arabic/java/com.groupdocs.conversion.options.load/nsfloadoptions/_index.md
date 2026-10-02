---
title: "NsfLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات Nsf."
type: docs
weight: 25
url: /ar/java/com.groupdocs.conversion.options.load/nsfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class NsfLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

خيارات تحميل مستندات Nsf.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [NsfLoadOptions()](#NsfLoadOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) |  |
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### NsfLoadOptions() {#NsfLoadOptions--}
```
public NsfLoadOptions()
```


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


يحصل على خيار للتحكم فيما إذا كان يجب تحويل حاوية المستندات نفسها


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

