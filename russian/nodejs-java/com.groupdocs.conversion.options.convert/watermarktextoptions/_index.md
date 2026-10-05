---
title: "WatermarkTextOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры настройки текстового водяного знака для конвертированного документа"
type: docs
weight: 45
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/watermarktextoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.convert.WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
```
public class WatermarkTextOptions extends WatermarkOptions
```

Параметры настройки текстового водяного знака для конвертированного документа
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WatermarkTextOptions(String text)](#WatermarkTextOptions-java.lang.String-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getText()](#getText--) | Текст водяного знака |
| [setText(String value)](#setText-java.lang.String-) | Текст водяного знака |
| [getWatermarkFont()](#getWatermarkFont--) | Шрифт водяного знака, если применён текстовый водяной знак |
| [setWatermarkFont(Font watermarkFont)](#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-) | Устанавливает шрифт водяного знака, если применён текстовый водяной знак |
| [getColor()](#getColor--) | Цвет шрифта водяного знака, если применён текстовый водяной знак |
| [getColorInternal()](#getColorInternal--) |  |
| [setColor(int argb)](#setColor-int-) | Цвет шрифта водяного знака в формате argb, если применён текстовый водяной знак |
| [setColor(String colorName)](#setColor-java.lang.String-) | Название цвета шрифта водяного знака, если применён текстовый водяной знак |
| [setColor(Color value)](#setColor-java.awt.Color-) | Цвет шрифта водяного знака, если применён текстовый водяной знак |
| [getHexColor()](#getHexColor--) |  |
### WatermarkTextOptions(String text) {#WatermarkTextOptions-java.lang.String-}
```
public WatermarkTextOptions(String text)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Текст водяного знака

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Текст водяного знака

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getWatermarkFont() {#getWatermarkFont--}
```
public Font getWatermarkFont()
```


Шрифт водяного знака, если применён текстовый водяной знак

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font) - font
### setWatermarkFont(Font watermarkFont) {#setWatermarkFont-com.groupdocs.conversion.options.convert.Font-}
```
public void setWatermarkFont(Font watermarkFont)
```


Устанавливает шрифт водяного знака, если применён текстовый водяной знак

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| watermarkFont | [Font](../../com.groupdocs.conversion.options.convert/font) | шрифт |

### getColor() {#getColor--}
```
public final Color getColor()
```


Цвет шрифта водяного знака, если применён текстовый водяной знак

**Returns:**
java.awt.Color
### getColorInternal() {#getColorInternal--}
```
public System.Drawing.Color getColorInternal()
```




**Returns:**
com.aspose.ms.System.Drawing.Color
### setColor(int argb) {#setColor-int-}
```
public final void setColor(int argb)
```


Цвет шрифта водяного знака в формате argb, если применён текстовый водяной знак

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb | int |  |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Название цвета шрифта водяного знака, если применён текстовый водяной знак

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorName | java.lang.String |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Цвет шрифта водяного знака, если применён текстовый водяной знак

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### getHexColor() {#getHexColor--}
```
public String getHexColor()
```




**Returns:**
java.lang.String
