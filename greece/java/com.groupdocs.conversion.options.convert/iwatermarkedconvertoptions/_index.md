---
title: "IWatermarkedConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αντιπροσωπεύει τις επιλογές μετατροπής που επιτρέπουν το αποτέλεσμα της μετατροπής να φέρει υδατογράφημα"
type: docs
weight: 57
url: /el/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

Αντιπροσωπεύει τις επιλογές μετατροπής που επιτρέπουν το αποτέλεσμα της μετατροπής να φέρει υδατογράφημα

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Λαμβάνει τις επιλογές του υδατογραφήματος |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | Ορίζει τις επιλογές του υδατογραφήματος |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


Λαμβάνει τις επιλογές του υδατογραφήματος


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


Ορίζει τις επιλογές του υδατογραφήματος


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | Ειδικές επιλογές υδατογραφήματος |
|

