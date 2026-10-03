---
title: "LayoutNames"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Καθορίζει ποια διατάξεις CAD θα μετατραπούν"
type: docs
weight: 70
url: /el/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

Καθορίζει ποια διατάξεις CAD θα μετατραπούν

```csharp
public string[] LayoutNames { get; set; }
```

### Παρατηρήσεις

Δεν τηρείται κατά τη μετατροπή σε PDF/UA-1. Αυτός ο προορισμός αποδίδει το σχέδιο ως μία ενιαία ετικετοποιημένη σελίδα, η οποία δεν μπορεί να περιέχει ένα φύλλο ανά επιλεγμένη διάταξη, έτσι όλο το σχέδιο μετατρέπεται αντί αυτού και τίποτα εδώ δεν εφαρμόζεται. Κάθε άλλος προορισμός, συμπεριλαμβανομένου του PDF, τηρεί την επιλογή. Σε αυτούς τους προορισμούς, τα ονόματα ταιριάζουν ακριβώς με τις διατάξεις που περιέχει το σχέδιο, έτσι ένα όνομα που διαφέρει μόνο σε πεζά/κεφαλαία θεωρείται διαφορετικό. Ένα όνομα που δεν ταιριάζει με τίποτα απορρίπτεται και κοστίζει στον καλούντα μόνο εκείνο το φύλλο· μια λίστα στην οποία τίποτα δεν ταιριάζει αποτυγχάνει τη μετατροπή με ένα [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) που ονομάζει τα ονόματα που λείπουν και τις διατάξεις που το σχέδιο περιέχει, αντί να αποδίδει φύλλα που ο καλών δεν ζήτησε. Ένα σχέδιο που δεν περιέχει καθόλου διατάξεις εξαιρείται: δεν υπάρχει τίποτα για το όνομα να ταιριάζει, οπότε κανένα δεν απορρίπτεται.

### Δείτε επίσης

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
