---
title: "WebConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات التحويل إلى نوع ملف ويب."
type: docs
weight: 46
url: /ar/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

خيارات التحويل إلى نوع ملف ويب.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | يقوم بإنشاء مثيل جديد للفئة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | يحدد ما إذا كان يجب تضمين موارد الخط داخل HTML الرئيسي. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | يحدد ما إذا كان يجب تضمين موارد الخط داخل HTML الرئيسي. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


يقوم بإنشاء مثيل جديد للفئة.


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
منطقي
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| usePdf | منطقي |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
منطقي
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fixedLayout | منطقي |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
منطقي
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fixedLayoutShowBorders | منطقي |  |

### getZoom() {#getZoom--}
```
public int getZoom()
```




**Returns:**
int
### setZoom(int zoom) {#setZoom-int-}
```
public void setZoom(int zoom)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


يحدد ما إذا كان سيتم تضمين موارد الخط داخل HTML الرئيسي. القيمة الافتراضية هي false. ملاحظة: إذا تم تعيين FixedLayout إلى true، فستتم دائمًا تضمين موارد الخط.


**Returns:**
منطقي
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


يحدد ما إذا كان سيتم تضمين موارد الخط داخل HTML الرئيسي. القيمة الافتراضية هي false. ملاحظة: إذا تم تعيين FixedLayout إلى true، فستتم دائمًا تضمين موارد الخط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| embedFontResources | منطقي |  |

