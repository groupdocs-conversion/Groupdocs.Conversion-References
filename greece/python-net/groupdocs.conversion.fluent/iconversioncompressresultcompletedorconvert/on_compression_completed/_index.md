---
title: "on_compression_completed μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει μια συμπιεσμένη ροή εγγράφου."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/
is_root: false
weight: 1020
---


## on_compression_completed {#compressed_document_stream}

Λαμβάνει μια συμπιεσμένη ροή εγγράφου. Ενεργοποιείται μόνο εάν έχει οριστεί `Compress(CompressionConvertOptions)`.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Κλήση επιστροφής για τη συμπιεσμένη ροή εγγράφου. |

**Returns:** Interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
