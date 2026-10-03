---
title: "ConvertTo"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Αποθηκεύστε το μετατρεπόμενο έγγραφο ως αρχείο"
type: docs
weight: 20
url: /el/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

Αποθηκεύστε το μετατρεπόμενο έγγραφο ως αρχείο

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Μετατρεπόμενο έγγραφο |

### Τιμή επιστροφής

Επιλογές ή διεπαφή ρύθμισης χειριστή για τη συνέχιση της δημιουργίας μετατροπής

### Δείτε επίσης

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

Αποθηκεύστε το μετατρεπόμενο έγγραφο ως ροή

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Πάροχος ροής μετατρεπόμενου εγγράφου Το πλαίσιο αποθήκευσης |

### Τιμή επιστροφής

Επιλογές ή διεπαφή ρύθμισης χειριστή για τη συνέχιση της δημιουργίας μετατροπής

### Δείτε επίσης

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
