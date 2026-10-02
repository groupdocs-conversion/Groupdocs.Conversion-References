---
title: "PdfLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات PDF."
type: docs
weight: 27
url: /ar/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

خيارات تحميل مستندات PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | يُنشئ مثيلًا جديدًا من الفئة [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | إزالة الملفات المضمنة. |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | إزالة الملفات المضمنة. |
|
|  | [getPassword()](#getPassword--) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
|  | [getDefaultFont()](#getDefaultFont--) | الخط الافتراضي لمستند Pdf. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | الخط الافتراضي لمستند Pdf. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | استبدال الخطوط المحددة عند تحويل مستند Pdf. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | استبدال الخطوط المحددة عند تحويل مستند Pdf. |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | إخفاء التعليقات التوضيحية في مستندات Pdf. |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | إخفاء التعليقات التوضيحية في مستندات Pdf. |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | تسوية جميع حقول نموذج PDF. |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | تسوية جميع حقول نموذج PDF. |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | إعادة تعيين مجلدات الخطوط قبل تحميل المستند. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | تمكين أو تعطيل إنشاء ترقيم الصفحات في المستند المحول. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | يحصل على علم Remove JavaScript. |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | يضبط علم Remove JavaScript. |
|
|  | [isConvertOwner()](#isConvertOwner--) | يحدد ما إذا كان يجب تحويل المستند الأصلي. |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | يحدد ما إذا كان يجب تحويل المستند الأصلي. |
|
|  | [isConvertOwned()](#isConvertOwned--) | يحدد ما إذا كان يجب تحويل المستندات المملوكة. |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | يحدد ما إذا كان يجب تحويل المستندات المملوكة. |
|
|  | [getDepth()](#getDepth--) | الحد الأقصى للعمق لمعالجة المستندات المملوكة. |
|
|  | [setDepth(int depth)](#setDepth-int-) | الحد الأقصى للعمق لمعالجة المستندات المملوكة. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


يُنشئ مثيلًا جديدًا من الفئة [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions).


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


نوع ملف المستند الإدخالي


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


إزالة الملفات المضمنة.


**Returns:**
منطقي
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


إزالة الملفات المضمنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


الخط الافتراضي لمستند Pdf.
سيتم استخدام الخط التالي إذا كان هناك خط مفقود.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


الخط الافتراضي لمستند Pdf.
سيتم استخدام الخط التالي إذا كان هناك خط مفقود.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


استبدال الخطوط المحددة عند تحويل مستند Pdf.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


استبدال الخطوط المحددة عند تحويل مستند Pdf.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


إخفاء التعليقات التوضيحية في مستندات Pdf.


**Returns:**
منطقي
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


إخفاء التعليقات التوضيحية في مستندات Pdf.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


تسوية جميع حقول نموذج PDF.


**Returns:**
منطقي
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


تسوية جميع حقول نموذج PDF.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


إعادة تعيين مجلدات الخطوط قبل تحميل المستند.


**Returns:**
منطقي
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resetFontFolders | منطقي |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


تمكين أو تعطيل إنشاء ترقيم الصفحات في المستند المحول. الافتراضي: false.


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

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


يحصل على علم Remove JavaScript.


**Returns:**
منطقي
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


يضبط علم Remove JavaScript.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| removeJavascript | منطقي |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


يحدد ما إذا كان يجب تحويل المستند الأصلي.

الافتراضي هو
true
.


**Returns:**
منطقي
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


يحدد ما إذا كان يجب تحويل المستند الأصلي.

الافتراضي هو
true
.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOwner | منطقي |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


يحدد ما إذا كان يجب تحويل المستندات المملوكة.

الافتراضي هو
false
.


**Returns:**
منطقي
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


يحدد ما إذا كان يجب تحويل المستندات المملوكة.

الافتراضي هو
false
.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOwned | منطقي |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


الحد الأقصى للعمق لمعالجة المستندات المملوكة.

الافتراضي هو
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


الحد الأقصى للعمق لمعالجة المستندات المملوكة.

الافتراضي هو
2
.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| depth | int |  |

