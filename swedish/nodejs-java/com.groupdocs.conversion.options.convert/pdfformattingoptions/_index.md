---
title: "PdfFormattingOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar PDF‑formateringsalternativ."
type: docs
weight: 28
url: /sv/nodejs-java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Definierar PDF‑formateringsalternativ.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCenterWindow()](#getCenterWindow--) | Anger om fönstrets position för dokumentet ska centreras på skärmen. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Anger om fönstrets position för dokumentet ska centreras på skärmen. |
| [getDirection()](#getDirection--) | Ställer in läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Ställer in läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [getDisplayDocTitle()](#getDisplayDocTitle--) | Anger om dokumentets fönstertitelrad ska visa dokumenttiteln. |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Anger om dokumentets fönstertitelrad ska visa dokumenttiteln. |
| [getFitWindow()](#getFitWindow--) | Anger om dokumentfönstret måste ändras i storlek för att passa den först visade sidan. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | Anger om dokumentfönstret måste ändras i storlek för att passa den först visade sidan. |
| [getHideMenuBar()](#getHideMenuBar--) | Anger om menyraden ska döljas när dokumentet är aktivt. |
| [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Anger om menyraden ska döljas när dokumentet är aktivt. |
| [getHideToolBar()](#getHideToolBar--) | Anger om verktygsfältet ska döljas när dokumentet är aktivt. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Anger om verktygsfältet ska döljas när dokumentet är aktivt. |
| [getHideWindowUI()](#getHideWindowUI--) | Anger om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Anger om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Ställer in sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge. |
| [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Ställer in sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge. |
| [getPageLayout()](#getPageLayout--) | Ställer in sidlayout som ska användas när dokumentet öppnas. |
| [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Ställer in sidlayout som ska användas när dokumentet öppnas. |
| [getPageMode()](#getPageMode--) | Ställer in sidläge, som specificerar hur dokumentet ska visas när det öppnas. |
| [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Ställer in sidläge, som specificerar hur dokumentet ska visas när det öppnas. |
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Anger om fönstrets position för dokumentet ska centreras på skärmen. Standard: false.

**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Anger om fönstrets position för dokumentet ska centreras på skärmen. Standard: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Ställer in läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). Standard: L2R.

**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Ställer in läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). Standard: L2R.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Anger om dokumentets fönstertitelrad ska visa dokumenttiteln. Standard: false.

**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Anger om dokumentets fönstertitelrad ska visa dokumenttiteln. Standard: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Anger om dokumentfönstret måste ändras i storlek för att passa den först visade sidan. Standard: false.

**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Anger om dokumentfönstret måste ändras i storlek för att passa den först visade sidan. Standard: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Anger om menyraden ska döljas när dokumentet är aktivt. Standard: false.

**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Anger om menyraden ska döljas när dokumentet är aktivt. Standard: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Anger om verktygsfältet ska döljas när dokumentet är aktivt. Standard: false.

**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Anger om verktygsfältet ska döljas när dokumentet är aktivt. Standard: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Anger om användargränssnittselement ska döljas när dokumentet är aktivt. Standard: false.

**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Anger om användargränssnittselement ska döljas när dokumentet är aktivt. Standard: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Ställer in sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Ställer in sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Ställer in sidlayout som ska användas när dokumentet öppnas.

**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Ställer in sidlayout som ska användas när dokumentet öppnas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Ställer in sidläge, som specificerar hur dokumentet ska visas när det öppnas.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Ställer in sidläge, som specificerar hur dokumentet ska visas när det öppnas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

