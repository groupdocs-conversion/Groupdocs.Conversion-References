---
title: "IWatermarkedConvertOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "변환 결과에 워터마크를 적용하도록 허용하는 변환 옵션을 나타냅니다."
type: docs
weight: 57
url: /ko/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

변환 결과에 워터마크를 적용하도록 허용하는 변환 옵션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | 워터마크 전용 옵션을 가져옵니다 |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | 워터마크 전용 옵션을 설정합니다 |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


워터마크 전용 옵션을 가져옵니다


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


워터마크 전용 옵션을 설정합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | 워터마크 전용 옵션 |
|

