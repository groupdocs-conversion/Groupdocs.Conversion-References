---
title: "свойство layout_scope"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Область макета, определяющая, какие пространства чертежа преобразуются."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

Область макета, определяющая, какие пространства рисунка преобразуются. По умолчанию — [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), что не ограничивает преобразование. Игнорируется, когда указаны [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/), поскольку явные имена макетов всегда имеют приоритет. Значение `None` рассматривается как [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

Если область не выбирает ни один из листов, предлагаемых чертежом, преобразование завершается ошибкой `InvalidLoadOptionsException`, в которой указываются область и доступные листы вместо рендеринга исключённых пространств. Чертеж, не предлагающий ни одного листа, остаётся неизменным и всё равно преобразуется как единое целое. Не учитывается при преобразовании в PDF/UA-1 по причине, указанной в [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### См. также
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
