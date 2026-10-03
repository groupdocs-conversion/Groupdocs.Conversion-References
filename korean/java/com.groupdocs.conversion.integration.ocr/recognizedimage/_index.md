---
title: "RecognizedImage"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "이미지에서 인식 과정을 통해 추출된 텍스트를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

이미지 인식 과정의 결과로 추출된 텍스트를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | 인식된 라인 집합을 사용하여 해당 클래스의 새 인스턴스를 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [EMPTY](#EMPTY) | 빈 인식 이미지 |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getLines()](#getLines--) | 문서 내에서 인식된 텍스트 라인과 해당 조각들을 가져옵니다. |
|
|  | [getText()](#getText--) | 구조화된 텍스트의 텍스트 등가물을 가져옵니다. |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


인식된 라인 집합을 사용하여 해당 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 라인 | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | 인식된 라인의 IEnumerable (예: 리스트 또는 배열) |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


빈 인식 이미지


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


문서 내에서 인식된 텍스트 라인과 해당 조각들을 가져옵니다.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


구조화된 텍스트의 텍스트 등가물을 가져옵니다.


**Returns:**
java.lang.String
