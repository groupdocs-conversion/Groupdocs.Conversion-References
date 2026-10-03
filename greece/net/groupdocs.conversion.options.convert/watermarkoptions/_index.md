---
title: "WatermarkOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιλογές ρύθμισης υδατογραφήματος στο μετατρεπόμενο έγγραφο"
type: docs
weight: 2300
url: /el/net/groupdocs.conversion.options.convert/watermarkoptions/
---
## WatermarkOptions class

Επιλογές ρύθμισης υδατογραφήματος στο μετατρεπόμενο έγγραφο

```csharp
public abstract class WatermarkOptions : ValueObject, ICloneable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Αυτόματη κλιμάκωση του υδατογραφήματος. Εάν η τιμή είναι true, η θέση και το μέγεθος υπολογίζονται αυτόματα ώστε να ταιριάζουν στο μέγεθος της σελίδας. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Δείχνει ότι το υδατογράφημα είναι τοποθετημένο ως φόντο. Εάν η τιμή είναι true, το υδατογράφημα τοποθετείται στο κάτω μέρος. Από προεπιλογή είναι false και το υδατογράφημα τοποθετείται στην κορυφή. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Ύψος υδατογραφήματος |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Αριστερή θέση υδατογραφήματος |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Γωνία περιστροφής υδατογραφήματος |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Άνω θέση υδατογραφήματος |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Διαφάνεια υδατογραφήματος. Τιμή μεταξύ 0 και 1. Η τιμή 0 είναι πλήρως ορατή, η τιμή 1 είναι αόρατη. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Πλάτος υδατογραφήματος |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Κλωνοποιήστε την τρέχουσα παρουσία |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
