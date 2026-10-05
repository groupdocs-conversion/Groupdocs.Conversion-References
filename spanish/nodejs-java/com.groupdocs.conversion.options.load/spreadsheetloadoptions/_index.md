---
title: "SpreadsheetLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para cargar documentos Spreadsheet."
type: docs
weight: 35
url: /es/nodejs-java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable
```

Opciones para cargar documentos Spreadsheet.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Inicializa una nueva instancia de la clase [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSheets()](#getSheets--) | Obtener el nombre de la hoja a convertir |
| [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Establecer el nombre de la hoja a convertir |
| [getCultureInfo()](#getCultureInfo--) | Obtener la información de cultura del sistema en el momento en que se carga el archivo |
| [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Establecer la información de cultura del sistema en el momento en que se carga el archivo |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Fuente predeterminada para el documento de hoja de cálculo. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Fuente predeterminada para el documento de hoja de cálculo. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Sustituir fuentes específicas al convertir el documento de hoja de cálculo. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sustituir fuentes específicas al convertir el documento de hoja de cálculo. |
| [getShowGridLines()](#getShowGridLines--) | Mostrar líneas de cuadrícula al convertir archivos de Excel. |
| [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Mostrar líneas de cuadrícula al convertir archivos de Excel. |
| [getShowHiddenSheets()](#getShowHiddenSheets--) | Mostrar hojas ocultas al convertir archivos de Excel. |
| [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Mostrar hojas ocultas al convertir archivos de Excel. |
| [getOnePagePerSheet()](#getOnePagePerSheet--) | Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página del documento PDF. |
| [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página del documento PDF. |
| [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Obtiene la propiedad AllColumnsInOnePagePerSheet |
| [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Establece la propiedad AllColumnsInOnePagePerSheet |
| [getOptimizePdfSize()](#getOptimizePdfSize--) | Si es verdadero y se convierte a PDF, la conversión está optimizada para un mejor tamaño de archivo que la calidad de impresión. |
| [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Si es verdadero y se convierte a PDF, la conversión está optimizada para un mejor tamaño de archivo que la calidad de impresión. |
| [getConvertRange()](#getConvertRange--) | Convertir un rango específico al convertir a un formato distinto de hoja de cálculo. |
| [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Convertir un rango específico al convertir a un formato distinto de hoja de cálculo. |
| [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Omite filas y columnas vacías al convertir. |
| [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Omite filas y columnas vacías al convertir. |
| [getPassword()](#getPassword--) | Establecer contraseña para desproteger el documento protegido. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Establecer contraseña para desproteger el documento protegido. |
| [getHideComments()](#getHideComments--) | Ocultar comentarios. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Ocultar comentarios. |
| [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Si se verifica la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas. |
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
| [getSheetIndexes()](#getSheetIndexes--) | Obtiene la lista de índices de hojas a convertir. |
| [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Establece la lista de índices de hojas a convertir. |
| [isAutoFitRows()](#isAutoFitRows--) | Ajusta automáticamente todas las filas al convertir |
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
| [getResetFontFolders()](#getResetFontFolders--) | Restablecer carpetas de fuentes antes de cargar el documento |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
| [deepClone()](#deepClone--) | Clona la instancia actual. |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Inicializa una nueva instancia de la clase [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions).

### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Obtener el nombre de la hoja a convertir

**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Establecer el nombre de la hoja a convertir

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hojas | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Obtener la información de cultura del sistema en el momento en que se carga el archivo

**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Establecer la información de cultura del sistema en el momento en que se carga el archivo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Tipo de archivo del documento de entrada

**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Fuente predeterminada para el documento de hoja de cálculo. La siguiente fuente se usará si falta una fuente.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Fuente predeterminada para el documento de hoja de cálculo. La siguiente fuente se usará si falta una fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sustituir fuentes específicas al convertir el documento de hoja de cálculo.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sustituir fuentes específicas al convertir el documento de hoja de cálculo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Mostrar líneas de cuadrícula al convertir archivos de Excel.

**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Mostrar líneas de cuadrícula al convertir archivos de Excel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Mostrar hojas ocultas al convertir archivos de Excel.

**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Mostrar hojas ocultas al convertir archivos de Excel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página del documento PDF. El valor predeterminado es falso.

**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página del documento PDF. El valor predeterminado es falso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Obtiene la propiedad AllColumnsInOnePagePerSheet

**Returns:**
booleano - verdadero si se ajustan todas las columnas a una página
### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Establece la propiedad AllColumnsInOnePagePerSheet

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| allColumnsInOnePagePerSheet | boolean | propiedad AllColumnsInOnePagePerSheet |

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Si es verdadero y se convierte a PDF, la conversión está optimizada para un mejor tamaño de archivo que la calidad de impresión.

**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Si es verdadero y se convierte a PDF, la conversión está optimizada para un mejor tamaño de archivo que la calidad de impresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Convertir un rango específico al convertir a un formato que no sea de hoja de cálculo. Ejemplo: "D1:F8".

**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Convertir un rango específico al convertir a un formato que no sea de hoja de cálculo. Ejemplo: "D1:F8".

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Omite filas y columnas vacías al convertir. El valor predeterminado es True.

**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Omite filas y columnas vacías al convertir. El valor predeterminado es True.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Establecer contraseña para desproteger el documento protegido.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Establecer contraseña para desproteger el documento protegido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Ocultar comentarios.

**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Ocultar comentarios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Indica si se verifica la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas. Por ejemplo, Excel no permite ingresar un valor de cadena de más de 32K. Cuando ingresas un valor de más de 32K, si esta propiedad es true, obtendrás una Exception. Si esta propiedad es false, aceptaremos la cadena ingresada como el valor de la celda, de modo que luego puedas exportar la cadena completa a otros formatos de archivo como CSV. Sin embargo, si estableces un valor que sea inválido para el formato de archivo Excel, no deberías guardar el libro de trabajo como formato Excel más adelante. De lo contrario, podría producirse un error inesperado en el archivo Excel generado.

**Returns:**
boolean - bandera de verificación de restricción
### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Obtiene la lista de índices de hojas a convertir.

**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Establece la lista de índices de hojas a convertir. Los índices deben comenzar en cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Ajusta automáticamente todas las filas al convertir

**Returns:**
boolean
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| autoFitRows | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Restablecer carpetas de fuentes antes de cargar el documento

**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona la instancia actual.

**Returns:**
java.lang.Object -
