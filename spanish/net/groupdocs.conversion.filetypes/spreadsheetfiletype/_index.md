---
title: SpreadsheetFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define documentos de hoja de cálculo. Incluye los siguientes tipos de archivo Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . Obtenga más información sobre los formatos de hoja de cálculoaquíhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 930
url: /es/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Define documentos de hoja de cálculo. Incluye los siguientes tipos de archivo: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Obtenga más información sobre los formatos de hoja de cálculo[aquí](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Constructor de serialización |

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
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Los archivos con extensión CSV (valores separados por comas) representan archivos de texto sin formato que contienen registros de datos con valores separados por comas. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF significa Formato de intercambio de datos que se utiliza para importar/exportar datos de hojas de cálculo entre diferentes aplicaciones. Estos incluyen Microsoft Excel, OpenOffice Calc, StarCalc y muchos otros. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Hoja de cálculo XML plano de OpenDocument |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Los archivos con extensión .numbers se clasifican como archivos de tipo hoja de cálculo, por eso son similares a los archivos .xlsx; pero los archivos de Numbers se crean con el software de hoja de cálculo de Apple iWork Numbers. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Los archivos con extensión ODS representan el formato de documento de hoja de cálculo OpenDocument que el usuario puede editar. Los datos se almacenan dentro del archivo ODF en filas y columnas. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Plantilla de hoja de cálculo OpenDocument |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Un formato basado en XML utilizado por OpenOffice y StarOffice |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Un formato de archivo de valores separados por tabulaciones (TSV) representa datos separados por tabulaciones en formato de texto sin formato. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | formato de documento Xlam |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS representa el formato de archivo binario de Excel. Estos archivos pueden crearse con Microsoft Excel, así como con otros programas de hojas de cálculo similares, como OpenOffice Calc o Apple Numbers. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | El formato de archivo XLSB especifica el formato de archivo binario de Excel, que es una colección de registros y estructuras que especifican el contenido del libro de Excel. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM es un tipo de archivo de hoja de cálculo que admite macros. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX es un formato conocido para documentos de Microsoft Excel que Microsoft introdujo con el lanzamiento de Microsoft Office 2007. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Los archivos con la extensión .XLT son archivos de plantilla creados con Microsoft Excel, que es una aplicación de hoja de cálculo que forma parte del paquete de Microsoft Office. Microsoft Office 97-2003 admitía la creación de nuevos archivos XLT y su apertura. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | La extensión de archivo XLTM representa archivos generados por Microsoft Excel como archivos de plantilla habilitados para macros. Los archivos XLTM son similares a XLTX en estructura, excepto que el último no admite la creación de archivos de plantilla con macros. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | El archivo XLTX representa una plantilla de Microsoft Excel que se basa en las especificaciones de formato de archivo OpenXML de Office. Se utiliza para crear un archivo de plantilla estándar que se puede utilizar para generar archivos XLSX que muestren la misma configuración que se especifica en el archivo XLTX. Obtenga más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xltx) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
