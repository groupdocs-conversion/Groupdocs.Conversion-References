---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν αποτύχει η μετατροπή εγγράφου. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγούμενο χειριστή."
type: docs
weight: 20
url: /el/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed/
---
## IConversionHandlersStage.OnConversionFailed method

Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή εγγράφου αποτύχει. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγούμενα ορισμένο χειριστή.

```csharp
public IConversionHandlersStage OnConversionFailed(Action<ConvertedContext, Exception> onFailed)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| onFailed | Action`2 | Μια ενέργεια για τη διαχείριση της αποτυχίας, λαμβάνοντας το πλαίσιο μετατροπής και την εξαίρεση που προκάλεσε την αποτυχία. |

### Τιμή επιστροφής

Αυτό το στάδιο, ώστε πρόσθετοι χειριστές ή `Convert` / `Compress` να μπορούν να αλυσοδεθούν.

### Δείτε επίσης

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
