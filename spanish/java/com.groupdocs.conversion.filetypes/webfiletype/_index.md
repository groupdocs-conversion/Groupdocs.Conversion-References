---
title: "WebFileType"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Define documentos web."
type: docs
weight: 27
url: /es/java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Define documentos web.
Incluye los siguientes tipos:
[Xml](../../com.groupdocs.conversion.filetypes/webfiletype#Xml),
[Json](../../com.groupdocs.conversion.filetypes/webfiletype#Json),
[Html](../../com.groupdocs.conversion.filetypes/webfiletype#Html),
[Htm](../../com.groupdocs.conversion.filetypes/webfiletype#Htm),
[Mht](../../com.groupdocs.conversion.filetypes/webfiletype#Mht),
[Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype#Mhtml),
[Chm](../../com.groupdocs.conversion.filetypes/webfiletype#Chm),
Obtén más información sobre los formatos web [aquí](../https://wiki.fileformat.com/web).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WebFileType()](#WebFileType--) | Constructor de serialización |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Xml](#Xml) | XML significa Extensible Markup Language, que es similar a HTML pero diferente al usar etiquetas para definir objetos. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) es un formato de archivo estándar abierto para compartir datos que utiliza texto legible por humanos para almacenar y transmitir datos. |
|
|  | [Html](#Html) | HTML (Hyper Text Markup Language) es la extensión para páginas web creadas para mostrarse en navegadores. |
|
|  | [Htm](#Htm) | HTM (Hyper Text Markup Language) es la extensión para páginas web creadas para mostrarse en navegadores. |
|
|  | [Mht](#Mht) | Los archivos con extensión MHTML representan un formato de archivo de archivo de página web que puede ser creado por varias aplicaciones diferentes. |
|
|  | [Mhtml](#Mhtml) | Los archivos con extensión MHTML representan un formato de archivo de archivo de página web que puede ser creado por varias aplicaciones diferentes. |
|
|  | [Chm](#Chm) | El formato de archivo CHM representa el archivo de ayuda HTML de Microsoft que consta de una colección de páginas HTML. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Constructor de serialización


### Xml {#Xml}
```
public static final WebFileType Xml
```


XML significa Extensible Markup Language, que es similar a HTML pero diferente al usar etiquetas para definir objetos. Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/web/xml).


### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation) es un formato de archivo estándar abierto para compartir datos que utiliza texto legible por humanos para almacenar y transmitir datos. Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/web/json).


### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language) es la extensión para páginas web creadas para mostrarse en navegadores. Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/web/html).


### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language) es la extensión para páginas web creadas para mostrarse en navegadores. Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/web/html).


### Mht {#Mht}
```
public static final WebFileType Mht
```


Los archivos con extensión MHTML representan un formato de archivo de archivo de página web que puede ser creado por varias aplicaciones diferentes. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/web/mhtml).


### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


Los archivos con extensión MHTML representan un formato de archivo de archivo de página web que puede ser creado por varias aplicaciones diferentes. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/web/mhtml).


### Chm {#Chm}
```
public static final WebFileType Chm
```


El formato de archivo CHM representa el archivo de ayuda HTML de Microsoft que consta de una colección de páginas HTML. Proporciona un índice para acceder rápidamente a los temas y una navegación a diferentes partes del documento de ayuda. Obtén más información sobre este formato de archivo [aquí](../https://docs.fileformat.com/web/chm).


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
