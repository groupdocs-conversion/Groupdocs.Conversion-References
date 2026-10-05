---
title: "PdfLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Pdf belgelerini yükleme seçenekleri."
type: docs
weight: 31
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfLoadOptions extends LoadOptions implements Serializable
```

Pdf belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) | Yeni bir [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Gömülü dosyaları kaldır. |
| [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Gömülü dosyaları kaldır. |
| [getPassword()](#getPassword--) | Korunan belgeyi korumasız hale getirmek için şifre ayarla. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Korunan belgeyi korumasız hale getirmek için şifre ayarla. |
| [getDefaultFont()](#getDefaultFont--) | Pdf belgesi için varsayılan yazı tipi. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pdf belgesi için varsayılan yazı tipi. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Pdf belgesi dönüştürülürken belirli yazı tiplerini değiştir. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Pdf belgesi dönüştürülürken belirli yazı tiplerini değiştir. |
| [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Pdf belgelerindeki açıklamaları gizle. |
| [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Pdf belgelerindeki açıklamaları gizle. |
| [getFlattenAllFields()](#getFlattenAllFields--) | PDF formundaki tüm alanları düzleştir. |
| [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | PDF formundaki tüm alanları düzleştir. |
| [getResetFontFolders()](#getResetFontFolders--) | Belge yüklemeden önce yazı tipi klasörlerini sıfırla |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Yeni bir [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) sınıfı örneği başlatır.

### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


Girdi belge dosya türü

**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


Gömülü dosyaları kaldır.

**Returns:**
boolean
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


Gömülü dosyaları kaldır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Korunan belgeyi korumasız hale getirmek için şifre ayarla.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Korunan belgeyi korumasız hale getirmek için şifre ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Pdf belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Pdf belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Pdf belgesi dönüştürülürken belirli yazı tiplerini değiştir.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Pdf belgesi dönüştürülürken belirli yazı tiplerini değiştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Pdf belgelerindeki açıklamaları gizle.

**Returns:**
boolean
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Pdf belgelerindeki açıklamaları gizle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


PDF formundaki tüm alanları düzleştir.

**Returns:**
boolean
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


PDF formundaki tüm alanları düzleştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Belge yüklemeden önce yazı tipi klasörlerini sıfırla

**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resetFontFolders | boolean |  |

