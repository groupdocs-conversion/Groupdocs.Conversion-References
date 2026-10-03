---
title: "MissingDependencyException"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Εξαίρεση GroupDocs που εκτοξεύεται όταν μια μετατροπή δεν μπορεί να εκτελεστεί επειδή ένα assembly από το οποίο εξαρτάται δεν υπάρχει στην έξοδο της εφαρμογής. Το έγγραφο δεν είναι υπεύθυνο."
type: docs
weight: 1030
url: /el/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

GroupDocs εξαίρεση που εκτοξεύεται όταν μια μετατροπή δεν μπορεί να εκτελεστεί επειδή μια συναρμολόγηση από την οποία εξαρτάται δεν υπάρχει στην έξοδο της εφαρμογής. Το έγγραφο δεν είναι υπεύθυνο.

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Προεπιλεγμένος κατασκευαστής |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Δημιουργεί μια παρουσία εξαίρεσης με ένα μήνυμα. |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Δημιουργεί ένα αντικείμενο εξαίρεσης με μήνυμα και διαδίδει την εσωτερική εξαίρεση |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Δημιουργεί ένα αντικείμενο εξαίρεσης ορίζοντας το assembly που δεν μπόρεσε να φορτωθεί |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | Το απλό όνομα του assembly που δεν μπόρεσε να φορτωθεί, ή null όταν δεν μπορεί να προσδιοριστεί. |

### Δείτε επίσης

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
