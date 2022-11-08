---
title: PresentationFileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Définit les formats de fichier de présentation qui stockent une collection denregistrements pour accueillir des données de présentation telles que des diapositives des formes du texte des animations de la vidéo de laudio et des objets intégrés. Inclut les types de fichiers suivants  Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . En savoir plus sur les formats de présentationicihttps//wiki.fileformat.com/presentation .
type: docs
weight: 910
url: /fr/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Définit les formats de fichier de présentation qui stockent une collection d'enregistrements pour accueillir des données de présentation telles que des diapositives, des formes, du texte, des animations, de la vidéo, de l'audio et des objets intégrés. Inclut les types de fichiers suivants : [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . En savoir plus sur les formats de présentation[ici](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Constructeur de sérialisation |

## Propriétés

| Nom | La description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension de fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | La description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Détermine si deux instances d'objet sont égales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sert de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Les fichiers avec l'extension FODP représentent la présentation OpenDocument Flat XML. Fichier de présentation enregistré au format OpenDocument, mais enregistré à l'aide d'un format XML plat au lieu du conteneur .ZIP utilisé par les fichiers .ODP standard |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Les fichiers avec l'extension ODP représentent le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASISOpen. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Les fichiers avec l'extension .OTP représentent des fichiers de modèle de présentation créés par des applications au format standard OASIS OpenDocument. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Les fichiers avec l'extension .POT représentent les fichiers de modèle Microsoft PowerPoint créés par les versions PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Les fichiers avec l'extension POTM sont des fichiers de modèle Microsoft PowerPoint prenant en charge les macros. Les fichiers POTM sont créés avec PowerPoint 2007 ou supérieur et contiennent des paramètres par défaut qui peuvent être utilisés pour créer d'autres fichiers de présentation. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Les fichiers avec l'extension .POTX représentent des modèles de présentation Microsoft PowerPoint créés avec Microsoft PowerPoint 2007 et versions ultérieures. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, diaporama PowerPoint, les fichiers sont créés à l'aide de Microsoft PowerPoint à des fins de diaporama. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Les fichiers avec l'extension PPSM représentent un format de fichier de diaporama prenant en charge les macros créé avec Microsoft PowerPoint 2007 ou une version ultérieure. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, diaporama Power Point, les fichiers sont créés à l'aide de Microsoft PowerPoint 2007 et supérieur à des fins de diaporama. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Un fichier avec l'extension PPT représente un fichier PowerPoint composé d'une collection de diapositives à afficher sous forme de diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Les fichiers avec l'extension PPTM sont des fichiers de présentation prenant en charge les macros qui sont créés avec Microsoft PowerPoint 2007 ou des versions supérieures. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Les fichiers avec l'extension PPTX sont des fichiers de présentation créés avec l'application Microsoft PowerPoint populaire. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de fichier de présentation XML ouvert de Microsoft PowerPoint. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/presentation/pptx) . |

### Voir également

* class [FileType](../filetype)
* espace de noms [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
