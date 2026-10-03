---
title: "ImageLoadOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "이미지 문서를 로드하기 위한 옵션."
type: docs
weight: 21
url: /ko/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

이미지 문서를 로드하기 위한 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | 새 인스턴스를 초기화합니다 [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) 클래스. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Psd, Emf, Wmf 문서 유형에 대한 기본 글꼴. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Psd, Emf, Wmf 문서 유형에 대한 기본 글꼴. |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | 이미지 OCR 커넥터 설정 |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | 문서를 로드하기 전에 글꼴 폴더를 재설정합니다 |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


새 인스턴스를 초기화합니다 [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) 클래스.


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


입력 문서 파일 유형


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Psd, Emf, Wmf 문서 유형에 대한 기본 글꼴. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Psd, Emf, Wmf 문서 유형에 대한 기본 글꼴. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### isRecognitionEnabled() {#isRecognitionEnabled--}
```
public boolean isRecognitionEnabled()
```




**Returns:**
불리언
### getOcrConnector() {#getOcrConnector--}
```
public IOcrConnector getOcrConnector()
```




**Returns:**
[IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector)
### setOcrConnector(IOcrConnector ocrConnector) {#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-}
```
public void setOcrConnector(IOcrConnector ocrConnector)
```


이미지 OCR 커넥터 설정


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | OCR 커넥터 인스턴스 |
|

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


문서를 로드하기 전에 글꼴 폴더를 재설정합니다


**Returns:**
불리언
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| resetFontFolders | 불리언 |  |

