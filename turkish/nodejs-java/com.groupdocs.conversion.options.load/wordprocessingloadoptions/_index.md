---
title: "WordProcessingLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "WordProcessing belgelerini yükleme seçenekleri."
type: docs
weight: 44
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

WordProcessing belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Yeni bir [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Words belgesi için varsayılan yazı tipi. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Words belgesi için varsayılan yazı tipi. |
| [getAutoFontSubstitution()](#getAutoFontSubstitution--) | AutoFontSubstitution devre dışı bırakıldığında, GroupDocs.Conversion eksik yazı tiplerinin yerine koyma için DefaultFont kullanır. |
| [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | AutoFontSubstitution devre dışı bırakıldığında, GroupDocs.Conversion eksik yazı tiplerinin yerine koyma için DefaultFont kullanır. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Words belgesini dönüştürürken belirli yazı tiplerini değiştirir. |
| [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | EmbedTrueTypeFonts true olduğunda, GroupDocs.Conversion çıktı belgesine TrueType yazı tiplerini gömer. |
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
| [isUpdatePageLayout()](#isUpdatePageLayout--) | Yüklemeden sonra sayfa düzenini güncelle. |
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
| [isUpdateFields()](#isUpdateFields--) | Yüklemeden sonra alanları güncelle. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
| [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Tarih alanının orijinal değerini koru. |
| [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Tarih alanının orijinal değerini korumayı ayarlar. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Words belgesini dönüştürürken belirli yazı tiplerini değiştirir. |
| [getPassword()](#getPassword--) | Korunan belgeyi korumasız hale getirmek için şifre ayarla. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Korunan belgeyi korumasız hale getirmek için şifre ayarla. |
| [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Word belgeleri için işaretlemeyi gizle ve değişiklikleri izle. |
| [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Word belgeleri için işaretlemeyi gizle ve değişiklikleri izle. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Yorumları gizle. |
| [getBookmarkOptions()](#getBookmarkOptions--) | Yer işaretleri seçenekleri |
| [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Yer işaretleri seçenekleri |
| [isPreserveFontFields()](#isPreserveFontFields--) | Microsoft Word form alanlarını PDF'de form alanı olarak koruyup korumayacağını veya metne dönüştürüleceğini belirtir. |
| [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | preserveFontFields bayrağını ayarlar |
| [isUseTextShaper()](#isUseTextShaper--) | Daha iyi kerning gösterimi için bir metin şekillendirici kullanılıp kullanılmayacağını belirtir. |
| [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Daha iyi kerning gösterimi için bir metin şekillendirici kullanılıp kullanılmayacağını belirtir. |
| [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | PDF'ye dönüştürürken belge yapısının korunup korunmayacağını belirler (varsayılan false'tur). |
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
| [getSkipExternalResources()](#getSkipExternalResources--) | \{@inheritDoc\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \{@inheritDoc\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \{@inheritDoc\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \{@inheritDoc\} |
| [getCommentDisplayMode()](#getCommentDisplayMode--) | Yorumların çıktı belgesinde nasıl görüntüleneceğini belirtir. |
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
| [getShowFullCommenterName()](#getShowFullCommenterName--) | Yorumlarda tam yorumcu adını göster. |
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


Yeni bir [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) sınıfının örneğini başlatır.

### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


Girdi belge dosya türü

**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Words belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Words belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


Eğer AutoFontSubstitution devre dışı bırakılmışsa, GroupDocs.Conversion eksik yazı tiplerinin yerine DefaultFont'u kullanır. AutoFontSubstitution etkinleştirilmişse, GroupDocs.Conversion eksik yazı tipi için FontInfo (Panose, Sig vb.) içindeki tüm ilgili alanları değerlendirir ve mevcut yazı tipi kaynakları arasında en yakın eşleşmeyi bulur. Not: yazı tipi ikame mekanizması, eksik yazı tipi için FontInfo belgede mevcut olduğunda DefaultFont'u geçersiz kılar. Varsayılan değer True'tir.

**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


Eğer AutoFontSubstitution devre dışı bırakılmışsa, GroupDocs.Conversion eksik yazı tiplerinin yerine DefaultFont'u kullanır. AutoFontSubstitution etkinleştirilmişse, GroupDocs.Conversion eksik yazı tipi için FontInfo (Panose, Sig vb.) içindeki tüm ilgili alanları değerlendirir ve mevcut yazı tipi kaynakları arasında en yakın eşleşmeyi bulur. Not: yazı tipi ikame mekanizması, eksik yazı tipi için FontInfo belgede mevcut olduğunda DefaultFont'u geçersiz kılar. Varsayılan değer True'tir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Words belgesini dönüştürürken belirli yazı tiplerini değiştirir.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


Eğer EmbedTrueTypeFonts true ise, GroupDocs.Conversion çıktı belgesine TrueType yazı tiplerini gömer. Varsayılan: false

**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


Yüklemeden sonra sayfa düzenini güncelle. Varsayılan: false

**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Yüklemeden sonra alanları güncelle. Varsayılan: false

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| updateFields | boolean |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


Tarih alanının orijinal değerini koru. Varsayılan: false

**Returns:**
boolean
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


Tarih alanının orijinal değerini korumayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keepDateFieldOriginalValue | boolean |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Words belgesini dönüştürürken belirli yazı tiplerini değiştirir.

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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Word belgeleri için işaretlemeyi gizle ve değişiklikleri izle.

**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Word belgeleri için işaretlemeyi gizle ve değişiklikleri izle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Yorumları gizle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


Yer işaretleri seçenekleri

**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


Yer işaretleri seçenekleri

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Microsoft Word form alanlarını PDF içinde form alanı olarak koruyup metne dönüştürülüp dönüştürülmeyeceğini belirtir. Varsayılan false'tur.

**Returns:**
boolean - preserveFontFields bayrağı
### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


preserveFontFields bayrağını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| preserveFontFields | boolean | Microsoft Word form alanlarını PDF içinde form alanı olarak koru veya metne dönüştür |

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


Daha iyi kerning gösterimi için bir metin şekillendirici kullanılıp kullanılmayacağını belirtir. Varsayılan false'tur.

**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


Daha iyi kerning gösterimi için bir metin şekillendirici kullanılıp kullanılmayacağını belirtir. Varsayılan false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isUseTextShaper | boolean | isUseTextShaper bayrağı |

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


PDF'ye dönüştürürken belge yapısının korunup korunmayacağını belirler (varsayılan false). Not: belge yapısını dışa aktarmak, özellikle büyük belgelerde bellek tüketimini önemli ölçüde artırır.

**Returns:**
boolean
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| preserveDocumentStructure | boolean |  |

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

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


Yorumların çıktı belgesinde nasıl görüntüleneceğini belirtir. Varsayılan ShowInBalloons'dur.

**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


Yorumlarda tam yorumcu adını göster. Varsayılan false'tur.

**Returns:**
boolean
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| showFullCommenterName | boolean |  |

