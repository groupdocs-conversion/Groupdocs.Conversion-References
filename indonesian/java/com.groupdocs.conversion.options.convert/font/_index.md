---
title: "Font"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Pengaturan font"
type: docs
weight: 16
url: /id/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Pengaturan font

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | membuat instance Font baru |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Mendapatkan nama keluarga font |
|
|  | [getSize()](#getSize--) | Mendapatkan ukuran font |
|
|  | [isBold()](#isBold--) | Penanda tebal Font |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Mengatur penanda tebal Font |
|
|  | [isItalic()](#isItalic--) | Penanda miring Font |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | Mengatur flag italic font |
|
|  | [isUnderline()](#isUnderline--) | Mendapatkan underline Font |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Mengatur underline Font |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


membuat instance Font baru


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Nama Font |
|
|  | size | float | Ukuran Font |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Mendapatkan nama keluarga font


**Returns:**
java.lang.String - Nama keluarga Font

### getSize() {#getSize--}
```
public float getSize()
```


Mendapatkan ukuran font


**Returns:**
float - Ukuran Font

### isBold() {#isBold--}
```
public boolean isBold()
```


Penanda tebal Font


**Returns:**
boolean - true jika tebal

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Mengatur penanda tebal Font


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | tebal | boolean | true jika tebal |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Penanda miring Font


**Returns:**
boolean - true jika miring

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Mengatur flag italic font


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | miring | boolean | true jika miring |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Mendapatkan underline Font


**Returns:**
boolean - true jika Font bergaris bawah

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Mengatur underline Font


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | garis bawah | boolean | Flag underline Font |
|

### getDefault() {#getDefault--}
```
public static Font getDefault()
```




**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
### clone(float newSize) {#clone-float-}
```
public Font clone(float newSize)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
