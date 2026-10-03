---
title: "NoteLoadOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "One belgelerini yükleme seçenekleri."
type: docs
weight: 24
url: /tr/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

One belgelerini yükleme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Note belgesi için varsayılan yazı tipi. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Note belgesi için varsayılan yazı tipi. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Note belgesi dönüştürülürken belirli yazı tipleri değiştirilir. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Note belgesi dönüştürülürken belirli yazı tipleri değiştirilir. |
|
|  | [getPassword()](#getPassword--) | Korunan belgeyi korumasız hale getirmek için şifre belirle. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Korunan belgeyi korumasız hale getirmek için şifre belirle. |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


[NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions) sınıfının yeni bir örneğini başlatır.


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


Girdi belge dosya türü


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Note belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Note belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Note belgesi dönüştürülürken belirli yazı tipleri değiştirilir.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Note belgesi dönüştürülürken belirli yazı tipleri değiştirilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Korunan belgeyi korumasız hale getirmek için şifre belirle.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Korunan belgeyi korumasız hale getirmek için şifre belirle.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

