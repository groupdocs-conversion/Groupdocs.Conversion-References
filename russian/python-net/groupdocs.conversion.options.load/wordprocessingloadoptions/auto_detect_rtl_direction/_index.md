---
title: "свойство auto_detect_rtl_direction"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Свойство autodetectrtldirection определяет, следует ли исправлять флаги bidi у абзацев и фрагментов с преимущественно правосторонним текстом перед конвертацией."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

Свойство auto_detect_rtl_direction определяет, следует ли исправлять флаги bidi у абзацев и фрагментов с преимущественно правосторонним текстом перед конвертацией.

Когда установлено значение True (по умолчанию), свойство применяет эвристику, используемую Microsoft Word и LibreOffice, исправляя отображение арабских/еврейских документов, созданных такими инструментами, как Google Docs, которые генерируют OOXML без `<w:bidi/>` и с `<w:rtl w:val=\"0\"/>` в фрагментах, содержащих только RTL‑скрипт. Установите значение False, чтобы сохранить строгую интерпретацию OOXML исходной разметки.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### См. также
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
