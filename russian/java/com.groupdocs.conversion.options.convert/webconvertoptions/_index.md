---
title: "WebConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры конвертации в тип файла Web."
type: docs
weight: 46
url: /ru/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Параметры конвертации в тип файла Web.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | Инициализирует новый экземпляр класса. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | Указывает, следует ли внедрять ресурсы шрифтов в основной HTML. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | Указывает, следует ли внедрять ресурсы шрифтов в основной HTML. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


Инициализирует новый экземпляр класса.


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
логический
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| usePdf | логический |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
логический
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fixedLayout | логический |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
логический
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fixedLayoutShowBorders | логический |  |

### getZoom() {#getZoom--}
```
public int getZoom()
```




**Returns:**
int
### setZoom(int zoom) {#setZoom-int-}
```
public void setZoom(int zoom)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


Указывает, следует ли встраивать ресурсы шрифтов в основной HTML. По умолчанию false. Примечание: если FixedLayout установлен в true, ресурсы шрифтов всегда будут встраиваться.


**Returns:**
логический
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


Указывает, следует ли встраивать ресурсы шрифтов в основной HTML. По умолчанию false. Примечание: если FixedLayout установлен в true, ресурсы шрифтов всегда будут встраиваться.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| embedFontResources | логический |  |

