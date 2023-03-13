---
title: SpreadsheetLoadOptions
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Επιλογές για τη φόρτωση εγγράφων υπολογιστικού φύλλου.
type: docs
weight: 2260
url: /el/net/groupdocs.conversion.options.load/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Επιλογές για τη φόρτωση εγγράφων υπολογιστικού φύλλου.

```csharp
public class SpreadsheetLoadOptions : LoadOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Αρχικοποιεί νέα παρουσία του[`SpreadsheetLoadOptions`](../spreadsheetloadoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Ελέγχετε τον περιορισμό του αρχείου excel όταν ο χρήστης τροποποιεί αντικείμενα που σχετίζονται με κελιά. Για παράδειγμα, το excel δεν επιτρέπει την εισαγωγή τιμής συμβολοσειράς μεγαλύτερης από 32K. Όταν εισάγετε μια τιμή μεγαλύτερη από 32K, εάν αυτή η ιδιότητα είναι αληθής, θα λάβετε μια Εξαίρεση. Εάν αυτή η ιδιότητα είναι ψευδής, θα δεχθούμε την τιμή συμβολοσειράς εισόδου ως τιμή του κελιού, ώστε αργότερα να μπορείτε να εξάγετε την πλήρη τιμή συμβολοσειράς για άλλες μορφές αρχείων, όπως το CSV. Ωστόσο, εάν έχετε ορίσει τέτοιου είδους τιμή που δεν είναι έγκυρη για τη μορφή αρχείου excel, δεν θα πρέπει να αποθηκεύσετε το βιβλίο εργασίας ως μορφή αρχείου excel αργότερα. Διαφορετικά, ενδέχεται να υπάρχει μη αναμενόμενο σφάλμα για το αρχείο excel που δημιουργήθηκε. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Μετατροπή συγκεκριμένου εύρους κατά τη μετατροπή σε μορφή διαφορετική από το υπολογιστικό φύλλο. Παράδειγμα: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Λάβετε ή ρυθμίστε τις πληροφορίες πολιτισμού συστήματος τη στιγμή που φορτώνεται το αρχείο |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Προεπιλεγμένη γραμματοσειρά για έγγραφο υπολογιστικού φύλλου. Η ακόλουθη γραμματοσειρά θα χρησιμοποιηθεί εάν λείπει μια γραμματοσειρά. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Αντικαταστήστε συγκεκριμένες γραμματοσειρές κατά τη μετατροπή εγγράφου υπολογιστικού φύλλου. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Τύπος αρχείου εγγράφου εισαγωγής. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Τύπος αρχείου εγγράφου εισαγωγής. |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Απόκρυψη σχολίων. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Εάν το OnePagePerSheet είναι αληθές, το περιεχόμενο του φύλλου θα μετατραπεί σε μία σελίδα στο έγγραφο PDF. Η προεπιλεγμένη τιμή είναι true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Εάν το True και μετατρέπεται σε Pdf, η μετατροπή έχει βελτιστοποιηθεί για καλύτερο μέγεθος αρχείου από την ποιότητα εκτύπωσης. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Ορίστε τον κωδικό πρόσβασης για να καταργήσετε την προστασία του προστατευμένου εγγράφου. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Λίστα ευρετηρίων φύλλων προς μετατροπή. Τα ευρετήρια πρέπει να είναι μηδενικής βάσης |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Όνομα φύλλου σε convert |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Εμφάνιση γραμμών πλέγματος κατά τη μετατροπή αρχείων Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Εμφάνιση κρυφών φύλλων κατά τη μετατροπή αρχείων Excel. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Παραλείπει κενές γραμμές και στήλες κατά τη μετατροπή. Η προεπιλογή είναι True. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Κλωνοποιεί την τρέχουσα παρουσία. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Εξυπηρετεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions)
* χώρος ονομάτων [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
