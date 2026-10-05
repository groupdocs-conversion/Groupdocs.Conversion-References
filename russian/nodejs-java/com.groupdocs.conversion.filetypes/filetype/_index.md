---
title: "FileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Базовый класс типа файла"
type: docs
weight: 16
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Базовый класс типа файла
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileType()](#FileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Unknown](#Unknown) | Неизвестный тип файла |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Формат файла |
| [getExtension()](#getExtension--) | Расширение файла |
| [getFamily()](#getFamily--) | Семейство файлов |
| [getDescription()](#getDescription--) | Описание типа файла |
| [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Возвращает FileType для указанного fileName |
| [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Получает FileType для предоставленного fileExtension |
| [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Возвращает FileType для предоставленного document stream |
| [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Возвращает все значения перечисления. |
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
| [toString()](#toString--) | Строковое представление |
| [getLoadOptions()](#getLoadOptions--) | Подготовлены параметры загрузки по умолчанию для исходного типа файла |
| [getConvertOptions()](#getConvertOptions--) | Подготовлены параметры конвертации по умолчанию для типа файла |
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Конструктор сериализации

### Unknown {#Unknown}
```
public static final FileType Unknown
```


Неизвестный тип файла

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Формат файла

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Расширение файла

**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


Семейство файлов

**Returns:**
java.lang.String - Семейство файлов
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Описание типа файла

**Returns:**
java.lang.String - описание
### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Возвращает FileType для указанного fileName

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name
### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Получает FileType для предоставленного fileExtension

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileExtension | java.lang.String | расширение файла |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type
### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Возвращает FileType для предоставленного document stream

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | TStream, который будет проверяться |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream
### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Возвращает все значения перечисления.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Перечисление типов файлов

T : Перечислимый тип объекта.
### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


Строковое представление

**Returns:**
java.lang.String - Строковое представление типа файла
### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Подготовлены параметры конвертации по умолчанию для типа файла

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported
### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
boolean
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Определяет, равны ли два экземпляра объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равны ли два экземпляра объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит функцией хеширования по умолчанию.

**Returns:**
int
