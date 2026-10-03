---
title: "IWatermarkedConvertOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Geeft de conversie‑opties weer die het mogelijk maken om de uitvoer van de conversie te voorzien van een watermerk."
type: docs
weight: 57
url: /nl/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

Geeft de conversie‑opties weer die het mogelijk maken om de uitvoer van de conversie te voorzien van een watermerk.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Haalt watermerk‑specifieke opties op |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | Stelt watermerk‑specifieke opties in |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


Haalt watermerk‑specifieke opties op


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


Stelt watermerk‑specifieke opties in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | Watermerk-specifieke opties |
|

