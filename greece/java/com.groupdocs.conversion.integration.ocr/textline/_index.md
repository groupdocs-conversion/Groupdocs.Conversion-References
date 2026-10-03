---
title: "TextLine"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αναπαριστά το κείμενο που εξήχθη από μια εικόνα ως αποτέλεσμα της διαδικασίας αναγνώρισής της."
type: docs
weight: 12
url: /el/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Αντιπροσωπεύει κείμενο, εξαγόμενο από εικόνα ως αποτέλεσμα της διαδικασίας αναγνώρισής της.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Αρχικοποιεί ένα νέο στιγμιότυπο μιας γραμμής κειμένου, που εξήχθη από τη μηχανή OCR από μια εικόνα. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFragments()](#getFragments--) | Λαμβάνει έναν πίνακα τμημάτων κειμένου, όπως σύμβολα και λέξεις, που αναγνωρίστηκαν στη γραμμή. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Αρχικοποιεί ένα νέο στιγμιότυπο μιας γραμμής κειμένου, που εξήχθη από τη μηχανή OCR από μια εικόνα.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | τμήματα | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | αρχικό σύνολο τμημάτων κειμένου |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Λαμβάνει έναν πίνακα τμημάτων κειμένου, όπως σύμβολα και λέξεις, που αναγνωρίστηκαν στη γραμμή.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
