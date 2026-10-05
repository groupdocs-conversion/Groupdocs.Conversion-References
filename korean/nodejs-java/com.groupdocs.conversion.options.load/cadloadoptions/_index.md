---
title: "CadLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "CAD 문서 불러오기 옵션."
type: docs
weight: 12
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

CAD 문서 불러오기 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CadLoadOptions()](#CadLoadOptions--) | 새 인스턴스를 초기화합니다 [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getWidth()](#getWidth--) | CAD 문서를 변환하기 위한 원하는 페이지 너비를 설정합니다 |
| [setWidth(int value)](#setWidth-int-) | CAD 문서를 변환하기 위한 원하는 페이지 너비를 설정합니다 |
| [getHeight()](#getHeight--) | CAD 문서를 변환하기 위한 원하는 페이지 높이를 설정합니다 |
| [setHeight(int value)](#setHeight-int-) | CAD 문서를 변환하기 위한 원하는 페이지 높이를 설정합니다 |
| [getLayoutNames()](#getLayoutNames--) | 변환할 CAD 레이아웃을 지정합니다 |
| [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | 변환할 CAD 레이아웃을 지정합니다 |
| [getDrawType()](#getDrawType--) | 그리기 유형을 가져옵니다. |
| [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | 그리기 유형을 설정합니다. |
| [getBackgroundColor()](#getBackgroundColor--) | 배경 색상을 가져옵니다. |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | 배경 색상을 설정합니다. |
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


새 인스턴스를 초기화합니다 [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions) 클래스.

### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


입력 문서 파일 유형

**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getWidth() {#getWidth--}
```
public final int getWidth()
```


CAD 문서를 변환하기 위한 원하는 페이지 너비를 설정합니다

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


CAD 문서를 변환하기 위한 원하는 페이지 너비를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


CAD 문서를 변환하기 위한 원하는 페이지 높이를 설정합니다

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


CAD 문서를 변환하기 위한 원하는 페이지 높이를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


변환할 CAD 레이아웃을 지정합니다

**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


변환할 CAD 레이아웃을 지정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


그리기 유형을 가져옵니다.

**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


그리기 유형을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


배경 색상을 가져옵니다.

**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


배경 색상을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

