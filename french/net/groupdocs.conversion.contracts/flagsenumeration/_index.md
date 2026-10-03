---
title: "FlagsEnumeration"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Représente une classe de base abstraite pour créer des énumérations qui prennent en charge les opérations de drapeaux bit à bit."
type: docs
weight: 220
url: /fr/net/groupdocs.conversion.contracts/flagsenumeration/
---
## FlagsEnumeration class

Représente une classe de base abstraite pour créer des énumérations qui prennent en charge les opérations de drapeaux bit à bit.

```csharp
public abstract class FlagsEnumeration : Enumeration
```

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Détermine si deux instances d'objet sont égales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | Vérifie si le drapeau actuel possède le drapeau spécifié. |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | Vérifie si le drapeau actuel possède la valeur spécifiée. |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | Convertit l'objet actuel en chaîne. |
| static [Combine&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/combine)(T, T) | Combine deux énumérations de drapeaux en une. |

### Voir aussi

* class [Enumeration](../enumeration)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
