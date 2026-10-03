---
title: "IWatermarkedConvertOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt Konvertierungsoptionen dar, die es erlauben, die Ausgabe der Konvertierung mit einem Wasserzeichen zu versehen"
type: docs
weight: 57
url: /de/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

Stellt Konvertierungsoptionen dar, die es erlauben, die Ausgabe der Konvertierung mit einem Wasserzeichen zu versehen

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Ruft wasserzeichenspezifische Optionen ab |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | Setzt wasserzeichenspezifische Optionen |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


Ruft wasserzeichenspezifische Optionen ab


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


Setzt wasserzeichenspezifische Optionen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | Wasserzeichen-spezifische Optionen |
|

