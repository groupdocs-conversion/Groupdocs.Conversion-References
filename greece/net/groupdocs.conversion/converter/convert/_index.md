---
title: "Convert"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο."
type: docs
weight: 20
url: /el/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Ο αντιπρόσωπος που αποθηκεύει το μετατρεπόμενο έγγραφο σε μια ροή. |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής που είναι συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
| cancellationToken | CancellationToken | Το διακριτικό ακύρωσης. |

### Παρατηρήσεις

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής που είναι συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
| documentCompleted | Action`1 | Αντιπρόσωπος που λαμβάνει τη ροή του μετατρεπόμενου εγγράφου. Υπογραφή: `Action<ConvertedContext>`. Η παράμετρος [`ConvertedContext`](../../convertedcontext) περιέχει τη ροή του μετατρεπόμενου εγγράφου και τα μεταδεδομένα. |
| cancellationToken | CancellationToken | Το διακριτικό ακύρωσης. |

### Παρατηρήσεις

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Αντιπρόσωπος που παρέχει τη ροή για την αποθήκευση του μετατρεπόμενου εγγράφου. Υπογραφή: `Func<SaveContext, Stream>`. Η παράμετρος [`SaveContext`](../../savecontext) περιέχει πληροφορίες για τη λειτουργία αποθήκευσης. |
| convertOptionsProvider | Func`2 | Αντιπρόσωπος που παρέχει επιλογές μετατροπής. Υπογραφή: `Func<ConvertContext, ConvertOptions>`. Η παράμετρος [`ConvertContext`](../../convertcontext) περιέχει πληροφορίες για τη λειτουργία μετατροπής. |
| cancellationToken | CancellationToken | Το διακριτικό ακύρωσης. |

### Παρατηρήσεις

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Αντιπρόσωπος που παρέχει επιλογές μετατροπής. Υπογραφή: `Func<ConvertContext, ConvertOptions>`. Η παράμετρος [`ConvertContext`](../../convertcontext) περιέχει πληροφορίες για τη λειτουργία μετατροπής. |
| documentCompleted | Action`1 | Αντιπρόσωπος που λαμβάνει τη ροή του μετατρεπόμενου εγγράφου. Υπογραφή: `Action<ConvertedContext>`. Η παράμετρος [`ConvertedContext`](../../convertedcontext) περιέχει τη ροή του μετατρεπόμενου εγγράφου και τα μεταδεδομένα. |
| cancellationToken | CancellationToken | Το διακριτικό ακύρωσης. |

### Παρατηρήσεις

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Μετατρέπει το έγγραφο πηγής. Αποθηκεύει ολόκληρο το μετατρεπόμενο έγγραφο.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής που είναι συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
| cancellationToken | CancellationToken | Το διακριτικό ακύρωσης. |

### Παρατηρήσεις

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Μετατρέπει το έγγραφο πηγής. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Αντιπρόσωπος που παρέχει μια ροή για την αποθήκευση κάθε μετατρεπόμενης σελίδας. Υπογραφή: `Func<SavePageContext, Stream>`. Η παράμετρος [`SavePageContext`](../../savepagecontext) περιέχει τον αριθμό σελίδας και πληροφορίες εγγράφου. |
| convertOptionsProvider | Func`2 | Αντιπρόσωπος που παρέχει επιλογές μετατροπής. Υπογραφή: `Func<ConvertContext, ConvertOptions>`. Η παράμετρος [`ConvertContext`](../../convertcontext) περιέχει πληροφορίες για τη λειτουργία μετατροπής. |
| cancellationToken | CancellationToken | Το διακριτικό ακύρωσης. |

### Παρατηρήσεις

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Μετατρέπει το έγγραφο πηγής. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Αντιπρόσωπος που παρέχει μια ροή για την αποθήκευση κάθε μετατρεπόμενης σελίδας. Υπογραφή: `Func<SavePageContext, Stream>`. Η παράμετρος [`SavePageContext`](../../savepagecontext) περιέχει τον αριθμό σελίδας και πληροφορίες εγγράφου. |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής που είναι συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
| cancellationToken | CancellationToken | Το διακριτικό ακύρωσης. |

### Παρατηρήσεις

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Μετατρέπει το έγγραφο πηγής. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Αντιπρόσωπος που λαμβάνει κάθε μετατρεπόμενη σελίδα. Υπογραφή: `Action<ConvertedPageContext>`. Η παράμετρος [`ConvertedPageContext`](../../convertedpagecontext) περιέχει τον αριθμό σελίδας, τη ροή, το όνομα αρχείου προέλευσης και τον τύπο αρχείου προορισμού. |
| convertOptions | Action`1 | Οι επιλογές μετατροπής που είναι συγκεκριμένες για τον επιθυμητό τύπο αρχείου προορισμού. |
| cancellationToken | CancellationToken | Το διακριτικό ακύρωσης. |

### Παρατηρήσεις

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Μετατρέπει το έγγραφο πηγής. Αποθηκεύει το μετατρεπόμενο έγγραφο σελίδα προς σελίδα.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Αντιπρόσωπος που παρέχει επιλογές μετατροπής. Υπογραφή: `Func<ConvertContext, ConvertOptions>`. Η παράμετρος [`ConvertContext`](../../convertcontext) περιέχει πληροφορίες για τη λειτουργία μετατροπής. |
| documentCompleted | Action`1 | Αντιπρόσωπος που λαμβάνει κάθε μετατρεπόμενη σελίδα. Υπογραφή: `Action<ConvertedPageContext>`. Η παράμετρος [`ConvertedPageContext`](../../convertedpagecontext) περιέχει τον αριθμό σελίδας, τη ροή, το όνομα αρχείου προέλευσης και τον τύπο αρχείου προορισμού. |
| cancellationToken | CancellationToken | Το διακριτικό ακύρωσης. |

### Παρατηρήσεις

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
