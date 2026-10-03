---
title: "IWatermarkedConvertOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente les options de conversion qui permettent d'ajouter un filigrane à la sortie de la conversion."
type: docs
weight: 57
url: /fr/java/com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IWatermarkedConvertOptions extends IConvertOptions
```

Représente les options de conversion qui permettent d'ajouter un filigrane à la sortie de la conversion.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Obtient les options spécifiques au filigrane |
|
|  | [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) | Définit les options spécifiques au filigrane |
|
### getWatermark() {#getWatermark--}
```
public abstract WatermarkOptions getWatermark()
```


Obtient les options spécifiques au filigrane


**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) - Watermark specific options

### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public abstract void setWatermark(WatermarkOptions watermark)
```


Définit les options spécifiques au filigrane


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) | Options spécifiques au filigrane |
|

