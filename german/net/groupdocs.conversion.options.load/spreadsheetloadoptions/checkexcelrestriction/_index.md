---
title: CheckExcelRestriction
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Ob die Einschränkung der ExcelDatei überprüft wird wenn der Benutzer zellenbezogene Objekte ändert. Beispielsweise erlaubt Excel keine Eingabe von Zeichenfolgenwerten die länger als 32 KB sind. Wenn Sie einen Wert eingeben der länger als 32 KB ist erhalten Sie eine Ausnahme wenn diese Eigenschaft wahr ist. Wenn diese Eigenschaft falsch ist akzeptieren wir Ihren EingabeStringWert als Wert der Zelle sodass Sie später den vollständigen StringWert für andere Dateiformate wie CSV ausgeben können. Wenn Sie jedoch einen solchen Wert festgelegt haben der für das ExcelDateiformat ungültig ist sollten Sie die Arbeitsmappe später nicht im ExcelDateiformat speichern. Andernfalls kann es zu einem unerwarteten Fehler für die generierte ExcelDatei kommen.
type: docs
weight: 20
url: /de/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert. Beispielsweise erlaubt Excel keine Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind. Wenn Sie einen Wert eingeben, der länger als 32 KB ist, erhalten Sie eine Ausnahme, wenn diese Eigenschaft wahr ist. Wenn diese Eigenschaft falsch ist, akzeptieren wir Ihren Eingabe-String-Wert als Wert der Zelle, sodass Sie später den vollständigen String-Wert für andere Dateiformate wie CSV ausgeben können. Wenn Sie jedoch einen solchen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist, sollten Sie die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu einem unerwarteten Fehler für die generierte Excel-Datei kommen.

```csharp
public bool CheckExcelRestriction { get; set; }
```

### Siehe auch

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namensraum [GroupDocs.Conversion.Options.Load](../../spreadsheetloadoptions)
* Montage [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->