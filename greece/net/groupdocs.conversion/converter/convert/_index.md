---
title: Convert
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.
type: docs
weight: 20
url: /el/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής ειδικά για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. |
| documentCompleted | Action`2 | Ο εκπρόσωπος που λαμβάνει τη ροή εγγράφων μετατροπής. Η ροή περιεχομένου του αρχείουΤο όνομα του αρχείου |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής ειδικά για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. |
| convertOptionsProvider | Func`3 | Μετατροπή παρόχου επιλογών. Θα κληθεί για κάθε μετατροπή για να παρέχει συγκεκριμένες επιλογές μετατροπής στον επιθυμητό τύπο εγγράφου-στόχου. Το όνομα του αρχείουΟ τύπος του αρχείου |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. |
| documentCompleted | Action`2 | Ο εκπρόσωπος που λαμβάνει τη ροή εγγράφων μετατροπής. Η ροή περιεχομένου του αρχείουΤο όνομα του αρχείου |
| convertOptionsProvider | Func`3 | Μετατροπή παρόχου επιλογών. Θα κληθεί για κάθε μετατροπή για να παρέχει συγκεκριμένες επιλογές μετατροπής στον επιθυμητό τύπο εγγράφου-στόχου. Το όνομα του αρχείουΟ τύπος του αρχείου |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`2 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. Ο τύπος του αρχείου προέλευσης |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής ειδικά για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`2 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. Ο τύπος του αρχείου προέλευσης |
| documentCompleted | Action`2 | Ο εκπρόσωπος που λαμβάνει τη ροή εγγράφων μετατροπής. Η ροή περιεχομένου του αρχείουΤο όνομα του αρχείου |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής ειδικά για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`2 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. Ο τύπος του αρχείου προέλευσης |
| convertOptionsProvider | Func`3 | Μετατροπή παρόχου επιλογών. Θα κληθεί για κάθε μετατροπή για να παρέχει συγκεκριμένες επιλογές μετατροπής στον επιθυμητό τύπο εγγράφου-στόχου. Το όνομα του αρχείουΟ τύπος του αρχείου |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`2 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. Ο τύπος του αρχείου προέλευσης |
| documentCompleted | Action`2 | Ο εκπρόσωπος που λαμβάνει τη ροή εγγράφων μετατροπής. Η ροή περιεχομένου του αρχείουΤο όνομα του αρχείου |
| convertOptionsProvider | Func`3 | Μετατροπή παρόχου επιλογών. Θα κληθεί για κάθε μετατροπή για να παρέχει συγκεκριμένες επιλογές μετατροπής στον επιθυμητό τύπο εγγράφου-στόχου. Το όνομα του αρχείουΟ τύπος του αρχείου |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς το έγγραφο προέλευσης. |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής ειδικά για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`2 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. Αριθμός σελίδας |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής ειδικά για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`2 | Ο πληρεξούσιος που αποθηκεύει τη σελίδα εγγράφου που έχει μετατραπεί σε ροή. Αριθμός σελίδας |
| documentCompleted | Action`3 | Ο πληρεξούσιος που λαμβάνει τη ροή της σελίδας του εγγράφου μετατροπής. Αριθμός σελίδαςΗ ροή περιεχομένου του αρχείουΤο όνομα του αρχείου |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής ειδικά για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`2 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. Αριθμός σελίδας |
| convertOptionsProvider | Func`3 | Μετατροπή παρόχου επιλογών. Θα κληθεί για κάθε μετατροπή για να παρέχει συγκεκριμένες επιλογές μετατροπής στον επιθυμητό τύπο εγγράφου-στόχου. Το όνομα του αρχείουΟ τύπος του αρχείου |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`2 | Ο πληρεξούσιος που αποθηκεύει τη σελίδα εγγράφου που έχει μετατραπεί σε ροή. Αριθμός σελίδας |
| documentCompleted | Action`3 | Ο πληρεξούσιος που λαμβάνει τη ροή της σελίδας του εγγράφου μετατροπής. Αριθμός σελίδαςΗ ροή περιεχομένου του αρχείουΤο όνομα του αρχείου |
| convertOptionsProvider | Func`3 | Μετατροπή παρόχου επιλογών. Θα κληθεί για κάθε μετατροπή για να παρέχει συγκεκριμένες επιλογές μετατροπής στον επιθυμητό τύπο εγγράφου-στόχου. Το όνομα του αρχείουΟ τύπος του αρχείου |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`3 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. Αριθμός σελίδας |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής ειδικά για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`3 | Ο πληρεξούσιος που αποθηκεύει τη σελίδα εγγράφου που έχει μετατραπεί σε ροή. Αριθμός σελίδαςΤύπος αρχείου |
| documentCompleted | Action`3 | Ο πληρεξούσιος που λαμβάνει τη ροή της σελίδας του εγγράφου μετατροπής. Αριθμός σελίδαςΗ ροή περιεχομένου του αρχείουΤο όνομα του αρχείου |
| convertOptions | ConvertOptions | Οι επιλογές μετατροπής ειδικά για τον επιθυμητό τύπο αρχείου προορισμού. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`3 | Ο πληρεξούσιος που αποθηκεύει το έγγραφο που έχει μετατραπεί σε ροή. Αριθμός σελίδαςΤύπος αρχείου |
| convertOptionsProvider | Func`3 | Μετατροπή παρόχου επιλογών. Θα κληθεί για κάθε μετατροπή για να παρέχει συγκεκριμένες επιλογές μετατροπής στον επιθυμητό τύπο εγγράφου-στόχου. Το όνομα του αρχείουΟ τύπος του αρχείου |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`3 | Ο πληρεξούσιος που αποθηκεύει τη σελίδα εγγράφου που έχει μετατραπεί σε ροή. Αριθμός σελίδαςΤύπος αρχείου |
| documentCompleted | Action`3 | Ο πληρεξούσιος που λαμβάνει τη ροή της σελίδας του εγγράφου μετατροπής. Αριθμός σελίδαςΗ ροή περιεχομένου του αρχείουΤο όνομα του αρχείου |
| convertOptionsProvider | Func`3 | Μετατροπή παρόχου επιλογών. Θα κληθεί για κάθε μετατροπή για να παρέχει συγκεκριμένες επιλογές μετατροπής στον επιθυμητό τύπο εγγράφου-στόχου. Το όνομα του αρχείουΟ τύπος του αρχείου |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τα βασικά σενάρια μετατροπής εγγράφων: [Πώς να μετατρέψετε ένα έγγραφο σε 3 βήματα](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Περιπτώσεις χρήσης μετατροπών, σύνθετες ρυθμίσεις και προσαρμογές: [Μετατροπή εγγράφου με προηγμένες ρυθμίσεις](https://docs.groupdocs.com/display/conversionnet/Converting)

### Δείτε επίσης

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* χώρος ονομάτων [GroupDocs.Conversion](../../converter)
* συνέλευση [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
