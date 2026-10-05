---
title: "PdfFormattingOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет параметры форматирования Pdf."
type: docs
weight: 28
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

Определяет параметры форматирования Pdf.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCenterWindow()](#getCenterWindow--) | Указывает, будет ли позиция окна документа центрирована на экране. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | Указывает, будет ли позиция окна документа центрирована на экране. |
| [getDirection()](#getDirection--) | Устанавливает порядок чтения текста: L2R (слева направо) или R2L (справа налево). |
| [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | Устанавливает порядок чтения текста: L2R (слева направо) или R2L (справа налево). |
| [getDisplayDocTitle()](#getDisplayDocTitle--) | Указывает, должен ли заголовок окна документа отображать название документа. |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | Указывает, должен ли заголовок окна документа отображать название документа. |
| [getFitWindow()](#getFitWindow--) | Указывает, должно ли окно документа быть изменено в размере, чтобы соответствовать первой отображаемой странице. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | Указывает, должно ли окно документа быть изменено в размере, чтобы соответствовать первой отображаемой странице. |
| [getHideMenuBar()](#getHideMenuBar--) | Указывает, должна ли панель меню скрываться, когда документ активен. |
| [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | Указывает, должна ли панель меню скрываться, когда документ активен. |
| [getHideToolBar()](#getHideToolBar--) | Указывает, должна ли панель инструментов скрываться, когда документ активен. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | Указывает, должна ли панель инструментов скрываться, когда документ активен. |
| [getHideWindowUI()](#getHideWindowUI--) | Указывает, должны ли элементы пользовательского интерфейса скрываться, когда документ активен. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | Указывает, должны ли элементы пользовательского интерфейса скрываться, когда документ активен. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | Устанавливает режим страницы, указывая, как отображать документ при выходе из полноэкранного режима. |
| [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Устанавливает режим страницы, указывая, как отображать документ при выходе из полноэкранного режима. |
| [getPageLayout()](#getPageLayout--) | Устанавливает макет страницы, который будет использоваться при открытии документа. |
| [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | Устанавливает макет страницы, который будет использоваться при открытии документа. |
| [getPageMode()](#getPageMode--) | Устанавливает режим страницы, указывая, как документ должен отображаться при открытии. |
| [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | Устанавливает режим страницы, указывая, как документ должен отображаться при открытии. |
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


Указывает, будет ли позиция окна документа центрирована на экране. По умолчанию: false.

**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


Указывает, будет ли позиция окна документа центрирована на экране. По умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


Устанавливает порядок чтения текста: L2R (слева направо) или R2L (справа налево). По умолчанию: L2R.

**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


Устанавливает порядок чтения текста: L2R (слева направо) или R2L (справа налево). По умолчанию: L2R.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


Указывает, должна ли строка заголовка окна документа отображать название документа. По умолчанию: false.

**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


Указывает, должна ли строка заголовка окна документа отображать название документа. По умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


Указывает, должно ли окно документа быть изменено в размере, чтобы соответствовать первой отображаемой странице. По умолчанию: false.

**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


Указывает, должно ли окно документа быть изменено в размере, чтобы соответствовать первой отображаемой странице. По умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


Указывает, должна ли панель меню скрываться, когда документ активен. По умолчанию: false.

**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


Указывает, должна ли панель меню скрываться, когда документ активен. По умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


Указывает, должна ли панель инструментов скрываться, когда документ активен. По умолчанию: false.

**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


Указывает, должна ли панель инструментов скрываться, когда документ активен. По умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


Указывает, должны ли элементы пользовательского интерфейса скрываться, когда документ активен. По умолчанию: false.

**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


Указывает, должны ли элементы пользовательского интерфейса скрываться, когда документ активен. По умолчанию: false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


Устанавливает режим страницы, указывая, как отображать документ при выходе из полноэкранного режима.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


Устанавливает режим страницы, указывая, как отображать документ при выходе из полноэкранного режима.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


Устанавливает макет страницы, который будет использоваться при открытии документа.

**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


Устанавливает макет страницы, который будет использоваться при открытии документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


Устанавливает режим страницы, указывая, как документ должен отображаться при открытии.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


Устанавливает режим страницы, указывая, как документ должен отображаться при открытии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

