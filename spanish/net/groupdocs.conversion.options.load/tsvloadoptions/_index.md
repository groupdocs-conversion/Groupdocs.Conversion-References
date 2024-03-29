---
title: TsvLoadOptions
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Opciones para cargar documentos Tsv.
type: docs
weight: 2280
url: /es/net/groupdocs.conversion.options.load/tsvloadoptions/
---
## TsvLoadOptions class

Opciones para cargar documentos Tsv.

```csharp
public sealed class TsvLoadOptions : SpreadsheetLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TsvLoadOptions](tsvloadoptions)() | Inicializa una nueva instancia de[`TsvLoadOptions`](../tsvloadoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Si verifica la restricción del archivo de Excel cuando el usuario modifica los objetos relacionados con las celdas. Por ejemplo, Excel no permite ingresar un valor de cadena de más de 32K. Cuando ingresa un valor mayor a 32K, si esta propiedad es verdadera, obtendrá una excepción. Si esta propiedad es falsa, aceptaremos su valor de cadena de entrada como el valor de la celda para que luego pueda generar el valor de cadena completo para otros formatos de archivo como CSV. Sin embargo, si ha establecido un tipo de valor que no es válido para el formato de archivo de Excel, no debe guardar el libro de trabajo como formato de archivo de Excel más adelante. De lo contrario, puede haber un error inesperado para el archivo de Excel generado. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Convertir rango específico al convertir a otro formato que no sea hoja de cálculo. Ejemplo: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Obtener o configurar la información cultural del sistema en el momento en que se carga el archivo |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Fuente predeterminada para documento de hoja de cálculo. La siguiente fuente se utilizará si falta una fuente. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Sustituir fuentes específicas al convertir un documento de hoja de cálculo. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Tipo de archivo de documento de entrada. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo de documento de entrada. |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Ocultar comentarios. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página en el documento PDF. El valor predeterminado es verdadero. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Si es Verdadero y se convierte a Pdf, la conversión está optimizada para un mejor tamaño de archivo que la calidad de impresión. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Establecer contraseña para desproteger documento protegido. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Lista de índices de hojas a convertir. Los índices deben ser de base cero |
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
