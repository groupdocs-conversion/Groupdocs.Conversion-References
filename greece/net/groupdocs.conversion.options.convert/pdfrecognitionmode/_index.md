---
title: "PdfRecognitionMode"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιτρέπει τον έλεγχο του τρόπου μετατροπής ενός εγγράφου PDF σε έγγραφο επεξεργασίας κειμένου."
type: docs
weight: 2160
url: /el/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

Επιτρέπει τον έλεγχο του τρόπου μετατροπής ενός εγγράφου PDF σε έγγραφο επεξεργασίας κειμένου.

```csharp
public sealed class PdfRecognitionMode : Enumeration
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | Λειτουργία πλήρους αναγνώρισης, η μηχανή εκτελεί ομαδοποίηση και πολυεπίπεδη ανάλυση για να αποκαταστήσει την πρόθεση του αρχικού συγγραφέα του εγγράφου και να παράγει ένα μέγιστα επεξεργάσιμο έγγραφο. Το μειονέκτημα είναι ότι το τελικό έγγραφο μπορεί να φαίνεται διαφορετικό από το αρχικό αρχείο PDF. |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | Αυτή η λειτουργία είναι γρήγορη και κατάλληλη για τη μέγιστη διατήρηση της αρχικής εμφάνισης του αρχείου PDF, αλλά η επεξεργασιμότητα του προκύπτοντος εγγράφου μπορεί να είναι περιορισμένη. Κάθε οπτικά ομαδοποιημένο μπλοκ κειμένου στο αρχικό αρχείο PDF μετατρέπεται σε πλαίσιο κειμένου στο προκύπτον έγγραφο. Αυτό επιτυγχάνει τη μέγιστη ομοιότητα του τελικού εγγράφου με το αρχικό αρχείο PDF. Το τελικό έγγραφο θα φαίνεται καλό, αλλά θα αποτελείται εξ ολοκλήρου από πλαίσια κειμένου και μπορεί να κάνει την περαιτέρω επεξεργασία του εγγράφου στο Microsoft Word αρκετά δύσκολη. Αυτή είναι η προεπιλεγμένη λειτουργία. |

### Δείτε επίσης

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
