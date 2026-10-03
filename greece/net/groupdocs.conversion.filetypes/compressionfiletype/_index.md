---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει μορφές συμπίεσης. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. Μάθετε περισσότερα για τις μορφές συμπίεσης εδώhttps//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /el/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Ορίζει μορφές συμπίεσης. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). Μάθετε περισσότερα για τις μορφές συμπίεσης [εδώ](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Περιγραφή τύπου αρχείου |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Η επέκταση αρχείου |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Η οικογένεια αρχείου |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Η μορφή αρχείου |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Ορίζει εάν η μορφή υποστηρίζει πολλαπλά αρχεία/φακέλους σε ένα ενιαίο αρχείο. |

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
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | Ένα αρχείο με επέκταση .aar είναι ένα Apple Archive, το κοντέινερ που η Apple παρέχει με το macOS για ομαδοποίηση αρχείων και φακέλων. Κάθε καταχώρηση συμπιέζεται ξεχωριστά, συνήθως με LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | Ένα αρχείο με επέκταση .alz είναι ένα αρχείο ALZip, μορφή από την ESTsoft που χρησιμοποιείται ευρέως στη Νότια Κορέα. Οι καταχωρήσεις μπορεί να κρυπτογραφηθούν ατομικά με κωδικό πρόσβασης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | Τα αρχεία BZ2 είναι συμπιεσμένα αρχεία που δημιουργούνται χρησιμοποιώντας τη μέθοδο ανοιχτού κώδικα BZIP2, κυρίως σε συστήματα UNIX ή Linux. Χρησιμοποιείται για συμπίεση ενός μόνο αρχείου και δεν προορίζεται για αρχειοθέτηση πολλαπλών αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Ένα αρχείο με επέκταση .cab ανήκει σε αρχείο cabinet των Windows που ανήκει στην κατηγορία των συστημικών αρχείων. Είναι ένα αρχείο που αποθηκεύεται σε μορφή αρχείου αρχειοθέτησης στις εκδόσεις του Microsoft Windows που υποστηρίζουν αλγόριθμους συμπίεσης δεδομένων, όπως το LZX, Quantum και ZIP. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Το Cpio είναι ένα γενικό εργαλείο αρχειοθέτησης αρχείων και η σχετική του μορφή αρχείου. Εγκαθίσταται κυρίως σε λειτουργικά συστήματα τύπου Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Ένα αρχείο GZ είναι ένα συμπιεσμένο αρχείο που δημιουργείται χρησιμοποιώντας τον τυπικό αλγόριθμο συμπίεσης gzip (GNU zip). Μπορεί να περιέχει πολλαπλά συμπιεσμένα αρχεία, καταλόγους και υποδείγματα αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Ένα αρχείο Gzip είναι ένα συμπιεσμένο αρχείο που δημιουργείται χρησιμοποιώντας τον τυπικό αλγόριθμο συμπίεσης gzip (GNU zip). Μπορεί να περιέχει πολλαπλά συμπιεσμένα αρχεία, καταλόγους και υποδείγματα αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | Ένα αρχείο με επέκταση .iso είναι ένα μη συμπιεσμένο αρχείο εικόνας δίσκου που αντιπροσωπεύει το περιεχόμενο ολόκληρων δεδομένων σε ένα οπτικό δίσκο όπως CD ή DVD. Βασισμένο στο πρότυπο ISO-9660, η μορφή αρχείου εικόνας ISO περιέχει τα δεδομένα του δίσκου μαζί με τις πληροφορίες του συστήματος αρχείων που αποθηκεύονται σε αυτό. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | Ένα αρχείο με επέκταση .lzh και .lha συνήθως σχετίζεται με μορφή αρχείου συμπίεσης. Αυτή η μορφή αρχείου είναι η ίδια με άλλες μορφές συμπίεσης όπως ZIP, RAR κ.λπ. Ο κύριος σκοπός αυτών των μορφών αρχείων είναι η μείωση του μεγέθους τους για εύκολη αποστολή καθώς και η διατήρησή τους μαζί σε συμπιεσμένη μορφή. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Ένα αρχείο με επέκταση .lz είναι ένα συμπιεσμένο αρχείο που δημιουργείται με το Lzip, ένα δωρεάν εργαλείο γραμμής εντολών για συμπίεση. Υποστηρίζει συνένωση για συμπίεση αρχείων υποστήριξης. Τα αρχεία LZ έχουν τύπο μέσου application/lzip και προσφέρουν υψηλότερους λόγους συμπίεσης από το BZ2. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | Ένα αρχείο με επέκταση .lz4 είναι ένα συμπιεσμένο αρχείο που δημιουργείται με εφαρμογές/εργαλεία που υποστηρίζουν τη συμπίεση LZ4. Ο αλγόριθμος LZ4 εστιάζει στην ισορροπία μεταξύ ταχύτητας και λόγου συμπίεσης. Συμπιεσμένα αρχεία LZ4 μπορούν να δημιουργηθούν χρησιμοποιώντας το εργαλείο γραμμής εντολών LZ4 και μπορούν να αποσυμπιεστούν με το ίδιο εργαλείο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Ένα αρχείο με επέκταση .lzma είναι ένα συμπιεσμένο αρχείο που δημιουργείται χρησιμοποιώντας τη μέθοδο συμπίεσης LZMA (αλγόριθμος Lempel‑Ziv‑Markov chain). Αυτά βρίσκονται/χρησιμοποιούνται κυρίως σε λειτουργικά συστήματα Unix και είναι παρόμοια με άλλους αλγόριθμους συμπίεσης όπως το ZIP για τη μείωση του μεγέθους του αρχείου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Τα αρχεία με επέκταση .rar είναι αρχεία που δημιουργούνται για αποθήκευση πληροφοριών σε συμπιεσμένη ή κανονική μορφή. RAR, που σημαίνει Roshal ARchive format. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | Το 7z είναι μια μορφή αρχειοθέτησης για συμπίεση αρχείων και φακέλων με υψηλό λόγο συμπίεσης. Βασίζεται σε αρχιτεκτονική ανοιχτού κώδικα, που επιτρέπει τη χρήση οποιωνδήποτε αλγόριθμων συμπίεσης και κρυπτογράφησης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Τα αρχεία με επέκταση .tar είναι αρχεία που δημιουργούνται με βοηθητικό πρόγραμμα βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. Πολλαπλά αρχεία αποθηκεύονται σε μη συμπιεσμένη μορφή με δυνατότητα προσθήκης αρχείων καθώς και φακέλων στο αρχείο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Ένα uuencoded αρχείο είναι ένα αρχείο ή συλλογή αρχείων που έχουν κωδικοποιηθεί χρησιμοποιώντας το σχήμα κωδικοποίησης Unix‑to‑Unix (uuencode). Αυτή η μέθοδος κωδικοποίησης μετατρέπει δυαδικά δεδομένα σε μορφή κειμένου, κάνοντας πιο εύκολη την αποστολή αρχείων μέσω καναλιών που υποστηρίζουν μόνο κείμενο, όπως το email. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | Ένα αρχείο με επέκταση .wim είναι ένα αρχείο Windows Imaging Format, μια εικόνα δίσκου βασισμένη σε αρχείο που η Microsoft χρησιμοποιεί για την ανάπτυξη των Windows. Ένα ενιαίο αρχείο περιέχει μία ή περισσότερες εικόνες και αποθηκεύει κάθε αρχείο μία φορά, ανεξάρτητα από το πόσες εικόνες το αναφέρονται. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | Ένα αρχείο με επέκταση .xar είναι ένα eXtensible ARchive, μια μορφή που βασίζεται σε πίνακα περιεχομένων αποθηκευμένο ως συμπιεσμένο XML. Χρησιμοποιείται για τη διανομή πακέτων εγκατάστασης macOS και διατηρεί κάθε καταχώρηση συμπιεσμένη ξεχωριστά. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | Το XZ είναι μια συμπιεσμένη μορφή αρχείου που χρησιμοποιεί τον αλγόριθμο συμπίεσης LZMA2. Σχεδιάστηκε ως αντικατάσταση των δημοφιλών μορφών gzip και bzip2, και προσφέρει μια σειρά πλεονεκτημάτων σε σχέση με αυτά τα παλαιότερα πρότυπα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Ένα αρχείο Z είναι μια κατηγορία αρχείων που ανήκει στα συμπιεσμένα δεδομένα UNIX. Τα συμπιεσμένα αρχεία Unix είναι ο πιο δημοφιλής και ευρέως χρησιμοποιούμενος τύπος επέκτασης του αρχείου Z. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Ένα αρχείο με επέκταση .zip είναι ένα αρχείο συμπιεσμένων δεδομένων που μπορεί να περιέχει ένα ή περισσότερα αρχεία ή καταλόγους. Το αρχείο μπορεί να έχει εφαρμοσμένη συμπίεση στα περιλαμβανόμενα αρχεία ώστε να μειωθεί το μέγεθος του αρχείου ZIP. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | Ένα αρχείο ZST είναι ένα συμπιεσμένο αρχείο που δημιουργείται με τον αλγόριθμο συμπίεσης Zstandard (zstd). Είναι ένα συμπιεσμένο αρχείο που δημιουργείται με μη απωλεστική συμπίεση από τον αλγόριθμο. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/compression/zst/). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
