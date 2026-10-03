---
title: "WordProcessingLoadOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "WordProcessing belgelerini yükleme seçenekleri."
type: docs
weight: 40
url: /tr/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

WordProcessing belgelerini yükleme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | Yeni bir [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) sınıfının örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Words belgesi için varsayılan yazı tipi. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Words belgesi için varsayılan yazı tipi. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | AutoFontSubstitution devre dışı bırakıldığında, GroupDocs.Conversion eksik yazı tiplerinin yerine koyma için DefaultFont'u kullanır. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | AutoFontSubstitution devre dışı bırakıldığında, GroupDocs.Conversion eksik yazı tiplerinin yerine koyma için DefaultFont'u kullanır. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Words belgesini dönüştürürken belirli yazı tiplerini yerine koy. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | EmbedTrueTypeFonts true olduğunda, GroupDocs.Conversion çıktı belgesine TrueType yazı tiplerini gömer. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | Yükleme sonrasında sayfa düzenini güncelle. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | Yükleme sonrasında alanları güncelle. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | Tarih alanının orijinal değerini koru. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | Tarih alanının orijinal değerini korumayı ayarlar. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Words belgesini dönüştürürken belirli yazı tiplerini yerine koy. |
|
|  | [getPassword()](#getPassword--) | Korunan belgeyi korumasız hale getirmek için şifre belirle. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Korunan belgeyi korumasız hale getirmek için şifre belirle. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Word belgeleri için işaretlemeyi ve değişiklik izlemeyi gizle. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Word belgeleri için işaretlemeyi ve değişiklik izlemeyi gizle. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Yorumları gizle. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | Yer işaretleri seçenekleri |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | Yer işaretleri seçenekleri |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Microsoft Word form alanlarını PDF içinde form alanı olarak koruyup korumayacağını veya metne dönüştürülüp dönüştürüleceğini belirtir. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | preserveFontFields bayrağını ayarlar |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | Daha iyi kerning gösterimi için bir metin şekillendirici kullanılıp kullanılmayacağını belirtir. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | Daha iyi kerning gösterimi için bir metin şekillendirici kullanılıp kullanılmayacağını belirtir. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | PDF'ye dönüştürürken belge yapısının korunup korunmayacağını belirler (varsayılan false'tur). |
|
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | Yorumların çıktı belgesinde nasıl görüntüleneceğini belirtir. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | Yorumlarda tam yorumcu adını göster. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | Dönüştürülen belgede sayfa numaralandırma oluşturulmasını etkinleştir veya devre dışı bırak. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | WordProcessing belgeleri için heceleme seçeneklerini al. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | WordProcessing belgeleri için heceleme seçeneklerini ayarlar. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | InterruptThreadIfImageExceptionThrown bayrağını alır Varsayılan: false Eğer true ise bir görüntü işleme iş parçacığında bir istisna oluştuğunda ana dönüşüm iş parçacığını kesintiye uğratır |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | InterruptThreadIfImageExceptionThrown bayrağını ayarlar |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | Etkinleştirildiğinde (varsayılan), metni ağırlıklı olarak sağdan sola (RTL) olan paragraflar ve koşular, dönüşümden önce bidi bayrakları onarılır. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | autoDetectRtlDirection ayarını yapar |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
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


Words belgesi için varsayılan yazı tipi. Yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Words belgesi için varsayılan yazı tipi. Yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


AutoFontSubstitution devre dışı bırakılırsa, GroupDocs.Conversion eksik yazı tiplerinin yerine DefaultFont'u kullanır. AutoFontSubstitution etkinleştirilirse,
GroupDocs.Conversion eksik yazı tipi için FontInfo (Panose, Sig vb.) içindeki tüm ilgili alanları değerlendirir ve mevcut yazı tipi kaynakları arasında en yakın eşleşmeyi bulur.
Yazı tipi ikame mekanizmasının, eksik yazı tipinin FontInfo'su belgede mevcut olduğunda DefaultFont'u geçersiz kılacağını unutmayın. Varsayılan değer True'tır.


**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


AutoFontSubstitution devre dışı bırakılırsa, GroupDocs.Conversion eksik yazı tiplerinin yerine DefaultFont'u kullanır. AutoFontSubstitution etkinleştirilirse,
GroupDocs.Conversion eksik yazı tipi için FontInfo (Panose, Sig vb.) içindeki tüm ilgili alanları değerlendirir ve mevcut yazı tipi kaynakları arasında en yakın eşleşmeyi bulur.
Yazı tipi ikame mekanizmasının, eksik yazı tipinin FontInfo'su belgede mevcut olduğunda DefaultFont'u geçersiz kılacağını unutmayın. Varsayılan değer True'tır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Words belgesini dönüştürürken belirli yazı tiplerini yerine koy.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


EmbedTrueTypeFonts true ise, GroupDocs.Conversion çıktı belgesine TrueType yazı tiplerini gömer. Varsayılan: false


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


Words belgesini dönüştürürken belirli yazı tiplerini yerine koy.


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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Word belgeleri için işaretlemeyi ve değişiklik izlemeyi gizle.


**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Word belgeleri için işaretlemeyi ve değişiklik izlemeyi gizle.


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


Microsoft Word form alanlarını PDF'de form alanı olarak koruyup korumayacağını veya metne dönüştürüleceğini belirtir. Varsayılan false'tur.


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
|  | preserveFontFields | boolean | Microsoft Word form alanlarını PDF'de form alanı olarak koru veya metne dönüştür |
|

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
|  | isUseTextShaper | boolean | isUseTextShaper bayrağı |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


PDF'ye dönüştürürken belge yapısının korunup korunmayacağını belirler (varsayılan false'tur). Belge yapısını dışa aktarmanın bellek tüketimini önemli ölçüde artırdığını, özellikle büyük belgeler için, unutmayın.


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


Doğru olduğunda tüm dış kaynaklar, içinde bulunan kaynaklar hariç, yüklenmeyecek


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


Her zaman yüklenecek dış kaynaklar


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


Yorumların çıktı belgesinde nasıl görüntüleneceğini belirler. Varsayılan ShowInBalloons'dur.


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

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


Dönüştürülmüş belgede sayfa numaralandırmasının oluşturulmasını etkinleştir veya devre dışı bırak. Varsayılan: false


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

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


WordProcessing belgeleri için heceleme seçeneklerini al.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


WordProcessing belgeleri için heceleme seçeneklerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


InterruptThreadIfImageExceptionThrown bayrağını alır Varsayılan: false Eğer true ise bir görüntü işleme iş parçacığında bir istisna oluştuğunda ana dönüşüm iş parçacığını kesintiye uğratır


**Returns:**
boolean
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


InterruptThreadIfImageExceptionThrown bayrağını ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | boolean |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


Etkinleştirildiğinde (varsayılan), metni ağırlıklı olarak sağdan sola (RTL) olan paragraflar ve koşular, dönüşümden önce bidi bayrakları onarılır.


Bu, Microsoft Word ve LibreOffice tarafından uygulanan sezgisel yöntemi eşleştirir ve
Üreteçler tarafından oluşturulan Arapça/İbranice belgelerin işlenmesini düzeltir
(özellikle Google Docs) OOXML'i olmadan yayan


ve ile

yalnızca RTL betiği içeren çalıştırmalarda.


Şu şekilde ayarla
false
katı OOXML yorumlamasını korumak için
kaynak işaretlemesi.


**Returns:**
boolean
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


autoDetectRtlDirection ayarını yapar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | autoDetectRtlDirection | boolean | autoDetectRtlDirection |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Belge konteynerinin kendisinin dönüştürülüp dönüştürülmeyeceğini kontrol etmek için seçeneği alır


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Belge konteynerindeki sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini kontrol etme seçeneği


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Dönüştürmenin kaç derinlik seviyesinde yapılacağını kontrol etme seçeneği


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| depth | int |  |

