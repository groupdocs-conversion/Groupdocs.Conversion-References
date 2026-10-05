---
title: "WatermarkTextOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "변환된 문서에 텍스트 워터마크를 설정하기 위한 옵션"
type: docs
weight: 45
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

변환된 문서에 텍스트 워터마크를 설정하기 위한 옵션
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getText()](#getText--) | 워터마크 텍스트 |
| [setText(String value)](#setText-java.lang.String-) | 워터마크 텍스트 |
| [getWatermarkFont()](#getWatermarkFont--) | 텍스트 워터마크가 적용된 경우 워터마크 글꼴 |
| [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | 텍스트 워터마크가 적용된 경우 워터마크 글꼴을 설정합니다. |
| [getColor()](#getColor--) | 텍스트 워터마크가 적용된 경우 워터마크 글꼴 색상 |
| [getColorInternal()](#getColorInternal--) |  |
| [setColor(int argb)](#setColor-int-) | 텍스트 워터마크가 적용된 경우 워터마크 글꼴 색상을 argb로 지정합니다. |
| [setColor(String colorName)](#setColor-java.lang.String-) | 텍스트 워터마크가 적용된 경우 워터마크 글꼴 색상 이름 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 텍스트 워터마크가 적용된 경우 워터마크 글꼴 색상 |
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


워터마크 텍스트

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


워터마크 텍스트

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


텍스트 워터마크가 적용된 경우 워터마크 글꼴

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font
### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


텍스트 워터마크가 적용된 경우 워터마크 글꼴을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | 글꼴 |

### getColor() {#getColor--}
```
public final Color getColor()
```


텍스트 워터마크가 적용된 경우 워터마크 글꼴 색상

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


텍스트 워터마크가 적용된 경우 워터마크 글꼴 색상을 argb로 지정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| argb | int |  |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


텍스트 워터마크가 적용된 경우 워터마크 글꼴 색상 이름

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| colorName | java.lang.String |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


텍스트 워터마크가 적용된 경우 워터마크 글꼴 색상

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
