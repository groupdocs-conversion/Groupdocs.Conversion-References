---
title: "TextFragment"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "OCR motoru tarafından çıkarılan tanınmış metin, kelime, sembol vb. bir bölümünü temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

OCR motoru tarafından çıkarılan tanınan metnin bir parçasını (kelime, sembol vb.) temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Tanınan metin fragmentinin yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getText()](#getText--) | Tanınan metin fragmentinin metinsel içeriğini alır. |
|
|  | [getRectangle()](#getRectangle--) | Tanınan metin fragmentinin sınırlayıcı dikdörtgenini alır. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Tanınan metin fragmentinin yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | tanınan metin fragmentinin metinsel içeriği |
|
|  | dikdörtgen | java.awt.Rectangle | tanınan metin fragmentinin sınırlayıcı dikdörtgeni |
|

### getText() {#getText--}
```
public String getText()
```


Tanınan metin fragmentinin metinsel içeriğini alır.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Tanınan metin fragmentinin sınırlayıcı dikdörtgenini alır.


**Returns:**
[Rectangle](../../java.awt/rectangle)
