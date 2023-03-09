---
title: FontFileType
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Καθορίζει τα έγγραφα γραμματοσειράς Περιλαμβάνει τους ακόλουθους τύπους Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Μάθετε περισσότερα σχετικά με τις μορφές γραμματοσειράςεδώhttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /el/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Καθορίζει τα έγγραφα γραμματοσειράς Περιλαμβάνει τους ακόλουθους τύπους: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Μάθετε περισσότερα σχετικά με τις μορφές γραμματοσειράς[εδώ](https://docs.fileformat.com/font/) .

```csharp
public sealed class FontFileType : FileType
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [FontFileType](fontfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Ένα αρχείο με επέκταση .cff είναι μια μορφή συμπαγούς γραμματοσειράς και είναι επίσης γνωστό ως PostScript Type 1 ή CIDFont. Το CFF λειτουργεί ως κοντέινερ για την αποθήκευση πολλών γραμματοσειρών μαζί σε μια ενιαία μονάδα γνωστή ως FontSet. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Ένα αρχείο με επέκταση .eot είναι μια γραμματοσειρά OpenType που είναι ενσωματωμένη σε ένα έγγραφο. Αυτά χρησιμοποιούνται κυρίως σε αρχεία Ιστού, όπως μια ιστοσελίδα. Δημιουργήθηκε από τη Microsoft και υποστηρίζεται από τα προϊόντα της Microsoft, συμπεριλαμβανομένης της παρουσίασης PowerPoint αρχείου .pps. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Ένα αρχείο με επέκταση .otf αναφέρεται σε μορφή γραμματοσειράς OpenType. Η μορφή γραμματοσειράς OTF είναι πιο επεκτάσιμη και επεκτείνει τις υπάρχουσες δυνατότητες των μορφών TTF για ψηφιακή τυπογραφία. Αναπτύχθηκε από τη Microsoft και την Adobe, το OTF συνδυάζει τις δυνατότητες των μορφών γραμματοσειράς PostScript και TrueType. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Ένα αρχείο με επέκταση .ttf αντιπροσωπεύει αρχεία γραμματοσειρών που βασίζονται στην τεχνολογία γραμματοσειρών προδιαγραφών TrueType. Αρχικά σχεδιάστηκε και κυκλοφόρησε από την Apple Computer, Inc για Mac OS και αργότερα υιοθετήθηκε από τη Microsoft για Windows OS. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Οι γραμματοσειρές Τύπου 1 είναι μια καταργημένη τεχνολογία της Adobe, η οποία χρησιμοποιήθηκε ευρέως στο λογισμικό έκδοσης επιτραπέζιου υπολογιστή και σε εκτυπωτές που μπορούσαν να χρησιμοποιούν PostScript. Παρόλο που οι γραμματοσειρές τύπου 1 δεν υποστηρίζονται σε πολλές σύγχρονες πλατφόρμες, προγράμματα περιήγησης ιστού και λειτουργικά συστήματα για κινητά, αλλά εξακολουθούν να υποστηρίζονται σε ορισμένα λειτουργικά συστήματα. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Ένα αρχείο με επέκταση .woff είναι ένα αρχείο γραμματοσειράς ιστού που βασίζεται στη μορφή ανοιχτής γραμματοσειράς Web (WOFF). Διαθέτει συμπιεσμένο κοντέινερ για συγκεκριμένη μορφή που βασίζεται είτε σε τύπους γραμματοσειράς TrueType (.TTF) είτε OpenType (.OTT). Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Ένα αρχείο με επέκταση .woff είναι ένα αρχείο γραμματοσειράς ιστού που βασίζεται στη μορφή ανοιχτής γραμματοσειράς Web (WOFF). Διαθέτει συμπιεσμένο κοντέινερ για συγκεκριμένη μορφή που βασίζεται είτε σε τύπους γραμματοσειράς TrueType (.TTF) είτε OpenType (.OTT). Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/font/woff/) . |

### Δείτε επίσης

* class [FileType](../filetype)
* χώρος ονομάτων [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
