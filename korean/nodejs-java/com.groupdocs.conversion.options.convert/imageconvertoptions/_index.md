---
title: "ImageConvertOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "이미지 파일 형식으로 변환 옵션."
type: docs
weight: 18
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

이미지 파일 형식으로 변환 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageConvertOptions()](#ImageConvertOptions--) | 새 인스턴스인 [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) 클래스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | 변환 후 원하는 이미지 너비. |
| [setWidth(int value)](#setWidth-int-) | 변환 후 원하는 이미지 너비. |
| [getHeight()](#getHeight--) | 변환 후 원하는 이미지 높이. |
| [setHeight(int value)](#setHeight-int-) | 변환 후 원하는 이미지 높이. |
| [getUsePdf()](#getUsePdf--) | true이면, 입력을 먼저 PDF로 변환한 다음 원하는 형식으로 변환합니다. |
| [setUsePdf(boolean value)](#setUsePdf-boolean-) | true이면, 입력을 먼저 PDF로 변환한 다음 원하는 형식으로 변환합니다. |
| [getHorizontalResolution()](#getHorizontalResolution--) | 변환 후 원하는 이미지 가로 해상도. |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | 변환 후 원하는 이미지 가로 해상도. |
| [getVerticalResolution()](#getVerticalResolution--) | 변환 후 원하는 이미지 세로 해상도. |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | 변환 후 원하는 이미지 세로 해상도. |
| [getTiffOptions()](#getTiffOptions--) | Tiff 전용 변환 옵션. |
| [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Tiff 전용 변환 옵션. |
| [getPsdOptions()](#getPsdOptions--) | Psd 전용 변환 옵션. |
| [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Psd 전용 변환 옵션. |
| [getWebpOptions()](#getWebpOptions--) | Webp 전용 변환 옵션. |
| [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Webp 전용 변환 옵션. |
| [getGrayscale()](#getGrayscale--) | 그레이스케일 이미지로 변환할지 여부를 나타냅니다. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | 그레이스케일 이미지로 변환할지 여부를 나타냅니다. |
| [getRotateAngle()](#getRotateAngle--) | 이미지 회전 각도. |
| [setRotateAngle(int value)](#setRotateAngle-int-) | 이미지 회전 각도. |
| [getJpegOptions()](#getJpegOptions--) | Jpeg 전용 변환 옵션. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Jpeg 전용 변환 옵션. |
| [getFlipMode()](#getFlipMode--) | 이미지 플립 모드. |
| [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | 이미지 플립 모드. |
| [getBrightness()](#getBrightness--) | 이미지 밝기를 조정합니다. |
| [setBrightness(int value)](#setBrightness-int-) | 이미지 밝기를 조정합니다. |
| [getContrast()](#getContrast--) | 이미지 대비를 조정합니다. |
| [setContrast(int value)](#setContrast-int-) | 이미지 대비를 조정합니다. |
| [getGamma()](#getGamma--) | 이미지 감마를 조정합니다. |
| [setGamma(double value)](#setGamma-double-) | 이미지 감마를 조정합니다. |
| [setGamma(float value)](#setGamma-float-) | 이미지 감마를 조정합니다. |
| [getBackgroundColor()](#getBackgroundColor--) | 배경 색상을 가져옵니다 |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | 소스 형식에서 지원되는 경우 배경 색상을 설정합니다 |
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


새 인스턴스인 [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions) 클래스를 초기화합니다.

### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


변환 후 원하는 이미지 너비.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


변환 후 원하는 이미지 너비.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


변환 후 원하는 이미지 높이.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


변환 후 원하는 이미지 높이.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


true이면, 입력을 먼저 PDF로 변환한 다음 원하는 형식으로 변환합니다.

**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


true이면, 입력을 먼저 PDF로 변환한 다음 원하는 형식으로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


변환 후 원하는 이미지 가로 해상도입니다. 기본 해상도는 입력 파일의 해상도 또는 96 dpi입니다.

**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


변환 후 원하는 이미지 가로 해상도입니다. 기본 해상도는 입력 파일의 해상도 또는 96 dpi입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


변환 후 원하는 이미지 세로 해상도입니다. 기본 해상도는 입력 파일의 해상도 또는 96 dpi입니다.

**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


변환 후 원하는 이미지 세로 해상도입니다. 기본 해상도는 입력 파일의 해상도 또는 96 dpi입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Tiff 전용 변환 옵션.

**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Tiff 전용 변환 옵션.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Psd 전용 변환 옵션.

**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Psd 전용 변환 옵션.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Webp 전용 변환 옵션.

**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Webp 전용 변환 옵션.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


그레이스케일 이미지로 변환할지 여부를 나타냅니다.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


그레이스케일 이미지로 변환할지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


이미지 회전 각도.

**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


이미지 회전 각도.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Jpeg 전용 변환 옵션.

**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Jpeg 전용 변환 옵션.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


이미지 플립 모드.

**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


이미지 플립 모드.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


이미지 밝기를 조정합니다.

**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


이미지 밝기를 조정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


이미지 대비를 조정합니다.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


이미지 대비를 조정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getGamma() {#getGamma--}
```
public final double getGamma()
```


이미지 감마를 조정합니다.

**Returns:**
double
### setGamma(double value) {#setGamma-double-}
```
public final void setGamma(double value)
```


이미지 감마를 조정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


이미지 감마를 조정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


배경 색상을 가져옵니다

**Returns:**
com.aspose.ms.System.Drawing.Color - 배경 색상
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


소스 형식에서 지원되는 경우 배경 색상을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color | 배경 색상 |

