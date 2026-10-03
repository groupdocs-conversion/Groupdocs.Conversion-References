---
title: "EmailFileType"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει μορφές αρχείων Email που χρησιμοποιούνται από εφαρμογές email για την αποθήκευση των διαφόρων δεδομένων τους, συμπεριλαμβανομένων των μηνυμάτων email, συνημμένων, φακέλων, βιβλίων διευθύνσεων κ.λπ."
type: docs
weight: 15
url: /el/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Ορίζει μορφές αρχείων Email που χρησιμοποιούνται από εφαρμογές email για την αποθήκευση των διαφόρων δεδομένων τους, συμπεριλαμβανομένων των μηνυμάτων email, συνημμένων, φακέλων, βιβλίων διευθύνσεων κ.λπ.
Περιλαμβάνει τους ακόλουθους τύπους αρχείων:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
Μάθετε περισσότερα για τις μορφές Email [εδώ](../https://wiki.fileformat.com/email).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | Κατασκευαστής σειριοποίησης |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Msg](#Msg) | Το MSG είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, ραντεβού ή άλλων εργασιών. |
|
|  | [Eml](#Eml) | Η μορφή αρχείου EML αντιπροσωπεύει μηνύματα email που αποθηκεύονται χρησιμοποιώντας το Outlook και άλλες σχετικές εφαρμογές. |
|
|  | [Emlx](#Emlx) | Η μορφή αρχείου EMLX υλοποιείται και αναπτύσσεται από την Apple. |
|
|  | [Vcf](#Vcf) | Το VCF (Virtual Card Format) ή vCard είναι μια ψηφιακή μορφή αρχείου για την αποθήκευση πληροφοριών επαφών. |
|
|  | [Mbox](#Mbox) | Η μορφή αρχείου MBox είναι ένας γενικός όρος που αντιπροσωπεύει ένα κοντέινερ για τη συλλογή ηλεκτρονικών μηνυμάτων. |
|
|  | [Pst](#Pst) | Αρχεία με επέκταση .PST αντιπροσωπεύουν τα Outlook Personal Storage Files (επίσης γνωστά ως Personal Storage Table) που αποθηκεύουν ποικίλες πληροφορίες χρήστη. |
|
|  | [Ost](#Ost) | Τα OST ή Offline Storage Files αντιπροσωπεύουν τα δεδομένα του γραμματοκιβωτίου του χρήστη σε offline λειτουργία στον τοπικό υπολογιστή κατά την εγγραφή στον Exchange Server χρησιμοποιώντας το Microsoft Outlook. |
|
|  | [Olm](#Olm) | Ένα αρχείο με επέκταση .olm είναι ένα αρχείο Microsoft Outlook για το λειτουργικό σύστημα Mac. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Κατασκευαστής σειριοποίησης


### Msg {#Msg}
```
public static final EmailFileType Msg
```


Το MSG είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, ραντεβού ή άλλων εργασιών.
Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


Το μορφότυπο αρχείου EML αντιπροσωπεύει μηνύματα ηλεκτρονικού ταχυδρομείου που αποθηκεύονται χρησιμοποιώντας το Outlook και άλλες σχετικές εφαρμογές. Σχεδόν όλοι οι πελάτες ηλεκτρονικού ταχυδρομείου υποστηρίζουν αυτό το μορφότυπο για τη συμμόρφωσή του με το πρότυπο RFC-822 Internet Message Format Standard.
Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


Το μορφότυπο αρχείου EMLX υλοποιείται και αναπτύσσεται από την Apple. Η εφαρμογή Apple Mail χρησιμοποιεί το μορφότυπο αρχείου EMLX για την εξαγωγή των email.
Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


Το VCF (Virtual Card Format) ή vCard είναι ένα ψηφιακό μορφότυπο αρχείου για την αποθήκευση πληροφοριών επαφών. Το μορφότυπο αυτό χρησιμοποιείται ευρέως για ανταλλαγή δεδομένων μεταξύ δημοφιλών εφαρμογών ανταλλαγής πληροφοριών.
Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


Το μορφότυπο αρχείου MBox είναι ένας γενικός όρος που αντιπροσωπεύει ένα δοχείο για τη συλλογή ηλεκτρονικών μηνυμάτων. Τα μηνύματα αποθηκεύονται μέσα στο δοχείο μαζί με τα συνημμένα τους.
Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


Αρχεία με επέκταση .PST αντιπροσωπεύουν τα Outlook Personal Storage Files (επίσης γνωστά ως Personal Storage Table) που αποθηκεύουν διάφορες πληροφορίες χρήστη. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


Τα OST ή Offline Storage Files αντιπροσωπεύουν τα δεδομένα του γραμματοκιβωτίου του χρήστη σε offline λειτουργία στον τοπικό υπολογιστή κατά την εγγραφή στον Exchange Server χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


Ένα αρχείο με επέκταση .olm είναι ένα αρχείο Microsoft Outlook για το λειτουργικό σύστημα Mac. Ένα αρχείο OLM αποθηκεύει μηνύματα ηλεκτρονικού ταχυδρομείου, ημερολόγια, δεδομένα ημερολογίου και άλλους τύπους δεδομένων εφαρμογών. Αυτά είναι παρόμοια με τα αρχεία PST που χρησιμοποιούνται από το Outlook σε λειτουργικό σύστημα Windows. Ωστόσο, τα αρχεία OLM που δημιουργήθηκαν από το Outlook για Mac δεν μπορούν\\u2019t να ανοιχτούν στο Outlook για Windows. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](../https://wiki.fileformat.com/email/olm).


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
