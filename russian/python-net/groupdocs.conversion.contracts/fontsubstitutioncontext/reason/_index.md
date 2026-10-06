---
title: "Свойство reason"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Сообщение о замене точно так, как оно сообщается конвейером преобразования, дословно и без разбора."
type: docs
url: /ru/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/
is_root: false
weight: 2020
---


## reason property

Сообщение о замене точно так, как оно сообщается конвейером преобразования, дословно и без разбора.

Для документов, которые структурно раскрывают имена шрифтов, это может быть None (используйте [`FontSubstitutionContext.original_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) / [`FontSubstitutionContext.substitute_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/)); для остальных оно содержит полное человекочитаемое описание, в котором указаны как отсутствующий, так и заменяющий шрифт.

### Definition:
```python
@property
def reason(self):
    ...
```

### См. также
* class [`FontSubstitutionContext`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/)
