---
title: DiagramConvertOptions
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Options de conversion en type de fichier Diagramme.
type: docs
weight: 1360
url: /fr/net/groupdocs.conversion.options.convert/diagramconvertoptions/
---
## DiagramConvertOptions class

Options de conversion en type de fichier Diagramme.

```csharp
public sealed class DiagramConvertOptions : CommonConvertOptions<DiagramFileType>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DiagramConvertOptions](diagramconvertoptions)() | Initialise la nouvelle instance de[`DiagramConvertOptions`](../diagramconvertoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoFitPageToDrawingContent](../../groupdocs.conversion.options.convert/diagramconvertoptions/autofitpagetodrawingcontent) { get; set; } | Définit s'il faut agrandir la page pour l'adapter au contenu du dessin ou non |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Le numéro de page à partir duquel commencer la conversion. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | La liste des index de page à convertir. Doit être spécifié pour convertir des pages spécifiques. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Nombre de pages à convertir à partir de`Numéro de page` . |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Options spécifiques au filigrane |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance d'options actuelle. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sert de fonction de hachage par défaut. |

### Voir également

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [DiagramFileType](../../groupdocs.conversion.filetypes/diagramfiletype)
* espace de noms [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->