---
title: "TextLine"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Bir görüntüden tanıma süreci sonucunda çıkarılan metni temsil eder."
type: docs
weight: 12
url: /tr/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Tanıma sürecinin bir sonucu olarak bir görüntüden çıkarılan metni temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | OCR motoru tarafından bir görüntüden çıkarılan bir metin satırının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFragments()](#getFragments--) | Satırda tanınan semboller ve kelimeler gibi metin fragmentlerinin bir dizisini alır. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


OCR motoru tarafından bir görüntüden çıkarılan bir metin satırının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fragmentler | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | metin fragmentlerinin ilk kümesi |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Satırda tanınan semboller ve kelimeler gibi metin fragmentlerinin bir dizisini alır.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
