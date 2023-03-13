---
title: Converter
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Αρχικοποιεί νέα παρουσία τουConvertergroupdocs.conversion/converter τάξη.
type: docs
weight: 10
url: /el/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(Func<Stream> document)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*document* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| settings | Func`1 | Οι ρυθμίσεις του μετατροπέα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | Func`1 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | Func`1 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. |
| settings | Func`1 | Οι ρυθμίσεις του μετατροπέα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | Func`2 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. Ο τύπος του αρχείου προέλευσης |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | Func`2 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. Ο τύπος του αρχείου προέλευσης |
| settings | Func`1 | Οι ρυθμίσεις του μετατροπέα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το έγγραφο προέλευσης. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το έγγραφο προέλευσης. |
| settings | Func`1 | Οι ρυθμίσεις του μετατροπέα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το έγγραφο προέλευσης. |
| loadOptions | Func`1 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το έγγραφο προέλευσης. |
| loadOptions | Func`1 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. |
| settings | Func`1 | Οι ρυθμίσεις του μετατροπέα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το έγγραφο προέλευσης. |
| loadOptions | Func`2 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. Ο τύπος του αρχείου προέλευσης |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το έγγραφο προέλευσης. |
| loadOptions | Func`2 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. Ο τύπος του αρχείου προέλευσης |
| settings | Func`1 | Οι ρυθμίσεις του μετατροπέα. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο φόρτωσης και μετατροπής εγγράφων που είναι αποθηκευμένα στο FTP, στο Amazon S3 Storage, στο Windows Azure ή σε οποιοδήποτε άλλο χώρο αποθήκευσης τρίτου μέρους: [Φόρτωση εγγράφου από διαφορετικές πηγές](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Περισσότερα σχετικά με τις επιλογές φόρτωσης εγγράφων ανάλογα με τον τύπο αρχείου: [Φόρτωση επιλογών για διαφορετικούς τύπους εγγράφων](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Αρχικοποιεί νέα παρουσία του[`Converter`](../../converter) τάξη για ρευστή ρύθμιση μετατροπής.

```csharp
public Converter()
```

### Παρατηρήσεις

Δείγμα χρήσης ρέουσας μετατροπής:

```csharp
var converter = new Converter();
```

```csharp
converter
    .Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
converter
    .WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
converter
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
    .OnConversionCompleted((number, stream) => {})
    .Convert();
```

```csharp
converter.Load("").GetPossibleConversions();
converter.Load("").GetDocumentInfo();
converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### Δείτε επίσης

* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
