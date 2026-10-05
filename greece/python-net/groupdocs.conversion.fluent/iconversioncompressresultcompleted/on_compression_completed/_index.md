---
title: "on_compression_completed μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει τη συμπιεσμένη ροή εγγράφου."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/
is_root: false
weight: 1010
---


## on_compression_completed {#compressed_document_stream}

Λαμβάνει τη συμπιεσμένη ροή εγγράφου.

Εκτελείται μόνο εάν έχει οριστεί το `Compress(CompressionConvertOptions)`.

```python
def on_compression_completed(self, compressed_document_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| compressed_document_stream | `Action[io.RawIOBase]` | Κλήση επιστροφής για τη συμπιεσμένη ροή εγγράφου. |

**Returns:** Interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/)
