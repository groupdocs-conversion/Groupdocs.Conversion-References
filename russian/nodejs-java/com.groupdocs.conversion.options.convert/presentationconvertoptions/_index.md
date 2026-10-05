---
title: "PresentationConvertOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Описывает параметры конвертации в тип файла Presentation."
type: docs
weight: 33
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Описывает параметры конвертации в тип файла Presentation.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PresentationConvertOptions()](#PresentationConvertOptions--) | Инициализирует новый экземпляр класса [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getPassword()](#getPassword--) | Установите это свойство, если вы хотите защитить преобразованный документ паролем. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установите это свойство, если вы хотите защитить преобразованный документ паролем. |
| [getZoom()](#getZoom--) | Указывает уровень масштабирования в процентах. |
| [setZoom(int value)](#setZoom-int-) | Указывает уровень масштабирования в процентах. |
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Инициализирует новый экземпляр класса [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Установите это свойство, если вы хотите защитить преобразованный документ паролем.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Установите это свойство, если вы хотите защитить преобразованный документ паролем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Указывает уровень масштабирования в процентах. По умолчанию 100. Масштаб по умолчанию поддерживается до Microsoft Powerpoint 2010. Начиная с Microsoft Powerpoint 2013 масштаб по умолчанию больше не устанавливается для документа, вместо этого, кажется, используется коэффициент масштабирования последнего открытого документа.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Указывает уровень масштабирования в процентах. По умолчанию 100. Масштаб по умолчанию поддерживается до Microsoft Powerpoint 2010. Начиная с Microsoft Powerpoint 2013 масштаб по умолчанию больше не устанавливается для документа, вместо этого, кажется, используется коэффициент масштабирования последнего открытого документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

