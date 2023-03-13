---
title: VideoFileType
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Ορίζει έγγραφα βίντεο Περιλαμβάνει τους ακόλουθους τύπους Mp4./videofiletype/mp4  Avi./videofiletype/avi  Flv./videofiletype/flv  Mkv./videofiletype/mkv  Mov./videofiletype/mov  Webm./videofiletype/webm  Wmv./videofiletype/wmv  Μάθετε περισσότερα σχετικά με τις μορφές βίντεοεδώhttps//docs.fileformat.com/video/ .
type: docs
weight: 1070
url: /el/net/groupdocs.conversion.filetypes/videofiletype/
---
## VideoFileType class

Ορίζει έγγραφα βίντεο Περιλαμβάνει τους ακόλουθους τύπους: [`Mp4`](./mp4) , [`Avi`](./avi) , [`Flv`](./flv) , [`Mkv`](./mkv) , [`Mov`](./mov) , [`Webm`](./webm) , [`Wmv`](./wmv) , Μάθετε περισσότερα σχετικά με τις μορφές βίντεο[εδώ](https://docs.fileformat.com/video/) .

```csharp
public sealed class VideoFileType : FileType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [VideoFileType](videofiletype)() | Κατασκευαστής σειριοποίησης |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Περιγραφή τύπου αρχείου |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Η επέκταση αρχείου |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Η οικογένεια αρχείων |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Η μορφή αρχείου |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει εάν δύο στιγμιότυπα αντικειμένων είναι ίσα. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Εξυπηρετεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Αναπαράσταση συμβολοσειράς |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Avi](../../groupdocs.conversion.filetypes/videofiletype/avi) | Η μορφή αρχείου AVI είναι μια μορφή αρχείου κοντέινερ πολυμέσων ήχου βίντεο που εισήχθη από τη Microsoft. Διατηρεί τα δεδομένα ήχου και βίντεο που δημιουργούνται και συμπιέζονται με τη χρήση πολλών κωδικοποιητών (Coders/Decoders) όπως XVid και DivX. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/video/avi/) . |
| static readonly [Flv](../../groupdocs.conversion.filetypes/videofiletype/flv) | Το FLV (Flash Video) είναι μια μορφή αρχείου κοντέινερ με επέκταση .flv. Το FLV χρησιμοποιείται για την παράδοση περιεχομένου ήχου/βίντεο μέσω του Διαδικτύου χρησιμοποιώντας το Adobe Flash Player ή το Adobe Air. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/video/flv/) . |
| static readonly [Mkv](../../groupdocs.conversion.filetypes/videofiletype/mkv) | Το MKV (Matroska Video) είναι ένα κοντέινερ πολυμέσων παρόμοιο με τη μορφή MOV και AVI, αλλά υποστηρίζει περισσότερα από ένα κομμάτια ήχου και υπότιτλων στο ίδιο αρχείο. Ένα αρχείο MKV είναι η μορφή κοντέινερ πολυμέσων Matroska που χρησιμοποιείται για βίντεο. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/video/mkv/) . |
| static readonly [Mov](../../groupdocs.conversion.filetypes/videofiletype/mov) | Η μορφή αρχείου MOV ή QuickTime είναι ένα κοντέινερ πολυμέσων που έχει αναπτυχθεί από την Apple: περιέχει ένα ή περισσότερα κομμάτια, κάθε κομμάτι περιέχει έναν συγκεκριμένο τύπο δεδομένων, π.χ. βίντεο, ήχος, κείμενο κ.λπ. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/video/mov/) . |
| static readonly [Mp4](../../groupdocs.conversion.filetypes/videofiletype/mp4) | Το MP4 (συντομογραφία για το MPEG-4 Μέρος 14) είναι μια μορφή αρχείου που βασίζεται στο ISO/IEC 14496-12:2004 που βασίζεται στη μορφή αρχείου QuickTime αλλά επίσημα καθορίζει την υποστήριξη για Περιγραφείς Αρχικών Αντικειμένων (IOD) και άλλες δυνατότητες MPEG. Learn περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/video/mp4/) . |
| static readonly [Webm](../../groupdocs.conversion.filetypes/videofiletype/webm) | Ένα αρχείο με επέκταση .webm είναι ένα αρχείο βίντεο που βασίζεται στην ανοιχτή μορφή αρχείου WebM χωρίς δικαιώματα εκμετάλλευσης. Έχει σχεδιαστεί για κοινή χρήση βίντεο στον Ιστό και καθορίζει τη δομή του κοντέινερ αρχείων, συμπεριλαμβανομένων των μορφών βίντεο και ήχου. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/video/webm//) . |
| static readonly [Wmv](../../groupdocs.conversion.filetypes/videofiletype/wmv) | Το Advanced Systems Format (ASF) είναι ένα ψηφιακό κοντέινερ πολυμέσων που έχει σχεδιαστεί κυρίως για την αποθήκευση και τη μετάδοση ροών πολυμέσων. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/video/wmv/) . |

### Δείτε επίσης

* class [FileType](../filetype)
* χώρος ονομάτων [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
