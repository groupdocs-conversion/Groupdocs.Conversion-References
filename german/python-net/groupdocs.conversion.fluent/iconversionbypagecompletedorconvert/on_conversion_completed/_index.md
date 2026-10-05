---
title: "on_conversion_completed Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Empfängt den konvertierten Seiten-Stream."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_page_stream}

Empfängt den konvertierten Seiten-Stream. Wird nur ausgelöst, wenn `ConvertTo(convertedStreamProvider)` festgelegt ist.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Anbieter für konvertierten Seiten-Stream. Der Anbieter erhält einen `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Siehe auch
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
