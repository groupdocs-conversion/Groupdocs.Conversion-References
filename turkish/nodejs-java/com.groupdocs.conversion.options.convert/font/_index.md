---
title: "Font"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Yazı tipi ayarları"
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Yazı tipi ayarları
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | yeni bir Font örneği oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Fets yazı tipi ailesi adı |
| [getSize()](#getSize--) | Yazı tipi boyutunu alır |
| [isBold()](#isBold--) | Yazı tipi kalın bayrağı |
| [setBold(boolean bold)](#setBold-boolean-) | Yazı tipi kalın bayrağını ayarlar |
| [isItalic()](#isItalic--) | Yazı tipi italik bayrağı |
| [setItalic(boolean italic)](#setItalic-boolean-) | Yazı tipi italik bayrağını ayarlar |
| [isUnderline()](#isUnderline--) | Yazı tipi alt çizgiyi alır |
| [setUnderline(boolean underline)](#setUnderline-boolean-) | Yazı tipi alt çizgiyi ayarlar |
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


yeni bir Font örneği oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Yazı tipi adı |
| size | float | Yazı tipi boyutu |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Fets yazı tipi ailesi adı

**Returns:**
java.lang.String - Yazı tipi ailesi adı
### getSize() {#getSize--}
```
public float getSize()
```


Yazı tipi boyutunu alır

**Returns:**
float - Yazı tipi boyutu
### isBold() {#isBold--}
```
public boolean isBold()
```


Yazı tipi kalın bayrağı

**Returns:**
boolean - kalın ise doğru
### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Yazı tipi kalın bayrağını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kalın | boolean | kalın ise doğru |

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Yazı tipi italik bayrağı

**Returns:**
boolean - italik ise doğru
### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Yazı tipi italik bayrağını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| italik | boolean | italik ise doğru |

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Yazı tipi alt çizgiyi alır

**Returns:**
boolean - yazı tipi alt çizgili ise doğru
### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Yazı tipi alt çizgiyi ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alt çizgi | boolean | Yazı tipi alt çizgi bayrağı |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
