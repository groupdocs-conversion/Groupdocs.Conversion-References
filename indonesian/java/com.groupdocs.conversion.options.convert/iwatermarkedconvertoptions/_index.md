---
title: "IWatermarkedConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili opsi konversi yang memungkinkan output konversi diberi watermark."
type: docs
weight: 57
url: /id/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

Mewakili opsi konversi yang memungkinkan output konversi diberi watermark.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Mendapatkan opsi khusus watermark |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | Mengatur opsi khusus watermark |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


Mendapatkan opsi khusus watermark


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


Mengatur opsi khusus watermark


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | Opsi khusus watermark |
|

