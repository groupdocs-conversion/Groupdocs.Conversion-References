---
title: "PresentationLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Sunum belgelerini yükleme seçenekleri."
type: docs
weight: 33
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/presentationloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class PresentationLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

Sunum belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) | Yeni bir [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Sunumu renderlamak için varsayılan yazı tipi. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Sunumu renderlamak için varsayılan yazı tipi. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Sunum belgesi dönüştürülürken belirli yazı tiplerini değiştir. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sunum belgesi dönüştürülürken belirli yazı tiplerini değiştir. |
| [getPassword()](#getPassword--) | Korunan belgeyi korumasız hale getirmek için şifre ayarla. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Korunan belgeyi korumasız hale getirmek için şifre ayarla. |
| [getHideComments()](#getHideComments--) | Yorumları gizle. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Yorumları gizle. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gizli slaytları göster. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gizli slaytları göster. |
| [getSkipExternalResources()](#getSkipExternalResources--) | \{@inheritDoc\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \{@inheritDoc\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \{@inheritDoc\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \{@inheritDoc\} |
| [getDocumentFontSources()](#getDocumentFontSources--) |  |
| [setDocumentFontSources(List<String> documentFontSources)](#setDocumentFontSources-java.util.List-java.lang.String--) |  |
| [getNotesPosition()](#getNotesPosition--) | Yorumların slayt ile birlikte nasıl yazdırıldığını temsil eder. |
| [setNotesPosition(PresentationNotesPosition notesPosition)](#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-) | Notların slayt ile birlikte nasıl yazdırıldığını temsil eder. |
| [getCommentsPosition()](#getCommentsPosition--) |  |
| [setCommentsPosition(PresentationCommentsPosition commentsPosition)](#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-) |  |
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


Yeni bir [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) sınıfı örneği başlatır.

### getFormat() {#getFormat--}
```
public final PresentationFileType getFormat()
```


Girdi belge dosya türü

**Returns:**
[PresentationFileType](../../com.groupdocs.conversion.filetypes/presentationfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Sunumu renderlamak için varsayılan yazı tipi. Sunumda bir yazı tipi eksikse aşağıdaki yazı tipi kullanılacaktır.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Sunumu renderlamak için varsayılan yazı tipi. Sunumda bir yazı tipi eksikse aşağıdaki yazı tipi kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sunum belgesi dönüştürülürken belirli yazı tiplerini değiştir.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sunum belgesi dönüştürülürken belirli yazı tiplerini değiştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

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

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Yorumları gizle.

**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Yorumları gizle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Gizli slaytları göster.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Gizli slaytları göster.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


Eğer true ise, tüm harici kaynaklar, içinde bulunan kaynaklar hariç, yüklenmeyecek.

**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| skip | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Her zaman yüklenecek harici kaynaklar

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getDocumentFontSources() {#getDocumentFontSources--}
```
public List<String> getDocumentFontSources()
```




**Returns:**
java.util.List<java.lang.String>
### setDocumentFontSources(List<String> documentFontSources) {#setDocumentFontSources-java.util.List-java.lang.String--}
```
public void setDocumentFontSources(List<String> documentFontSources)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentFontSources | java.util.List<java.lang.String> |  |

### getNotesPosition() {#getNotesPosition--}
```
public PresentationNotesPosition getNotesPosition()
```


Yorumların slayt ile birlikte nasıl yazdırıldığını temsil eder. Varsayılan değer None'dur.

**Returns:**
[PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition)
### setNotesPosition(PresentationNotesPosition notesPosition) {#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-}
```
public void setNotesPosition(PresentationNotesPosition notesPosition)
```


Notların slayt ile birlikte nasıl yazdırıldığını temsil eder. Varsayılan değer None'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| notesPosition | [PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition) |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public PresentationCommentsPosition getCommentsPosition()
```




**Returns:**
[PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) - 
### setCommentsPosition(PresentationCommentsPosition commentsPosition) {#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-}
```
public void setCommentsPosition(PresentationCommentsPosition commentsPosition)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| commentsPosition | [PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) |  |

