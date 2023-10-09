---
title: PdfFormattingOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Pdf formatting options.
type: docs
weight: 28
url: /java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Defines Pdf formatting options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCenterWindow()](#getCenterWindow--) | Specifies whether position of the document's window will be centered on the screen. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Specifies whether position of the document's window will be centered on the screen. |
| [getDirection()](#getDirection--) | Sets reading order of text: L2R (left to right) or R2L (right to left). |
| [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Sets reading order of text: L2R (left to right) or R2L (right to left). |
| [getDisplayDocTitle()](#getDisplayDocTitle--) | Specifies whether document's window title bar should display document title. |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Specifies whether document's window title bar should display document title. |
| [getFitWindow()](#getFitWindow--) | Specifies whether document window must be resized to fit the first displayed page. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | Specifies whether document window must be resized to fit the first displayed page. |
| [getHideMenuBar()](#getHideMenuBar--) | Specifies whether menu bar should be hidden when document is active. |
| [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Specifies whether menu bar should be hidden when document is active. |
| [getHideToolBar()](#getHideToolBar--) | Specifies whether toolbar should be hidden when document is active. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Specifies whether toolbar should be hidden when document is active. |
| [getHideWindowUI()](#getHideWindowUI--) | Specifies whether user interface elements should be hidden when document is active. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Specifies whether user interface elements should be hidden when document is active. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Sets page mode, specifying how to display the document on exiting full-screen mode. |
| [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Sets page mode, specifying how to display the document on exiting full-screen mode. |
| [getPageLayout()](#getPageLayout--) | Sets page layout which shall be used when the document is opened. |
| [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Sets page layout which shall be used when the document is opened. |
| [getPageMode()](#getPageMode--) | Sets page mode, specifying how document should be displayed when opened. |
| [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Sets page mode, specifying how document should be displayed when opened. |
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Specifies whether position of the document's window will be centered on the screen. Default: false.

**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Specifies whether position of the document's window will be centered on the screen. Default: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Sets reading order of text: L2R (left to right) or R2L (right to left). Default: L2R.

**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Sets reading order of text: L2R (left to right) or R2L (right to left). Default: L2R.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Specifies whether document's window title bar should display document title. Default: false.

**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Specifies whether document's window title bar should display document title. Default: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Specifies whether document window must be resized to fit the first displayed page. Default: false.

**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Specifies whether document window must be resized to fit the first displayed page. Default: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Specifies whether menu bar should be hidden when document is active. Default: false.

**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Specifies whether menu bar should be hidden when document is active. Default: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Specifies whether toolbar should be hidden when document is active. Default: false.

**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Specifies whether toolbar should be hidden when document is active. Default: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Specifies whether user interface elements should be hidden when document is active. Default: false.

**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Specifies whether user interface elements should be hidden when document is active. Default: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Sets page mode, specifying how to display the document on exiting full-screen mode.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Sets page mode, specifying how to display the document on exiting full-screen mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Sets page layout which shall be used when the document is opened.

**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Sets page layout which shall be used when the document is opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Sets page mode, specifying how document should be displayed when opened.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Sets page mode, specifying how document should be displayed when opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

