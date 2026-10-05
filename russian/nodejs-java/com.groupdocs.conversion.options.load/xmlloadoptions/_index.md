---
title: "XmlLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов XML."
type: docs
weight: 45
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/xmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.WebLoadOptions](../../com.groupdocs.conversion.options.load/webloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class XmlLoadOptions extends WebLoadOptions implements Serializable
```

Параметры загрузки документов XML.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmlLoadOptions()](#XmlLoadOptions--) | Инициализирует новый экземпляр класса [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getXslFoFactory()](#getXslFoFactory--) | Поток документа XSL-FO для преобразования XML-FO с использованием XSL. |
| [setXslFoFactory(Supplier<System.IO.Stream> value)](#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | Поток документа XSL для преобразования XML-FO с использованием XSL. |
| [getXsltFactory()](#getXsltFactory--) | получить поток документа XSLT для преобразования XML, выполняя трансформацию XSL в HTML. |
| [setXsltFactory(Supplier<System.IO.Stream> value)](#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--) | установить поток документа XSLT для преобразования XML, выполняя трансформацию XSL в HTML. |
| [isUseAsDataSource()](#isUseAsDataSource--) | Использовать документ Xml в качестве источника данных |
| [setUseAsDataSource(boolean useAsDataSource)](#setUseAsDataSource-boolean-) | Установить использование документа Xml в качестве источника данных |
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Инициализирует новый экземпляр класса [XmlLoadOptions](../../com.groupdocs.conversion.options.load/xmlloadoptions).

### getXslFoFactory() {#getXslFoFactory--}
```
public final Supplier<System.IO.Stream> getXslFoFactory()
```


Поток документа XSL-FO для преобразования XML-FO с использованием XSL.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXslFoFactory(Supplier<System.IO.Stream> value) {#setXslFoFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXslFoFactory(Supplier<System.IO.Stream> value)
```


Поток документа XSL для преобразования XML-FO с использованием XSL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### getXsltFactory() {#getXsltFactory--}
```
public final Supplier<System.IO.Stream> getXsltFactory()
```


получить поток документа XSLT для преобразования XML, выполняя трансформацию XSL в HTML.

**Returns:**
java.util.function.Supplier<com.aspose.ms.System.IO.Stream>
### setXsltFactory(Supplier<System.IO.Stream> value) {#setXsltFactory-java.util.function.Supplier-com.aspose.ms.System.IO.Stream--}
```
public final void setXsltFactory(Supplier<System.IO.Stream> value)
```


установить поток документа XSLT для преобразования XML, выполняя трансформацию XSL в HTML.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.function.Supplier<com.aspose.ms.System.IO.Stream> |  |

### isUseAsDataSource() {#isUseAsDataSource--}
```
public boolean isUseAsDataSource()
```


Использовать документ Xml в качестве источника данных

**Returns:**
boolean - true, если используется
### setUseAsDataSource(boolean useAsDataSource) {#setUseAsDataSource-boolean-}
```
public void setUseAsDataSource(boolean useAsDataSource)
```


Установить использование документа Xml в качестве источника данных

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| useAsDataSource | boolean | использовать документ Xml в качестве источника данных |

