---
title: "PdfFormattingOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce le opzioni di formattazione Pdf."
type: docs
weight: 28
url: /it/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Definisce le opzioni di formattazione Pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | Specifica se la posizione della finestra del documento sarà centrata sullo schermo. |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Specifica se la posizione della finestra del documento sarà centrata sullo schermo. |
|
|  | [getDirection()](#getDirection--) | Imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | Specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
|
|  | [getFitWindow()](#getFitWindow--) | Specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | Specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | Specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
|
|  | [getHideToolBar()](#getHideToolBar--) | Specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | Specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Imposta la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero. |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Imposta la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero. |
|
|  | [getPageLayout()](#getPageLayout--) | Imposta il layout della pagina da utilizzare quando il documento viene aperto. |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Imposta il layout della pagina da utilizzare quando il documento viene aperto. |
|
|  | [getPageMode()](#getPageMode--) | Imposta la modalità pagina, specificando come il documento deve essere visualizzato quando viene aperto. |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Imposta la modalità pagina, specificando come il documento deve essere visualizzato quando viene aperto. |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Specifica se la posizione della finestra del documento sarà centrata sullo schermo. Predefinito: false.


**Returns:**
booleano
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Specifica se la posizione della finestra del documento sarà centrata sullo schermo. Predefinito: false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). Predefinito: L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). Predefinito: L2R.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. Predefinito: false.


**Returns:**
booleano
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. Predefinito: false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. Predefinito: false.


**Returns:**
booleano
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. Predefinito: false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Specifica se la barra dei menu deve essere nascosta quando il documento è attivo. Predefinito: false.


**Returns:**
booleano
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Specifica se la barra dei menu deve essere nascosta quando il documento è attivo. Predefinito: false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. Predefinito: false.


**Returns:**
booleano
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. Predefinito: false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. Predefinito: false.


**Returns:**
booleano
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. Predefinito: false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Imposta la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Imposta la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Imposta il layout della pagina da utilizzare quando il documento viene aperto.


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Imposta il layout della pagina da utilizzare quando il documento viene aperto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Imposta la modalità pagina, specificando come il documento deve essere visualizzato quando viene aperto.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Imposta la modalità pagina, specificando come il documento deve essere visualizzato quando viene aperto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

