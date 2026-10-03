---
title: "IWatermarkedConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Представляет параметры конвертации, позволяющие добавить водяной знак к результату конвертации"
type: docs
weight: 57
url: /ru/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

Представляет параметры конвертации, позволяющие добавить водяной знак к результату конвертации

## Методы

| Метод | Описание |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Получает параметры, специфичные для водяного знака |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | Устанавливает параметры, специфичные для водяного знака |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


Получает параметры, специфичные для водяного знака


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


Устанавливает параметры, специфичные для водяного знака


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | Параметры, специфичные для водяного знака |
|

