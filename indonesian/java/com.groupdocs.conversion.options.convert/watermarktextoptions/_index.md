---
title: "WatermarkTextOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk mengatur watermark teks pada dokumen yang dikonversi"
type: docs
weight: 45
url: /id/java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Opsi untuk mengatur watermark teks pada dokumen yang dikonversi

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getText()](#getText--) | Teks watermark |
|
|  | [setText(String value)](#setText-java.lang.String-) | Teks watermark |
|
|  | [getWatermarkFont()](#getWatermarkFont--) | Font watermark jika watermark teks diterapkan |
|
|  | [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Mengatur font watermark jika watermark teks diterapkan |
|
|  | [getColor()](#getColor--) | Warna font watermark jika watermark teks diterapkan |
|
| [getColorInternal()](#getColorInternal--) |  |
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Warna font watermark jika watermark teks diterapkan |
|
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Teks watermark


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Teks watermark


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Font watermark jika watermark teks diterapkan


**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font

### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Mengatur font watermark jika watermark teks diterapkan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | font |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Warna font watermark jika watermark teks diterapkan


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


Warna font watermark jika watermark teks diterapkan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
