---
title: "IConversionByPageHandlersStage"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Εξομαλυνμένο στάδιο χειριστών μετατροπής bypage. Καθρέπτης perpage του IConversionHandlersStage./iconversionhandlersstage."
type: docs
weight: 1320
url: /el/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

Εξομαλυνμένο στάδιο χειριστών μετατροπής by-page. Καθρέπτης per-page του [`IConversionHandlersStage`](../iconversionhandlersstage).

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή σελίδας ολοκληρωθεί επιτυχώς. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγουμένως ορισμένο χειριστή. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή σελίδας αποτύχει. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγουμένως ορισμένο χειριστή. |

### Δείτε επίσης

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
