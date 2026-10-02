---
title: "WordProcessingLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات معالجة النصوص."
type: docs
weight: 40
url: /ar/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

خيارات تحميل مستندات معالجة النصوص.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | يُنشئ مثيلًا جديدًا من الفئة [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) class. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | الخط الافتراضي لمستند Words. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | الخط الافتراضي لمستند Words. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | إذا تم تعطيل AutoFontSubstitution، يستخدم GroupDocs.Conversion الخط الافتراضي DefaultFont لاستبدال الخطوط المفقودة. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | إذا تم تعطيل AutoFontSubstitution، يستخدم GroupDocs.Conversion الخط الافتراضي DefaultFont لاستبدال الخطوط المفقودة. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | استبدال خطوط محددة عند تحويل مستند Words. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | إذا كان EmbedTrueTypeFonts صحيحًا، يقوم GroupDocs.Conversion بدمج خطوط True Type في مستند الإخراج. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | تحديث تخطيط الصفحة بعد التحميل. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | تحديث الحقول بعد التحميل. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | الاحتفاظ بالقيمة الأصلية لحقل التاريخ. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | يضبط الاحتفاظ بالقيمة الأصلية لحقل التاريخ. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | استبدال خطوط محددة عند تحويل مستند Words. |
|
|  | [getPassword()](#getPassword--) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | إخفاء العلامات وتتبع التغييرات لمستندات Word. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | إخفاء العلامات وتتبع التغييرات لمستندات Word. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | إخفاء التعليقات. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | خيارات العلامات المرجعية |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | خيارات العلامات المرجعية |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | يحدد ما إذا كان يجب الحفاظ على حقول نماذج Microsoft Word كحقول نماذج في PDF أو تحويلها إلى نص. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | يضبط علم preserveFontFields |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | يحدد ما إذا كان يجب استخدام مُشكِّل نص لتحسين عرض التباعد بين الحروف. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | يحدد ما إذا كان يجب استخدام مُشكِّل نص لتحسين عرض التباعد بين الحروف. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | يحدد ما إذا كان ينبغي الحفاظ على بنية المستند عند التحويل إلى PDF (القيمة الافتراضية هي false). |
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
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | يحدد كيفية عرض التعليقات في مستند الإخراج. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | عرض الاسم الكامل للمعلق في التعليقات. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | تمكين أو تعطيل إنشاء ترقيم الصفحات في المستند المحول. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | يحصل على خيارات التجزئة لكلمات المستندات WordProcessing. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | يضبط خيارات التجزيء للكلمات في مستندات WordProcessing. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | يحصل على علم InterruptThreadIfImageExceptionThrown القيمة الافتراضية: false إذا كان true فسيتم مقاطعة خيط التحويل الرئيسي إذا حدث استثناء في خيط معالجة الصورة. |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | يضبط علم InterruptThreadIfImageExceptionThrown |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | عند التمكين (الافتراضي)، سيتم إصلاح أعلام bidi للفقارات والقطع التي يكون نصها في الغالب من اليمين إلى اليسار (RTL) قبل التحويل. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | يضبط autoDetectRtlDirection |
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


يُنشئ مثيلًا جديدًا من الفئة [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) class.


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


نوع ملف المستند الإدخالي


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


الخط الافتراضي لمستند Words. سيتم استخدام الخط التالي إذا كان الخط مفقودًا.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


الخط الافتراضي لمستند Words. سيتم استخدام الخط التالي إذا كان الخط مفقودًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


إذا تم تعطيل AutoFontSubstitution، يستخدم GroupDocs.Conversion الخط الافتراضي لاستبدال الخطوط المفقودة. إذا تم تمكين AutoFontSubstitution،
يقوم GroupDocs.Conversion بتقييم جميع الحقول ذات الصلة في FontInfo (Panose، Sig وغيرها) للخط المفقود ويجد أقرب تطابق بين مصادر الخطوط المتاحة.
لاحظ أن آلية استبدال الخطوط ستحل محل DefaultFont في الحالات التي يتوفر فيها FontInfo للخط المفقود داخل المستند. القيمة الافتراضية هي True.


**Returns:**
منطقي
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


إذا تم تعطيل AutoFontSubstitution، يستخدم GroupDocs.Conversion الخط الافتراضي لاستبدال الخطوط المفقودة. إذا تم تمكين AutoFontSubstitution،
يقوم GroupDocs.Conversion بتقييم جميع الحقول ذات الصلة في FontInfo (Panose، Sig وغيرها) للخط المفقود ويجد أقرب تطابق بين مصادر الخطوط المتاحة.
لاحظ أن آلية استبدال الخطوط ستحل محل DefaultFont في الحالات التي يتوفر فيها FontInfo للخط المفقود داخل المستند. القيمة الافتراضية هي True.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


استبدال خطوط محددة عند تحويل مستند Words.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


إذا كان EmbedTrueTypeFonts true، يقوم GroupDocs.Conversion بدمج خطوط True Type في المستند الناتج. القيمة الافتراضية: false


**Returns:**
منطقي
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| embedTrueTypeFonts | منطقي |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


تحديث تخطيط الصفحة بعد التحميل. القيمة الافتراضية: false


**Returns:**
منطقي
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| updatePageLayout | منطقي |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


تحديث الحقول بعد التحميل. القيمة الافتراضية: false


**Returns:**
منطقي
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| updateFields | منطقي |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


الاحتفاظ بالقيمة الأصلية لحقل التاريخ. القيمة الافتراضية: false


**Returns:**
منطقي
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


يضبط الاحتفاظ بالقيمة الأصلية لحقل التاريخ.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| keepDateFieldOriginalValue | منطقي |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


استبدال خطوط محددة عند تحويل مستند Words.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


تعيين كلمة مرور لإلغاء حماية المستند المحمي.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


تعيين كلمة مرور لإلغاء حماية المستند المحمي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


إخفاء العلامات وتتبع التغييرات لمستندات Word.


**Returns:**
منطقي
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


إخفاء العلامات وتتبع التغييرات لمستندات Word.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


إخفاء التعليقات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


خيارات العلامات المرجعية


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


خيارات العلامات المرجعية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


يحدد ما إذا كان يجب الحفاظ على حقول نماذج Microsoft Word كحقول نماذج في PDF أو تحويلها إلى نص. القيمة الافتراضية هي false.


**Returns:**
منطقي - علم preserveFontFields

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


يضبط علم preserveFontFields


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | preserveFontFields | منطقي | حافظ على حقول نماذج Microsoft Word كحقول نماذج في PDF أو تحويلها إلى نص |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


يحدد ما إذا كان يجب استخدام مُشكل النص للحصول على عرض أفضل للتقارب الحرفي. القيمة الافتراضية هي false.


**Returns:**
منطقي
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


يحدد ما إذا كان يجب استخدام مُشكل النص للحصول على عرض أفضل للتقارب الحرفي. القيمة الافتراضية هي false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | isUseTextShaper | منطقي | isUseTextShaper علامة |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


يحدد ما إذا كان يجب الحفاظ على بنية المستند عند التحويل إلى PDF (القيمة الافتراضية هي false). لاحظ أن تصدير بنية المستند يزيد بشكل كبير من استهلاك الذاكرة، خاصةً للمستندات الكبيرة.


**Returns:**
منطقي
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| preserveDocumentStructure | منطقي |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


إذا كانت true لن يتم تحميل جميع الموارد الخارجية باستثناء الموارد الموجودة في الـ


**Returns:**
منطقي
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تخطي | منطقي |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


الموارد الخارجية التي سيتم تحميلها دائمًا


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


يحدد كيفية عرض التعليقات في المستند الناتج. الافتراضي هو ShowInBalloons.


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


إظهار اسم المعلق الكامل في التعليقات. الافتراضي هو false.


**Returns:**
منطقي
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| showFullCommenterName | منطقي |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


تمكين أو تعطيل إنشاء ترقيم الصفحات في المستند المحول. الافتراضي: false


**Returns:**
منطقي
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isPageNumbering | منطقي |  |

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


يحصل على خيارات التجزئة لكلمات المستندات WordProcessing.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


يضبط خيارات التجزيء للكلمات في مستندات WordProcessing.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


يحصل على علم InterruptThreadIfImageExceptionThrown القيمة الافتراضية: false إذا كان true فسيتم مقاطعة خيط التحويل الرئيسي إذا حدث استثناء في خيط معالجة الصورة.


**Returns:**
منطقي
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


يضبط علم InterruptThreadIfImageExceptionThrown


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | منطقي |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


عند التمكين (الافتراضي)، سيتم إصلاح أعلام bidi للفقارات والقطع التي يكون نصها في الغالب من اليمين إلى اليسار (RTL) قبل التحويل.


هذا يتطابق مع الخوارزمية المستخدمة من قبل Microsoft Word و LibreOffice و
يصلح عرض المستندات العربية/العبرية التي ينتجها المولدون
(وبشكل خاص Google Docs) التي تُصدر OOXML بدون


ومع

على المقاطع التي تحتوي فقط على نص RTL.


ضبط إلى
false
للحفاظ على تفسير OOXML الصارم للـ
ترميز المصدر.


**Returns:**
منطقي
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


يضبط autoDetectRtlDirection


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | autoDetectRtlDirection | منطقي | autoDetectRtlDirection |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


يحصل على خيار للتحكم فيما إذا كان يجب تحويل حاوية المستندات نفسها


**Returns:**
منطقي
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOwner | منطقي |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


خيار للتحكم فيما إذا كان يجب تحويل المستندات المملوكة في حاوية المستندات


**Returns:**
منطقي
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOwned | منطقي |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


خيار للتحكم بعدد المستويات في العمق التي يتم فيها إجراء التحويل


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| depth | int |  |

