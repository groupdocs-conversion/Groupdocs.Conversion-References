---
title: "TextLine"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل النص المستخرج من صورة نتيجة عملية التعرف عليه."
type: docs
weight: 12
url: /ar/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

يمثل النص المستخرج من صورة نتيجة عملية التعرف عليها.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | يُنشئ مثيلاً جديداً لسطر نصي، مستخرج بواسطة محرك OCR من صورة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFragments()](#getFragments--) | يحصل على مصفوفة من مجزئات النص، مثل الرموز والكلمات، المُعترف بها في السطر. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


يُنشئ مثيلاً جديداً لسطر نصي، مستخرج بواسطة محرك OCR من صورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مجزئات | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | المجموعة الأولية من مجزئات النص |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


يحصل على مصفوفة من مجزئات النص، مثل الرموز والكلمات، المُعترف بها في السطر.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
