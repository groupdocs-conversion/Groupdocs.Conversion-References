---
title: "WithEvents"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Παραλλαγή Entrystage της αλυσίδας fluent που ξεκινά με χειριστές γεγονότων κύκλου ζωής μετατροπής. Καθίσταται στο ίδιο στάδιο εισόδου με το WithSettingsgroupdocs.conversion/fluentconverter/withsettings και η προκύπτουσα ConversionEventsgroupdocs.conversion/conversionevents σακούλα ενεργοποιείται σε κάθε εκτέλεση μετατροπής από τον μετατροπέα."
type: docs
weight: 20
url: /el/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

Παραλλαγή entry-stage της αλυσίδας fluent που ξεκινά με χειριστές γεγονότων κύκλου ζωής μετατροπής. Καθίσταται στο ίδιο στάδιο εισόδου με το [`WithSettings`](../withsettings), και η προκύπτουσα σακούλα [`ConversionEvents`](../../conversionevents) ενεργοποιείται σε κάθε εκτέλεση μετατροπής από τον μετατροπέα.

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| configure | Action`1 | Δράση που τροποποιεί την τσάντα γεγονότων. |

### Τιμή επιστροφής

Το στάδιο επιλογής πηγής ώστε το `Load` να μπορεί να αλυσοδεθεί.

### Δείτε επίσης

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
