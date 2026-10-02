---
title: "PdfFormattingOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد خيارات تنسيق Pdf."
type: docs
weight: 28
url: /ar/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

يحدد خيارات تنسيق Pdf.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | يحدد ما إذا كان موضع نافذة المستند سيُوسَّط على الشاشة. |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | يحدد ما إذا كان موضع نافذة المستند سيُوسَّط على الشاشة. |
|
|  | [getDirection()](#getDirection--) | يضبط ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | يضبط ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | يحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند. |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | يحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند. |
|
|  | [getFitWindow()](#getFitWindow--) | يحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة المعروضة أولاً. |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | يحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة المعروضة أولاً. |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | يحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا. |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | يحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا. |
|
|  | [getHideToolBar()](#getHideToolBar--) | يحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا. |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | يحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا. |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | يحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | يحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة. |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة. |
|
|  | [getPageLayout()](#getPageLayout--) | يضبط تخطيط الصفحة الذي سيُستخدم عند فتح المستند. |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | يضبط تخطيط الصفحة الذي سيُستخدم عند فتح المستند. |
|
|  | [getPageMode()](#getPageMode--) | يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الفتح. |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الفتح. |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


يحدد ما إذا كان موضع نافذة المستند سيُوسَّط على الشاشة. الافتراضي: false.


**Returns:**
منطقي
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


يحدد ما إذا كان موضع نافذة المستند سيُوسَّط على الشاشة. الافتراضي: false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


يضبط ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). الافتراضي: L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


يضبط ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). الافتراضي: L2R.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


يحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند. الافتراضي: false.


**Returns:**
منطقي
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


يحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند. الافتراضي: false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


يحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة المعروضة أولاً. الافتراضي: false.


**Returns:**
منطقي
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


يحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة المعروضة أولاً. الافتراضي: false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


يحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا. الافتراضي: false.


**Returns:**
منطقي
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


يحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا. الافتراضي: false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


يحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا. الافتراضي: false.


**Returns:**
منطقي
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


يحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا. الافتراضي: false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


يحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. الافتراضي: false.


**Returns:**
منطقي
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


يحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. الافتراضي: false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


يضبط تخطيط الصفحة الذي سيُستخدم عند فتح المستند.


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


يضبط تخطيط الصفحة الذي سيُستخدم عند فتح المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الفتح.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الفتح.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

