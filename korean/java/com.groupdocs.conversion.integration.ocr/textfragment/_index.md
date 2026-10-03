---
title: "TextFragment"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "OCR 엔진에 의해 추출된 인식된 텍스트, 단어, 기호 등을 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

OCR 엔진에 의해 추출된 인식된 텍스트(단어, 기호 등)의 일부를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | 인식된 텍스트 조각의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 인식된 텍스트 조각의 텍스트 내용을 가져옵니다. |
|
|  | [getRectangle()](#getRectangle--) | 인식된 텍스트 조각의 경계 사각형을 가져옵니다. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


인식된 텍스트 조각의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 인식된 텍스트 조각의 텍스트 내용 |
|
|  | 사각형 | java.awt.Rectangle | 인식된 텍스트 조각의 경계 사각형 |
|

### getText() {#getText--}
```
public String getText()
```


인식된 텍스트 조각의 텍스트 내용을 가져옵니다.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


인식된 텍스트 조각의 경계 사각형을 가져옵니다.


**Returns:**
[Rectangle](../../java.awt/rectangle)
