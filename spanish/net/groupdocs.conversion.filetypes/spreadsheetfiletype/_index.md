---
title: "SpreadsheetFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define documentos de hoja de cálculo. Incluye los siguientes tipos de archivo Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. Obtenga más información sobre los formatos de hoja de cálculo aquíhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /es/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Define documentos de hoja de cálculo. Incluye los siguientes tipos de archivo: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Obtenga más información sobre los formatos de hoja de cálculo [aquí](https://wiki.fileformat.com/spreadsheet).

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Los archivos con extensión CSV (Valores Separados por Comas) representan archivos de texto plano que contienen registros de datos con valores separados por comas. Obtenga más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF significa Formato de Intercambio de Datos y se utiliza para importar/exportar datos de hojas de cálculo entre diferentes aplicaciones. Estas incluyen Microsoft Excel, OpenOffice Calc, StarCalc y muchas otras. Obtenga más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel es Office Open XML SpreadsheetML almacenado en un archivo XML plano en lugar de un paquete ZIP. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Un archivo con extensión .fods es un tipo de formato de documento OpenDocument Spreadsheet que almacena datos en filas y columnas. El formato está especificado como parte de las especificaciones ODF 1.2 publicadas y mantenidas por OASIS. Obtenga más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Los archivos con extensión .numbers se clasifican como tipo de archivo de hoja de cálculo, por eso son similares a los archivos .xlsx; pero los archivos Numbers se crean usando el software de hoja de cálculo Apple iWork Numbers. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Los archivos con extensión ODS representan el formato de documento OpenDocument Spreadsheet que es editable por el usuario. Los datos se almacenan dentro del archivo ODF en filas y columnas. Obtenga más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Un archivo con extensión .ots es un archivo de plantilla OpenDocument Spreadsheet que se crea con el software de aplicación Calc incluido en Apache OpenOffice. El software de aplicación Calc es similar a Excel disponible en Microsoft Office. Obtenga más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | El formato de archivo SXC (Sun XML Calc) pertenece a una suite de oficina llamada OpenOffice.org. Este formato generalmente cubre las necesidades de hoja de cálculo de los usuarios ya que es un formato de archivo de hoja de cálculo basado en XML. El formato SXC admite fórmulas, funciones, macros y gráficos junto con DataPilot. Obtenga más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Un formato de archivo de valores separados por tabulaciones (TSV) representa datos separados por tabulaciones en formato de texto plano. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM es un archivo de complemento habilitado para macros que se utiliza para agregar nuevas funciones a las hojas de cálculo. Un complemento es un programa suplementario que ejecuta código adicional y brinda funcionalidad adicional para las hojas de cálculo. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS representa el formato de archivo binario de Excel. Estos archivos pueden ser creados por Microsoft Excel, así como por otros programas de hojas de cálculo similares, como OpenOffice Calc o Apple Numbers. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | El formato de archivo XLSB especifica el Formato de Archivo Binario de Excel, que es una colección de registros y estructuras que definen el contenido de un libro de Excel. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM es un tipo de archivo de hoja de cálculo que admite macros. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX es un formato bien conocido para documentos de Microsoft Excel que fue introducido por Microsoft con el lanzamiento de Microsoft Office 2007. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Los archivos con extensión .XLT son archivos de plantilla creados con Microsoft Excel, que es una aplicación de hoja de cálculo incluida en la suite Microsoft Office. Microsoft Office 97-2003 permitía crear nuevos archivos XLT así como abrirlos. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | La extensión de archivo XLTM representa archivos generados por Microsoft Excel como plantillas habilitadas para macros. Los archivos XLTM son similares a los XLTX en estructura, salvo que estos últimos no admiten crear plantillas con macros. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | El archivo XLTX representa una plantilla de Microsoft Excel basada en las especificaciones del formato de archivo Office OpenXML. Se utiliza para crear un archivo de plantilla estándar que puede emplearse para generar archivos XLSX que presenten la misma configuración especificada en el archivo XLTX. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xltx). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
