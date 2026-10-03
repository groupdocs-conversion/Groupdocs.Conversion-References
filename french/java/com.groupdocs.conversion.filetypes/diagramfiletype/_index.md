---
title: "DiagramFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents Diagramme."
type: docs
weight: 13
url: /fr/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Définit les documents Diagram. Inclut les types suivants :
[Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdw),
[Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdx),
[Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsd),
[Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdm),
[Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdx),
[Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vss),
[Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssm),
[Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssx),
[Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vst),
[Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstm),
[Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstx),
[Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsx),
[Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vtx).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Vsd](#Vsd) | Les fichiers VSD sont des dessins créés avec l'application Microsoft Visio pour représenter une variété d'objets graphiques et leurs interconnexions. |
|
|  | [Vsdx](#Vsdx) | Les fichiers avec l'extension .VSDX représentent le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. |
|
|  | [Vss](#Vss) | Les VSS sont des fichiers de gabarits créés avec Microsoft Visio 2007 et antérieurs. |
|
|  | [Vst](#Vst) | Les fichiers avec l'extension VST sont des images vectorielles créées avec Microsoft Visio et servent de modèle pour créer d'autres fichiers. |
|
|  | [Vsx](#Vsx) | Les fichiers avec l'extension .VSX désignent des gabarits composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. |
|
|  | [Vtx](#Vtx) | Un fichier avec l'extension VTX est un modèle de dessin Microsoft Visio enregistré sur le disque au format XML. |
|
|  | [Vdw](#Vdw) | VDW est le format de fichier Visio Graphics Service qui spécifie les flux et les stockages nécessaires au rendu d'un dessin Web. |
|
|  | [Vdx](#Vdx) | Tout dessin ou graphique créé dans Microsoft Visio, mais enregistré au format XML, possède l'extension .VDX. |
|
|  | [Vssx](#Vssx) | Les fichiers avec l'extension .VSSX sont des gabarits de dessin créés avec Microsoft Visio 2013 et versions ultérieures. |
|
|  | [Vstx](#Vstx) | Les fichiers avec l'extension VSTX sont des modèles de dessin créés avec Microsoft Visio 2013 et versions ultérieures. |
|
|  | [Vsdm](#Vsdm) | Les fichiers avec l'extension VSDM sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. |
|
|  | [Vssm](#Vssm) | Les fichiers avec l'extension .VSSM sont des fichiers de gabarit Microsoft Visio qui offrent une prise en charge des macros. |
|
|  | [Vstm](#Vstm) | Les fichiers avec l'extension VSTM sont des modèles créés avec Microsoft Visio qui prennent en charge les macros. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Constructeur de sérialisation


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


Les fichiers VSD sont des dessins créés avec l'application Microsoft Visio pour représenter une variété d'objets graphiques et leurs interconnexions.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vsd).


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


Les fichiers avec l'extension .VSDX représentent le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. Il a été développé pour remplacer le format de fichier binaire, .VSD, qui est pris en charge par les versions antérieures de Microsoft Visio.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vsdx).


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


Les VSS sont des fichiers de gabarits créés avec Microsoft Visio 2007 et antérieurs. Les fichiers de gabarits fournissent des objets de dessin qui peuvent être inclus dans un dessin .VSD Visio.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vss).


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


Les fichiers avec l'extension VST sont des images vectorielles créées avec Microsoft Visio et servent de modèle pour créer d'autres fichiers. Ces fichiers modèles sont au format binaire et contiennent la mise en page et les paramètres par défaut utilisés pour la création de nouveaux dessins Visio.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vst).


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


Les fichiers avec l'extension .VSX désignent des gabarits composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. Les fichiers VSX sont enregistrés au format XML et étaient pris en charge jusqu'à Visio 2013.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vsx).


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


Un fichier avec l'extension VTX est un modèle de dessin Microsoft Visio enregistré sur le disque au format XML. Le modèle vise à fournir un fichier avec des paramètres de base qui peuvent être utilisés pour créer plusieurs fichiers Visio avec les mêmes paramètres.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vtx).


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW est le format de fichier Visio Graphics Service qui spécifie les flux et les stockages nécessaires au rendu d'un dessin Web.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/vdw).


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Tout dessin ou graphique créé dans Microsoft Visio, mais enregistré au format XML possède l'extension .VDX. Un fichier XML de dessin Visio est créé dans le logiciel Visio, qui est développé par Microsoft.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vdx).


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


Les fichiers avec l'extension .VSSX sont des gabarits de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Le format de fichier VSSX peut être ouvert avec Visio 2013 et versions ultérieures. Les fichiers Visio sont connus pour la représentation d'une variété d'éléments de dessin tels que des collections de formes, des connecteurs, des organigrammes, des schémas réseau, des diagrammes UML,
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vssx).


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


Les fichiers avec l'extension VSTX sont des modèles de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Ces fichiers VSTX offrent un point de départ pour créer des dessins Visio, enregistrés au format .VSDX, avec une mise en page et des paramètres par défaut.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vstx).


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


Les fichiers avec l'extension VSDM sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. Les fichiers VSDM sont des dessins OPC/XML similaires aux VSDX, mais offrent également la capacité d'exécuter des macros lors de l'ouverture du fichier.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vsdm).


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


Les fichiers avec l'extension .VSSM sont des fichiers de gabarit Microsoft Visio qui prennent en charge les macros. Un fichier VSSM, lorsqu'il est ouvert, permet d'exécuter les macros afin d'obtenir le formatage et le placement souhaités des formes dans un diagramme.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vssm).


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


Les fichiers avec l'extension VSTM sont des fichiers de modèle créés avec Microsoft Visio qui prennent en charge les macros. Contrairement aux fichiers VSDX, les fichiers créés à partir de modèles VSTM peuvent exécuter des macros développées en code Visual Basic for Applications (VBA).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vstm).


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
