---
title: "PdfOptimizationOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحدد خيارات تحسين Pdf."
type: docs
weight: 29
url: /ar/java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

يحدد خيارات تحسين Pdf.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | ينشئ مثيلاً جديدًا لـ [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) الفئة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | ربط التدفقات المكررة |
|
|  | [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | ربط التدفقات المكررة |
|
|  | [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | إزالة الكائنات غير المستخدمة |
|
|  | [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | إزالة الكائنات غير المستخدمة |
|
|  | [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | إزالة التدفقات غير المستخدمة |
|
|  | [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | إزالة التدفقات غير المستخدمة |
|
|  | [getCompressImages()](#getCompressImages--) | إذا تم تعيين CompressImages إلى |
true
, جميع الصور في المستند يتم إعادة ضغطها.
|
|  | [setCompressImages(boolean value)](#setCompressImages-boolean-) | إذا تم تعيين CompressImages إلى |
true
, جميع الصور في المستند يتم إعادة ضغطها.
|
|  | [getImageQuality()](#getImageQuality--) | القيمة بالنسبة المئوية حيث 100% تعني جودة وحجم الصورة غير متغيرين. |
|
|  | [setImageQuality(int value)](#setImageQuality-int-) | القيمة بالنسبة المئوية حيث 100% تعني جودة وحجم الصورة غير متغيرين. |
|
|  | [getUnembedFonts()](#getUnembedFonts--) | اجعل الخطوط غير مضمنة إذا تم تعيينها إلى true |
|
|  | [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | اجعل الخطوط غير مضمنة إذا تم تعيينها إلى true |
|
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
|  | [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | تعيين استراتيجية تجزئة الخط |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


ينشئ مثيلاً جديدًا لـ [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) الفئة.


### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


ربط التدفقات المكررة


**Returns:**
منطقي
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


ربط التدفقات المكررة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


إزالة الكائنات غير المستخدمة


**Returns:**
منطقي
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


إزالة الكائنات غير المستخدمة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


إزالة التدفقات غير المستخدمة


**Returns:**
منطقي
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


إزالة التدفقات غير المستخدمة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


إذا تم تعيين CompressImages إلى
true
, جميع الصور في المستند يتم إعادة ضغطها. يتم تعريف الضغط بواسطة خاصية ImageQuality.


**Returns:**
منطقي
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


إذا تم تعيين CompressImages إلى
true
, جميع الصور في المستند يتم إعادة ضغطها. يتم تعريف الضغط بواسطة خاصية ImageQuality.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


القيمة بالنسبة المئوية حيث 100% تعني جودة وحجم الصورة غير متغيرين. لتقليل حجم الصورة، عيّن هذه الخاصية إلى أقل من 100


**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


القيمة بالنسبة المئوية حيث 100% تعني جودة وحجم الصورة غير متغيرين. لتقليل حجم الصورة، عيّن هذه الخاصية إلى أقل من 100


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


اجعل الخطوط غير مضمنة إذا تم تعيينها إلى true


**Returns:**
منطقي
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


اجعل الخطوط غير مضمنة إذا تم تعيينها إلى true


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getFontSubsetStrategy() {#getFontSubsetStrategy--}
```
public PdfFontSubsetStrategy getFontSubsetStrategy()
```




**Returns:**
[PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy)
### setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy) {#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-}
```
public void setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)
```


تعيين استراتيجية تجزئة الخط


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

