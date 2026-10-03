---
title: "SpreadsheetLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos de hoja de cálculo."
type: docs
weight: 31
url: /es/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

Opciones para cargar documentos de hoja de cálculo.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Inicializa una nueva instancia de la clase [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSheets()](#getSheets--) | Obtener el nombre de la hoja a convertir |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Establecer el nombre de la hoja a convertir |
|
|  | [getCultureInfo()](#getCultureInfo--) | Obtener la información de cultura del sistema en el momento en que se carga el archivo |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Establecer la información de cultura del sistema en el momento en que se carga el archivo |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Fuente predeterminada para el documento de hoja de cálculo. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Fuente predeterminada para el documento de hoja de cálculo. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Sustituir fuentes específicas al convertir el documento de hoja de cálculo. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sustituir fuentes específicas al convertir el documento de hoja de cálculo. |
|
|  | [getShowGridLines()](#getShowGridLines--) | Mostrar líneas de cuadrícula al convertir archivos de Excel. |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Mostrar líneas de cuadrícula al convertir archivos de Excel. |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | Mostrar hojas ocultas al convertir archivos de Excel. |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Mostrar hojas ocultas al convertir archivos de Excel. |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página del documento PDF. |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página del documento PDF. |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Obtiene la propiedad AllColumnsInOnePagePerSheet |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Establece la propiedad AllColumnsInOnePagePerSheet |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | Si es verdadero y se convierte a PDF, la conversión se optimiza para obtener un mejor tamaño de archivo que la calidad de impresión. |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Si es verdadero y se convierte a PDF, la conversión se optimiza para obtener un mejor tamaño de archivo que la calidad de impresión. |
|
|  | [getConvertRange()](#getConvertRange--) | Convertir un rango específico al convertir a un formato distinto de hoja de cálculo. |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Convertir un rango específico al convertir a un formato distinto de hoja de cálculo. |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Omite filas y columnas vacías al convertir. |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Omite filas y columnas vacías al convertir. |
|
|  | [getPassword()](#getPassword--) | Establecer contraseña para desproteger el documento protegido. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establecer contraseña para desproteger el documento protegido. |
|
|  | [getHideComments()](#getHideComments--) | Ocultar comentarios. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Ocultar comentarios. |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Indica si se verifica la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas. |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | Obtiene la lista de índices de hojas a convertir. |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Establece la lista de índices de hojas a convertir. |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | Ajusta automáticamente todas las filas al convertir |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | Restablecer carpetas de fuentes antes de cargar el documento |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | Clona la instancia actual. |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | Dividir una hoja de cálculo en páginas por filas. |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | Dividir una hoja de cálculo en páginas por filas. |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | Dividir una hoja de cálculo en páginas por columnas. |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | Dividir una hoja de cálculo en páginas por columnas. |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
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


Fuente predeterminada para el documento de hoja de cálculo. La siguiente fuente se utilizará si falta una fuente.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Fuente predeterminada para el documento de hoja de cálculo. La siguiente fuente se utilizará si falta una fuente.


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
booleano
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Mostrar líneas de cuadrícula al convertir archivos de Excel.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Mostrar hojas ocultas al convertir archivos de Excel.


**Returns:**
booleano
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Mostrar hojas ocultas al convertir archivos de Excel.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página del documento PDF. El valor predeterminado es falso.


**Returns:**
booleano
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Si OnePagePerSheet es verdadero, el contenido de la hoja se convertirá en una página del documento PDF. El valor predeterminado es falso.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Obtiene la propiedad AllColumnsInOnePagePerSheet


**Returns:**
boolean - verdadero si ajusta todas las columnas a una página

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Establece la propiedad AllColumnsInOnePagePerSheet


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | booleano | propiedad AllColumnsInOnePagePerSheet |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Si es verdadero y se convierte a PDF, la conversión se optimiza para obtener un mejor tamaño de archivo que la calidad de impresión.


**Returns:**
booleano
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Si es verdadero y se convierte a PDF, la conversión se optimiza para obtener un mejor tamaño de archivo que la calidad de impresión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Convertir rango específico al convertir a un formato que no sea de hoja de cálculo. Ejemplo: "D1:F8".


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Convertir rango específico al convertir a un formato que no sea de hoja de cálculo. Ejemplo: "D1:F8".


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Omite filas y columnas vacías al convertir. El valor predeterminado es Verdadero.


**Returns:**
booleano
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Omite filas y columnas vacías al convertir. El valor predeterminado es Verdadero.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

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
booleano
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Ocultar comentarios.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Indica si se verifica la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas. Por ejemplo, Excel no permite ingresar un valor de cadena mayor a 32 K. Cuando ingresas un valor mayor a 32 K, si esta propiedad es verdadera, obtendrás una Exception. Si esta propiedad es falsa, aceptaremos tu cadena ingresada como el valor de la celda, de modo que luego puedas exportar el valor completo de la cadena a otros formatos de archivo como CSV. Sin embargo, si has establecido un valor de este tipo que es inválido para el formato de archivo Excel, no deberías guardar el libro de trabajo como formato Excel más adelante. De lo contrario, podría haber errores inesperados en el archivo Excel generado.


**Returns:**
boolean - indicador de verificación de restricción

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| checkExcelRestriction | booleano |  |

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
booleano
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| autoFitRows | booleano |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Restablecer carpetas de fuentes antes de cargar el documento


**Returns:**
booleano
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resetFontFolders | booleano |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona la instancia actual.


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


Dividir una hoja de cálculo en páginas por filas. El valor predeterminado es 0, sin paginación.


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


Dividir una hoja de cálculo en páginas por filas. El valor predeterminado es 0, sin paginación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


Dividir una hoja de cálculo en páginas por columnas. El valor predeterminado es 0, sin paginación.


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


Dividir una hoja de cálculo en páginas por columnas. El valor predeterminado es 0, sin paginación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnsPerPage | int |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Obtiene la opción para controlar si el contenedor de los documentos debe convertirse


**Returns:**
booleano
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwner | booleano |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opción para controlar si los documentos propios en el contenedor de documentos deben convertirse


**Returns:**
booleano
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOwned | booleano |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Opción para controlar cuántos niveles de profundidad se deben usar para realizar la conversión


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| depth | int |  |

