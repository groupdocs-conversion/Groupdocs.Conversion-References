---
title: "WordProcessingConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع ملف معالجة النصوص."
type: docs
weight: 48
url: /ar/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

خيارات التحويل إلى نوع ملف معالجة النصوص.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | ينشئ مثلاً جديداً من الفئة [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getDpi()](#getDpi--) | دقة DPI للصفحة المطلوبة بعد التحويل. |
|
|  | [setDpi(int value)](#setDpi-int-) | دقة DPI للصفحة المطلوبة بعد التحويل. |
|
|  | [getPassword()](#getPassword--) | عيّن هذه الخاصية إذا كنت تريد حماية المستند المحوّل بكلمة مرور. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | عيّن هذه الخاصية إذا كنت تريد حماية المستند المحوّل بكلمة مرور. |
|
|  | [getRtfOptions()](#getRtfOptions--) | خيارات التحويل الخاصة بـ RTF |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | خيارات التحويل الخاصة بـ RTF |
|
|  | [getZoom()](#getZoom--) | يحدد مستوى التكبير بالنسبة المئوية. |
|
|  | [setZoom(int value)](#setZoom-int-) | يحدد مستوى التكبير بالنسبة المئوية. |
|
|  | [getMarginTop()](#getMarginTop--) | الهامش العلوي للصفحة المطلوب بالنقاط بعد التحويل. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | الهامش العلوي للصفحة المطلوب بالنقاط بعد التحويل. |
|
|  | [getMarginBottom()](#getMarginBottom--) | الهامش السفلي للصفحة المطلوب بالنقاط بعد التحويل. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | الهامش السفلي للصفحة المطلوب بالنقاط بعد التحويل. |
|
|  | [getMarginLeft()](#getMarginLeft--) | الهامش الأيسر للصفحة المطلوب بالنقاط بعد التحويل. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | الهامش الأيسر للصفحة المطلوب بالنقاط بعد التحويل. |
|
|  | [getMarginRight()](#getMarginRight--) | الهامش الأيمن للصفحة المطلوب بالنقاط بعد التحويل. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | الهامش الأيمن للصفحة المطلوب بالنقاط بعد التحويل. |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPdfRecognitionMode()](#getPdfRecognitionMode--) |  |
| [setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)](#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-) |  |
|  | [getMarkdownOptions()](#getMarkdownOptions--) | يسترجع |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | يضبط |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


ينشئ مثلاً جديداً من الفئة [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions).


### getDpi() {#getDpi--}
```
public final int getDpi()
```


دقة DPI المطلوبة للصفحة بعد التحويل. الدقة الافتراضية هي: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


دقة DPI المطلوبة للصفحة بعد التحويل. الدقة الافتراضية هي: 96 dpi.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


عيّن هذه الخاصية إذا كنت تريد حماية المستند المحوّل بكلمة مرور.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


عيّن هذه الخاصية إذا كنت تريد حماية المستند المحوّل بكلمة مرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


خيارات التحويل الخاصة بـ RTF


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


خيارات التحويل الخاصة بـ RTF


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


يحدد مستوى التكبير بالنسبة المئوية. القيمة الافتراضية هي 100.
التكبير الافتراضي مدعوم حتى Microsoft Word 2010. بدءًا من Microsoft Word 2013 لم يعد يتم تعيين التكبير الافتراضي للمستند، بل يبدو أنه يستخدم عامل التكبير للمستند الأخير الذي تم فتحه.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


يحدد مستوى التكبير بالنسبة المئوية. القيمة الافتراضية هي 100.
التكبير الافتراضي مدعوم حتى Microsoft Word 2010. بدءًا من Microsoft Word 2013 لم يعد يتم تعيين التكبير الافتراضي للمستند، بل يبدو أنه يستخدم عامل التكبير للمستند الأخير الذي تم فتحه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


الهامش العلوي للصفحة المطلوب بالنقاط بعد التحويل.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


الهامش العلوي للصفحة المطلوب بالنقاط بعد التحويل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


الهامش السفلي للصفحة المطلوب بالنقاط بعد التحويل.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


الهامش السفلي للصفحة المطلوب بالنقاط بعد التحويل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


الهامش الأيسر للصفحة المطلوب بالنقاط بعد التحويل.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


الهامش الأيسر للصفحة المطلوب بالنقاط بعد التحويل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


الهامش الأيمن للصفحة المطلوب بالنقاط بعد التحويل.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


الهامش الأيمن للصفحة المطلوب بالنقاط بعد التحويل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


يسترجع اتجاه الصفحة بعد التحويل


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


يضبط اتجاه الصفحة المطلوب بعد التحويل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


يسترجع حجم الصفحة المطلوب بعد التحويل


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


يضبط حجم الصفحة المطلوب بعد التحويل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


عرض الصفحة المحدد بالنقاط إذا تم تعيينه إلى PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


يضبط عرض الصفحة المطلوب


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


ارتفاع الصفحة المحدد بالنقاط إذا تم تعيينه إلى PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


يضبط ارتفاع الصفحة المطلوب


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageHeight | float |  |

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


يحصل على وضع التعرف عند التحويل من pdf


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


يضبط وضع التعرف عند التحويل من pdf


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


يسترجع


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


يضبط


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

