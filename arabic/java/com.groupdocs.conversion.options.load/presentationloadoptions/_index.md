---
title: "PresentationLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات العرض التقديمي."
type: docs
weight: 29
url: /ar/java/com.groupdocs.conversion.options.load/presentationloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PresentationLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IDocumentsContainerLoadOptions
```

خيارات تحميل مستندات العرض التقديمي.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PresentationLoadOptions()](#PresentationLoadOptions--) | ينشئ نسخة جديدة من الفئة [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | الخط الافتراضي لتقديم presentation. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | الخط الافتراضي لتقديم presentation. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | استبدال الخطوط المحددة عند تحويل مستند Presentation. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | استبدال الخطوط المحددة عند تحويل مستند Presentation. |
|
|  | [getPassword()](#getPassword--) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
|  | [getHideComments()](#getHideComments--) | إخفاء التعليقات. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | إخفاء التعليقات. |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | إظهار الشرائح المخفية. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | إظهار الشرائح المخفية. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
| [getDocumentFontSources()](#getDocumentFontSources--) |  |
| [setDocumentFontSources(List<String> documentFontSources)](#setDocumentFontSources-java.util.List-java.lang.String--) |  |
|  | [getNotesPosition()](#getNotesPosition--) | يمثل الطريقة التي تُطبع بها التعليقات مع الشريحة. |
|
|  | [setNotesPosition(PresentationNotesPosition notesPosition)](#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-) | يمثل الطريقة التي تُطبع بها الملاحظات مع الشريحة. |
|
| [getCommentsPosition()](#getCommentsPosition--) |  |
| [setCommentsPosition(PresentationCommentsPosition commentsPosition)](#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-) |  |
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


ينشئ نسخة جديدة من الفئة [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final PresentationFileType getFormat()
```


نوع ملف المستند الإدخالي


**Returns:**
[PresentationFileType](../../com.groupdocs.conversion.filetypes/presentationfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


الخط الافتراضي لتصيير العرض التقديمي. سيتم استخدام الخط التالي إذا كان خط العرض مفقودًا.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


الخط الافتراضي لتصيير العرض التقديمي. سيتم استخدام الخط التالي إذا كان خط العرض مفقودًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


استبدال الخطوط المحددة عند تحويل مستند Presentation.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


استبدال الخطوط المحددة عند تحويل مستند Presentation.


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

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


إخفاء التعليقات.


**Returns:**
منطقي
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


إخفاء التعليقات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


إظهار الشرائح المخفية.


**Returns:**
منطقي
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


إظهار الشرائح المخفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| documentFontSources | java.util.List<java.lang.String> |  |

### getNotesPosition() {#getNotesPosition--}
```
public PresentationNotesPosition getNotesPosition()
```


يمثل الطريقة التي تُطبع بها التعليقات مع الشريحة. القيمة الافتراضية هي لا شيء.


**Returns:**
[PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition)
### setNotesPosition(PresentationNotesPosition notesPosition) {#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-}
```
public void setNotesPosition(PresentationNotesPosition notesPosition)
```


يمثل الطريقة التي تُطبع بها الملاحظات مع الشريحة. القيمة الافتراضية هي لا شيء.


**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| commentsPosition | [PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) |  |

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

