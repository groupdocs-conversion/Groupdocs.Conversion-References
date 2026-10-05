---
title: "EmailFileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define los formatos de archivo de correo electrónico que son utilizados por las aplicaciones de correo para almacenar sus diversos datos, incluidos mensajes de correo, archivos adjuntos, carpetas, libretas de direcciones, etc."
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Define los formatos de archivo de correo electrónico que son utilizados por las aplicaciones de correo para almacenar sus diversos datos, incluidos mensajes de correo, archivos adjuntos, carpetas, libretas de direcciones, etc. Incluye los siguientes tipos de archivo: [Eml](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Eml), [Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Emlx), [Msg](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Msg), [Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Vcf). [Pst](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Pst). [Ost](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Ost). [Olm](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Olm). Obtén más información sobre los formatos de correo electrónico [aquí][].


[here]: https://wiki.fileformat.com/email
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmailFileType()](#EmailFileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Msg](#Msg) | MSG es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. |
| [Eml](#Eml) | El formato de archivo EML representa mensajes de correo electrónico guardados usando Outlook y otras aplicaciones relevantes. |
| [Emlx](#Emlx) | El formato de archivo EMLX es implementado y desarrollado por Apple. |
| [Vcf](#Vcf) | VCF (Formato de Tarjeta Virtual) o vCard es un formato de archivo digital para almacenar información de contactos. |
| [Mbox](#Mbox) | El formato de archivo MBox es un término genérico que representa un contenedor para una colección de mensajes de correo electrónico. |
| [Pst](#Pst) | Los archivos con extensión .PST representan los Archivos de Almacenamiento Personal de Outlook (también llamados Tabla de Almacenamiento Personal) que almacenan una variedad de información del usuario. |
| [Ost](#Ost) | OST o Archivos de Almacenamiento Offline representan los datos del buzón del usuario en modo offline en la máquina local tras el registro con Exchange Server usando Microsoft Outlook. |
| [Olm](#Olm) | Un archivo con extensión .olm es un archivo de Microsoft Outlook para el sistema operativo Mac. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Constructor de serialización

### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/email/msg

### Eml {#Eml}
```
public static final EmailFileType Eml
```


El formato de archivo EML representa mensajes de correo electrónico guardados usando Outlook y otras aplicaciones relevantes. Casi todos los clientes de correo admiten este formato de archivo por su cumplimiento con el estándar RFC-822 Internet Message Format. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/email/eml

### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


El formato de archivo EMLX es implementado y desarrollado por Apple. La aplicación Apple Mail utiliza el formato de archivo EMLX para exportar los correos electrónicos. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/email/emlx

### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Formato de Tarjeta Virtual) o vCard es un formato de archivo digital para almacenar información de contactos. El formato es ampliamente utilizado para el intercambio de datos entre aplicaciones populares de intercambio de información. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/email/vcf

### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


El formato de archivo MBox es un término genérico que representa un contenedor para una colección de mensajes de correo electrónico. Los mensajes se almacenan dentro del contenedor junto con sus archivos adjuntos. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/email/mbox/

### Pst {#Pst}
```
public static final EmailFileType Pst
```


Los archivos con extensión .PST representan los Archivos de Almacenamiento Personal de Outlook (también llamados Personal Storage Table) que almacenan una variedad de información del usuario. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/email/pst

### Ost {#Ost}
```
public static final EmailFileType Ost
```


Los archivos OST o Offline Storage representan los datos del buzón del usuario en modo offline en la máquina local tras el registro con Exchange Server mediante Microsoft Outlook. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/email/ost

### Olm {#Olm}
```
public static final EmailFileType Olm
```


Un archivo con extensión .olm es un archivo de Microsoft Outlook para el sistema operativo Mac. Un archivo OLM almacena mensajes de correo electrónico, diarios, datos de calendario y otros tipos de datos de aplicación. Estos son similares a los archivos PST utilizados por Outlook en el sistema operativo Windows. Sin embargo, los archivos OLM creados por Outlook para Mac no pueden\\u2019abrirse en Outlook para Windows. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/email/olm

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
