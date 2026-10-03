---
title: "PdfFormattingOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les options de formatage Pdf."
type: docs
weight: 28
url: /fr/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Définit les options de formatage Pdf.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | Spécifie si la position de la fenêtre du document sera centrée à l'écran. |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Spécifie si la position de la fenêtre du document sera centrée à l'écran. |
|
|  | [getDirection()](#getDirection--) | Définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | Spécifie si la barre de titre de la fenêtre du document doit afficher le titre du document. |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Spécifie si la barre de titre de la fenêtre du document doit afficher le titre du document. |
|
|  | [getFitWindow()](#getFitWindow--) | Spécifie si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | Spécifie si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | Spécifie si la barre de menus doit être masquée lorsque le document est actif. |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Spécifie si la barre de menus doit être masquée lorsque le document est actif. |
|
|  | [getHideToolBar()](#getHideToolBar--) | Spécifie si la barre d'outils doit être masquée lorsque le document est actif. |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Spécifie si la barre d'outils doit être masquée lorsque le document est actif. |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | Spécifie si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Spécifie si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Définit le mode de page, spécifiant comment afficher le document en quittant le mode plein écran. |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Définit le mode de page, spécifiant comment afficher le document en quittant le mode plein écran. |
|
|  | [getPageLayout()](#getPageLayout--) | Définit la mise en page qui sera utilisée lorsque le document est ouvert. |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Définit la mise en page qui sera utilisée lorsque le document est ouvert. |
|
|  | [getPageMode()](#getPageMode--) | Définit le mode de page, spécifiant comment le document doit être affiché lorsqu'il est ouvert. |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Définit le mode de page, spécifiant comment le document doit être affiché lorsqu'il est ouvert. |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Spécifie si la position de la fenêtre du document sera centrée à l'écran. Valeur par défaut : false.


**Returns:**
booléen
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Spécifie si la position de la fenêtre du document sera centrée à l'écran. Valeur par défaut : false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). Valeur par défaut : L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). Valeur par défaut : L2R.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Spécifie si la barre de titre de la fenêtre du document doit afficher le titre du document. Valeur par défaut : false.


**Returns:**
booléen
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Spécifie si la barre de titre de la fenêtre du document doit afficher le titre du document. Valeur par défaut : false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Spécifie si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. Valeur par défaut : false.


**Returns:**
booléen
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Spécifie si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. Valeur par défaut : false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Spécifie si la barre de menus doit être masquée lorsque le document est actif. Valeur par défaut : false.


**Returns:**
booléen
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Spécifie si la barre de menus doit être masquée lorsque le document est actif. Valeur par défaut : false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Spécifie si la barre d'outils doit être masquée lorsque le document est actif. Valeur par défaut : false.


**Returns:**
booléen
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Spécifie si la barre d'outils doit être masquée lorsque le document est actif. Valeur par défaut : false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Spécifie si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. Valeur par défaut : false.


**Returns:**
booléen
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Spécifie si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. Valeur par défaut : false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Définit le mode de page, spécifiant comment afficher le document en quittant le mode plein écran.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Définit le mode de page, spécifiant comment afficher le document en quittant le mode plein écran.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Définit la mise en page qui sera utilisée lorsque le document est ouvert.


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Définit la mise en page qui sera utilisée lorsque le document est ouvert.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Définit le mode de page, spécifiant comment le document doit être affiché lorsqu'il est ouvert.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Définit le mode de page, spécifiant comment le document doit être affiché lorsqu'il est ouvert.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

