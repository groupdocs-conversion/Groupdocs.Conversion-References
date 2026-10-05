---
title: "Επισκόπηση Χαρακτηριστικών"
linkTitle: "Features overview"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Κύρια χαρακτηριστικά του GroupDocs.Conversion για Python μέσω .NET — πάνω από 10.000 ζεύγος μορφών, επιλογή σελίδας, επιλογές φόρτωσης/μετατροπής, υδατογραφήματα, επιθεώρηση εγγράφων και ενσωμάτωση AI‑pipeline."
type: docs
url: /el/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

Το GroupDocs.Conversion για Python μέσω .NET μετατρέπει έγγραφα μεταξύ **10,000+ format pairs** — Microsoft Office, PDF, OpenDocument, εικόνες, CAD, email, αρχεία, eBooks, HTML, TeX και γλώσσες περιγραφής σελίδων. Εκτελείται εξ ολοκλήρου on‑premise, δεν απαιτεί εγκατάσταση Microsoft Office ή Adobe Acrobat, και διανέμεται ως προ‑συγκροτημένο wheel σε Windows, Linux και macOS.

Δείτε την πλήρη λίστα των [supported formats]() ή περιηγηθείτε στον [Developer Guide]() για παραδείγματα εκτέλεσης κάθε επιφάνειας API.

## File Conversion

Η βασική δυνατότητα είναι η μετατροπή οποιουδήποτε υποστηριζόμενου πηγαίου εγγράφου σε οποιαδήποτε υποστηριζόμενη μορφή προορισμού. Όλες οι μετατροπές είναι δυνατές χωρίς εγκατεστημένο Microsoft Office, LibreOffice ή Adobe Acrobat. Το GroupDocs.Conversion προσφέρει ένα ευέλικτο σύνολο επιλογών για προσαρμογή του pipeline.

### Convert specific document pages

Μετατρέψτε ολόκληρα έγγραφα, μεμονωμένες σελίδες ή περιοχές σελίδων. Χρησιμοποιήστε είτε μια ρητή λίστα `pages` είτε ένα εύρος `page_number` + `pages_count` στην κλάση [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/). Δείτε το [Convert a Document to Another Format]() για παραδείγματα εκτέλεσης.

### Per-page file output

Δημιουργήστε ένα αρχείο εξόδου ανά σελίδα — χρήσιμο για παρουσιάσεις, PDF πολλαπλών σελίδων και απόδοση εγγράφων σε εικόνες. Επαναλάβετε το χαρακτηριστικό `page_number` διατηρώντας `pages_count = 1`. Δείτε το [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

Όταν ένα αρχείο προέλευσης φτάνει ως ροή byte χωρίς όνομα αρχείου, το GroupDocs.Conversion εντοπίζει αυτόματα τη μορφή ελέγχοντας την κεφαλίδα της ροής. Δείτε το [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

Κάθε κλάση επιλογών φόρτωσης εκθέτει ρυθμίσεις ειδικές για τη μορφή:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

Ερωτήστε τη μηχανή για υποστηριζόμενες μορφές προορισμού πριν εκτελέσετε ένα pipeline — σε επίπεδο ολόκληρης βιβλιοθήκης, κατά επέκταση ή για συγκεκριμένο φορτωμένο έγγραφο. Δείτε το [Get Possible Conversions]() για τις τρεις υπερφορτώσεις.

### Watermark the converted document

Προσθέστε υδατογράφημα κειμένου κατά τη μετατροπή — ελέγξτε το χρώμα, το μέγεθος, την περιστροφή, τη διαφάνεια και τη θέση φόντου/προσκηνίου. Δείτε το [Add a Watermark to Converted Document]().

### Convert files inside a container

Ανοίξτε containers ZIP, RAR, 7Z, OST ή PST, μετατρέψτε τα περιεχόμενα και γράψτε ένα ενοποιημένο έγγραφο εξόδου με μία κλήση. Δείτε το [Convert Files Within Document Containers]().

## Document Information Extraction

Το GroupDocs.Conversion μπορεί να διαβάσει μεταδεδομένα από ένα πηγαίο έγγραφο χωρίς να το μετατρέψει — μορφή, αριθμός σελίδων ή διαφανειών, συγγραφέας, ημερομηνία δημιουργίας, διαστάσεις, πίνακας περιεχομένων και λεπτομέρειες ειδικές για τη μορφή. Δείτε το [Getting Document Information]() για όλες τις εννέα παραλλαγές:

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Ο Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) κατασκευαστής δέχεται τόσο διαδρομή αρχείου όσο και δυαδικό αντικείμενο τύπου file‑like, ώστε μπορείτε να φορτώνετε έγγραφα από:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

Η αποθήκευση στο σύννεφο (Amazon S3, Azure Blob Storage, Google Cloud Storage) λειτουργεί ανακτώντας byte σε έναν buffer `BytesIO` και περνώντας το στον κατασκευαστή του [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

## Logging and Diagnostics

Συνδέστε ένα [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) μέσω του [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) για να παρακολουθήσετε την αλυσίδα μετατροπής — επιλογή φορτωτή, έναρξη και ολοκλήρωση μετατροπής, καθώς και τυχόν προειδοποιήσεις που δημιουργεί η μηχανή. Δείτε το [Καταγραφή και Διαγνωστικά]().

## AI and LLM Integration

Το GroupDocs.Conversion έχει σχεδιαστεί ώστε να αποτελεί ένα κορυφαίο δομικό στοιχείο για αγωγούς εγγράφων AI. Το πακέτο pip `groupdocs-conversion-net` περιλαμβάνει ένα αρχείο `AGENTS.md` μέσα στο wheel, ώστε οι βοηθοί κώδικα AI να μπορούν να ανακαλύψουν αυτόματα την επιφάνεια του API, και το GroupDocs εκτελεί έναν δημόσιο [MCP server](https://docs.groupdocs.com/mcp) για αναζητήσεις τεκμηρίωσης κατά απαίτηση. Δείτε το [Ενσωμάτωση Agents και LLM]().

## On-Premise Deployment

Χωρίς κλήσεις στο σύννεφο, χωρίς εξερχόμενη κίνηση δικτύου, χωρίς εξαρτήσεις λογισμικού τρίτων εκτός από ό,τι παρέχει ήδη το λειτουργικό σύστημα. Το wheel είναι αυτόνομο στα Windows και περιλαμβάνει τις δικές του εγγενείς βιβλιοθήκες χρόνου εκτέλεσης σε Linux και macOS. Δείτε τις [Απαιτήσεις Συστήματος]().
