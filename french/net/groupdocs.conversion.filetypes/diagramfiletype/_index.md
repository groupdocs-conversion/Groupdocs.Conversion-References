---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les documents Diagram. Inclut les types suivants Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /fr/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Définit les documents Diagram. Inclut les types suivants : [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Constructeur de sérialisation |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | Un fichier avec l'extension DRAWIO est un diagramme créé avec diagrams.net (anciennement draw.io). Il est stocké au format de fichier XML avec l'élément racine mxfile et contient le contenu et le formatage des éléments du diagramme tels que le texte, les images, la mise en page, les formes et le positionnement. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | Un fichier avec l'extension MMD est un diagramme écrit en langage de balisage Mermaid. Il est stocké sous forme de document texte brut qui commence par la déclaration du diagramme, telle que flowchart ou sequenceDiagram, suivie de la définition des nœuds et des connexions entre eux. En savoir plus sur ce format de fichier [ici](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW est le format de fichier Visio Graphics Service qui spécifie les flux et les espaces de stockage nécessaires au rendu d'un dessin Web. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Tout dessin ou graphique créé dans Microsoft Visio, mais enregistré au format XML possède l'extension .VDX. Un fichier XML de dessin Visio est créé dans le logiciel Visio, développé par Microsoft. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | Les fichiers VSD sont des dessins créés avec l'application Microsoft Visio pour représenter une variété d'objets graphiques et leurs interconnexions. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Les fichiers avec l'extension VSDM sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. Les fichiers VSDM sont des dessins OPC/XML similaires aux VSDX, mais offrent également la possibilité d'exécuter des macros lorsque le fichier est ouvert. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Les fichiers avec l'extension .VSDX représentent le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. Il a été développé pour remplacer le format de fichier binaire, .VSD, qui est pris en charge par les versions antérieures de Microsoft Visio. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | Les VSS sont des fichiers de gabarit créés avec Microsoft Visio 2007 et antérieurs. Les fichiers de gabarit fournissent des objets de dessin qui peuvent être inclus dans un dessin Visio .VSD. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Les fichiers avec l'extension .VSSM sont des fichiers de gabarit Microsoft Visio qui offrent la prise en charge des macros. Un fichier VSSM, lorsqu'il est ouvert, permet d'exécuter les macros pour obtenir le formatage et le placement souhaités des formes dans un diagramme. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Les fichiers avec l'extension .VSSX sont des gabarits de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Le format de fichier VSSX peut être ouvert avec Visio 2013 et versions ultérieures. Les fichiers Visio sont connus pour la représentation d'une variété d'éléments de dessin tels que des collections de formes, des connecteurs, des organigrammes, des agencements réseau, des diagrammes UML. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Les fichiers avec l'extension VST sont des images vectorielles créées avec Microsoft Visio et servent de modèle pour créer d'autres fichiers. Ces fichiers modèle sont au format binaire et contiennent la mise en page et les paramètres par défaut utilisés pour la création de nouveaux dessins Visio. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Les fichiers avec l'extension VSTM sont des fichiers modèle créés avec Microsoft Visio qui prennent en charge les macros. Contrairement aux fichiers VSDX, les fichiers créés à partir de modèles VSTM peuvent exécuter des macros développées en code Visual Basic for Applications (VBA). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Les fichiers avec l'extension VSTX sont des fichiers de modèle de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Ces fichiers VSTX offrent un point de départ pour créer des dessins Visio, enregistrés au format .VSDX, avec une mise en page et des paramètres par défaut. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Les fichiers avec l'extension .VSX désignent des gabarits composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. Les fichiers VSX sont enregistrés au format XML et étaient pris en charge jusqu'à Visio 2013. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Un fichier avec l'extension VTX est un modèle de dessin Microsoft Visio enregistré sur le disque au format XML. Le modèle vise à fournir un fichier avec des paramètres de base pouvant être utilisés pour créer plusieurs fichiers Visio avec les mêmes paramètres. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/image/vtx). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
