---
title: "TextFragment"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل جزءًا من النص المعترف به، كلمة، رمز، إلخ، المستخرج بواسطة محرك OCR."
type: docs
weight: 11
url: /ar/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

يمثل جزءًا من النص المعترف به (كلمة، رمز، إلخ)، مستخرجًا بواسطة محرك OCR.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | يُنشئ مثيلاً جديداً لمجزأ النص المُعترف به. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | يحصل على المحتوى النصي لمجزأ النص المُعترف به. |
|
|  | [getRectangle()](#getRectangle--) | يحصل على المستطيل المحيط لمجزأ النص المُعترف به. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


يُنشئ مثيلاً جديداً لمجزأ النص المُعترف به.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | المحتوى النصي لمجزأ النص المُعترف به |
|
|  | مستطيل | java.awt.Rectangle | المستطيل المحيط لمجزأ النص المُعترف به |
|

### getText() {#getText--}
```
public String getText()
```


يحصل على المحتوى النصي لمجزأ النص المُعترف به.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


يحصل على المستطيل المحيط لمجزأ النص المُعترف به.


**Returns:**
[Rectangle](../../java.awt/rectangle)
