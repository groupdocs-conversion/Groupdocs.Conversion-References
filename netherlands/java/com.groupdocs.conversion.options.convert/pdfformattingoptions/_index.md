---
title: "PdfFormattingOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert Pdf-opmaakopties."
type: docs
weight: 28
url: /nl/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Definieert Pdf-opmaakopties.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | Specificeert of de positie van het documentvenster op het scherm wordt gecentreerd. |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Specificeert of de positie van het documentvenster op het scherm wordt gecentreerd. |
|
|  | [getDirection()](#getDirection--) | Stelt de leesvolgorde van tekst in: L2R (van links naar rechts) of R2L (van rechts naar links). |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Stelt de leesvolgorde van tekst in: L2R (van links naar rechts) of R2L (van rechts naar links). |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | Specificeert of de titelbalk van het documentvenster de documenttitel moet weergeven. |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Specificeert of de titelbalk van het documentvenster de documenttitel moet weergeven. |
|
|  | [getFitWindow()](#getFitWindow--) | Specificeert of het documentvenster moet worden aangepast aan de eerste weergegeven pagina. |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | Specificeert of het documentvenster moet worden aangepast aan de eerste weergegeven pagina. |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | Specificeert of de menubalk moet worden verborgen wanneer het document actief is. |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Specificeert of de menubalk moet worden verborgen wanneer het document actief is. |
|
|  | [getHideToolBar()](#getHideToolBar--) | Specificeert of de werkbalk moet worden verborgen wanneer het document actief is. |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Specificeert of de werkbalk moet worden verborgen wanneer het document actief is. |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | Specificeert of gebruikersinterface‑elementen moeten worden verborgen wanneer het document actief is. |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Specificeert of gebruikersinterface‑elementen moeten worden verborgen wanneer het document actief is. |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Stelt de paginamodus in, waarmee wordt gespecificeerd hoe het document wordt weergegeven bij het verlaten van de volledige‑schermmodus. |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Stelt de paginamodus in, waarmee wordt gespecificeerd hoe het document wordt weergegeven bij het verlaten van de volledige‑schermmodus. |
|
|  | [getPageLayout()](#getPageLayout--) | Stelt de pagina‑indeling in die moet worden gebruikt wanneer het document wordt geopend. |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Stelt de pagina‑indeling in die moet worden gebruikt wanneer het document wordt geopend. |
|
|  | [getPageMode()](#getPageMode--) | Stelt de paginamodus in, waarmee wordt gespecificeerd hoe het document moet worden weergegeven bij het openen. |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Stelt de paginamodus in, waarmee wordt gespecificeerd hoe het document moet worden weergegeven bij het openen. |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Specificeert of de positie van het documentvenster op het scherm wordt gecentreerd. Standaard: false.


**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Specificeert of de positie van het documentvenster op het scherm wordt gecentreerd. Standaard: false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Stelt de leesvolgorde van tekst in: L2R (van links naar rechts) of R2L (van rechts naar links). Standaard: L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Stelt de leesvolgorde van tekst in: L2R (van links naar rechts) of R2L (van rechts naar links). Standaard: L2R.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Specificeert of de titelbalk van het documentvenster de documenttitel moet weergeven. Standaard: false.


**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Specificeert of de titelbalk van het documentvenster de documenttitel moet weergeven. Standaard: false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Specificeert of het documentvenster moet worden aangepast aan de eerste weergegeven pagina. Standaard: false.


**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Specificeert of het documentvenster moet worden aangepast aan de eerste weergegeven pagina. Standaard: false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Specificeert of de menubalk moet worden verborgen wanneer het document actief is. Standaard: false.


**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Specificeert of de menubalk moet worden verborgen wanneer het document actief is. Standaard: false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Specificeert of de werkbalk moet worden verborgen wanneer het document actief is. Standaard: false.


**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Specificeert of de werkbalk moet worden verborgen wanneer het document actief is. Standaard: false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Specificeert of gebruikersinterface‑elementen moeten worden verborgen wanneer het document actief is. Standaard: false.


**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Specificeert of gebruikersinterface‑elementen moeten worden verborgen wanneer het document actief is. Standaard: false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Stelt de paginamodus in, waarmee wordt gespecificeerd hoe het document wordt weergegeven bij het verlaten van de volledige‑schermmodus.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Stelt de paginamodus in, waarmee wordt gespecificeerd hoe het document wordt weergegeven bij het verlaten van de volledige‑schermmodus.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Stelt de pagina‑indeling in die moet worden gebruikt wanneer het document wordt geopend.


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Stelt de pagina‑indeling in die moet worden gebruikt wanneer het document wordt geopend.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Stelt de paginamodus in, waarmee wordt gespecificeerd hoe het document moet worden weergegeven bij het openen.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Stelt de paginamodus in, waarmee wordt gespecificeerd hoe het document moet worden weergegeven bij het openen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

