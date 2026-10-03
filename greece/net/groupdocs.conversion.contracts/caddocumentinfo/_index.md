---
title: "CadDocumentInfo"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Περιέχει μεταδεδομένα εγγράφου Cad"
type: docs
weight: 110
url: /el/net/groupdocs.conversion.contracts/caddocumentinfo/
---
## CadDocumentInfo class

Περιέχει μεταδεδομένα εγγράφου Cad

```csharp
public class CadDocumentInfo : DocumentInfo
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CreationDate](../../groupdocs.conversion.contracts/documentinfo/creationdate) { get; } | Υλοποιεί [`CreationDate`](../idocumentinfo/creationdate) |
| [Format](../../groupdocs.conversion.contracts/documentinfo/format) { get; } | Υλοποιεί [`Format`](../idocumentinfo/format) |
| [Height](../../groupdocs.conversion.contracts/caddocumentinfo/height) { get; } | Ύψος |
| [Item](../../groupdocs.conversion.contracts/documentinfo/item) { get; } | Υλοποιεί [`Item`](../idocumentinfo/item) |
| [Layers](../../groupdocs.conversion.contracts/caddocumentinfo/layers) { get; } | Στρώματα στο έγγραφο |
| [Layouts](../../groupdocs.conversion.contracts/caddocumentinfo/layouts) { get; } | Διατάξεις στο έγγραφο |
| [PagesCount](../../groupdocs.conversion.contracts/documentinfo/pagescount) { get; } | Υλοποιεί [`PagesCount`](../idocumentinfo/pagescount) |
| [PropertyNames](../../groupdocs.conversion.contracts/documentinfo/propertynames) { get; } | Υλοποιεί [`PropertyNames`](../idocumentinfo/propertynames) |
| [Size](../../groupdocs.conversion.contracts/documentinfo/size) { get; } | Υλοποιεί [`Size`](../idocumentinfo/size) |
| [Width](../../groupdocs.conversion.contracts/caddocumentinfo/width) { get; } | Πλάτος |

### Παρατηρήσεις

[`PagesCount`](../documentinfo/pagescount) counts the sheets the drawing offers under the load options it was read with. Without explicit [`LayoutNames`](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) those sheets are model space, which is always plottable and therefore always a sheet, plus every paper-space layout whose stored page setup has a positive width and height, narrowed by [`LayoutScope`](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope). Explicit layout names win outright instead: the sheets are then the supplied names the drawing carries, matched ordinally, with neither the scope nor the page setup screening them. For a DWF the published page set is reported. The one count below one is zero, reported when the requested scope matches no sheet of a drawing that offers one: the metadata still describes the drawing, and zero says the scope selects nothing rather than failing the caller who asked what the drawing holds. A conversion under those same load options does fail. The count is therefore not the size of [`Layouts`](./layouts), which lists every plot configuration the drawing carries including those no sheet can be published from, and it does not predict how many pages a particular conversion emits.

### Δείτε επίσης

* class [DocumentInfo](../documentinfo)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
