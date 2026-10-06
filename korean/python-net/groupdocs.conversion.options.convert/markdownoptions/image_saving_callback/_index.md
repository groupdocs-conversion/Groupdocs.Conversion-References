---
title: "image_saving_callback 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "Markdown을 저장하는 동안 이미지당 한 번 호출되는 콜백입니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Markdown을 저장하는 동안 이미지당 한 번 호출되는 콜백입니다. 호출자가 이미지를 외부에 저장하고 문서에 삽입된 URI를 대체할 수 있게 합니다. None이 아닌 경우 [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/)보다 우선합니다.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### 또 보기
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
