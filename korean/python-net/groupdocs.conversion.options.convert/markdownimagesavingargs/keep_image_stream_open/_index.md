---
title: "keep_image_stream_open 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "이 속성은 변환 후 변환기가 이미지 스트림을 열어 둔 상태로 유지할지 여부를 결정합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

이 속성은 변환 후 변환기가 이미지 스트림을 열어 둔 상태로 유지할지 여부를 결정합니다.

False(기본값)인 경우, 변환기는 기록 후 [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/)를 닫습니다 — 디스크에 플러시해야 하는 `io.RawIOBase` 교체에 관례적인 동작입니다. True로 설정하면 변환이 완료된 후 스트림을 열어 둡니다(`io.BytesIO`를 직접 읽으려는 경우에 일반적). 이때 호출자가 스트림 폐기를 담당합니다.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### 또 보기
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
