---
title: "IWatermarkedConvertOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta le opzioni di conversione che consentono di aggiungere una filigrana all'output della conversione"
type: docs
weight: 57
url: /it/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

Rappresenta le opzioni di conversione che consentono di aggiungere una filigrana all'output della conversione

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Ottiene le opzioni specifiche del watermark |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | Imposta le opzioni specifiche del watermark |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


Ottiene le opzioni specifiche del watermark


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


Imposta le opzioni specifiche del watermark


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | Opzioni specifiche per il watermark |
|

