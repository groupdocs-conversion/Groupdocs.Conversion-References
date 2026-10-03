---
title: "TextFragment"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αντιπροσωπεύει ένα μέρος του αναγνωρισμένου κειμένου, λέξης, συμβόλου κ.λπ. που εξάγεται από τη μηχανή OCR."
type: docs
weight: 11
url: /el/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Αντιπροσωπεύει μέρος του αναγνωρισμένου κειμένου (λέξη, σύμβολο κ.λπ.), εξαγόμενο από τη μηχανή OCR.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Αρχικοποιεί ένα νέο στιγμιότυπο του αναγνωρισμένου τμήματος κειμένου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getText()](#getText--) | Λαμβάνει το κειμενικό περιεχόμενο του αναγνωρισμένου τμήματος κειμένου. |
|
|  | [getRectangle()](#getRectangle--) | Λαμβάνει ένα περιοριστικό ορθογώνιο του αναγνωρισμένου τμήματος κειμένου. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Αρχικοποιεί ένα νέο στιγμιότυπο του αναγνωρισμένου τμήματος κειμένου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | text | java.lang.String | κειμενικό περιεχόμενο του αναγνωρισμένου τμήματος κειμένου |
|
|  | ορθογώνιο | java.awt.Rectangle | περιοριστικό ορθογώνιο του αναγνωρισμένου τμήματος κειμένου |
|

### getText() {#getText--}
```
public String getText()
```


Λαμβάνει το κειμενικό περιεχόμενο του αναγνωρισμένου τμήματος κειμένου.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Λαμβάνει ένα περιοριστικό ορθογώνιο του αναγνωρισμένου τμήματος κειμένου.


**Returns:**
[Rectangle](../../java.awt/rectangle)
