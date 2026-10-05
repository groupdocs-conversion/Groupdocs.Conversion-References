---
title: "Φόρτωση αρχείου με προστασία κωδικού"
linkTitle: "Load Password-Protected File"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ξεκλειδώστε και μετατρέψτε έγγραφα Word, Excel, PowerPoint και PDF με προστασία κωδικού, περνώντας μια παρουσίαση LoadOptions με το χαρακτηριστικό password στον κατασκευαστή Converter στο GroupDocs.Conversion for Python via .NET."
type: docs
url: /el/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


Με *GroupDocs.Conversion for Python via .NET* μπορείτε να φορτώνετε και να μετατρέπετε έγγραφα που είναι προστατευμένα με κωδικό. Αυτή η δυνατότητα είναι χρήσιμη όταν χρειάζεται να διαχειριστείτε έγγραφα που απαιτούν έλεγχο ταυτότητας για πρόσβαση στο περιεχόμενό τους.

Για να φορτώσετε και να μετατρέψετε ένα έγγραφο με προστασία κωδικού, ακολουθήστε τα βήματα που περιγράφονται στο παρακάτω παράδειγμα κώδικα:

{{< tabs "code-example">}}
{{< tab \"load_password_protected_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Ορίστε τη διαδρομή του αρχείου
    file_path = "./password-protected.docx"
    
    # Δημιουργήστε το load options και ορίστε τον κωδικό
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Καθορίστε τη ροή του αρχείου προέλευσης και το load options
    converter = Converter(file_path, wp_load_options)
    
    # Specify output file location and convert options
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Convert and save to output path
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab \"password-protected.docx\" >}}

`password-protected.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"password-protected.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

Σε περίπτωση που ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος, θα προκληθεί σφάλμα χρόνου εκτέλεσης. Το αναμενόμενο σφάλμα και το μήνυμα σφάλματος είναι ως εξής:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: Η διαδρομή αρχείου για το έγγραφο με προστασία κωδικού πρόσβασης καθορίζεται. Σε αυτό το παράδειγμα, υποτίθεται ότι το έγγραφο ονομάζεται `password-protected.docx`.

2. **Load Options**: Δημιουργείται μια παρουσία του [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/), και ορίζεται ο κωδικός πρόσβασης που απαιτείται για το άνοιγμα του εγγράφου.

3. **Converter Initialization**: Δημιουργείται μια παρουσία του [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) χρησιμοποιώντας τη διαδρομή αρχείου και τις επιλογές φόρτωσης που περιλαμβάνουν τον κωδικό πρόσβασης.

4. **Convert Options**: Δημιουργείται μια παρουσία του [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) για τη διαδικασία μετατροπής. Μπορείτε επίσης να ορίσετε τον κωδικό πρόσβασης εξόδου για το παραγόμενο PDF εάν απαιτείται.

4. **Conversion Execution**: Τέλος, η μέθοδος `convert` καλείται στην παρουσία του [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) για να μετατρέψει το έγγραφο με προστασία κωδικού πρόσβασης και να το αποθηκεύσει ως PDF.

### Conclusion

Αυτό το παράδειγμα δείχνει πώς να φορτώνετε και να μετατρέπετε αποδοτικά έγγραφα με προστασία κωδικού πρόσβασης χρησιμοποιώντας το GroupDocs.Conversion for Python API. Βεβαιωθείτε ότι αντικαθιστάτε τους κωδικούς πρόσβασης και τις διαδρομές αρχείων με τις πραγματικές τιμές σας πριν εκτελέσετε τον κώδικα.
