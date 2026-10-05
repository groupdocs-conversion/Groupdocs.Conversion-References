---
title: "WatermarkOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "변환된 문서에 워터마크를 설정하기 위한 옵션"
type: docs
weight: 44
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

변환된 문서에 워터마크를 설정하기 위한 옵션
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WatermarkOptions()](#WatermarkOptions--) | WatermarkOptions 클래스를 생성하고 워터마크 텍스트를 설정합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | 워터마크 너비 |
| [setWidth(int value)](#setWidth-int-) | 워터마크 너비 |
| [getHeight()](#getHeight--) | 워터마크 높이 |
| [setHeight(int value)](#setHeight-int-) | 워터마크 높이 |
| [getTop()](#getTop--) | 워터마크 상단 위치 |
| [setTop(int value)](#setTop-int-) | 워터마크 상단 위치 |
| [getLeft()](#getLeft--) | 워터마크 왼쪽 위치 |
| [setLeft(int value)](#setLeft-int-) | 워터마크 왼쪽 위치 |
| [getRotationAngle()](#getRotationAngle--) | 워터마크 회전 각도 |
| [setRotationAngle(int value)](#setRotationAngle-int-) | 워터마크 회전 각도 |
| [getTransparency()](#getTransparency--) | 워터마크 투명도. |
| [setTransparency(double value)](#setTransparency-double-) | 워터마크 투명도. |
| [getBackground()](#getBackground--) | 워터마크가 배경으로 찍힌다는 것을 나타냅니다. |
| [setBackground(boolean value)](#setBackground-boolean-) | 워터마크가 배경으로 찍힌다는 것을 나타냅니다. |
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
| [deepClone()](#deepClone--) | 현재 인스턴스를 복제합니다. |
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


WatermarkOptions 클래스를 생성하고 워터마크 텍스트를 설정합니다.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


워터마크 너비

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


워터마크 너비

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


워터마크 높이

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


워터마크 높이

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


워터마크 상단 위치

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


워터마크 상단 위치

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


워터마크 왼쪽 위치

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


워터마크 왼쪽 위치

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


워터마크 회전 각도

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


워터마크 회전 각도

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


워터마크 투명도. 값은 0과 1 사이입니다. 값 0은 완전히 보이며, 값 1은 보이지 않습니다.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


워터마크 투명도. 값은 0과 1 사이입니다. 값 0은 완전히 보이며, 값 1은 보이지 않습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


워터마크가 배경으로 찍힌다는 것을 나타냅니다. 값이 true이면 워터마크가 하단에 배치됩니다. 기본값은 false이며 워터마크가 상단에 배치됩니다.

**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


워터마크가 배경으로 찍힌다는 것을 나타냅니다. 값이 true이면 워터마크가 하단에 배치됩니다. 기본값은 false이며 워터마크가 상단에 배치됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### isAutoAlign() {#isAutoAlign--}
```
public boolean isAutoAlign()
```




**Returns:**
boolean
### setAutoAlign(boolean autoAlign) {#setAutoAlign-boolean-}
```
public void setAutoAlign(boolean autoAlign)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


현재 인스턴스를 복제합니다.

**Returns:**
java.lang.Object - 인스턴스
