---
title: "IWatermarkedConvertOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "表示允许对转换输出添加水印的转换选项"
type: docs
weight: 57
url: /zh/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

表示允许对转换输出添加水印的转换选项

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | 获取水印特定选项 |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | 设置水印特定选项 |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


获取水印特定选项


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


设置水印特定选项


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | 水印特定选项 |
|

