---
title: "CheckExcelRestriction"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Indica si se deben verificar las restricciones del archivo Excel cuando el usuario modifica objetos relacionados con celdas. Por ejemplo, Excel no permite introducir un valor de cadena superior a 32 K. Si introduce un valor mayor a 32 K y esta propiedad es verdadera, obtendrá una excepción. Si la propiedad es falsa, aceptaremos la cadena introducida como valor de la celda, de modo que posteriormente pueda exportar el valor completo a otros formatos de archivo como CSV. Sin embargo, si ha establecido un valor que no es válido para el formato de archivo Excel, no debe guardar el libro de trabajo como formato Excel más adelante. De lo contrario, podrían producirse errores inesperados en el archivo Excel generado."
type: docs
weight: 40
url: /es/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

Indica si se verifica la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas. Por ejemplo, Excel no permite introducir un valor de cadena mayor a 32 K. Cuando introduces un valor mayor a 32 K, si esta propiedad es verdadera, obtendrás una excepción. Si esta propiedad es falsa, aceptaremos tu cadena de entrada como el valor de la celda, de modo que luego puedas exportar la cadena completa a otros formatos de archivo como CSV. Sin embargo, si has establecido un valor que no es válido para el formato de archivo Excel, no deberías guardar el libro de trabajo en formato Excel más adelante. De lo contrario, podría producirse un error inesperado en el archivo Excel generado.

```csharp
public bool CheckExcelRestriction { get; set; }
```

### Ver también

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
