---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Λάβετε τη ροή του μετατρεπόμενου εγγράφου. Θα ενεργοποιηθεί μόνο εάν ορίσετε το ConvertTostring fileName ή το ConvertToconvertedStreamProvider."
type: docs
weight: 10
url: /el/net/groupdocs.conversion.fluent/iconversioncompleted/onconversioncompleted/
---
## IConversionCompleted.OnConversionCompleted method

Λαμβάνει τη ροή του μετατρεπόμενου εγγράφου. Θα ενεργοποιηθεί μόνο εάν έχει οριστεί "ConvertTo(string fileName)" ή ConvertTo(convertedStreamProvider)".

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedContext> convertedFileStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| convertedFileStream | Action`1 | Πάροχος ροής μετατρεπόμενου εγγράφου Το [`ConvertedContext`](../../../groupdocs.conversion/convertedcontext) |

### Τιμή επιστροφής

Διεπαφή για τη συνέχιση της δημιουργίας μετατροπής

### Δείτε επίσης

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionCompleted](../../iconversioncompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
