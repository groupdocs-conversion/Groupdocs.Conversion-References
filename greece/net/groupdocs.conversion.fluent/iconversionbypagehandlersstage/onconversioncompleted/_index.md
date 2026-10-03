---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή σελίδας ολοκληρωθεί επιτυχώς. Η επανακλήση αντικαθιστά οποιονδήποτε προηγουμένως ορισμένο χειριστή."
type: docs
weight: 10
url: /el/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted/
---
## IConversionByPageHandlersStage.OnConversionCompleted method

Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή σελίδας ολοκληρωθεί επιτυχώς. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγουμένως ορισμένο χειριστή.

```csharp
public IConversionByPageHandlersStage OnConversionCompleted(
    Action<ConvertedPageContext> onCompleted)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| onCompleted | Action`1 | Μια ενέργεια για τη διαχείριση της ολοκλήρωσης, λαμβάνοντας το περιεχόμενο της μετατρεπόμενης σελίδας. |

### Τιμή επιστροφής

Αυτό το στάδιο, ώστε πρόσθετοι χειριστές ή `Convert` / `Compress` να μπορούν να αλυσοδεθούν.

### Δείτε επίσης

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
