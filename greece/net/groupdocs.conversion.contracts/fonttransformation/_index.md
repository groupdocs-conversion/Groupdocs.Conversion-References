---
title: "FontTransformation"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Περιγράφει τη διαμόρφωση μετασχηματισμού γραμματοσειράς, συμπεριλαμβανομένων των χαρακτηριστικών γραμματοσειράς. Οι μετασχηματισμοί γραμματοσειράς εφαρμόζονται μετά τη φόρτωση του εγγράφου και την αντικατάσταση γραμματοσειράς."
type: docs
weight: 260
url: /el/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

Περιγράφει τη διαμόρφωση μετασχηματισμού γραμματοσειράς, συμπεριλαμβανομένων των χαρακτηριστικών γραμματοσειράς. Οι μετασχηματισμοί γραμματοσειράς εφαρμόζονται μετά τη φόρτωση του εγγράφου και την αντικατάσταση γραμματοσειράς.

```csharp
public class FontTransformation : ValueObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | Όταν είναι true, ταιριάζει με οποιοδήποτε μέγεθος γραμματοσειράς για το αρχικό όνομα γραμματοσειράς. Όταν είναι false, ταιριάζει με το ακριβές μέγεθος γραμματοσειράς που καθορίζεται στο OriginalFont. |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | Όταν είναι true, ταιριάζει με οποιοδήποτε στυλ γραμματοσειράς (bold, italic, underline) για την αρχική γραμματοσειρά. Όταν είναι false, ταιριάζει με το ακριβές στυλ γραμματοσειράς που καθορίζεται στο OriginalFont. |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | Η αρχική προδιαγραφή γραμματοσειράς για αντιστοίχιση και αντικατάσταση. |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | Η προδιαγραφή αντικατάστασης γραμματοσειράς. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | Δημιουργεί μια μετατροπή γραμματοσειράς με ακριβή αντιστοίχιση γραμματοσειράς (το μέγεθος και το στυλ πρέπει να ταιριάζουν). |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | Δημιουργεί μια μετατροπή γραμματοσειράς μόνο με βάση το όνομα, ταιριάζοντας με οποιοδήποτε μέγεθος και στυλ. Η γραμματοσειρά αντικατάστασης θα διατηρήσει το μέγεθος και το στυλ της αρχικής γραμματοσειράς. |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | Δημιουργεί μια μετατροπή γραμματοσειράς με ευέλικτες επιλογές αντιστοίχισης. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |

### Δείτε επίσης

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
