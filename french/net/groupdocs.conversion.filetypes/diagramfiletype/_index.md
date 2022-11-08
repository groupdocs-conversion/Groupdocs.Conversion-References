---
title: DiagramFileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Définit les documents de diagramme. Inclut les types suivants  Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx .
type: docs
weight: 830
url: /fr/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Définit les documents de diagramme. Inclut les types suivants : [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx) .

```csharp
public sealed class DiagramFileType : FileType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Constructeur de sérialisation |

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
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW est le format de fichier Visio Graphics Service qui spécifie les flux et les stockages requis pour le rendu d'un dessin Web. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Tout dessin ou graphique créé dans Microsoft Visio, mais enregistré au format XML, porte l'extension .VDX. Un fichier XML de dessin Visio est créé dans le logiciel Visio, développé par Microsoft. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | Les fichiers VSD sont des dessins créés avec l'application Microsoft Visio pour représenter une variété d'objets graphiques et l'interconnexion entre ceux-ci. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Les fichiers avec l'extension VSDM sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. Les fichiers VSDM sont des dessins OPC/XML similaires à VSDX, mais offrent également la possibilité d'exécuter des macros lorsque le fichier est ouvert. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Les fichiers avec l'extension .VSDX représentent le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. Il a été développé pour remplacer le format de fichier binaire, .VSD, qui est pris en charge par les versions antérieures de Microsoft Visio. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS sont des fichiers stencil créés avec Microsoft Visio 2007 et versions antérieures. Les fichiers Stencil fournissent des objets de dessin qui peuvent être inclus dans un dessin .VSD Visio. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vss) . |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Les fichiers avec l'extension .VSSM sont des fichiers Microsoft Visio Stencil qui prennent en charge les macros. Un fichier VSSM lorsqu'il est ouvert permet d'exécuter les macros pour obtenir le formatage et le placement souhaités des formes dans un diagramme. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vssm) . |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Les fichiers avec l'extension .VSSX sont des gabarits de dessin créés avec Microsoft Visio 2013 et supérieur. Le format de fichier VSSX peut être ouvert avec Visio 2013 et supérieur. Les fichiers Visio sont connus pour la représentation d'une variété d'éléments de dessin tels que la collection de formes, les connecteurs, les organigrammes, la disposition du réseau, les diagrammes UML, En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vssx) . |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Les fichiers avec l'extension VST sont des fichiers d'image vectorielle créés avec Microsoft Visio et servent de modèle pour créer d'autres fichiers. Ces fichiers de modèle sont au format de fichier binaire et contiennent la disposition et les paramètres par défaut utilisés pour la création de nouveaux dessins Visio. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vst) . |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Les fichiers avec l'extension VSTM sont des fichiers modèles créés avec Microsoft Visio qui prennent en charge les macros. Contrairement aux fichiers VSDX, les fichiers créés à partir de modèles VSTM peuvent exécuter des macros développées dans le code Visual Basic pour Applications (VBA). En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vstm) . |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Les fichiers avec les extensions VSTX sont des fichiers de modèle de dessin créés avec Microsoft Visio 2013 et supérieur. Ces fichiers VSTX fournissent un point de départ pour la création de dessins Visio, enregistrés en tant que fichiers .VSDX, avec la mise en page et les paramètres par défaut. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vstx) . |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Les fichiers avec l'extension .VSX font référence à des gabarits constitués de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. Les fichiers VSX sont enregistrés au format de fichier XML et étaient pris en charge jusqu'à Visio 2013. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vsx) . |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Un fichier avec l'extension VTX est un modèle de dessin Microsoft Visio qui est enregistré sur le disque au format de fichier XML. Le modèle vise à fournir un fichier avec des paramètres de base pouvant être utilisés pour créer plusieurs fichiers Visio avec les mêmes paramètres. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/image/vtx) . |

### Voir également

* class [FileType](../filetype)
* espace de noms [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
