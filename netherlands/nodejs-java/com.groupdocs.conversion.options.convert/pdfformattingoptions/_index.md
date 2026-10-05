---
title: "PdfFormattingOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert PDF‑opmaakopties."
type: docs
weight: 28
url: /nl/nodejs-java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Definieert PDF‑opmaakopties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCenterWindow()](#getCenterWindow--) | Specificeert of de positie van het documentvenster gecentreerd op het scherm wordt. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Specificeert of de positie van het documentvenster gecentreerd op het scherm wordt. |
| [getDirection()](#getDirection--) | Stelt de leesvolgorde van tekst in: L2R (van links naar rechts) of R2L (van rechts naar links). |
| [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Stelt de leesvolgorde van tekst in: L2R (van links naar rechts) of R2L (van rechts naar links). |
| [getDisplayDocTitle()](#getDisplayDocTitle--) | Specificeert of de titelbalk van het documentvenster de documenttitel moet weergeven. |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Specificeert of de titelbalk van het documentvenster de documenttitel moet weergeven. |
| [getFitWindow()](#getFitWindow--) | Geeft aan of het documentvenster moet worden aangepast om de eerst weergegeven pagina te passen. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | Geeft aan of het documentvenster moet worden aangepast om de eerst weergegeven pagina te passen. |
| [getHideMenuBar()](#getHideMenuBar--) | Geeft aan of de menubalk verborgen moet worden wanneer het document actief is. |
| [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Geeft aan of de menubalk verborgen moet worden wanneer het document actief is. |
| [getHideToolBar()](#getHideToolBar--) | Geeft aan of de werkbalk verborgen moet worden wanneer het document actief is. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Geeft aan of de werkbalk verborgen moet worden wanneer het document actief is. |
| [getHideWindowUI()](#getHideWindowUI--) | Geeft aan of de gebruikersinterface‑elementen verborgen moeten worden wanneer het document actief is. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Geeft aan of de gebruikersinterface‑elementen verborgen moeten worden wanneer het document actief is. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Stelt paginamodus in, waarbij wordt gespecificeerd hoe het document moet worden weergegeven bij het verlaten van de volledige‑schermmodus. |
| [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Stelt paginamodus in, waarbij wordt gespecificeerd hoe het document moet worden weergegeven bij het verlaten van de volledige‑schermmodus. |
| [getPageLayout()](#getPageLayout--) | Stelt de paginalay-out in die moet worden gebruikt wanneer het document wordt geopend. |
| [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Stelt de paginalay-out in die moet worden gebruikt wanneer het document wordt geopend. |
| [getPageMode()](#getPageMode--) | Stelt paginamodus in, waarbij wordt gespecificeerd hoe het document moet worden weergegeven bij openen. |
| [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Stelt paginamodus in, waarbij wordt gespecificeerd hoe het document moet worden weergegeven bij openen. |
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Geeft aan of de positie van het documentvenster gecentreerd wordt op het scherm. Standaard: false.

**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Geeft aan of de positie van het documentvenster gecentreerd wordt op het scherm. Standaard: false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Stelt de leesrichting van tekst in: L2R (van links naar rechts) of R2L (van rechts naar links). Standaard: L2R.

**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Stelt de leesrichting van tekst in: L2R (van links naar rechts) of R2L (van rechts naar links). Standaard: L2R.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Geeft aan of de titelbalk van het documentvenster de documenttitel moet weergeven. Standaard: false.

**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Geeft aan of de titelbalk van het documentvenster de documenttitel moet weergeven. Standaard: false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Geeft aan of het documentvenster moet worden aangepast om de eerst weergegeven pagina te passen. Standaard: false.

**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Geeft aan of het documentvenster moet worden aangepast om de eerst weergegeven pagina te passen. Standaard: false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Geeft aan of de menubalk verborgen moet worden wanneer het document actief is. Standaard: false.

**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Geeft aan of de menubalk verborgen moet worden wanneer het document actief is. Standaard: false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Geeft aan of de werkbalk verborgen moet worden wanneer het document actief is. Standaard: false.

**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Geeft aan of de werkbalk verborgen moet worden wanneer het document actief is. Standaard: false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Geeft aan of de gebruikersinterface‑elementen verborgen moeten worden wanneer het document actief is. Standaard: false.

**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Geeft aan of de gebruikersinterface‑elementen verborgen moeten worden wanneer het document actief is. Standaard: false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Stelt paginamodus in, waarbij wordt gespecificeerd hoe het document moet worden weergegeven bij het verlaten van de volledige‑schermmodus.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Stelt paginamodus in, waarbij wordt gespecificeerd hoe het document moet worden weergegeven bij het verlaten van de volledige‑schermmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Stelt de paginalay-out in die moet worden gebruikt wanneer het document wordt geopend.

**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Stelt de paginalay-out in die moet worden gebruikt wanneer het document wordt geopend.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Stelt paginamodus in, waarbij wordt gespecificeerd hoe het document moet worden weergegeven bij openen.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Stelt paginamodus in, waarbij wordt gespecificeerd hoe het document moet worden weergegeven bij openen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

