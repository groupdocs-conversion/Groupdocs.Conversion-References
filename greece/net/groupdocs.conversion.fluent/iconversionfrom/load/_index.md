---
title: "Φόρτωση"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίστε το fileName του πηγαίου εγγράφου"
type: docs
weight: 10
url: /el/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

Ορίστε το fileName του πηγαίου εγγράφου

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Πηγαίο έγγραφο |

### Δείτε επίσης

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Ορίστε τον πίνακα πηγαίων εγγράφων

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String[] | Σύνολο πηγαίων εγγράφων |

### Δείτε επίσης

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Ορίστε τη ροή του πηγαίου εγγράφου

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Πάροχος ροής πηγαίου εγγράφου |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Εάν η επικύρωση των ρυθμίσεων του μετατροπέα αποτύχει, αυτή η εξαίρεση θα ριχτεί |

### Δείτε επίσης

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Ορίστε τον πίνακα ροών πηγαίων εγγράφων

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Πάροχος ροών πηγής εγγράφου |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Εάν η επικύρωση των ρυθμίσεων του μετατροπέα αποτύχει, αυτή η εξαίρεση θα ριχτεί |

### Δείτε επίσης

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
