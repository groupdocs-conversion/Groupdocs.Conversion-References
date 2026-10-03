---
title: "DiagramConvertOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "Diagram 파일 유형으로 변환하기 위한 옵션."
type: docs
weight: 13
url: /ko/java/com.groupdocs.conversion.options.convert/diagramconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class DiagramConvertOptions extends CommonConvertOptions<DiagramFileType>
```

Diagram 파일 유형으로 변환하기 위한 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DiagramConvertOptions()](#DiagramConvertOptions--) | 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isAutoFitPageToDrawingContent()](#isAutoFitPageToDrawingContent--) | 그리기 내용을 맞추기 위해 페이지를 확대해야 하는지 여부를 정의합니다 |
|
|  | [setAutoFitPageToDrawingContent(boolean autoFitPageToDrawingContent)](#setAutoFitPageToDrawingContent-boolean-) | 페이지 확대 필요 플래그를 설정합니다 |
|
### DiagramConvertOptions() {#DiagramConvertOptions--}
```
public DiagramConvertOptions()
```


클래스의 새 인스턴스를 초기화합니다.


### isAutoFitPageToDrawingContent() {#isAutoFitPageToDrawingContent--}
```
public boolean isAutoFitPageToDrawingContent()
```


그리기 내용을 맞추기 위해 페이지를 확대해야 하는지 여부를 정의합니다


**Returns:**
boolean - 페이지 확대 필요 플래그

### setAutoFitPageToDrawingContent(boolean autoFitPageToDrawingContent) {#setAutoFitPageToDrawingContent-boolean-}
```
public void setAutoFitPageToDrawingContent(boolean autoFitPageToDrawingContent)
```


페이지 확대 필요 플래그를 설정합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | autoFitPageToDrawingContent | 불리언 | 페이지 확대 필요 플래그 |
|

