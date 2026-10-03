---
title: "Converter"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Αρχικοποιεί νέα παρουσία της κλάσης Convertergroupdocs.conversion/converter."
type: docs
weight: 10
url: /el/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *sourceStreamProvider* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| settings | Func`1 | Οι ρυθμίσεις του Converter. |

### Παρατηρήσεις

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | Func`2 | Αντιπρόσωπος που παρέχει επιλογές φόρτωσης για το έγγραφο. Υπογραφή: `Func<LoadContext, LoadOptions>`. Η παράμετρος [`LoadContext`](../../loadcontext) περιέχει πληροφορίες σχετικά με το έγγραφο που φορτώνεται. |
| settings | Func`1 | Οι ρυθμίσεις του Converter. |

### Παρατηρήσεις

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter) με ρητά γεγονότα μετατροπής.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | Func`2 | Αντιπρόσωπος που παρέχει επιλογές φόρτωσης για το έγγραφο. |
| settings | Func`1 | Οι ρυθμίσεις του Converter. |
| events | Func`1 | Αντιπρόσωπος που παρέχει συγκεντρωμένα [`ConversionEvents`](../../conversionevents) καταχωρημένα για τη διάρκεια ζωής του μετατροπέα. |

### Δείτε επίσης

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter) με ρητά γεγονότα μετατροπής.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| settings | Func`1 | Οι ρυθμίσεις του Converter. |
| events | Func`1 | Αντιπρόσωπος που παρέχει συγκεντρωμένα [`ConversionEvents`](../../conversionevents) καταχωρημένα για τη διάρκεια ζωής του μετατροπέα. |

### Δείτε επίσης

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter).

```csharp
public Converter(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |

### Παρατηρήσεις

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| settings | Func`1 | Οι ρυθμίσεις του Converter. |

### Παρατηρήσεις

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| loadOptions | Func`2 | Αντιπρόσωπος που παρέχει επιλογές φόρτωσης για το έγγραφο. Υπογραφή: `Func<LoadContext, LoadOptions>`. Η παράμετρος [`LoadContext`](../../loadcontext) περιέχει πληροφορίες σχετικά με το έγγραφο που φορτώνεται. |
| settings | Func`1 | Οι ρυθμίσεις του Converter. |

### Παρατηρήσεις

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter) με ρητά γεγονότα μετατροπής.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| loadOptions | Func`2 | Αντιπρόσωπος που παρέχει επιλογές φόρτωσης για το έγγραφο. |
| settings | Func`1 | Οι ρυθμίσεις του Converter. |
| events | Func`1 | Αντιπρόσωπος που παρέχει συγκεντρωμένα [`ConversionEvents`](../../conversionevents) καταχωρημένα για τη διάρκεια ζωής του μετατροπέα. |

### Δείτε επίσης

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Αρχικοποιεί νέα παρουσία της κλάσης [`Converter`](../../converter) με ρητά γεγονότα μετατροπής.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το πηγαίο έγγραφο. |
| settings | Func`1 | Οι ρυθμίσεις του Converter. |
| events | Func`1 | Αντιπρόσωπος που παρέχει συγκεντρωμένα [`ConversionEvents`](../../conversionevents) καταχωρημένα για τη διάρκεια ζωής του μετατροπέα. |

### Δείτε επίσης

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
