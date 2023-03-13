---
title: Converter
second_title: GroupDocs.Conversion για Αναφορά API .NET
description: Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία μετατροπής εγγράφων.
type: docs
weight: 730
url: /el/net/groupdocs.conversion/converter/
---
## Converter class

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία μετατροπής εγγράφων.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Converter](converter#constructor)() | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη για ρευστή ρύθμιση μετατροπής. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_7)(string) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Αρχικοποιεί νέα παρουσία του[`Converter`](../converter) τάξη. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει το έγγραφο που έχει μετατραπεί σελίδα προς σελίδα. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Μετατρέπει το έγγραφο προέλευσης. Αποθηκεύει ολόκληρο το έγγραφο που έχει μετατραπεί. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Απελευθερώνει πόρους. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Λαμβάνει πληροφορίες εγγράφου πηγής - πλήθος σελίδων και άλλες ιδιότητες εγγράφου ειδικά για τον τύπο αρχείου. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Λαμβάνει πιθανές μετατροπές για το έγγραφο προέλευσης. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Διαμόρφωση ροής εγγράφου πηγής |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Διαμόρφωση συνόλου ροών εγγράφων πηγής |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Διαμόρφωση εγγράφου πηγής για μετατροπή |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Διαμόρφωση συνόλου εγγράφων πηγής |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Διαμόρφωση ρυθμίσεων μετατροπής |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Λαμβάνει όλες τις υποστηριζόμενες μετατροπές |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Λαμβάνει υποστηριζόμενες μετατροπές για την παρεχόμενη επέκταση |

### Δείτε επίσης

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* χώρος ονομάτων [GroupDocs.Conversion](../../groupdocs.conversion)
* συνέλευση [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
