---
title: "VideoLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "비디오 문서를 로드하기 위한 옵션."
type: docs
weight: 41
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/videoloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
```
public class VideoLoadOptions extends LoadOptions
```

비디오 문서를 로드하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VideoLoadOptions()](#VideoLoadOptions--) |   클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVideoConnector()](#getVideoConnector--) |  |
| [setVideoConnector(IVideoConnector videoConnector)](#setVideoConnector-com.groupdocs.conversion.integration.video.IVideoConnector-) | 비디오 문서 커넥터를 설정합니다. |
### VideoLoadOptions() {#VideoLoadOptions--}
```
public VideoLoadOptions()
```


  클래스의 새 인스턴스를 초기화합니다.

### getVideoConnector() {#getVideoConnector--}
```
public IVideoConnector getVideoConnector()
```




**Returns:**
[IVideoConnector](../../com.groupdocs.conversion.integration.video/ivideoconnector)
### setVideoConnector(IVideoConnector videoConnector) {#setVideoConnector-com.groupdocs.conversion.integration.video.IVideoConnector-}
```
public void setVideoConnector(IVideoConnector videoConnector)
```


비디오 문서 커넥터를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| videoConnector | [IVideoConnector](../../com.groupdocs.conversion.integration.video/ivideoconnector) | 비디오 커넥터 인스턴스 |

