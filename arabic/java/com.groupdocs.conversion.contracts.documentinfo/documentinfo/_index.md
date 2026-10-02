---
title: "DocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يوفر تنفيذًا أساسيًا لاسترجاع معلومات المستند المتعددة الأشكال"
type: docs
weight: 16
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

يوفر تنفيذًا أساسيًا لاسترجاع معلومات المستند المتعددة الأشكال

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPropertyNames()](#getPropertyNames--) | {@inheritDoc} |
|
|  | [getProperty(String propertyName)](#getProperty-java.lang.String-) | {@inheritDoc} |
|
|  | [getPagesCount()](#getPagesCount--) | {@inheritDoc} |
|
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [getSize()](#getSize--) | {@inheritDoc} |
|
|  | [getCreationDate()](#getCreationDate--) | {@inheritDoc} |
|
### getPropertyNames() {#getPropertyNames--}
```
public List<String> getPropertyNames()
```


قائمة بجميع الخصائص التي يمكن الحصول عليها لمعلومات المستند الحالي


**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


احصل على القيمة لخاصية مقدمة كمفتاح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


عدد صفحات المستند.


**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


تنسيق المستند


**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


حجم المستند بالبايت


**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


تاريخ إنشاء المستند


**Returns:**
java.util.Date
