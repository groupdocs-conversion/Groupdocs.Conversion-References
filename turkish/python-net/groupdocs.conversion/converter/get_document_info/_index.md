---
title: "get_document_info yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Sayfa sayısı ve dosya türüne özgü diğer özellikler dahil olmak üzere kaynak belge bilgilerini alır."
type: docs
url: /tr/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Sayfa sayısı ve dosya türüne özgü diğer özellikler dahil olmak üzere kaynak belge bilgilerini alır.

Dönüştürülmüş belge hakkında daha fazla bilgi edinin – dosya türü, sayfa sayısı, oluşturma tarihi ve birçok diğer format‑özel özelliği:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Örnek

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Ayrıca Bakınız
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
