---
title: "CadLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов CAD."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

Параметры загрузки документов CAD.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CadLoadOptions()](#CadLoadOptions--) | Инициализирует новый экземпляр класса [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getWidth()](#getWidth--) | Устанавливает желаемую ширину страницы при конвертации CAD‑документа |
| [setWidth(int value)](#setWidth-int-) | Устанавливает желаемую ширину страницы при конвертации CAD‑документа |
| [getHeight()](#getHeight--) | Устанавливает желаемую высоту страницы при конвертации CAD‑документа |
| [setHeight(int value)](#setHeight-int-) | Устанавливает желаемую высоту страницы при конвертации CAD‑документа |
| [getLayoutNames()](#getLayoutNames--) | Указывает, какие макеты CAD следует конвертировать |
| [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Указывает, какие макеты CAD следует конвертировать |
| [getDrawType()](#getDrawType--) | Получает тип чертежа. |
| [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Устанавливает тип чертежа. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона. |
| [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Устанавливает цвет фона. |
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Инициализирует новый экземпляр класса [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions).

### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Тип файла входного документа

**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Устанавливает желаемую ширину страницы при конвертации CAD‑документа

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает желаемую ширину страницы при конвертации CAD‑документа

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Устанавливает желаемую высоту страницы при конвертации CAD‑документа

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает желаемую высоту страницы при конвертации CAD‑документа

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Указывает, какие макеты CAD следует конвертировать

**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Указывает, какие макеты CAD следует конвертировать

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Получает тип чертежа.

**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Устанавливает тип чертежа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Получает цвет фона.

**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Устанавливает цвет фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

