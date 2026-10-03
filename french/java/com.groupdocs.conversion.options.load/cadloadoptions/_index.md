---
title: "CadLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents CAD."
type: docs
weight: 12
url: /fr/java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

Options de chargement des documents CAD.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [CadLoadOptions()](#CadLoadOptions--) | Initialise une nouvelle instance de la classe [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getLayoutNames()](#getLayoutNames--) | Spécifie quels agencements CAD doivent être convertis |
|
|  | [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Spécifie quels agencements CAD doivent être convertis |
|
|  | [getDrawType()](#getDrawType--) | Obtient le type du dessin. |
|
|  | [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Définit le type du dessin. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Obtient une couleur d'arrière-plan. |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Définit une couleur d'arrière-plan. |
|
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
|  | [getCtbSources()](#getCtbSources--) | Obtient les sources CTB. |
|
|  | [setCtbSources(Map<String,InputStream> ctbSources)](#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--) | Définit les sources CTB. |
|
|  | [getDrawColor()](#getDrawColor--) | Obtient la couleur de premier plan. |
|
|  | [setDrawColor(System.Drawing.Color drawColor)](#setDrawColor-com.aspose.ms.System.Drawing.Color-) | Définit la couleur de premier plan. |
|
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Initialise une nouvelle instance de la classe [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions).


### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Type de fichier du document d’entrée.


**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Spécifie quels agencements CAD doivent être convertis


**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Spécifie quels agencements CAD doivent être convertis


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Obtient le type du dessin.


**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Définit le type du dessin.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Obtient une couleur d'arrière-plan.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Définit une couleur d'arrière-plan.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

### getCtbSources() {#getCtbSources--}
```
public Map<String,InputStream> getCtbSources()
```


Obtient les sources CTB.


**Returns:**
java.util.Map<java.lang.String,java.io.InputStream>
### setCtbSources(Map<String,InputStream> ctbSources) {#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--}
```
public void setCtbSources(Map<String,InputStream> ctbSources)
```


Définit les sources CTB.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ctbSources | java.util.Map<java.lang.String,java.io.InputStream> |  |

### getDrawColor() {#getDrawColor--}
```
public System.Drawing.Color getDrawColor()
```


Obtient la couleur de premier plan.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setDrawColor(System.Drawing.Color drawColor) {#setDrawColor-com.aspose.ms.System.Drawing.Color-}
```
public void setDrawColor(System.Drawing.Color drawColor)
```


Définit la couleur de premier plan.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| drawColor | com.aspose.ms.System.Drawing.Color |  |

