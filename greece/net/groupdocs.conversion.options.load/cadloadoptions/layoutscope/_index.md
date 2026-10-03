---
title: "LayoutScope"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Λαμβάνει ή ορίζει ποιοι χώροι σχεδίου μετατρέπονται. Η προεπιλογή είναι Bothgroupdocs.conversion.options.load/cadlayoutscope/both, που δεν περιορίζει τη μετατροπή. Αγνοείται όταν παρέχονται LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames, επειδή τα ρητά ονόματα διατάξεων πάντα προτιμώνται. Μια τιμή null αντιμετωπίζεται ως Bothgroupdocs.conversion.options.load/cadlayoutscope/both."
type: docs
weight: 80
url: /el/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

Λαμβάνει ή ορίζει ποιοι χώροι σχεδίου μετατρέπονται. Η προεπιλογή είναι [`Both`](../../cadlayoutscope/both), που δεν περιορίζει τη μετατροπή. Αγνοείται όταν παρέχεται [`LayoutNames`](../layoutnames), επειδή τα ρητά ονόματα διατάξεων πάντα προτιμώνται. Μια τιμή `null` αντιμετωπίζεται ως [`Both`](../../cadlayoutscope/both).

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### Παρατηρήσεις

Ένα πεδίο που δεν επιλέγει κανένα από τα φύλλα που προσφέρει ένα σχέδιο αποτυγχάνει τη μετατροπή με ένα [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) που ονομάζει το πεδίο και τα φύλλα που υπάρχουν, αντί να αποδίδει τους χώρους που εξαιρέθηκαν από το πεδίο. Ένα σχέδιο που δεν προσφέρει κανένα φύλλο παραμένει αμετάβλητο και εξακολουθεί να μετατρέπεται ως μία ενιαία μονάδα. Δεν τηρείται κατά τη μετατροπή σε PDF/UA-1, για τον λόγο που αναφέρεται στο [`LayoutNames`](../layoutnames).

### Δείτε επίσης

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
