---
title: EmailFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define los formatos de archivo de correo electrónico que utilizan las aplicaciones de correo electrónico para almacenar sus diversos datos incluidos mensajes de correo electrónico archivos adjuntos carpetas libretas de direcciones etc. Incluye los siguientes tipos de archivo Eml./emailfiletype/eml  Emlx./emailfiletype/emlx  Msg./emailfiletype/msg  Vcf./emailfiletype/vcf . Mbox./emailfiletype/mbox . Pst./emailfiletype/pst . Ost./emailfiletype/ost . Obtenga más información sobre los formatos de correo electrónicoaquíhttps//wiki.fileformat.com/email .
type: docs
weight: 920
url: /es/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Define los formatos de archivo de correo electrónico que utilizan las aplicaciones de correo electrónico para almacenar sus diversos datos, incluidos mensajes de correo electrónico, archivos adjuntos, carpetas, libretas de direcciones, etc. Incluye los siguientes tipos de archivo: [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Vcf`](./vcf) . [`Mbox`](./mbox) . [`Pst`](./pst) . [`Ost`](./ost) . Obtenga más información sobre los formatos de correo electrónico[aquí](https://wiki.fileformat.com/email) .

```csharp
public sealed class EmailFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmailFileType](emailfiletype)() | Constructor de serialización |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descripción del tipo de archivo |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | La extensión del archivo |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | El archivo family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato de archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | El formato de archivo EML representa los mensajes de correo electrónico guardados con Outlook y otras aplicaciones relevantes. Casi todos los clientes de correo electrónico admiten este formato de archivo para cumplir con el estándar de formato de mensajes de Internet RFC-822. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/email/eml) . |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Apple implementa y desarrolla el formato de archivo EMLX. La aplicación Apple Mail utiliza el formato de archivo EMLX para exportar los correos electrónicos. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/email/emlx) . |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | El formato de archivo MBox es un término genérico que representa un contenedor para la recopilación de mensajes de correo electrónico. Los mensajes se almacenan dentro del contenedor junto con sus archivos adjuntos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/email/msg) . |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST o archivos de almacenamiento fuera de línea representan los datos del buzón de correo del usuario en modo fuera de línea en la máquina local al registrarse con Exchange Server usando Microsoft Outlook. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/email/ost) . |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Los archivos con la extensión .PST representan archivos de almacenamiento personal de Outlook (también llamados tablas de almacenamiento personal) que almacenan una variedad de información del usuario. Obtenga más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/email/pst) . |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (formato de tarjeta virtual) o vCard es un formato de archivo digital para almacenar información de contacto. El formato es ampliamente utilizado para el intercambio de datos entre aplicaciones populares de intercambio de información. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/email/vcf) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
