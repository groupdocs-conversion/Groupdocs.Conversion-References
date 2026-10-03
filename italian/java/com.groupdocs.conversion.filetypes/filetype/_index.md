---
title: "FileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Classe base del tipo di file"
type: docs
weight: 16
url: /it/java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Classe base del tipo di file

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FileType()](#FileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Unknown](#Unknown) | Tipo di file sconosciuto |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Il formato del file |
|
|  | [getExtension()](#getExtension--) | L'estensione del file |
|
|  | [getFamily()](#getFamily--) | La famiglia del file |
|
|  | [getDescription()](#getDescription--) | Descrizione del tipo di file |
|
|  | [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Restituisce FileType per il fileName specificato |
|
|  | [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Ottiene FileType per fileExtension fornita |
|
|  | [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Restituisce FileType per lo stream di documento fornito |
|
|  | [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Restituisce tutti i valori dell'enumerazione. |
|
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
|  | [toString()](#toString--) | Rappresentazione stringa |
|
|  | [getLoadOptions()](#getLoadOptions--) | Opzioni di caricamento predefinite preparate per il tipo di file di origine |
|
|  | [getConvertOptions()](#getConvertOptions--) | Opzioni di conversione predefinite preparate per il tipo di file |
|
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Costruttore di serializzazione


### Unknown {#Unknown}
```
public static final FileType Unknown
```


Tipo di file sconosciuto


### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Il formato del file


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


L'estensione del file


**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


La famiglia del file


**Returns:**
java.lang.String - La famiglia del file

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Descrizione del tipo di file


**Returns:**
java.lang.String - descrizione

### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Restituisce FileType per il fileName specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileName | java.lang.String | Il nome del file |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name

### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Ottiene FileType per fileExtension fornita


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileExtension | java.lang.String | estensione del file |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type

### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Restituisce FileType per lo stream di documento fornito


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | TStream che sarà esaminato |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream

### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Restituisce tutti i valori dell'enumerazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Enumerabile dei tipi di file


T
: Tipo di oggetto enumerato.

### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa


**Returns:**
java.lang.String - Rappresentazione stringa del tipo di file

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite preparate per il tipo di file di origine


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opzioni di conversione predefinite preparate per il tipo di file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported

### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
booleano
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Determina se due istanze di oggetto sono uguali.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
booleano
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se due istanze di oggetto sono uguali.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
booleano
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funziona come funzione hash predefinita.


**Returns:**
int
