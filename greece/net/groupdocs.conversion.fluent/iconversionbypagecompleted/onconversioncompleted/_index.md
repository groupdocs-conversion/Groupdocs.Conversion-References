---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Λάβετε τη ροή μετατρεπόμενης σελίδας. Θα ενεργοποιηθεί μόνο εάν έχει οριστεί το ConvertToconvertedStreamProvider."
type: docs
weight: 10
url: /el/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Λήψη ροής μετατρεπόμενης σελίδας. Θα ενεργοποιηθεί μόνο εάν έχει οριστεί "ConvertTo(convertedStreamProvider)".

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<ConvertedPageContext> convertedPageStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| convertedPageStream | Action`1 | Πάροχος ροής μετατρεπόμενης σελίδας Το [`ConvertedPageContext`](../../../groupdocs.conversion/convertedpagecontext) |

### Τιμή επιστροφής

Διεπαφή για τη συνέχιση της δημιουργίας μετατροπής

### Δείτε επίσης

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
