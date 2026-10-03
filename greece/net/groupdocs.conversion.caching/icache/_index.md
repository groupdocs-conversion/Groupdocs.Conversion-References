---
title: "ICache"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει τις μεθόδους που απαιτούνται για την αποθήκευση του αποδομένου εγγράφου και των πόρων του εγγράφου στην cache."
type: docs
weight: 20
url: /el/net/groupdocs.conversion.caching/icache/
---
## ICache interface

Ορίζει τις μεθόδους που απαιτούνται για την αποθήκευση του αποδομένου εγγράφου και των πόρων του εγγράφου στην cache.

```csharp
public interface ICache
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/icache/getkeys)(string) | Επιστρέφει όλα τα κλειδιά που ταιριάζουν με το φίλτρο. |
| [Set](../../groupdocs.conversion.caching/icache/set)(string, object) | Εισάγει μια καταχώρηση cache στην κρυφή μνήμη. |
| [TryGetValue](../../groupdocs.conversion.caching/icache/trygetvalue)(string, out object) | Λαμβάνει την καταχώρηση που σχετίζεται με αυτό το κλειδί εάν υπάρχει. |

### Δείτε επίσης

* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
