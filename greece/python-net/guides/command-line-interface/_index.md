---
title: "Διεπαφή Γραμμής Εντολών"
linkTitle: "Command Line Interface"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Μετατρέψτε έγγραφα απευθείας από το τερματικό με το εργαλείο γραμμής εντολών groupdocs-conversion — δεν απαιτείται script Python. Εξετάστε έγγραφα, καταγράψτε τις υποστηριζόμενες μορφές και εφαρμόστε άδεια, όλα από το κέλυφος."
type: docs
url: /el/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


Η εγκατάσταση του πακέτου `groupdocs-conversion-net` τοποθετεί επίσης ένα script κονσόλας `groupdocs-conversion` στο `PATH` σας. Πρόκειται για μια ελαφριά επικάλυψη πάνω από το Python API, σχεδιασμένη για περιπτώσεις όπου η εκτέλεση ενός script Python είναι υπερβολική — αγωγοί κελύφους, κανόνες Make, βήματα CI και μοναδικές μετατροπές.

## Prerequisites

Το CLI περιλαμβάνεται στο πακέτο, οπότε δεν απαιτείται πρόσθετη εγκατάσταση. Βεβαιωθείτε ότι το `groupdocs-conversion-net` είναι εγκατεστημένο (δείτε τον [Quick Start Guide]()), στη συνέχεια επαληθεύστε ότι το script κονσόλας είναι διαθέσιμο:

```bash
groupdocs-conversion --version
```

Θα πρέπει να δείτε την έκδοση του πακέτου εκτυπωμένη, για παράδειγμα `groupdocs-conversion 26.9.0`.

Εάν η εντολή `groupdocs-conversion` δεν βρεθεί, ο φάκελος script του πακέτου μπορεί να μην βρίσκεται στο `PATH` σας. Μπορείτε πάντα να καλέσετε το CLI μέσω της μορφής του Python module: `python -m groupdocs.conversion`. Τα δύο είναι ισοδύναμα.

## Commands

Το CLI εκθέτει τέσσερις υποεντολές. Εκτελέστε `groupdocs-conversion --help` για την πλήρη λίστα σημαιών, ή `groupdocs-conversion <command> --help` για μια συγκεκριμένη υποεντολή.

### convert

Μετατρέψτε ένα έγγραφο σε άλλη μορφή. Η μορφή προορισμού προκύπτει από την επέκταση του αρχείου εξόδου· περάστε `--format` για να την παρακάμψετε.

```bash
# Η επέκταση επιλέγει τη μορφή προορισμού
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Παρακάμψτε τη μορφή όταν το όνομα εξόδου δεν περιέχει μια χρήσιμη επέκταση
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Μετατρέψτε μια μόνο σελίδα (αρίθμηση από 1) — χρήσιμο για raster στόχους
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Ανοίξτε μια πηγή προστατευμένη με κωδικό
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Επιλογή | Περιγραφή |
| :- | :- |
| `--format` | Διακριτικό μορφής προορισμού (παρακάμπτει την επέκταση εξόδου). |
| `--password` | Κωδικός πρόσβασης για ένα προστατευμένο πηγαίο έγγραφο. |
| `--page` | Πρώτη σελίδα για μετατροπή, με αρίθμηση από 1. |
| `--count` | Αριθμός σελίδων για μετατροπή. |

Σε περίπτωση επιτυχίας, η εντολή εκτυπώνει τη διαδρομή εξόδου και εξέρχεται με κωδικό `0`.

### info

Εκτυπώστε βασικές πληροφορίες για ένα έγγραφο — μορφή, μέγεθος, αριθμός σελίδων και ημερομηνία δημιουργίας όταν είναι διαθέσιμη.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Χρησιμοποιήστε `--password` για προστατευμένες πηγές.

### list-formats

Καταγράψτε κάθε μορφή προορισμού που μπορεί να δημιουργήσει η μηχανή για ένα συγκεκριμένο έγγραφο εισόδου, χωρισμένη σε κύριους και δευτερεύοντες στόχους.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Χρησιμοποιήστε `--password` για προστατευμένες πηγές.

### list-all-formats

Εκτυπώστε το πλήρες πίνακα μετατροπής από πηγή σε προορισμό που γνωρίζει η μηχανή — κάθε μορφή εισόδου και τους προορισμούς στους οποίους μπορεί να μετατραπεί.

```bash
groupdocs-conversion list-all-formats
```

Αυτή η εντολή δεν απαιτεί αρχείο εισόδου.

## Global options

Αυτές οι επιλογές ισχύουν για κάθε εντολή:

| Επιλογή | Περιγραφή |
| :- | :- |
| `--license PATH` | Εφαρμόστε ένα αρχείο άδειας πριν εκτελέσετε την εντολή. |
| `--version` | Εκτυπώστε την έκδοση του CLI και εξέρθετε. |
| `--help` | Εμφανίστε τη βοήθεια χρήσης και εξέρθετε. |

Εφαρμόστε μια άδεια εκ των προτέρων τοποθετώντας `--license` πριν από την υποεντολή:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

Το CLI επίσης σέβεται τη μεταβλητή περιβάλλοντος `GROUPDOCS_LIC_PATH` — εάν είναι ορισμένη, η άδεια εφαρμόζεται αυτόματα και μπορείτε να παραλείψετε το `--license`. Δείτε το θέμα [Licensing]() για λεπτομέρειες.

## Format tokens

`convert` αντιστοιχίζει την επέκταση εξόδου — ή την τιμή `--format`, σε πεζά — στις αντίστοιχες επιλογές μετατροπής και τύπο αρχείου. Τα υποστηριζόμενα διακριτικά είναι:

| Κατηγορία | Διακριτικά |
| :- | :- |
| PDF | `pdf` |
| Επεξεργασία κειμένου | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Φύλλο εργασίας | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Παρουσίαση | `ppt`, `pptx`, `pptm`, `odp` |
| Ιστός | `html`, `htm`, `mhtml` |
| Εικόνα | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| Ηλεκτρονικό βιβλίο | `epub`, `mobi`, `azw3` |

Ένα άγνωστο διακριτικό προκαλεί την έξοδο της εντολής με κωδικό `2` και εκτυπώνει τη λίστα των αποδεκτών διακριτικών.

## Exit codes

| Κώδικας | Σημασία |
| :- | :- |
| `0` | Επιτυχία. |
| `2` | Σφάλμα χρήστη — άγνωστο διακριτικό μορφής ή λείπει το αρχείο εισόδου. |
| `1` | Σφάλμα χρόνου εκτέλεσης — το υποκείμενο μήνυμα εξαίρεσης .NET εκτυπώνεται στο τυπικό σφάλμα. |

Αυτοί οι κώδικες καθιστούν το CLI εύκολο για διακλάδωση σε scripts κελύφους και pipelines CI.

## When to use the Python API instead

Το CLI καλύπτει τις κοινές περιπτώσεις μετατροπής ενός μόνο εγγράφου. Για οτιδήποτε πέρα από αυτό — κλήσεις ανά σελίδα, ροές στη μνήμη, υδατογράφημα, γραμματοσειρά ή επιλογές περιοχής κελιών, και ιεραρχίες πολλαπλών εγγράφων — χρησιμοποιήστε απευθείας το Python API. Παρέχει πιο πλούσια λειτουργικότητα από τις σημαίες του CLI. Δείτε τον [Developer Guide]() για το πλήρες σύνολο χαρακτηριστικών.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
