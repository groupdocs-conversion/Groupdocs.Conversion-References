---
title: "VideoFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει έγγραφα βίντεο Περιλαμβάνει τους ακόλουθους τύπους Mp4./videofiletype/mp4 Avi./videofiletype/avi Flv./videofiletype/flv Mkv./videofiletype/mkv Mov./videofiletype/mov Webm./videofiletype/webm Wmv./videofiletype/wmv Μάθετε περισσότερα για τις μορφές βίντεο εδώhttps//docs.fileformat.com/video/."
type: docs
weight: 1260
url: /el/net/groupdocs.conversion.filetypes/videofiletype/
---
## VideoFileType class

Ορίζει έγγραφα βίντεο Περιλαμβάνει τους ακόλουθους τύπους: [`Mp4`](./mp4), [`Avi`](./avi), [`Flv`](./flv), [`Mkv`](./mkv), [`Mov`](./mov), [`Webm`](./webm), [`Wmv`](./wmv), Μάθετε περισσότερα για τις μορφές βίντεο [εδώ](https://docs.fileformat.com/video/).

```csharp
public sealed class VideoFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [VideoFileType](videofiletype)() | Κατασκευαστής σειριοποίησης |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Περιγραφή τύπου αρχείου |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Η επέκταση αρχείου |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Η οικογένεια αρχείου |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Η μορφή αρχείου |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Υλοποιεί [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Αναπαράσταση συμβολοσειράς |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [Avi](../../groupdocs.conversion.filetypes/videofiletype/avi) | Η μορφή αρχείου AVI είναι μια μορφή αρχείου περιέκτη ήχου-βίντεο πολυμέσων που εισήχθη από τη Microsoft. Περιέχει τα δεδομένα ήχου και βίντεο που δημιουργήθηκαν και συμπιέστηκαν χρησιμοποιώντας διάφορους κωδικοποιητές (Coders/Decoders) όπως το XVid και το DivX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/video/avi/). |
| static readonly [Flv](../../groupdocs.conversion.filetypes/videofiletype/flv) | Το FLV (Flash Video) είναι μια μορφή αρχείου κοντέινερ με την επέκταση .flv. Το FLV χρησιμοποιείται για τη διανομή περιεχομένου ήχου/βίντεο μέσω του διαδικτύου χρησιμοποιώντας το Adobe Flash Player ή το Adobe Air. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/video/flv/). |
| static readonly [Mkv](../../groupdocs.conversion.filetypes/videofiletype/mkv) | Το MKV (Matroska Video) είναι ένα πολυμέσο κοντέινερ παρόμοιο με τις μορφές MOV και AVI, αλλά υποστηρίζει περισσότερα από ένα κανάλια ήχου και υπότιτλων στο ίδιο αρχείο. Ένα αρχείο MKV είναι η μορφή κοντέινερ Matroska που χρησιμοποιείται για βίντεο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/video/mkv/). |
| static readonly [Mov](../../groupdocs.conversion.filetypes/videofiletype/mov) | Το MOV ή μορφή αρχείου QuickTime είναι ένα πολυμέσο κοντέινερ που αναπτύχθηκε από την Apple: περιέχει ένα ή περισσότερα κομμάτια, κάθε κομμάτι κρατά έναν συγκεκριμένο τύπο δεδομένων, π.χ. βίντεο, ήχο, κείμενο κ.λπ. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/video/mov/). |
| static readonly [Mp4](../../groupdocs.conversion.filetypes/videofiletype/mp4) | Το MP4 (συντομογραφία του MPEG-4 Part 14) είναι μια μορφή αρχείου βασισμένη στο ISO/IEC 14496-12:2004, η οποία προέρχεται από τη μορφή QuickTime File Format, αλλά ορίζει επίσημα υποστήριξη για Initial Object Descriptors (IOD) και άλλα χαρακτηριστικά MPEG. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/video/mp4/). |
| static readonly [Webm](../../groupdocs.conversion.filetypes/videofiletype/webm) | Ένα αρχείο με επέκταση .webm είναι ένα αρχείο βίντεο βασισμένο στην ανοιχτή, χωρίς δικαιώματα χρήσης μορφή WebM. Έχει σχεδιαστεί για κοινή χρήση βίντεο στο διαδίκτυο και ορίζει τη δομή του κοντέινερ αρχείου, συμπεριλαμβανομένων των μορφών βίντεο και ήχου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/video/webm//). |
| static readonly [Wmv](../../groupdocs.conversion.filetypes/videofiletype/wmv) | Το Windows Media Video είναι η συμπιεσμένη μορφή βίντεο που αναπτύχθηκε από τη Microsoft. Μετά την τυποποίηση από την Society of Motion Picture and Television Engineers (SMPTE), το WMV θεωρείται πλέον ανοιχτής προδιαγραφής μορφή. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/video/wmv/). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
