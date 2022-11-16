---
title: PossibleConversions
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Stellt eine Zuordnung dar welche Konvertierungspaare für ein bestimmtes Quelldateiformat unterstützt werden
type: docs
weight: 370
url: /de/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Stellt eine Zuordnung dar, welche Konvertierungspaare für ein bestimmtes Quelldateiformat unterstützt werden

```csharp
public sealed class PossibleConversions : ValueObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Alle Zieldateitypen und primäres/sekundäres Flag  IEnumerable von[`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Gibt die Zielkonvertierung für den angegebenen Zieldateityp zurück (2 indexers) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Vordefinierte Ladeoptionen, die zum Konvertieren vom aktuellen Typ verwendet werden könnten |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Primäre Zieldateitypen |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Sekundäre Zieldateitypen |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Quelldateiformate |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hash-Funktion. |

### Siehe auch

* class [ValueObject](../valueobject)
* namensraum [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->