---
title: "FontFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει έγγραφα γραμματοσειρών Περιλαμβάνει τους ακόλουθους τύπους Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Μάθετε περισσότερα για τις μορφές γραμματοσειρών εδώhttps//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /el/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Ορίζει έγγραφα γραμματοσειρών Περιλαμβάνει τους ακόλουθους τύπους: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Μάθετε περισσότερα για τις μορφές γραμματοσειρών [εδώ](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [FontFileType](fontfiletype)() | Κατασκευαστής σειριοποίησης |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Ένα αρχείο με επέκταση .cff είναι μια Compact Font Format και είναι επίσης γνωστό ως PostScript Type 1 ή CIDFont. Το CFF λειτουργεί ως κοντέινερ για την αποθήκευση πολλαπλών γραμματοσειρών μαζί σε μια ενιαία μονάδα που ονομάζεται FontSet. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Ένα αρχείο με επέκταση .eot είναι μια γραμματοσειρά OpenType που είναι ενσωματωμένη σε ένα έγγραφο. Αυτές χρησιμοποιούνται κυρίως σε αρχεία ιστού όπως μια ιστοσελίδα. Δημιουργήθηκε από τη Microsoft και υποστηρίζεται από προϊόντα της Microsoft, συμπεριλαμβανομένου του PowerPoint παρουσίασης .pps. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Ένα αρχείο με επέκταση .otf αναφέρεται στη μορφή γραμματοσειράς OpenType. Η μορφή γραμματοσειράς OTF είναι πιο κλιμακώσιμη και επεκτείνει τις υπάρχουσες δυνατότητες των μορφών TTF για ψηφιακή τυπογραφία. Αναπτύχθηκε από τη Microsoft και την Adobe, το OTF συνδυάζει τις δυνατότητες των μορφών PostScript και TrueType. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Ένα αρχείο με επέκταση .ttf αντιπροσωπεύει αρχεία γραμματοσειρών βασισμένα στην τεχνολογία γραμματοσειρών προδιαγραφών TrueType. Σχεδιάστηκε αρχικά και κυκλοφόρησε από την Apple Computer, Inc για το Mac OS και αργότερα υιοθετήθηκε από τη Microsoft για το Windows OS. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Οι γραμματοσειρές Type 1 είναι μια παρωχημένη τεχνολογία της Adobe που χρησιμοποιήθηκε ευρέως στο λογισμικό επιτραπέζιας δημοσίευσης και στους εκτυπωτές που μπορούσαν να χρησιμοποιήσουν PostScript. Αν και οι γραμματοσειρές Type 1 δεν υποστηρίζονται σε πολλές σύγχρονες πλατφόρμες, προγράμματα περιήγησης και κινητά λειτουργικά συστήματα, εξακολουθούν να υποστηρίζονται σε ορισμένα λειτουργικά συστήματα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Ένα αρχείο με επέκταση .woff είναι ένα αρχείο γραμματοσειράς ιστού βασισμένο στο Web Open Font Format (WOFF). Διαθέτει συμπιεσμένο κοντέινερ ειδικό για τη μορφή, βασισμένο είτε σε TrueType (.TTF) είτε σε OpenType (.OTT) τύπους γραμματοσειρών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Ένα αρχείο με επέκταση .woff είναι ένα αρχείο γραμματοσειράς ιστού βασισμένο στο Web Open Font Format (WOFF). Διαθέτει συμπιεσμένο κοντέινερ ειδικό για τη μορφή, βασισμένο είτε σε TrueType (.TTF) είτε σε OpenType (.OTT) τύπους γραμματοσειρών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/font/woff/). |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
