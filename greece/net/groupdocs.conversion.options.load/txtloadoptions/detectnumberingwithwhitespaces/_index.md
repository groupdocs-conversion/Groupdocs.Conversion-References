---
title: "DetectNumberingWithWhitespaces"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Επιτρέπει τον καθορισμό του τρόπου αναγνώρισης των στοιχείων αριθμημένης λίστας όταν το έγγραφο απλού κειμένου μετατρέπεται. Η προεπιλεγμένη τιμή είναι true."
type: docs
weight: 30
url: /el/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

Επιτρέπει τον καθορισμό του τρόπου αναγνώρισης των στοιχείων αριθμημένης λίστας όταν το έγγραφο απλού κειμένου μετατρέπεται. Η προεπιλεγμένη τιμή είναι true.

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### Παρατηρήσεις

Εάν αυτή η επιλογή οριστεί σε false, ο αλγόριθμος αναγνώρισης λιστών εντοπίζει παραγράφους λιστών, όταν οι αριθμοί λίστας τελειώνουν είτε με τελεία, δεξιό αγκύλη ή σύμβολα κουκίδας (όπως "•", "*", "-" ή "o").

Εάν αυτή η επιλογή οριστεί σε true, τα κενά χρησιμοποιούνται επίσης ως διαχωριστικά αριθμών λίστας: ο αλγόριθμος αναγνώρισης λιστών για αραβική μορφή αρίθμησης (1., 1.1.2.) χρησιμοποιεί τόσο τα κενά όσο και το σύμβολο τελείας (".").

### Δείτε επίσης

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
