---
title: "listener プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換ステータスと進行状況を監視するために使用されるコンバータリスナー実装で、Started、Progress、Completed コールバックが ConversionEvents.onconversionstarted に転送されます…"
type: docs
url: /ja/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

変換ステータスと進行状況を監視するために使用されるコンバータリスナー実装で、Started、Progress、Completed コールバックは、[`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/)、[`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/)、[`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) に転送され、[`Converter`](/conversion/python-net/groupdocs.conversion/converter/) の構築時に使用されます。

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### 関連項目
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
