---
title: "FontFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει έγγραφα γραμματοσειράς."
type: docs
weight: 17
url: /el/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Ορίζει έγγραφα γραμματοσειράς.
Περιλαμβάνει τους ακόλουθους τύπους:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
Μάθετε περισσότερα για μορφότυπους γραμματοσειρών [εδώ](../https://wiki.fileformat.com/font).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Ttf](#Ttf) | Ένα αρχείο με επέκταση .ttf αντιπροσωπεύει αρχεία γραμματοσειρών βασισμένα στην τεχνολογία γραμματοσειρών TrueType specifications. |
|
|  | [Eot](#Eot) | Ένα αρχείο με επέκταση .eot είναι μια γραμματοσειρά OpenType που είναι ενσωματωμένη σε ένα έγγραφο. |
|
|  | [Otf](#Otf) | Ένα αρχείο με επέκταση .otf αναφέρεται στη μορφή γραμματοσειράς OpenType. |
|
|  | [Cff](#Cff) | Ένα αρχείο με επέκταση .cff είναι μια Compact Font Format και είναι επίσης γνωστό ως PostScript Type 1 ή CIDFont. |
|
|  | [Type1](#Type1) | Οι γραμματοσειρές Type 1 είναι μια παρωχημένη τεχνολογία της Adobe που χρησιμοποιήθηκε ευρέως σε λογισμικό επιτραπέζιας δημοσίευσης και εκτυπωτές που μπορούσαν να χρησιμοποιήσουν PostScript. |
|
|  | [Woff](#Woff) | Ένα αρχείο με επέκταση .woff είναι ένα αρχείο γραμματοσειράς web βασισμένο στο Web Open Font Format (WOFF). |
|
|  | [Woff2](#Woff2) | Ένα αρχείο με επέκταση .woff είναι ένα αρχείο γραμματοσειράς web βασισμένο στο Web Open Font Format (WOFF). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Κατασκευαστής σειριοποίησης


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


Ένα αρχείο με επέκταση .ttf αντιπροσωπεύει γραμματοσειρές βασισμένες στην τεχνολογία γραμματοσειρών TrueType. Σχεδιάστηκε αρχικά και κυκλοφόρησε από την Apple Computer, Inc για το Mac OS και αργότερα υιοθετήθηκε από τη Microsoft για το Windows OS. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


Ένα αρχείο με επέκταση .eot είναι μια γραμματοσειρά OpenType που είναι ενσωματωμένη σε ένα έγγραφο. Αυτές χρησιμοποιούνται κυρίως σε αρχεία web όπως μια ιστοσελίδα. Δημιουργήθηκε από τη Microsoft και υποστηρίζεται από προϊόντα της Microsoft, συμπεριλαμβανομένου του αρχείου παρουσίασης PowerPoint .pps. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


Ένα αρχείο με επέκταση .otf αναφέρεται στη μορφή γραμματοσειράς OpenType. Η μορφή γραμματοσειράς OTF είναι πιο επεκτάσιμη και επεκτείνει τις υπάρχουσες δυνατότητες των μορφών TTF για ψηφιακή τυπογραφία. Αναπτύχθηκε από τη Microsoft και την Adobe, το OTF συνδυάζει τις δυνατότητες των μορφών γραμματοσειρών PostScript και TrueType. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


Ένα αρχείο με επέκταση .cff είναι μια Compact Font Format και είναι επίσης γνωστό ως PostScript Type 1 ή CIDFont. Το CFF λειτουργεί ως κοντέινερ για την αποθήκευση πολλαπλών γραμματοσειρών μαζί σε μια ενιαία μονάδα που ονομάζεται FontSet. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


Οι γραμματοσειρές Type 1 είναι μια παρωχημένη τεχνολογία της Adobe που χρησιμοποιήθηκε ευρέως σε λογισμικό επιτραπέζιας δημοσίευσης και εκτυπωτές που μπορούσαν να χρησιμοποιήσουν PostScript. Αν και οι γραμματοσειρές Type 1 δεν υποστηρίζονται σε πολλές σύγχρονες πλατφόρμες, προγράμματα περιήγησης και κινητά λειτουργικά συστήματα, παραμένουν υποστηριζόμενες σε ορισμένα λειτουργικά συστήματα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


Ένα αρχείο με επέκταση .woff είναι ένα αρχείο γραμματοσειράς web βασισμένο στο Web Open Font Format (WOFF). Διαθέτει συμπιεσμένο κοντέινερ ειδικό για τη μορφή, βασισμένο είτε σε TrueType (.TTF) είτε σε OpenType (.OTT) τύπους γραμματοσειρών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


Ένα αρχείο με επέκταση .woff είναι ένα αρχείο γραμματοσειράς web βασισμένο στο Web Open Font Format (WOFF). Διαθέτει συμπιεσμένο κοντέινερ ειδικό για τη μορφή, βασισμένο είτε σε TrueType (.TTF) είτε σε OpenType (.OTT) τύπους γραμματοσειρών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](../https://docs.fileformat.com/font/woff/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές φόρτωσης για τον τύπο πηγαίου αρχείου


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Προετοιμάστηκαν προεπιλεγμένες επιλογές μετατροπής για τον τύπο αρχείου


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
