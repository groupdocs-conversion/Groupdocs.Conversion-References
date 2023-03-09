---
title: CadFileType
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Définit les documents CAO conception assistée par ordinateur qui sont utilisés pour un format de fichier graphique 3D et peuvent contenir des conceptions 2D ou 3D. Inclut les types suivants  Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . En savoir plus sur les formats CAOicihttps//wiki.fileformat.com/cad .
type: docs
weight: 860
url: /fr/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Définit les documents CAO (conception assistée par ordinateur) qui sont utilisés pour un format de fichier graphique 3D et peuvent contenir des conceptions 2D ou 3D. Inclut les types suivants : [`Cf2`](./cf2)[`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwfx`](./dwfx)[`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . En savoir plus sur les formats CAO[ici](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [CadFileType](cadfiletype)() | Constructeur de sérialisation |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Détermine si deux instances d'objet sont égales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sert de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Fichier de format de fichier commun. Fichier CAO contenant des conceptions de package 3D ou d'autres données de modèle ; peut être traité et coupé par une machine CAD/CAM, telle qu'un dispositif de découpe. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, les fichiers sont des dessins créés et pris en charge par des applications de CAO telles que MicroStation et Intergraph Interactive Graphics Design System. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) représente un dessin 2D/3D au format compressé pour l'affichage, la révision ou l'impression de fichiers de conception. Il contient des graphiques et du texte dans le cadre des données de conception et réduit la taille du fichier en raison de son format compressé. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | Le fichier DWFX est un dessin 2D ou 3D créé avec le logiciel de CAO Autodesk. Il est enregistré au format DWFx, qui est similaire à un fichier . Fichier DWF, mais formaté à l'aide de la spécification XML Paper Specification (XPS) de Microsoft. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Les fichiers avec l'extension DWG représentent des fichiers binaires propriétaires utilisés pour contenir des données de conception 2D et 3D. Comme DXF, qui sont des fichiers ASCII, DWG représente le format de fichier binaire pour les dessins CAO (conception assistée par ordinateur). En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Un fichier DWT est un fichier de modèle de dessin AutoCAD utilisé comme point de départ pour créer des dessins pouvant être enregistrés en tant que fichiers DWG. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, ou Drawing Exchange Format, est une représentation de données étiquetées du fichier de dessin AutoCAD. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Les fichiers avec l'extension IFC font référence au format de fichier IFC (Industry Foundation Classes) qui établit des normes internationales pour importer et exporter des objets de construction et leurs propriétés. Ce format de fichier permet l'interopérabilité entre différentes applications logicielles. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Format de document Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Le format de fichier PLT est un fichier de traceur vectoriel introduit par Autodesk, Inc. et contient des informations pour un certain fichier CAO. Les détails de traçage nécessitent de l'exactitude et de la précision dans la production, et l'utilisation du fichier PLT le garantit car toutes les images sont imprimées à l'aide de lignes au lieu de points. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, abréviation de stéréolithographie, est un format de fichier interchangeable qui représente la géométrie de surface en 3 dimensions. Le format de fichier trouve son utilisation dans plusieurs domaines tels que le prototypage rapide, l'impression 3D et la fabrication assistée par ordinateur. En savoir plus sur ce format de fichier[ici](https://wiki.fileformat.com/cad/stl) . |

### Voir également

* class [FileType](../filetype)
* espace de noms [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
