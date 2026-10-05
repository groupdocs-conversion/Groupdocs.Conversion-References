---
title: "cap_resolution_to_page_content Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Eigenschaft begrenzt die Renderauflösung pro Seite des PDFs auf die native Rasterauflösung der Seite, verhindert das Rendern mit einer höheren DPI als das eingebettete Bild und gibt die Seite in ihrer nativen (kleineren) Auflösung aus…"
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

Die Eigenschaft begrenzt die PDF‑Renderauflösung pro Seite auf die native Rasterauflösung der Seite, verhindert das Rendern mit einer höheren DPI als das eingebettete Bild und gibt die Seite in ihrer nativen (kleineren) Pixelgröße und DPI in der endgültigen Ausgabe aus.

Nur bild‑dominierte (Scan‑)Seiten sind betroffen; Seiten mit Text‑ oder Vektorinhalt werden niemals weichgezeichnet und mit der angeforderten DPI ausgegeben. Die Begrenzung wird ignoriert, wenn ein expliziter Ausgabewert [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) oder [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) festgelegt ist. Der Standardwert ist False (keine Begrenzung; jede Seite wird mit der angeforderten DPI gerendert und ausgegeben).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### Siehe auch
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
