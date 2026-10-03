---
title: "PdfFormattingOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Pdf-Formatierungsoptionen."
type: docs
weight: 28
url: /de/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Definiert Pdf-Formatierungsoptionen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | Gibt an, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird. |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Gibt an, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird. |
|
|  | [getDirection()](#getDirection--) | Legt die Lesereihenfolge des Textes fest: L2R (von links nach rechts) oder R2L (von rechts nach links). |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Legt die Lesereihenfolge des Textes fest: L2R (von links nach rechts) oder R2L (von rechts nach links). |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | Gibt an, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Gibt an, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. |
|
|  | [getFitWindow()](#getFitWindow--) | Gibt an, ob das Dokumentfenster auf die erste angezeigte Seite skaliert werden muss. |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | Gibt an, ob das Dokumentfenster auf die erste angezeigte Seite skaliert werden muss. |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | Gibt an, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Gibt an, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
|
|  | [getHideToolBar()](#getHideToolBar--) | Gibt an, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Gibt an, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | Gibt an, ob Benutzerschnittstellenelemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Gibt an, ob Benutzerschnittstellenelemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Legt den Seitenmodus fest und gibt an, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Legt den Seitenmodus fest und gibt an, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
|
|  | [getPageLayout()](#getPageLayout--) | Legt das Seitenlayout fest, das verwendet werden soll, wenn das Dokument geöffnet wird. |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Legt das Seitenlayout fest, das verwendet werden soll, wenn das Dokument geöffnet wird. |
|
|  | [getPageMode()](#getPageMode--) | Legt den Seitenmodus fest und gibt an, wie das Dokument beim Öffnen angezeigt werden soll. |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Legt den Seitenmodus fest und gibt an, wie das Dokument beim Öffnen angezeigt werden soll. |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Gibt an, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird. Standard: false.


**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Gibt an, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird. Standard: false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Legt die Lesereihenfolge des Textes fest: L2R (von links nach rechts) oder R2L (von rechts nach links). Standard: L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Legt die Lesereihenfolge des Textes fest: L2R (von links nach rechts) oder R2L (von rechts nach links). Standard: L2R.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Gibt an, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. Standard: false.


**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Gibt an, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. Standard: false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Gibt an, ob das Dokumentfenster an die erste angezeigte Seite angepasst werden muss. Standard: false.


**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Gibt an, ob das Dokumentfenster an die erste angezeigte Seite angepasst werden muss. Standard: false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Gibt an, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. Standard: false.


**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Gibt an, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. Standard: false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Gibt an, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. Standard: false.


**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Gibt an, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. Standard: false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Gibt an, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. Standard: false.


**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Gibt an, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. Standard: false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Legt den Seitenmodus fest und gibt an, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Legt den Seitenmodus fest und gibt an, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Legt das Seitenlayout fest, das verwendet werden soll, wenn das Dokument geöffnet wird.


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Legt das Seitenlayout fest, das verwendet werden soll, wenn das Dokument geöffnet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Legt den Seitenmodus fest und gibt an, wie das Dokument beim Öffnen angezeigt werden soll.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Legt den Seitenmodus fest und gibt an, wie das Dokument beim Öffnen angezeigt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

