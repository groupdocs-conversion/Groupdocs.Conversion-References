---
title: "attachment_content_handler 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "이메일 첨부 파일의 사용자 지정 처리를 담당하는 대리자."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

이메일 첨부 파일의 사용자 지정 처리를 담당하는 대리자.

델리게이트는 첨부 파일 이름(`str`), 콘텐츠 유형(`str`), 원본 첨부 스트림(`io.RawIOBase`)을 받고, 수정된 첨부 스트림(`io.RawIOBase`)을 반환해야 합니다.

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### 또 보기
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
