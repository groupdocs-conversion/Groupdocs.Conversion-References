---
title: "auto_detect_rtl_direction proprietà"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "La proprietà autodetectrtldirection determina se i paragrafi e le sequenze di testo con predominanza di scrittura da destra a sinistra hanno i loro flag bidi corretti prima della conversione."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

La proprietà auto_detect_rtl_direction determina se i paragrafi e le run con testo prevalentemente da destra a sinistra hanno i loro flag bidi riparati prima della conversione.

Quando impostata su True (predefinito), la proprietà applica un'euristica utilizzata da Microsoft Word e LibreOffice, correggendo il rendering dei documenti arabi/ebraici generati da strumenti come Google Docs che emettono OOXML senza `<w:bidi/>` e con `<w:rtl w:val=\"0\"/>` sulle sequenze contenenti solo script RTL. Impostala su False per preservare l'interpretazione rigorosa di OOXML del markup di origine.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### Vedi anche
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
