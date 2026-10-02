---
title: "ImageLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات الصورة."
type: docs
weight: 21
url: /ar/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

خيارات تحميل مستندات الصورة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | ينشئ نسخة جديدة من الفئة [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | الخط الافتراضي لأنواع المستندات Psd و Emf و Wmf. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | الخط الافتراضي لأنواع المستندات Psd و Emf و Wmf. |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | تعيين موصل OCR للصورة |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | إعادة تعيين مجلدات الخطوط قبل تحميل المستند. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


ينشئ نسخة جديدة من الفئة [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions).


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


نوع ملف المستند الإدخالي


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


الخط الافتراضي لأنواع المستندات Psd و Emf و Wmf. سيتم استخدام الخط التالي إذا كان الخط مفقودًا.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


الخط الافتراضي لأنواع المستندات Psd و Emf و Wmf. سيتم استخدام الخط التالي إذا كان الخط مفقودًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### isRecognitionEnabled() {#isRecognitionEnabled--}
```
public boolean isRecognitionEnabled()
```




**Returns:**
منطقي
### getOcrConnector() {#getOcrConnector--}
```
public IOcrConnector getOcrConnector()
```




**Returns:**
[IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector)
### setOcrConnector(IOcrConnector ocrConnector) {#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-}
```
public void setOcrConnector(IOcrConnector ocrConnector)
```


تعيين موصل OCR للصورة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | مثيل موصل OCR |
|

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

