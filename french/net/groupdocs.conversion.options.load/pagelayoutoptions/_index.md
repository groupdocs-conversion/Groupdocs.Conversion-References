---
title: "PageLayoutOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Décrit les modes de mise en page lors du chargement des documents Web."
type: docs
weight: 2720
url: /fr/net/groupdocs.conversion.options.load/pagelayoutoptions/
---
## PageLayoutOptions class

Décrit les modes de mise en page lors du chargement des documents Web.

```csharp
public class PageLayoutOptions : FlagsEnumeration
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
| [operator &#x7C;](../../groupdocs.conversion.options.load/pagelayoutoptions/op_bitwiseor) | Combine deux drapeaux [`PageLayoutOptions`](../pagelayoutoptions) en utilisant le OU binaire. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [None](../../groupdocs.conversion.options.load/pagelayoutoptions/none) | Valeur par défaut |
| static readonly [ScaleToPageHeight](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopageheight) | Ce drapeau indique que le contenu du document sera mis à l'échelle pour s'adapter à la hauteur de la première page. Tout le contenu du document sera placé uniquement sur la page unique. |
| static readonly [ScaleToPageWidth](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopagewidth) | Indique que le contenu du document sera mis à l'échelle pour s'adapter à la page où la différence entre la largeur de page disponible et le contenu qui se chevauche est la plus grande. |

### Voir aussi

* class [FlagsEnumeration](../../groupdocs.conversion.contracts/flagsenumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
