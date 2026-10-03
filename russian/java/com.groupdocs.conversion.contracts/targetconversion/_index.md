---
title: "TargetConversion"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Представляет возможное целевое преобразование и флаг, является ли оно первичным или вторичным"
type: docs
weight: 14
url: /ru/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Представляет возможное целевое преобразование и флаг, является ли оно первичным или вторичным

## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormat()](#getFormat--) | Целевой формат документа |
|
|  | [isPrimary()](#isPrimary--) | Является ли преобразование основным |
|
|  | [getConvertOptions()](#getConvertOptions--) | Предопределённые параметры конвертации, которые могут быть использованы для преобразования в текущий тип |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Целевой формат документа


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Является ли преобразование основным


**Returns:**
boolean - `true`, если основной

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Предопределённые параметры конвертации, которые могут быть использованы для преобразования в текущий тип


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

