---
title: "IWatermarkedConvertOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Dönüştürme çıktısının filigranlı olmasına izin veren dönüştürme seçeneklerini temsil eder"
type: docs
weight: 57
url: /tr/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

Dönüştürme çıktısının filigranlı olmasına izin veren dönüştürme seçeneklerini temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Filigran özel seçeneklerini alır |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | Filigran özel seçeneklerini ayarlar |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


Filigran özel seçeneklerini alır


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


Filigran özel seçeneklerini ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | Filigran'a özgü seçenekler |
|

