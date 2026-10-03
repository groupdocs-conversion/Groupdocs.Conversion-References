---
title: "WithOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίστε επιλογές φόρτωσης"
type: docs
weight: 10
url: /el/net/groupdocs.conversion.fluent/iconversionloadoptions/withoptions/
---
## WithOptions(LoadOptions) {#withoptions}

Ορίστε επιλογές φόρτωσης

```csharp
public IConversionSourceDocumentLoaded WithOptions(LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| loadOptions | LoadOptions | Επιλογές φόρτωσης |

### Δείτε επίσης

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;LoadContext, LoadOptions&gt;) {#withoptions_1}

Παρέχετε επιλογές φόρτωσης για το έγγραφο που φορτώνεται αυτή τη στιγμή

```csharp
public IConversionSourceDocumentLoaded WithOptions(
    Func<LoadContext, LoadOptions> loadOptionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| loadOptionsProvider | Func`2 | Πάροχος επιλογών φόρτωσης Το πλαίσιο επιλογών φόρτωσης |

### Δείτε επίσης

* interface [IConversionSourceDocumentLoaded](../../iconversionsourcedocumentloaded)
* class [LoadContext](../../../groupdocs.conversion/loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* interface [IConversionLoadOptions](../../iconversionloadoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
