---
title: "IWatermarkedConvertOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل خيارات التحويل التي تسمح بوضع علامة مائية على ناتج التحويل"
type: docs
weight: 57
url: /ar/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

يمثل خيارات التحويل التي تسمح بوضع علامة مائية على ناتج التحويل

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | يحصل على خيارات العلامة المائية المحددة |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | يضبط خيارات العلامة المائية المحددة |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


يحصل على خيارات العلامة المائية المحددة


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


يضبط خيارات العلامة المائية المحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | خيارات العلامة المائية الخاصة |
|

