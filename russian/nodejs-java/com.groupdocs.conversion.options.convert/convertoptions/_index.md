---
title: "ConvertOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Общий класс параметров конвертации."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

Общий класс параметров конвертации.
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) | \{@inheritDoc\} |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Желаемый тип файла, в который должен быть конвертирован входной документ. |
| [deepClone()](#deepClone--) | Клонирует текущий экземпляр параметров. |
| [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | Желаемый тип файла, в который должен быть конвертирован входной документ. |
| [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | Желаемый тип файла, в который должен быть конвертирован входной документ. |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Получает желаемый тип файла, в который должен быть конвертирован входной документ.

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Желаемый тип файла, в который должен быть конвертирован входной документ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Клонирует текущий экземпляр параметров.

**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


Желаемый тип файла, в который должен быть конвертирован входной документ.

**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


Желаемый тип файла, в который должен быть конвертирован входной документ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | TFileType |  |

