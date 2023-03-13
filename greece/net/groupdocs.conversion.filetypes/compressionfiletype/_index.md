---
title: CompressionFileType
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Καθορίζει μορφές συμπίεσης. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . Μάθετε περισσότερα σχετικά με τις μορφές συμπίεσηςεδώhttps//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /el/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Καθορίζει μορφές συμπίεσης. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . Μάθετε περισσότερα σχετικά με τις μορφές συμπίεσης[εδώ](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | Τα BZ2 είναι συμπιεσμένα αρχεία που δημιουργούνται χρησιμοποιώντας τη μέθοδο συμπίεσης ανοιχτού κώδικα BZIP2, κυρίως σε σύστημα UNIX ή Linux. Χρησιμοποιείται για τη συμπίεση ενός μόνο αρχείου και δεν προορίζεται για την αρχειοθέτηση πολλών αρχείων. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Ένα αρχείο με επέκταση .cab ανήκει σε ένα αρχείο cabinet των Windows που ανήκει στην κατηγορία των αρχείων συστήματος. Είναι ένα αρχείο που αποθηκεύεται σε μορφή αρχείου αρχειοθέτησης στις εκδόσεις των Microsoft Windows που υποστηρίζουν αλγόριθμους συμπιεσμένων δεδομένων, όπως οι LZX, Quantum και ZIP. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Το Cpio είναι ένα γενικό βοηθητικό πρόγραμμα αρχειοθέτησης αρχείων και η σχετική του μορφή αρχείου. Εγκαθίσταται κυρίως σε λειτουργικά συστήματα υπολογιστών παρόμοια με το Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Ένα αρχείο GZ είναι ένα συμπιεσμένο αρχείο που δημιουργείται χρησιμοποιώντας τον τυπικό αλγόριθμο συμπίεσης gzip (GNU zip). Μπορεί να περιέχει πολλά συμπιεσμένα αρχεία, καταλόγους και στελέχη αρχείων. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Ένα αρχείο Gzip είναι ένα συμπιεσμένο αρχείο που δημιουργείται χρησιμοποιώντας τον τυπικό αλγόριθμο συμπίεσης gzip (GNU zip). Μπορεί να περιέχει πολλά συμπιεσμένα αρχεία, καταλόγους και στελέχη αρχείων. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Ένα αρχείο με επέκταση .lz είναι ένα συμπιεσμένο αρχείο αρχειοθέτησης που δημιουργήθηκε με το Lzip, το οποίο είναι ένα δωρεάν εργαλείο γραμμής εντολών για συμπίεση. Υποστηρίζει συνένωση για τη συμπίεση αρχείων υποστήριξης. Τα αρχεία LZ έχουν εφαρμογή τύπου πολυμέσων/lzip και υποστηρίζουν υψηλότερα ποσοστά συμπίεσης από το BZ2. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Ένα αρχείο με επέκταση .lzma είναι ένα συμπιεσμένο αρχείο αρχειοθέτησης που δημιουργήθηκε χρησιμοποιώντας τη μέθοδο συμπίεσης LZMA (Lempel-Ziv-Markov chain Algorithm). Αυτοί βρίσκονται/χρησιμοποιούνται κυρίως στο λειτουργικό σύστημα Unix και είναι παρόμοιοι με άλλους αλγόριθμους συμπίεσης όπως ο ZIP για την ελαχιστοποίηση του μεγέθους του αρχείου. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Τα αρχεία με επέκταση .rar είναι αρχεία αρχειοθέτησης που δημιουργούνται για την αποθήκευση πληροφοριών σε συμπιεσμένη ή κανονική μορφή. RAR, που σημαίνει μορφή αρχείου Roshal ARchive. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | Το 7z είναι μια μορφή αρχειοθέτησης για τη συμπίεση αρχείων και φακέλων με υψηλή αναλογία συμπίεσης. Βασίζεται στην αρχιτεκτονική ανοιχτού κώδικα που καθιστά δυνατή τη χρήση οποιωνδήποτε αλγορίθμων συμπίεσης και κρυπτογράφησης. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Τα αρχεία με επέκταση .tar είναι αρχεία που δημιουργούνται με βοηθητικό πρόγραμμα που βασίζεται σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. Πολλά αρχεία αποθηκεύονται σε ασυμπίεστη μορφή με την υποστήριξη της προσθήκης αρχείων καθώς και φακέλων στο αρχείο. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | Το XZ είναι μια συμπιεσμένη μορφή αρχείου που χρησιμοποιεί τον αλγόριθμο συμπίεσης LZMA2. Σχεδιάστηκε ως αντικατάσταση των δημοφιλών μορφών gzip και bzip2 και προσφέρει μια σειρά από πλεονεκτήματα σε σχέση με αυτά τα παλαιότερα πρότυπα. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Το αρχείο AZ είναι μια κατηγορία αρχείων που ανήκουν στα αρχεία συμπιεσμένων δεδομένων UNIX. Τα συμπιεσμένα αρχεία Unix είναι ο πιο δημοφιλής και ευρέως χρησιμοποιούμενος τύπος επέκτασης του αρχείου Z. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Ένα αρχείο με επέκταση .zip είναι ένα αρχείο που μπορεί να περιέχει ένα ή περισσότερα αρχεία ή καταλόγους. Το αρχείο μπορεί να έχει εφαρμογή συμπίεσης στα αρχεία που περιλαμβάνονται προκειμένου να μειωθεί το μέγεθος του αρχείου ZIP. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/compression/zip/) . |

### Δείτε επίσης

* class [FileType](../filetype)
* χώρος ονομάτων [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
