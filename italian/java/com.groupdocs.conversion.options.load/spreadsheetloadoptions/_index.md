---
title: "SpreadsheetLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Spreadsheet."
type: docs
weight: 31
url: /it/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

Opzioni per il caricamento dei documenti Spreadsheet.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Inizializza una nuova istanza della classe [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSheets()](#getSheets--) | Ottieni il nome del foglio da convertire |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Imposta il nome del foglio da convertire |
|
|  | [getCultureInfo()](#getCultureInfo--) | Ottieni le informazioni sulla cultura di sistema al momento del caricamento del file |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Imposta le informazioni sulla cultura di sistema al momento del caricamento del file |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Carattere predefinito per il documento di foglio di calcolo. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Carattere predefinito per il documento di foglio di calcolo. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Sostituisci caratteri specifici durante la conversione del documento di foglio di calcolo. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Sostituisci caratteri specifici durante la conversione del documento di foglio di calcolo. |
|
|  | [getShowGridLines()](#getShowGridLines--) | Mostra le linee della griglia durante la conversione dei file Excel. |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Mostra le linee della griglia durante la conversione dei file Excel. |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | Mostra i fogli nascosti durante la conversione dei file Excel. |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Mostra i fogli nascosti durante la conversione dei file Excel. |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | Se OnePagePerSheet è true, il contenuto del foglio verrà convertito in una pagina nel documento PDF. |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | Se OnePagePerSheet è true, il contenuto del foglio verrà convertito in una pagina nel documento PDF. |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Ottiene la proprietà AllColumnsInOnePagePerSheet |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Imposta la proprietà AllColumnsInOnePagePerSheet |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | Se True e si converte in PDF, la conversione è ottimizzata per una dimensione del file migliore rispetto alla qualità di stampa. |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | Se True e si converte in PDF, la conversione è ottimizzata per una dimensione del file migliore rispetto alla qualità di stampa. |
|
|  | [getConvertRange()](#getConvertRange--) | Converti un intervallo specifico quando si converte in un formato diverso da quello del foglio di calcolo. |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Converti un intervallo specifico quando si converte in un formato diverso da quello del foglio di calcolo. |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Salta righe e colonne vuote durante la conversione. |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Salta righe e colonne vuote durante la conversione. |
|
|  | [getPassword()](#getPassword--) | Imposta la password per rimuovere la protezione del documento protetto. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta la password per rimuovere la protezione del documento protetto. |
|
|  | [getHideComments()](#getHideComments--) | Nascondi i commenti. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Nascondi i commenti. |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Indica se verificare le restrizioni del file Excel quando l'utente modifica oggetti correlati alle celle. |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | Ottiene l'elenco degli indici dei fogli da convertire. |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Imposta l'elenco degli indici dei fogli da convertire. |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | Adatta automaticamente tutte le righe durante la conversione |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | Reimposta le cartelle dei caratteri prima di caricare il documento |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | Clona l'istanza corrente. |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | Dividi un foglio di lavoro in pagine per righe. |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | Dividi un foglio di lavoro in pagine per righe. |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | Dividi un foglio di lavoro in pagine per colonne. |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | Dividi un foglio di lavoro in pagine per colonne. |
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


Inizializza una nuova istanza della classe [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions).


### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Ottieni il nome del foglio da convertire


**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Imposta il nome del foglio da convertire


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fogli | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Ottieni le informazioni sulla cultura di sistema al momento del caricamento del file


**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Imposta le informazioni sulla cultura di sistema al momento del caricamento del file


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Carattere predefinito per il documento di foglio di calcolo. Il carattere seguente verrà utilizzato se un carattere è mancante.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Carattere predefinito per il documento di foglio di calcolo. Il carattere seguente verrà utilizzato se un carattere è mancante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Sostituisci caratteri specifici durante la conversione del documento di foglio di calcolo.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Sostituisci caratteri specifici durante la conversione del documento di foglio di calcolo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Mostra le linee della griglia durante la conversione dei file Excel.


**Returns:**
booleano
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Mostra le linee della griglia durante la conversione dei file Excel.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Mostra i fogli nascosti durante la conversione dei file Excel.


**Returns:**
booleano
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Mostra i fogli nascosti durante la conversione dei file Excel.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


Se OnePagePerSheet è true, il contenuto del foglio verrà convertito in una pagina nel documento PDF. Il valore predefinito è false.


**Returns:**
booleano
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


Se OnePagePerSheet è true, il contenuto del foglio verrà convertito in una pagina nel documento PDF. Il valore predefinito è false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Ottiene la proprietà AllColumnsInOnePagePerSheet


**Returns:**
boolean - true se adatta tutte le colonne a una pagina

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Imposta la proprietà AllColumnsInOnePagePerSheet


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | booleano | Proprietà AllColumnsInOnePagePerSheet |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


Se True e si converte in PDF, la conversione è ottimizzata per una dimensione del file migliore rispetto alla qualità di stampa.


**Returns:**
booleano
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


Se True e si converte in PDF, la conversione è ottimizzata per una dimensione del file migliore rispetto alla qualità di stampa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Converti un intervallo specifico durante la conversione in un formato diverso da quello del foglio di calcolo. Esempio: "D1:F8".


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Converti un intervallo specifico durante la conversione in un formato diverso da quello del foglio di calcolo. Esempio: "D1:F8".


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Ignora righe e colonne vuote durante la conversione. Il valore predefinito è True.


**Returns:**
booleano
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Ignora righe e colonne vuote durante la conversione. Il valore predefinito è True.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Imposta la password per rimuovere la protezione del documento protetto.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Imposta la password per rimuovere la protezione del documento protetto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Nascondi i commenti.


**Returns:**
booleano
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Nascondi i commenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Indica se verificare le restrizioni del file Excel quando l'utente modifica gli oggetti correlati alle celle. Ad esempio, Excel non consente l'inserimento di una stringa più lunga di 32K. Quando inserisci un valore più lungo di 32K, se questa proprietà è true, otterrai un'eccezione. Se questa proprietà è false, accetteremo la tua stringa di input come valore della cella, così in seguito potrai esportare la stringa completa per altri formati di file come CSV. Tuttavia, se hai impostato un valore di questo tipo non valido per il formato file Excel, non dovresti salvare la cartella di lavoro come formato file Excel in seguito. Altrimenti potrebbero verificarsi errori imprevisti nel file Excel generato.


**Returns:**
boolean - flag di verifica restrizione

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| checkExcelRestriction | booleano |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Ottiene l'elenco degli indici dei fogli da convertire.


**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Imposta l'elenco degli indici dei fogli da convertire. Gli indici devono essere basati su zero.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Adatta automaticamente tutte le righe durante la conversione


**Returns:**
booleano
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| autoFitRows | booleano |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reimposta le cartelle dei caratteri prima di caricare il documento


**Returns:**
booleano
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resetFontFolders | booleano |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona l'istanza corrente.


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


Dividi un foglio di lavoro in pagine per righe. Il valore predefinito è 0, nessuna paginazione.


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


Dividi un foglio di lavoro in pagine per righe. Il valore predefinito è 0, nessuna paginazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


Dividi un foglio di lavoro in pagine per colonne. Il valore predefinito è 0, nessuna paginazione.


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


Dividi un foglio di lavoro in pagine per colonne. Il valore predefinito è 0, nessuna paginazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnsPerPage | int |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Ottiene l'opzione per controllare se il contenitore dei documenti stesso deve essere convertito


**Returns:**
booleano
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| convertOwner | booleano |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opzione per controllare se i documenti di proprietà nel contenitore dei documenti devono essere convertiti


**Returns:**
booleano
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| convertOwned | booleano |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Opzione per controllare quanti livelli di profondità eseguire la conversione


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| depth | int |  |

