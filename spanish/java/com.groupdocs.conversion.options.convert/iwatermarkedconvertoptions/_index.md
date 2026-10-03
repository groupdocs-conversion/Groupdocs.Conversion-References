---
title: "IWatermarkedConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa las opciones de conversión que permiten que la salida de la conversión tenga marca de agua"
type: docs
weight: 57
url: /es/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

Representa las opciones de conversión que permiten que la salida de la conversión tenga marca de agua

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Obtiene opciones específicas de marca de agua |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | Establece opciones específicas de marca de agua |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


Obtiene opciones específicas de marca de agua


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


Establece opciones específicas de marca de agua


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | Opciones específicas de marca de agua |
|

