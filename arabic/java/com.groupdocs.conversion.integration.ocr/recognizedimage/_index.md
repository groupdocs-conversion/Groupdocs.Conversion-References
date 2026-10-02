---
title: "RecognizedImage"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل النص المستخرج من صورة نتيجة عملية التعرف عليه."
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

يمثل النص المستخرج من صورة نتيجة عملية التعرف عليها.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | يُنشئ مثيلاً جديداً للفئة، باستخدام مجموعة من السطور المُعترف بها. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [EMPTY](#EMPTY) | صورة مُعترف بها فارغة |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getLines()](#getLines--) | يحصل على سطور النص، مع مجزئاتها، المُعترف بها داخل المستند. |
|
|  | [getText()](#getText--) | يحصل على المكافئ النصي للنص المُنظم |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


يُنشئ مثيلاً جديداً للفئة، باستخدام مجموعة من السطور المُعترف بها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | سطور | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | IEnumerable (مثل القائمة أو المصفوفة) من السطور المُعترف بها |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


صورة مُعترف بها فارغة


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


يحصل على سطور النص، مع مجزئاتها، المُعترف بها داخل المستند.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


يحصل على المكافئ النصي للنص المُنظم


**Returns:**
java.lang.String
