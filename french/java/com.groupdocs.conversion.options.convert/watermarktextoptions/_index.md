---
title: "WatermarkTextOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour configurer le filigrane texte du document converti."
type: docs
weight: 45
url: /fr/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Options pour configurer le filigrane texte du document converti.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getText()](#getText--) | Texte du filigrane |
|
|  | [setText(String value)](#setText-java.lang.String-) | Texte du filigrane |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | Police du filigrane si le filigrane texte est appliqué |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Définit la police du filigrane si le filigrane texte est appliqué |
|
|  | [getColor()](#getColor--) | Couleur de la police du filigrane si le filigrane texte est appliqué |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Couleur de la police du filigrane si le filigrane texte est appliqué |
|
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Texte du filigrane


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Texte du filigrane


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Police du filigrane si le filigrane texte est appliqué


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Définit la police du filigrane si le filigrane texte est appliqué


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | police |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Couleur de la police du filigrane si le filigrane texte est appliqué


**Returns:**
java.awt.Color
### getColorInternal() {#getColorInternal--}
```
public System.Drawing.Color getColorInternal()
```




**Returns:**
com.aspose.ms.System.Drawing.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Couleur de la police du filigrane si le filigrane texte est appliqué


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
