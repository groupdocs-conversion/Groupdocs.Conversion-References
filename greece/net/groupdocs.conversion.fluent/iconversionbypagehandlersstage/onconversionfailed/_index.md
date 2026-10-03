---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή σελίδας αποτύχει. Η επανακλήση αντικαθιστά οποιονδήποτε προηγουμένως ορισμένο χειριστή."
type: docs
weight: 20
url: /el/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή σελίδας αποτύχει. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγουμένως ορισμένο χειριστή.

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| onFailed | Action`2 | Μια ενέργεια για τη διαχείριση της αποτυχίας, λαμβάνοντας το περιεχόμενο της μετατρεπόμενης σελίδας και την εξαίρεση που προκάλεσε την αποτυχία. |

### Τιμή επιστροφής

Αυτό το στάδιο, ώστε πρόσθετοι χειριστές ή `Convert` / `Compress` να μπορούν να αλυσοδεθούν.

### Δείτε επίσης

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
