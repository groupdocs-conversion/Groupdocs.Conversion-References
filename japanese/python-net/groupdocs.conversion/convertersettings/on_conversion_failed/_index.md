---
title: "on_conversion_failed プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換が失敗したときに呼び出されるイベントハンドラです。"
type: docs
url: /ja/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

変換が失敗したときに呼び出されるイベントハンドラです。

下位互換性のために尊重されます: この値は [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) の構築時に内部イベントバッグにマージされ（[`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) にマッピングされ）、同じハンドラが `events` コンストラクタパラメータにも設定されている場合は上書きされます。

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### 関連項目
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
