---
title: "WebConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk konversi ke tipe file Web."
type: docs
weight: 46
url: /id/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Opsi untuk konversi ke tipe file Web.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | Menginisialisasi instance baru dari kelas. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | Menentukan apakah akan menyematkan sumber daya font dalam HTML utama. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | Menentukan apakah akan menyematkan sumber daya font dalam HTML utama. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


Menginisialisasi instance baru dari kelas.


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
boolean
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| usePdf | boolean |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
boolean
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fixedLayout | boolean |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
boolean
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fixedLayoutShowBorders | boolean |  |

### getZoom() {#getZoom--}
```
public int getZoom()
```




**Returns:**
int
### setZoom(int zoom) {#setZoom-int-}
```
public void setZoom(int zoom)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


Menentukan apakah akan menyematkan sumber daya font dalam HTML utama. Nilai default adalah false. Catatan: Jika FixedLayout diatur ke true, sumber daya font akan selalu disematkan.


**Returns:**
boolean
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


Menentukan apakah akan menyematkan sumber daya font dalam HTML utama. Nilai default adalah false. Catatan: Jika FixedLayout diatur ke true, sumber daya font akan selalu disematkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| embedFontResources | boolean |  |

