---
title: "CadFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les documents CAD (Computer Aided Design) qui sont utilisés pour des formats de fichiers graphiques 3D et peuvent contenir des conceptions 2D ou 3D. Inclut les types suivants Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. En savoir plus sur les formats CAD icihttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /fr/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Définit les documents CAD (Computer Aided Design) qui sont utilisés pour des formats de fichiers graphiques 3D et peuvent contenir des conceptions 2D ou 3D. Inclut les types suivants : [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). En savoir plus sur les formats CAD [ici](https://wiki.fileformat.com/cad).

```csharp
public sealed class CadFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CadFileType](cadfiletype)() | Constructeur de sérialisation |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Common File Format File. Fichier CAD qui contient des conceptions d’ensemble 3D ou d’autres données de modèle ; peut être traité et découpé par une machine CAD/CAM, telle qu’un dispositif de découpe. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | Les fichiers DGN, Design, sont des dessins créés par et pris en charge par des applications CAD telles que MicroStation et Intergraph Interactive Graphics Design System. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Le Design Web Format (DWF) représente des dessins 2D/3D au format compressé pour la visualisation, la révision ou l’impression de fichiers de conception. Il contient des graphiques et du texte faisant partie des données de conception et réduit la taille du fichier grâce à son format compressé. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | Le fichier DWFX est un dessin 2D ou 3D créé avec le logiciel Autodesk CAD. Il est enregistré au format DWFx, qui est similaire à un fichier .DWF, mais est formaté en utilisant la spécification XML Paper de Microsoft (XPS). |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Les fichiers avec l'extension DWG représentent des fichiers binaires propriétaires utilisés pour contenir des données de conception 2D et 3D. Comme le DXF, qui sont des fichiers ASCII, le DWG représente le format de fichier binaire pour les dessins CAO (Conception Assistée par Ordinateur). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Un fichier DWT est un modèle de dessin AutoCAD utilisé comme point de départ pour créer des dessins qui peuvent être enregistrés au format DWG. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, ou Drawing Exchange Format, est une représentation de données balisées d'un fichier de dessin AutoCAD. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Les fichiers avec l'extension IFC font référence au format de fichier Industry Foundation Classes (IFC) qui établit des normes internationales pour l'importation et l'exportation d'objets de bâtiment et de leurs propriétés. Ce format de fichier assure l'interopérabilité entre différentes applications logicielles. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Format de document Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Le format de fichier PLT est un fichier traceur vectoriel introduit par Autodesk, Inc. et contient des informations pour un certain fichier CAD. Les détails du traçage nécessitent précision et exactitude en production, et l'utilisation du fichier PLT garantit cela car toutes les images sont imprimées avec des lignes plutôt qu'avec des points. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, abréviation de stéréolithographie, est un format de fichier interchangeable qui représente la géométrie de surface 3D. Ce format de fichier est utilisé dans plusieurs domaines tels que le prototypage rapide, l'impression 3D et la fabrication assistée par ordinateur. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/cad/stl). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
