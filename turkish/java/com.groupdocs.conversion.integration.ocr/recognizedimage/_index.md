---
title: "RecognizedImage"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Bir görüntüden tanıma süreci sonucunda çıkarılan metni temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Tanıma sürecinin bir sonucu olarak bir görüntüden çıkarılan metni temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Tanınan satırların bir kümesini kullanarak sınıfın yeni bir örneğini başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [EMPTY](#EMPTY) | Boş tanınan görüntü |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getLines()](#getLines--) | Belge içinde tanınan metin satırlarını ve bunların fragmentlerini alır. |
|
|  | [getText()](#getText--) | Yapılandırılmış metnin metinsel eşdeğerini alır |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Tanınan satırların bir kümesini kullanarak sınıfın yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | satırlar | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | tanınan satırların bir IEnumerable'i (ör. bir liste veya dizi) |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Boş tanınan görüntü


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Belge içinde tanınan metin satırlarını ve bunların fragmentlerini alır.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Yapılandırılmış metnin metinsel eşdeğerini alır


**Returns:**
java.lang.String
