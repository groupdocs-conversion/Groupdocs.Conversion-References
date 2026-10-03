---
title: "EBookFileType"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Define documentos CAD (Computer Aided Design) que se utilizan para formatos de archivo gráfico 3D y pueden contener diseños 2D o 3D."
type: docs
weight: 14
url: /es/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Define documentos CAD (Diseño Asistido por Computadora) que se utilizan para formatos de archivo de gráficos 3D y pueden contener diseños 2D o 3D.
Incluye los siguientes tipos:
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
Obtén más información sobre los formatos CAD [aquí](../https://wiki.fileformat.com/cad).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | Constructor de serialización |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Epub](#Epub) | La extensión EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar para editores y consumidores. |
|
|  | [Mobi](#Mobi) | El formato de archivo MOBI es uno de los formatos de libro electrónico más ampliamente utilizados. |
|
|  | [Azw3](#Azw3) | AZW3, también conocido como Kindle Format 8 (KF8), es la versión modificada del formato de archivo digital de libro electrónico AZW desarrollado para dispositivos Amazon Kindle. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Constructor de serialización


### Epub {#Epub}
```
public static final EBookFileType Epub
```


La extensión EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar para editores y consumidores. El formato se ha vuelto tan común que ahora es compatible con muchos lectores electrónicos y aplicaciones de software. Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


El formato de archivo MOBI es uno de los formatos de libro electrónico más ampliamente utilizados. El formato es una mejora del antiguo formato OEB (Open Ebook Format) y se utilizó como formato propietario para Mobipocket Reader. Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, también conocido como Kindle Format 8 (KF8), es la versión modificada del formato de archivo digital de libro electrónico AZW desarrollado para dispositivos Amazon Kindle. El formato es una mejora de los archivos AZW más antiguos y se utiliza únicamente en dispositivos Kindle Fire, con compatibilidad retroactiva para los formatos de archivo ancestrales, es decir, MOBI y AZW. Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/ebook/azw3/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opciones de conversión predeterminadas preparadas para el tipo de archivo


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
