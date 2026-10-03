---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή εγγράφου ολοκληρωθεί επιτυχώς. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγούμενο χειριστή."
type: docs
weight: 10
url: /el/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted/
---
## IConversionHandlersStage.OnConversionCompleted method

Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή εγγράφου ολοκληρωθεί επιτυχώς. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγούμενα ορισμένο χειριστή.

```csharp
public IConversionHandlersStage OnConversionCompleted(Action<ConvertedContext> onCompleted)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| onCompleted | Action`1 | Μια ενέργεια για τη διαχείριση της ολοκλήρωσης, λαμβάνοντας το πλαίσιο μετατροπής. |

### Τιμή επιστροφής

Αυτό το στάδιο, ώστε πρόσθετοι χειριστές ή `Convert` / `Compress` να μπορούν να αλυσοδεθούν.

### Δείτε επίσης

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
