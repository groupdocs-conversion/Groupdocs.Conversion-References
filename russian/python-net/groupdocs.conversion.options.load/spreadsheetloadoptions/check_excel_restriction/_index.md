---
title: "свойство check_excel_restriction"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Свойство определяет, проверяются ли ограничения файлов Excel при изменении объектов, связанных с ячейками."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

Свойство определяет, проверяются ли ограничения файлов Excel при изменении объектов, связанных с ячейками.

Если true, попытка ввести строку длиной более 32 K вызовет исключение. Если false, строка принимается, позволяя вывести полное значение в другие форматы, такие как CSV. Однако сохранение книги обратно в формат Excel с такими недопустимыми значениями может вызвать непредвидённые ошибки.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### См. также
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
