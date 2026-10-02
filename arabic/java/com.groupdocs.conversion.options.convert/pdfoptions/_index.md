---
title: "PdfOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع ملف Pdf."
type: docs
weight: 30
url: /ar/java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

خيارات التحويل إلى نوع ملف Pdf.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | ctor |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPdfFormat()](#getPdfFormat--) | يضبط تنسيق pdf للمستند المحول. |
|
|  | [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | يضبط تنسيق pdf للمستند المحول. |
|
|  | [getRemovePdfACompliance()](#getRemovePdfACompliance--) | يزيل توافق Pdf-A |
|
|  | [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | يزيل توافق Pdf-A |
|
|  | [getZoom()](#getZoom--) | يحدد مستوى التكبير بالنسبة المئوية. |
|
|  | [setZoom(int value)](#setZoom-int-) | يحدد مستوى التكبير بالنسبة المئوية. |
|
|  | [getLinearize()](#getLinearize--) | يقوم بترتيب مستند PDF للويب |
|
|  | [setLinearize(boolean value)](#setLinearize-boolean-) | يقوم بترتيب مستند PDF للويب |
|
|  | [getOptimizationOptions()](#getOptimizationOptions--) | خيارات تحسين PDF |
|
|  | [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | خيارات تحسين PDF |
|
|  | [getGrayscale()](#getGrayscale--) | تحويل PDF من مساحة ألوان RGB إلى تدرج الرمادي |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | تحويل PDF من مساحة ألوان RGB إلى تدرج الرمادي |
|
|  | [getFormattingOptions()](#getFormattingOptions--) | خيارات تنسيق PDF |
|
|  | [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | خيارات تنسيق PDF |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | معلومات التعريف لمستند PDF. |
|
| [setDocumentInfo(PdfDocumentInfo documentInfo)](#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-) |  |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


ctor


### getPdfFormat() {#getPdfFormat--}
```
public final PdfFormats getPdfFormat()
```


يضبط تنسيق pdf للمستند المحول.


**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


يضبط تنسيق pdf للمستند المحول.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


يزيل توافق Pdf-A


**Returns:**
منطقي
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


يزيل توافق Pdf-A


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


يحدد مستوى التكبير بالنسبة المئوية. القيمة الافتراضية هي 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


يحدد مستوى التكبير بالنسبة المئوية. القيمة الافتراضية هي 100.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


يقوم بترتيب مستند PDF للويب


**Returns:**
منطقي
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


يقوم بترتيب مستند PDF للويب


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


خيارات تحسين PDF


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


خيارات تحسين PDF


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


تحويل PDF من مساحة ألوان RGB إلى تدرج الرمادي


**Returns:**
منطقي
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


تحويل PDF من مساحة ألوان RGB إلى تدرج الرمادي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


خيارات تنسيق PDF


**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


خيارات تنسيق PDF


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


معلومات التعريف لمستند PDF.


**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

