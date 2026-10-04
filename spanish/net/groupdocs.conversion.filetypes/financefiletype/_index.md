---
title: "TipoDeArchivoFinanciero"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define documentos financieros. Incluye los siguientes tipos Xbrl./financefiletype/xbrlIXbrl./financefiletype/ixbrlOfx./financefiletype/ofx. Obtén más información sobre los formatos financieros aquí https//docs.fileformat.com/finance/."
type: docs
weight: 1140
url: /es/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

Define documentos financieros. Incluye los siguientes tipos: [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx). Obtén más información sobre los formatos financieros [aquí](https://docs.fileformat.com/finance/).

```csharp
public sealed class FinanceFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FinanceFileType](financefiletype)() | Constructor de serialización |

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
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | Dentro del iXBRL, el contenido de XBRL está envuelto en el formato de archivo xHTML que utiliza etiquetas XML. Al igual que XBRL, es el elemento raíz de los archivos iXBRL. El formato XHTML representa su contenido como una colección de diferentes tipos de documentos y módulos. Todos los archivos en XHTML se basan en el formato de archivo XML y cumplen con los estándares de documentos XML. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/finance/ixbrl/). |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) es un formato de flujo de datos para intercambiar información financiera que evolucionó a partir de Open Financial Connectivity (OFC) de Microsoft y los formatos de archivo Open Exchange de Intuit. Obtén más información sobre este formato de archivo [aquí](https://en.wikipedia.org/wiki/Open_Financial_Exchange). |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL es un estándar internacional abierto para la presentación digital de informes empresariales que se utiliza ampliamente a nivel mundial. Es un lenguaje basado en XML que usa elementos XBRL, conocidos como etiquetas, para describir cada elemento de datos empresariales y formular datos para la clasificación y análisis de informes. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/finance/xbrl/). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
