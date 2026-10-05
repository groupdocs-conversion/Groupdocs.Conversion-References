---
title: "ιδιότητα listener"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η υλοποίηση του listener του μετατροπέα που χρησιμοποιείται για την παρακολούθηση της κατάστασης και της προόδου της μετατροπής, με τις κλήσεις Started, Progress και Completed να προωθούνται στο ConversionEvents.onconversionstarted…"
type: docs
url: /el/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

Η υλοποίηση του ακροατή μετατροπέα που χρησιμοποιείται για την παρακολούθηση της κατάστασης και της προόδου της μετατροπής, με τις κλήσεις Started, Progress και Completed να προωθούνται στο [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), και [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) κατά τη δημιουργία του [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### Δείτε επίσης
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
