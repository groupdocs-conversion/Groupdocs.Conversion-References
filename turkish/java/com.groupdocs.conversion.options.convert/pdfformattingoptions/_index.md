---
title: "PdfFormattingOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Pdf biçimlendirme seçeneklerini tanımlar."
type: docs
weight: 28
url: /tr/java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Pdf biçimlendirme seçeneklerini tanımlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCenterWindow()](#getCenterWindow--) | Belgenin pencere konumunun ekranda ortalanıp ortalanmayacağını belirtir. |
|
|  | [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Belgenin pencere konumunun ekranda ortalanıp ortalanmayacağını belirtir. |
|
|  | [getDirection()](#getDirection--) | Metnin okuma sırasını ayarlar: L2R (soldan sağa) veya R2L (sağdan sola). |
|
|  | [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Metnin okuma sırasını ayarlar: L2R (soldan sağa) veya R2L (sağdan sola). |
|
|  | [getDisplayDocTitle()](#getDisplayDocTitle--) | Belgenin pencere başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirtir. |
|
|  | [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Belgenin pencere başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirtir. |
|
|  | [getFitWindow()](#getFitWindow--) | Belge penceresinin ilk görüntülenen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirtir. |
|
|  | [setFitWindow(boolean value)](#setFitWindow-boolean-) | Belge penceresinin ilk görüntülenen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirtir. |
|
|  | [getHideMenuBar()](#getHideMenuBar--) | Belge aktif olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirtir. |
|
|  | [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Belge aktif olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirtir. |
|
|  | [getHideToolBar()](#getHideToolBar--) | Belge aktif olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirtir. |
|
|  | [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Belge aktif olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirtir. |
|
|  | [getHideWindowUI()](#getHideWindowUI--) | Belge aktif olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirtir. |
|
|  | [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Belge aktif olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirtir. |
|
|  | [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Sayfa modunu ayarlar, tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirler. |
|
|  | [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Sayfa modunu ayarlar, tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirler. |
|
|  | [getPageLayout()](#getPageLayout--) | Belge açıldığında kullanılacak sayfa düzenini ayarlar. |
|
|  | [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Belge açıldığında kullanılacak sayfa düzenini ayarlar. |
|
|  | [getPageMode()](#getPageMode--) | Sayfa modunu ayarlar, belgenin açıldığında nasıl görüntüleneceğini belirler. |
|
|  | [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Sayfa modunu ayarlar, belgenin açıldığında nasıl görüntüleneceğini belirler. |
|
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Belgenin pencere konumunun ekranda ortalanıp ortalanmayacağını belirtir. Varsayılan: false.


**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Belgenin pencere konumunun ekranda ortalanıp ortalanmayacağını belirtir. Varsayılan: false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Metnin okuma sırasını ayarlar: L2R (soldan sağa) veya R2L (sağdan sola). Varsayılan: L2R.


**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Metnin okuma sırasını ayarlar: L2R (soldan sağa) veya R2L (sağdan sola). Varsayılan: L2R.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Belgenin pencere başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirtir. Varsayılan: false.


**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Belgenin pencere başlık çubuğunun belge başlığını gösterip göstermeyeceğini belirtir. Varsayılan: false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Belge penceresinin ilk görüntülenen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirtir. Varsayılan: false.


**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Belge penceresinin ilk görüntülenen sayfaya sığacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirtir. Varsayılan: false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Belge aktif olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirtir. Varsayılan: false.


**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Belge aktif olduğunda menü çubuğunun gizlenip gizlenmeyeceğini belirtir. Varsayılan: false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Belge aktif olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirtir. Varsayılan: false.


**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Belge aktif olduğunda araç çubuğunun gizlenip gizlenmeyeceğini belirtir. Varsayılan: false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Belge aktif olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirtir. Varsayılan: false.


**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Belge aktif olduğunda kullanıcı arayüzü öğelerinin gizlenip gizlenmeyeceğini belirtir. Varsayılan: false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Sayfa modunu ayarlar, tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirler.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Sayfa modunu ayarlar, tam ekran modundan çıkarken belgenin nasıl görüntüleneceğini belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Belge açıldığında kullanılacak sayfa düzenini ayarlar.


**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Belge açıldığında kullanılacak sayfa düzenini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Sayfa modunu ayarlar, belgenin açıldığında nasıl görüntüleneceğini belirler.


**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Sayfa modunu ayarlar, belgenin açıldığında nasıl görüntüleneceğini belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

