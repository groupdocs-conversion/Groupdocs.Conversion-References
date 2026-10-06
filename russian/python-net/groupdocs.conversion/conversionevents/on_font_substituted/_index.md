---
title: "свойство on_font_substituted"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Событие, вызываемое, когда шрифт, указанный в исходном документе, недоступен и заменяется (либо правилом FontSubstitute, предоставленным клиентом, либо настроенным шрифтом по умолчанию, либо …"
type: docs
url: /ru/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

Событие вызывается, когда шрифт, указанный в исходном документе, недоступен и заменяется (либо правилом [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) от клиента, либо настроенным шрифтом по умолчанию, либо внутренним резервным шрифтом конвертационного конвейера).

Событие дедуплицируется по `(SourceFileName, OriginalFontName)` в рамках одного вызова `Converter.Convert(...)` — подписчики получают не более одного уведомления о каждом отсутствующем шрифте в исходном документе. Срабатывает синхронно в потоке конвертации. Не генерируется для конвертации изображений.

Для презентационных документов замена шрифтов обнаруживается только в Windows, поскольку движок определяет её через платформенно‑специфичное сопоставление шрифтов, недоступное в других операционных системах.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### См. также
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
