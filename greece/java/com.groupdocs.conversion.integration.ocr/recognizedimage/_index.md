---
title: "RecognizedImage"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αναπαριστά το κείμενο που εξήχθη από μια εικόνα ως αποτέλεσμα της διαδικασίας αναγνώρισής της."
type: docs
weight: 10
url: /el/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Αντιπροσωπεύει κείμενο, εξαγόμενο από εικόνα ως αποτέλεσμα της διαδικασίας αναγνώρισής της.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης, χρησιμοποιώντας ένα σύνολο αναγνωρισμένων γραμμών. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [EMPTY](#EMPTY) | Κενή αναγνωρισμένη εικόνα |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getLines()](#getLines--) | Λαμβάνει γραμμές κειμένου, με τα τμήματά τους, που αναγνωρίστηκαν εντός του εγγράφου. |
|
|  | [getText()](#getText--) | Λαμβάνει το κειμενικό ισοδύναμο του δομημένου κειμένου |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης, χρησιμοποιώντας ένα σύνολο αναγνωρισμένων γραμμών.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | γραμμές | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | ένα IEnumerable (π.χ. λίστα ή πίνακας) των αναγνωρισμένων γραμμών |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Κενή αναγνωρισμένη εικόνα


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Λαμβάνει γραμμές κειμένου, με τα τμήματά τους, που αναγνωρίστηκαν εντός του εγγράφου.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Λαμβάνει το κειμενικό ισοδύναμο του δομημένου κειμένου


**Returns:**
java.lang.String
