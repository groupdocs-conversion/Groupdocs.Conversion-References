---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les formats de fichiers de présentation qui stockent une collection d'enregistrements pour accueillir les données de présentation telles que les diapositives, les formes, le texte, les animations, la vidéo, l'audio et les objets incorporés. Inclut les types de fichiers suivants Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. En savoir plus sur les formats de présentation icihttps//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /fr/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Définit les formats de fichiers de présentation qui stockent une collection d'enregistrements pour accueillir les données de présentation telles que les diapositives, les formes, le texte, les animations, la vidéo, l'audio et les objets incorporés. Inclut les types de fichiers suivants : [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). En savoir plus sur les formats de présentation [ici](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Constructeur de sérialisation |

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension du fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implémente [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Les fichiers avec l'extension FODP représentent une présentation OpenDocument Flat XML. Fichier de présentation enregistré au format OpenDocument, mais enregistré en utilisant un format XML plat au lieu du conteneur .ZIP utilisé par les fichiers .ODP standard. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Les fichiers avec l'extension ODP représentent le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASIS Open. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Les fichiers avec l'extension .OTP représentent des modèles de présentation créés par des applications au format standard OASIS OpenDocument. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Les fichiers avec l'extension .POT représentent des modèles Microsoft PowerPoint créés par les versions PowerPoint 97-2003. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Les fichiers avec l'extension POTM sont des modèles Microsoft PowerPoint avec prise en charge des macros. Les fichiers POTM sont créés avec PowerPoint 2007 ou ultérieur et contiennent des paramètres par défaut pouvant être utilisés pour créer d'autres fichiers de présentation. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Les fichiers avec l'extension .POTX représentent des modèles de présentation Microsoft PowerPoint créés avec Microsoft PowerPoint 2007 et versions ultérieures. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | Les fichiers PPS, PowerPoint Slide Show, sont créés avec Microsoft PowerPoint à des fins de diaporama. La lecture et la création des fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Les fichiers avec l'extension PPSM représentent le format de diaporama avec macros créé avec Microsoft PowerPoint 2007 ou supérieur. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | Les fichiers PPSX, Power Point Slide Show, sont créés avec Microsoft PowerPoint 2007 et versions ultérieures à des fins de diaporama. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Un fichier avec l'extension PPT représente un fichier PowerPoint qui consiste en une collection de diapositives affichées sous forme de diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Les fichiers avec l'extension PPTM sont des présentations avec macros créées avec Microsoft PowerPoint 2007 ou des versions supérieures. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Les fichiers avec l'extension PPTX sont des fichiers de présentation créés avec l'application populaire Microsoft PowerPoint. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de fichier de présentation Open XML de Microsoft PowerPoint. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/presentation/pptx). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
