---
title: "EmailFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define los formatos de archivo de correo electrónico que son usados por las aplicaciones de correo para almacenar sus diversos datos, incluidos mensajes de correo, archivos adjuntos, carpetas, libretas de direcciones, etc. Incluye los siguientes tipos de archivo: Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. Obtén más información sobre los formatos de correo electrónico aquíhttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /es/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Define los formatos de archivo de correo electrónico que son utilizados por las aplicaciones de correo para almacenar sus diversos datos, incluidos mensajes de correo, archivos adjuntos, carpetas, libretas de direcciones, etc. Incluye los siguientes tipos de archivo: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). Obtén más información sobre los formatos de correo electrónico [aquí](https://wiki.fileformat.com/email).

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
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La familia del archivo |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato del archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | El formato de archivo EML representa mensajes de correo electrónico guardados usando Outlook y otras aplicaciones relevantes. Casi todos los clientes de correo admiten este formato de archivo por su cumplimiento con el estándar RFC-822 Internet Message Format. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | El formato de archivo EMLX es implementado y desarrollado por Apple. La aplicación Apple Mail utiliza el formato de archivo EMLX para exportar los correos electrónicos. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | El formato de archivo ICS (iCalendar) se utiliza para representar e intercambiar información de calendario y programación, como eventos, tareas y datos de disponibilidad. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | El formato de archivo MBox es un término genérico que representa un contenedor para una colección de mensajes de correo electrónico. Los mensajes se almacenan dentro del contenedor junto con sus archivos adjuntos. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | Un archivo con extensión .olm es un archivo de Microsoft Outlook para el sistema operativo macOS. Un archivo OLM almacena mensajes de correo electrónico, diarios, datos de calendario y otros tipos de datos de la aplicación. Son similares a los archivos PST utilizados por Outlook en Windows. Sin embargo, los archivos OLM creados por Outlook para Mac no pueden abrirse en Outlook para Windows. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | Los archivos OST o Offline Storage representan los datos del buzón del usuario en modo offline en la máquina local tras registrarse en un servidor Exchange mediante Microsoft Outlook. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Los archivos con extensión .PST representan los archivos de almacenamiento personal de Outlook (también llamados Personal Storage Table) que almacenan una variedad de información del usuario. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) o vCard es un formato de archivo digital para almacenar información de contactos. El formato se utiliza ampliamente para el intercambio de datos entre aplicaciones populares de intercambio de información. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/email/vcf). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
