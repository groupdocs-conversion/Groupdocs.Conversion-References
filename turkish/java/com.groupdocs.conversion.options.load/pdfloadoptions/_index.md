---
title: "PdfLoadOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Pdf belgelerini yükleme seçenekleri."
type: docs
weight: 27
url: /tr/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

Pdf belgelerini yükleme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | Yeni bir [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) sınıfının örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | Gömülü dosyaları kaldır. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | Gömülü dosyaları kaldır. |
|
|  | [getPassword()](#getPassword--) | Korunan belgeyi korumasız hale getirmek için şifre belirle. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Korunan belgeyi korumasız hale getirmek için şifre belirle. |
|
|  | [getDefaultFont()](#getDefaultFont--) | Pdf belgesi için varsayılan yazı tipi. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pdf belgesi için varsayılan yazı tipi. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Pdf belgesi dönüştürülürken belirli yazı tiplerini değiştir. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Pdf belgesi dönüştürülürken belirli yazı tiplerini değiştir. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Pdf belgelerindeki açıklamaları gizle. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Pdf belgelerindeki açıklamaları gizle. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | PDF formundaki tüm alanları düzleştir. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | PDF formundaki tüm alanları düzleştir. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Belgeyi yüklemeden önce yazı tipi klasörlerini sıfırla. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Dönüştürülen belgede sayfa numaralandırma oluşturulmasını etkinleştir veya devre dışı bırak. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Remove JavaScript bayrağını alır. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Remove JavaScript bayrağını ayarlar. |
|
|  | [isConvertOwner()](#isConvertOwner--) | Sahip belgeyin dönüştürülüp dönüştürülmeyeceğini belirtir. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | Sahip belgeyin dönüştürülüp dönüştürülmeyeceğini belirtir. |
|
|  | [isConvertOwned()](#isConvertOwned--) | Sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini belirtir. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | Sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini belirtir. |
|
|  | [getDepth()](#getDepth--) | Sahip olunan belgelerin işlenmesi için maksimum derinlik. |
|
|  | [setDepth(int depth)](#setDepth-int-) | Sahip olunan belgelerin işlenmesi için maksimum derinlik. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


Yeni bir [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) sınıfının örneğini başlatır.


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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Pdf belgesi için varsayılan yazı tipi.
Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacak.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Pdf belgesi için varsayılan yazı tipi.
Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacak.


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


Belgeyi yüklemeden önce yazı tipi klasörlerini sıfırla.


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

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Dönüştürülen belgede sayfa numaralandırma oluşturulmasını etkinleştir veya devre dışı bırak. Varsayılan: false.


**Returns:**
boolean
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isPageNumbering | boolean |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Remove JavaScript bayrağını alır.


**Returns:**
boolean
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Remove JavaScript bayrağını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| removeJavascript | boolean |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Sahip belgeyin dönüştürülüp dönüştürülmeyeceğini belirtir.

Varsayılan
true
.


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


Sahip belgeyin dönüştürülüp dönüştürülmeyeceğini belirtir.

Varsayılan
true
.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini belirtir.

Varsayılan
false
.


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


Sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini belirtir.

Varsayılan
false
.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Sahip olunan belgelerin işlenmesi için maksimum derinlik.

Varsayılan
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


Sahip olunan belgelerin işlenmesi için maksimum derinlik.

Varsayılan
2
.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| depth | int |  |

