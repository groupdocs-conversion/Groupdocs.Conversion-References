---
title: "WithOptions"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει επιλογές μετατροπής για τη διαδικασία μετατροπής."
type: docs
weight: 10
url: /el/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Ορίζει επιλογές μετατροπής για τη διαδικασία μετατροπής.

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| convertOptions | ConvertOptions | Επιλογές μετατροπής. |

### Τιμή επιστροφής

Στάδιο χειριστών για τη συνέχιση της δημιουργίας μετατροπής.

### Δείτε επίσης

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Ορίζει επιλογές μετατροπής χρησιμοποιώντας μια συνάρτηση παρόχου.

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| optionsProvider | Func`2 | Μια συνάρτηση που παρέχει επιλογές μετατροπής βάσει του πλαισίου μετατροπής. |

### Τιμή επιστροφής

Στάδιο χειριστών για τη συνέχιση της δημιουργίας μετατροπής.

### Δείτε επίσης

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
