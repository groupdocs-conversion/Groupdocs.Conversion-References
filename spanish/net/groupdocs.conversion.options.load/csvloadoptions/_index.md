---
title: CsvLoadOptions
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Opciones para cargar documentos Csv.
type: docs
weight: 1860
url: /es/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

Opciones para cargar documentos Csv.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | Inicializa una nueva instancia de[`CsvLoadOptions`](../csvloadoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Si verifica la restricción del archivo de Excel cuando el usuario modifica los objetos relacionados con las celdas. Por ejemplo, Excel no permite ingresar un valor de cadena de más de 32K. Cuando ingresa un valor mayor a 32K, si esta propiedad es verdadera, obtendrá una excepción. Si esta propiedad es falsa, aceptaremos su valor de cadena de entrada como el valor de la celda para que luego pueda generar el valor de cadena completo para otros formatos de archivo como CSV. Sin embargo, si ha establecido un tipo de valor que no es válido para el formato de archivo de Excel, no debe guardar el libro de trabajo como formato de archivo de Excel más adelante. De lo contrario, puede haber un error inesperado para el archivo de Excel generado. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | Indica si la cadena en el archivo se convierte a la fecha. El valor predeterminado es Verdadero. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | Indica si la cadena del archivo se convierte a numérico. El valor predeterminado es Verdadero. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Convertir rango específico al convertir a otro formato que no sea hoja de cálculo. Ejemplo: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Obtener o configurar la información cultural del sistema en el momento en que se carga el archivo |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Fuente predeterminada para documento de hoja de cálculo. La siguiente fuente se utilizará si falta una fuente. |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | Codificación. El valor predeterminado es Codificación.Predeterminado. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Sustituir fuentes específicas al convertir un documento de hoja de cálculo. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Tipo de archivo de documento de entrada. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo de documento de entrada. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | Indica si el texto es fórmula si comienza con "=". |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Ocultar comentarios. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | Verdadero significa que el archivo contiene varias codificaciones. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página en el documento PDF. El valor predeterminado es verdadero. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Si es Verdadero y se convierte a Pdf, la conversión está optimizada para un mejor tamaño de archivo que la calidad de impresión. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Establecer contraseña para desproteger documento protegido. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Delimitador de un archivo Csv. |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Nombre de hoja a convertir |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Mostrar líneas de cuadrícula al convertir archivos de Excel. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Mostrar hojas ocultas al convertir archivos de Excel. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Omite filas y columnas vacías al convertir. El valor predeterminado es Verdadero. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Clona la instancia actual. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* espacio de nombres [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->