---
title: "PdfConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع ملف Pdf."
type: docs
weight: 25
url: /ar/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

خيارات التحويل إلى نوع ملف Pdf.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | ينشئ مثلاً جديدًا من الفئة [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
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
|  | [getPdfOptions()](#getPdfOptions--) | خيارات التحويل الخاصة بـ Pdf |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | خيارات التحويل الخاصة بـ Pdf |
|
|  | [getRotate()](#getRotate--) | تدوير الصفحة |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | تدوير الصفحة |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
### PdfConvertOptions() {#PdfConvertOptions--}
```
public PdfConvertOptions()
```


ينشئ مثلاً جديدًا من الفئة [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


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

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


خيارات التحويل الخاصة بـ Pdf


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


خيارات التحويل الخاصة بـ Pdf


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


تدوير الصفحة


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


تدوير الصفحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

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

