---
title: "AutoDetectRtlDirection"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Όταν είναι true, οι προεπιλεγμένες παράγραφοι και τμήματα κειμένου των οποίων το κείμενο είναι κυρίως δεξιά‑προς‑αριστερά θα έχουν τις σημαίες bidi διορθωμένες πριν από τη μετατροπή. Αυτό ταιριάζει με την ευρετική που εφαρμόζουν τα Microsoft Word και LibreOffice και διορθώνει την απόδοση εγγράφων Αραβικών/Εβραϊκών που παράγονται από δημιουργούς, κυρίως το Google Docs, τα οποία εκδίδουν OOXML χωρίς ltwbidi/gt και με ltwrtl wval0/gt σε τμήματα που περιέχουν μόνο σενάριο RTL. Ορίστε σε false για να διατηρήσετε την αυστηρή ερμηνεία OOXML του πηγαίου markup."
type: docs
weight: 20
url: /el/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

Όταν είναι true (προεπιλογή), οι παράγραφοι και τα runs των οποίων το κείμενο είναι κυρίως από δεξιά προς τα αριστερά θα έχουν τα bidi flags τους διορθωμένα πριν από τη μετατροπή. Αυτό ταιριάζει με την ευρετική που εφαρμόζουν τα Microsoft Word και LibreOffice και διορθώνει την απόδοση των εγγράφων Αραβικών/Εβραϊκών που παράγονται από δημιουργούς (ιδιαίτερα Google Docs) που εκδίδουν OOXML χωρίς &lt;w:bidi/&gt; και με &lt;w:rtl w:val=\"0\"/&gt; σε runs που περιέχουν μόνο RTL script. Ορίστε σε false για να διατηρήσετε την αυστηρή ερμηνεία του OOXML του πρωτοτύπου markup.

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### Δείτε επίσης

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
