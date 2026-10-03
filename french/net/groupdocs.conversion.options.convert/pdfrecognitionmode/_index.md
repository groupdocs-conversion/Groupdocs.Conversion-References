---
title: "PdfRecognitionMode"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Permet de contrôler comment un document PDF est converti en document de traitement de texte."
type: docs
weight: 2160
url: /fr/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

Permet de contrôler comment un document PDF est converti en document de traitement de texte.

```csharp
public sealed class PdfRecognitionMode : Enumeration
```

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Détermine si deux instances d'objet sont égales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | Mode de reconnaissance complet, le moteur effectue le regroupement et une analyse multi-niveaux pour restaurer l'intention de l'auteur du document original et produire un document aussi éditable que possible. L'inconvénient est que le document de sortie peut différer du fichier PDF original. |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | Ce mode est rapide et permet de préserver au maximum l'apparence originale du fichier PDF, mais l'édition du document résultant peut être limitée. Chaque bloc de texte visuellement groupé dans le fichier PDF original est converti en zone de texte dans le document résultant. Cela assure une ressemblance maximale du document de sortie avec le fichier PDF original. Le document de sortie aura une bonne apparence, mais il sera entièrement composé de zones de texte, ce qui peut rendre l'édition ultérieure du document dans Microsoft Word assez difficile. C'est le mode par défaut. |

### Voir aussi

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
