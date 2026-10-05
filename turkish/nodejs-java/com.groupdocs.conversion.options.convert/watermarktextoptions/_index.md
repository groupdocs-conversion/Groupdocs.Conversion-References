---
title: "WatermarkTextOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Dönüştürülen belgeye metin filigranı ayarları için seçenekler"
type: docs
weight: 45
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Dönüştürülen belgeye metin filigranı ayarları için seçenekler
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getText()](#getText--) | Filigran metni |
| [setText(String value)](#setText-java.lang.String-) | Filigran metni |
| [getWatermarkFont()](#getWatermarkFont--) | Metin filigranı uygulandığında filigran yazı tipi |
| [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Metin filigranı uygulandığında filigran yazı tipini ayarlar |
| [getColor()](#getColor--) | Metin filigranı uygulandığında filigran yazı tipi rengi |
| [getColorInternal()](#getColorInternal--) |  |
| [setColor(int argb)](#setColor-int-) | Metin filigranı uygulandığında filigran yazı tipi rengi argb olarak |
| [setColor(String colorName)](#setColor-java.lang.String-) | Metin filigranı uygulandığında filigran yazı tipi renk adı |
| [setColor(Color value)](#setColor-java.awt.Color-) | Metin filigranı uygulandığında filigran yazı tipi rengi |
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Filigran metni

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Filigran metni

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Metin filigranı uygulandığında filigran yazı tipi

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font
### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Metin filigranı uygulandığında filigran yazı tipini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | yazı tipi |

### getColor() {#getColor--}
```
public final Color getColor()
```


Metin filigranı uygulandığında filigran yazı tipi rengi

**Returns:**
java.awt.Color
### getColorInternal() {#getColorInternal--}
```
public System.Drawing.Color getColorInternal()
```




**Returns:**
com.aspose.ms.System.Drawing.Color
### setColor(int argb) {#setColor-int-}
```
public final void setColor(int argb)
```


Metin filigranı uygulandığında filigran yazı tipi rengi argb olarak

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb | int |  |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Metin filigranı uygulandığında filigran yazı tipi renk adı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorName | java.lang.String |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Metin filigranı uygulandığında filigran yazı tipi rengi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
