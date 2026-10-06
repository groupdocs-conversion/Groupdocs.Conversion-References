---
title: "свойство detect_numbering_with_whitespaces"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Свойство определяет, как распознаются элементы нумерованных списков при конвертации простого текстового документа."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

Свойство определяет, как распознаются нумерованные элементы списка при конвертации обычного текстового документа. Значение по умолчанию: True.

Если эта опция установлена в False, алгоритм распознавания списков обнаруживает абзацы списка, когда номера списков заканчиваются точкой, закрывающей скобкой или символами маркеров (например, "•", "*", "-" или "o").

Если эта опция установлена в True, пробелы также используются в качестве разделителей номеров списков: алгоритм распознавания списков для нумерации в арабском стиле (например, 1., 1.1.2.) использует как пробелы, так и точку (".") в качестве символов.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### См. также
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
