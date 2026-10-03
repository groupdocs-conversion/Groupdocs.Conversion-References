---
title: "CadFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents CAD (Conception Assistée par Ordinateur) qui sont utilisés pour des formats de fichiers graphiques 3D et peuvent contenir des conceptions 2D ou 3D."
type: docs
weight: 11
url: /fr/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

Définit les documents CAD (Conception Assistée par Ordinateur) qui sont utilisés pour les formats de fichiers graphiques 3D et peuvent contenir des conceptions 2D ou 3D.
Inclut les types suivants :
[Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype#Dgn),
[Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwf),
[Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwg),
[Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwt),
[Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dxf),
[Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype#Ifc),
[Igs](../../com.groupdocs.conversion.filetypes/cadfiletype#Igs),
[Plt](../../com.groupdocs.conversion.filetypes/cadfiletype#Plt),
[Stl](../../com.groupdocs.conversion.filetypes/cadfiletype#Stl).
[Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype#Cf2).
[Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwfx).
En savoir plus sur les formats CAD [ici](../https://wiki.fileformat.com/cad).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Dxf](#Dxf) | DXF, Drawing Interchange Format, ou Drawing Exchange Format, est une représentation de données balisées d’un fichier de dessin AutoCAD. |
|
|  | [Dwg](#Dwg) | Les fichiers avec extension DWG représentent des fichiers binaires propriétaires utilisés pour contenir des données de conception 2D et 3D. |
|
|  | [Dgn](#Dgn) | DGN, Design, les fichiers sont des dessins créés et pris en charge par des applications CAD telles que MicroStation et Intergraph Interactive Graphics Design System. |
|
|  | [Dwf](#Dwf) | Design Web Format (DWF) représente des dessins 2D/3D au format compressé pour la visualisation, la révision ou l’impression de fichiers de conception. |
|
|  | [Stl](#Stl) | STL, abréviation de stereolithrography, est un format de fichier interchangeable qui représente la géométrie de surface tridimensionnelle. |
|
|  | [Ifc](#Ifc) | Les fichiers avec extension IFC font référence au format de fichier Industry Foundation Classes (IFC) qui établit des normes internationales pour l’importation et l’exportation d’objets de bâtiment et de leurs propriétés. |
|
|  | [Plt](#Plt) | Le format de fichier PLT est un fichier traceur vectoriel introduit par Autodesk, Inc. |
|
|  | [Igs](#Igs) | Format de document Igs |
|
|  | [Dwt](#Dwt) | Un fichier DWT est un modèle de dessin AutoCAD utilisé comme point de départ pour créer des dessins qui peuvent être enregistrés au format DWG. |
|
|  | [Dwfx](#Dwfx) | Le fichier DWFX est un dessin 2D ou 3D créé avec le logiciel Autodesk CAD. |
|
|  | [Cf2](#Cf2) | Fichier Common File Format. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Constructeur de sérialisation


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF, Drawing Interchange Format, ou Drawing Exchange Format, est une représentation de données balisées d’un fichier de dessin AutoCAD.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


Les fichiers avec extension DWG représentent des fichiers binaires propriétaires utilisés pour contenir des données de conception 2D et 3D. Comme DXF, qui sont des fichiers ASCII, DWG représente le format de fichier binaire pour les dessins CAD (Conception Assistée par Ordinateur).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN, Design, les fichiers sont des dessins créés et pris en charge par des applications CAD telles que MicroStation et Intergraph Interactive Graphics Design System.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Le Design Web Format (DWF) représente des dessins 2D/3D au format compressé pour visualiser, examiner ou imprimer les fichiers de conception. Il contient des graphiques et du texte comme partie des données de conception et réduit la taille du fichier grâce à son format compressé.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, abréviation de stéréolithographie, est un format de fichier interchangeable qui représente la géométrie de surface tridimensionnelle. Ce format de fichier est utilisé dans plusieurs domaines tels que le prototypage rapide, l'impression 3D et la fabrication assistée par ordinateur.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


Les fichiers avec l'extension IFC font référence au format de fichier Industry Foundation Classes (IFC) qui établit des normes internationales pour l'importation et l'exportation d'objets de bâtiment et de leurs propriétés. Ce format de fichier assure l'interopérabilité entre différentes applications logicielles.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


Le format de fichier PLT est un fichier traceur vectoriel introduit par Autodesk, Inc. et contient des informations pour un certain fichier CAD. Les détails du traçage nécessitent précision et exactitude en production, et l'utilisation du fichier PLT garantit cela, car toutes les images sont imprimées avec des lignes plutôt qu'avec des points.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Format de document Igs


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


Un fichier DWT est un modèle de dessin AutoCAD utilisé comme point de départ pour créer des dessins qui peuvent être enregistrés au format DWG.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


Le fichier DWFX est un dessin 2D ou 3D créé avec le logiciel Autodesk CAD. Il est enregistré au format DWFx, qui est similaire à un fichier .DWF, mais est formaté en utilisant la spécification XML Paper Specification (XPS) de Microsoft.


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Fichier au format Common File Format. Fichier CAD contenant des conceptions d'assemblages 3D ou d'autres données de modèle ; peut être traité et découpé par une machine CAD/CAM, comme un dispositif de découpe par poinçon.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement par défaut préparées pour le type de fichier source


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Options de conversion par défaut préparées pour le type de fichier


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
