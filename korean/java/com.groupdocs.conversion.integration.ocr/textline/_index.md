---
title: "TextLine"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "이미지에서 인식 과정을 통해 추출된 텍스트를 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

이미지 인식 과정의 결과로 추출된 텍스트를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | OCR 엔진이 이미지에서 추출한 텍스트 라인의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFragments()](#getFragments--) | 라인에서 인식된 기호 및 단어와 같은 텍스트 조각들의 배열을 가져옵니다. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


OCR 엔진이 이미지에서 추출한 텍스트 라인의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 조각들 | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | 초기 텍스트 조각 집합 |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


라인에서 인식된 기호 및 단어와 같은 텍스트 조각들의 배열을 가져옵니다.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
