---
title: "FileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Clase base de tipo de archivo"
type: docs
weight: 16
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Clase base de tipo de archivo
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileType()](#FileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Unknown](#Unknown) | Tipo de archivo desconocido |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | El formato de archivo |
| [getExtension()](#getExtension--) | La extensión del archivo |
| [getFamily()](#getFamily--) | La familia del archivo |
| [getDescription()](#getDescription--) | Descripción del tipo de archivo |
| [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Devuelve FileType para el nombre de archivo especificado |
| [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Obtiene FileType para la extensión de archivo proporcionada |
| [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Devuelve FileType para el flujo de documento proporcionado |
| [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Devuelve todos los valores de enumeración. |
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
| [toString()](#toString--) | Representación de cadena |
| [getLoadOptions()](#getLoadOptions--) | Opciones de carga predeterminadas preparadas para el tipo de archivo de origen |
| [getConvertOptions()](#getConvertOptions--) | Opciones de conversión predeterminadas preparadas para el tipo de archivo |
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Constructor de serialización

### Unknown {#Unknown}
```
public static final FileType Unknown
```


Tipo de archivo desconocido

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


El formato de archivo

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


La extensión del archivo

**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


La familia del archivo

**Returns:**
java.lang.String - La familia de archivos
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Descripción del tipo de archivo

**Returns:**
java.lang.String - descripción
### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Devuelve FileType para el nombre de archivo especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El nombre del archivo |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name
### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Obtiene FileType para la extensión de archivo proporcionada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileExtension | java.lang.String | extensión de archivo |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type
### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Devuelve FileType para el flujo de documento proporcionado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | java.io.InputStream | TStream que será sondado |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream
### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Devuelve todos los valores de enumeración.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Enumeración de tipos de archivo

T : Tipo de objeto enumerado.
### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


Representación de cadena

**Returns:**
java.lang.String - Representación de cadena del tipo de archivo
### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opciones de conversión predeterminadas preparadas para el tipo de archivo

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


Determina si dos instancias de objeto son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si dos instancias de objeto son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sirve como la función hash predeterminada.

**Returns:**
int
