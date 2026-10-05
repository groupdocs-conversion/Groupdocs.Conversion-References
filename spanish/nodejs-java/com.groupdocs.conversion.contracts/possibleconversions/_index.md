---
title: "PossibleConversions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Representa un mapeo de los pares de conversión compatibles con un formato de archivo fuente específico"
type: docs
weight: 13
url: /es/nodejs-java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Representa un mapeo de los pares de conversión compatibles con un formato de archivo fuente específico
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Crea una lista de conversiones posibles para el formato de archivo fuente especificado |
## Campos

| Campo | Descripción |
| --- | --- |
| [NULL](#NULL) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) | Opciones de carga predefinidas que podrían usarse para convertir desde el tipo actual |
| [getAll()](#getAll--) | Todos los tipos de archivo de destino y la bandera primaria/secundaria |
| [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Devuelve la conversión de destino para el tipo de archivo de destino especificado |
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
| [getPrimary()](#getPrimary--) | Tipos de archivo de destino primarios |
| [getSecondary()](#getSecondary--) | Tipos de archivo de destino secundarios |
| [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Agregar par de conversión |
| [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Buscar par de conversión en la lista actual para el tipo de archivo de destino |
| [getSource()](#getSource--) | Formatos de archivo de origen |
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Crea una lista de conversiones posibles para el formato de archivo fuente especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo de archivo de origen |

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predefinidas que podrían usarse para convertir desde el tipo actual

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options
### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Todos los tipos de archivo de destino y la bandera primaria/secundaria

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Iterable de [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Devuelve la conversión de destino para el tipo de archivo de destino especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo de archivo de destino |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions
### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extensión | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Tipos de archivo de destino primarios

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - tipos de archivo de destino primarios
### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Tipos de archivo de destino secundarios

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - tipos de archivo de destino secundarios
### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Agregar par de conversión

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | par de conversión |

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Buscar par de conversión en la lista actual para el tipo de archivo de destino

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo de archivo de destino |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair
### getSource() {#getSource--}
```
public FileType getSource()
```


Formatos de archivo de origen

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats
