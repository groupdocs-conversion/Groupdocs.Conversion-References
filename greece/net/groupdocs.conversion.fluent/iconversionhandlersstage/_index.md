---
title: "IConversionHandlersStage"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Στάδιο επίπεδων χειριστών μετατροπής. Επιτρέπει τη ρύθμιση του OnConversionCompleted ή του OnConversionFailed με οποιαδήποτε σειρά και οποιονδήποτε αριθμό φορών πριν προχωρήσετε στο Convert / Compress. Τα γεγονότα πρέπει να καταχωρίζονται στο αρχικό στάδιο μέσω του WithEvents./iconversionsettings/withevents αντί σε αυτό το στάδιο."
type: docs
weight: 1480
url: /el/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

Στάδιο επίπεδων χειριστών μετατροπής. Επιτρέπει τη ρύθμιση του `OnConversionCompleted` ή του `OnConversionFailed` με οποιαδήποτε σειρά και οποιονδήποτε αριθμό φορών, πριν προχωρήσετε στο `Convert` / `Compress`. Τα γεγονότα πρέπει να καταχωρίζονται στο αρχικό στάδιο μέσω του [`WithEvents`](../iconversionsettings/withevents) αντί σε αυτό το στάδιο.

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή εγγράφου ολοκληρωθεί επιτυχώς. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγούμενα ορισμένο χειριστή. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | Καταχωρίζει μια κλήση επιστροφής που θα κληθεί όταν μια μετατροπή εγγράφου αποτύχει. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγούμενα ορισμένο χειριστή. |

### Δείτε επίσης

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
