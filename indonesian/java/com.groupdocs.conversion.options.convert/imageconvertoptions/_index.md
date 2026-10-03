---
title: "ImageConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk konversi ke tipe file Image."
type: docs
weight: 18
url: /id/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Opsi untuk konversi ke tipe file Image.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | Menginisialisasi instance baru dari kelas [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions). |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWidth()](#getWidth--) | Lebar gambar yang diinginkan setelah konversi. |
|
|  | [setWidth(int value)](#setWidth-int-) | Lebar gambar yang diinginkan setelah konversi. |
|
|  | [getHeight()](#getHeight--) | Tinggi gambar yang diinginkan setelah konversi. |
|
|  | [setHeight(int value)](#setHeight-int-) | Tinggi gambar yang diinginkan setelah konversi. |
|
|  | [getUsePdf()](#getUsePdf--) | Jika |
true
, input pertama kali dikonversi ke PDF dan setelah itu ke format yang diinginkan.
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | Jika |
true
, input pertama kali dikonversi ke PDF dan setelah itu ke format yang diinginkan.
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Resolusi horizontal gambar yang diinginkan setelah konversi. |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Resolusi horizontal gambar yang diinginkan setelah konversi. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Resolusi vertikal gambar yang diinginkan setelah konversi. |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | Resolusi vertikal gambar yang diinginkan setelah konversi. |
|
|  | [getTiffOptions()](#getTiffOptions--) | Opsi konversi khusus Tiff. |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Opsi konversi khusus Tiff. |
|
|  | [getPsdOptions()](#getPsdOptions--) | Opsi konversi khusus Psd. |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Opsi konversi khusus Psd. |
|
|  | [getWebpOptions()](#getWebpOptions--) | Opsi konversi khusus Webp. |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Opsi konversi khusus Webp. |
|
|  | [getGrayscale()](#getGrayscale--) | Menunjukkan apakah akan mengonversi menjadi gambar skala abu-abu. |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Menunjukkan apakah akan mengonversi menjadi gambar skala abu-abu. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Sudut rotasi gambar. |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | Sudut rotasi gambar. |
|
|  | [getJpegOptions()](#getJpegOptions--) | Opsi konversi khusus Jpeg. |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Opsi konversi khusus Jpeg. |
|
|  | [getFlipMode()](#getFlipMode--) | Mode pembalikan gambar. |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Mode pembalikan gambar. |
|
|  | [getBrightness()](#getBrightness--) | Menyesuaikan kecerahan gambar. |
|
|  | [setBrightness(int value)](#setBrightness-int-) | Menyesuaikan kecerahan gambar. |
|
|  | [getContrast()](#getContrast--) | Menyesuaikan kontras gambar. |
|
|  | [setContrast(int value)](#setContrast-int-) | Menyesuaikan kontras gambar. |
|
|  | [getGamma()](#getGamma--) | Menyesuaikan gamma gambar. |
|
|  | [setGamma(float value)](#setGamma-float-) | Menyesuaikan gamma gambar. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan warna latar belakang |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Mengatur warna latar belakang bila didukung oleh format sumber |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Menginisialisasi instance baru dari kelas [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions).


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lebar gambar yang diinginkan setelah konversi.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lebar gambar yang diinginkan setelah konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Tinggi gambar yang diinginkan setelah konversi.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Tinggi gambar yang diinginkan setelah konversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Jika
true
, input pertama kali dikonversi ke PDF dan setelah itu ke format yang diinginkan.


**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Jika
true
, input pertama kali dikonversi ke PDF dan setelah itu ke format yang diinginkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Resolusi horizontal gambar yang diinginkan setelah konversi. Resolusi default adalah resolusi file input atau 96 dpi.


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Resolusi horizontal gambar yang diinginkan setelah konversi. Resolusi default adalah resolusi file input atau 96 dpi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Resolusi vertikal gambar yang diinginkan setelah konversi. Resolusi default adalah resolusi file input atau 96 dpi.


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Resolusi vertikal gambar yang diinginkan setelah konversi. Resolusi default adalah resolusi file input atau 96 dpi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Opsi konversi khusus Tiff.


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Opsi konversi khusus Tiff.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Opsi konversi khusus Psd.


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Opsi konversi khusus Psd.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Opsi konversi khusus Webp.


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Opsi konversi khusus Webp.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Menunjukkan apakah akan mengonversi menjadi gambar skala abu-abu.


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Menunjukkan apakah akan mengonversi menjadi gambar skala abu-abu.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Sudut rotasi gambar.


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Sudut rotasi gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Opsi konversi khusus Jpeg.


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Opsi konversi khusus Jpeg.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Mode pembalikan gambar.


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Mode pembalikan gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Menyesuaikan kecerahan gambar.


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Menyesuaikan kecerahan gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Menyesuaikan kontras gambar.


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Menyesuaikan kontras gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


Menyesuaikan gamma gambar.


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Menyesuaikan gamma gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Mendapatkan warna latar belakang


**Returns:**
com.aspose.ms.System.Drawing.Color - warna latar belakang

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Mengatur warna latar belakang bila didukung oleh format sumber


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | warna latar belakang |
|

