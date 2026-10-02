---
title: "SpreadsheetLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات جدول البيانات."
type: docs
weight: 31
url: /ar/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

خيارات تحميل مستندات جدول البيانات.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | يُنشئ مثلاً جديدًا من الفئة [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSheets()](#getSheets--) | احصل على اسم الورقة للتحويل |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | حدد اسم الورقة للتحويل |
|
|  | [getCultureInfo()](#getCultureInfo--) | احصل على معلومات الثقافة النظامية في وقت تحميل الملف |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | حدد معلومات الثقافة النظامية في وقت تحميل الملف |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | الخط الافتراضي لمستند الجدول. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | الخط الافتراضي لمستند الجدول. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | استبدل الخطوط المحددة عند تحويل مستند الجدول. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | استبدل الخطوط المحددة عند تحويل مستند الجدول. |
|
|  | [getShowGridLines()](#getShowGridLines--) | إظهار خطوط الشبكة عند تحويل ملفات Excel. |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | إظهار خطوط الشبكة عند تحويل ملفات Excel. |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | إظهار الأوراق المخفية عند تحويل ملفات Excel. |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | إظهار الأوراق المخفية عند تحويل ملفات Excel. |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | إذا كان OnePagePerSheet صحيحًا، فسيتم تحويل محتوى الورقة إلى صفحة واحدة في مستند PDF. |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | إذا كان OnePagePerSheet صحيحًا، فسيتم تحويل محتوى الورقة إلى صفحة واحدة في مستند PDF. |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | يحصل على خاصية AllColumnsInOnePagePerSheet |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | يضبط خاصية AllColumnsInOnePagePerSheet |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | إذا كان True وعند التحويل إلى PDF، يتم تحسين التحويل للحصول على حجم ملف أفضل من جودة الطباعة. |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | إذا كان True وعند التحويل إلى PDF، يتم تحسين التحويل للحصول على حجم ملف أفضل من جودة الطباعة. |
|
|  | [getConvertRange()](#getConvertRange--) | تحويل نطاق محدد عند التحويل إلى صيغة غير جدولية. |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | تحويل نطاق محدد عند التحويل إلى صيغة غير جدولية. |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | يتخطى الصفوف والأعمدة الفارغة عند التحويل. |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | يتخطى الصفوف والأعمدة الفارغة عند التحويل. |
|
|  | [getPassword()](#getPassword--) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | تعيين كلمة مرور لإلغاء حماية المستند المحمي. |
|
|  | [getHideComments()](#getHideComments--) | إخفاء التعليقات. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | إخفاء التعليقات. |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | ما إذا كان يتم التحقق من قيود ملف Excel عندما يقوم المستخدم بتعديل الكائنات المتعلقة بالخلايا. |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | يحصل على قائمة فهارس الأوراق للتحويل. |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | يضبط قائمة فهارس الأوراق للتحويل. |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | تعديل حجم جميع الصفوف تلقائيًا عند التحويل |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | إعادة تعيين مجلدات الخطوط قبل تحميل المستند. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | ينسخ النسخة الحالية. |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | تقسيم ورقة العمل إلى صفحات حسب الصفوف. |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | تقسيم ورقة العمل إلى صفحات حسب الصفوف. |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | تقسيم ورقة العمل إلى صفحات حسب الأعمدة. |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | تقسيم ورقة العمل إلى صفحات حسب الأعمدة. |
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


يُنشئ مثلاً جديدًا من الفئة [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions).


### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


احصل على اسم الورقة للتحويل


**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


حدد اسم الورقة للتحويل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| أوراق | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


احصل على معلومات الثقافة النظامية في وقت تحميل الملف


**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


حدد معلومات الثقافة النظامية في وقت تحميل الملف


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


نوع ملف المستند الإدخالي


**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


الخط الافتراضي لمستند جدول البيانات. سيتم استخدام الخط التالي إذا كان الخط مفقودًا.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


الخط الافتراضي لمستند جدول البيانات. سيتم استخدام الخط التالي إذا كان الخط مفقودًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


استبدل الخطوط المحددة عند تحويل مستند الجدول.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


استبدل الخطوط المحددة عند تحويل مستند الجدول.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


إظهار خطوط الشبكة عند تحويل ملفات Excel.


**Returns:**
منطقي
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


إظهار خطوط الشبكة عند تحويل ملفات Excel.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


إظهار الأوراق المخفية عند تحويل ملفات Excel.


**Returns:**
منطقي
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


إظهار الأوراق المخفية عند تحويل ملفات Excel.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


إذا كان OnePagePerSheet صحيحًا، سيتم تحويل محتوى الورقة إلى صفحة واحدة في مستند PDF. القيمة الافتراضية هي false.


**Returns:**
منطقي
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


إذا كان OnePagePerSheet صحيحًا، سيتم تحويل محتوى الورقة إلى صفحة واحدة في مستند PDF. القيمة الافتراضية هي false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


يحصل على خاصية AllColumnsInOnePagePerSheet


**Returns:**
منطقي - true إذا تم ضبط جميع الأعمدة لتناسب صفحة واحدة

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


يضبط خاصية AllColumnsInOnePagePerSheet


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | منطقي | خاصية AllColumnsInOnePagePerSheet |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


إذا كان True وعند التحويل إلى PDF، يتم تحسين التحويل للحصول على حجم ملف أفضل من جودة الطباعة.


**Returns:**
منطقي
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


إذا كان True وعند التحويل إلى PDF، يتم تحسين التحويل للحصول على حجم ملف أفضل من جودة الطباعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


تحويل النطاق المحدد عند التحويل إلى تنسيق غير جدول البيانات. مثال: "D1:F8".


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


تحويل النطاق المحدد عند التحويل إلى تنسيق غير جدول البيانات. مثال: "D1:F8".


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


يتخطى الصفوف والأعمدة الفارغة عند التحويل. القيمة الافتراضية هي True.


**Returns:**
منطقي
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


يتخطى الصفوف والأعمدة الفارغة عند التحويل. القيمة الافتراضية هي True.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


تعيين كلمة مرور لإلغاء حماية المستند المحمي.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


تعيين كلمة مرور لإلغاء حماية المستند المحمي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


إخفاء التعليقات.


**Returns:**
منطقي
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


إخفاء التعليقات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


ما إذا كان يتم التحقق من قيود ملف excel عندما يقوم المستخدم بتعديل الكائنات المتعلقة بالخلايا. على سبيل المثال، لا يسمح excel بإدخال قيمة نصية أطول من 32K. عندما تدخل قيمة أطول من 32K، إذا كانت هذه الخاصية true، ستحصل على Exception. إذا كانت هذه الخاصية false، سنقبل قيمة السلسلة التي أدخلتها كقيمة الخلية بحيث يمكنك لاحقًا إخراج القيمة الكاملة للملفات الأخرى مثل CSV. ومع ذلك، إذا قمت بتعيين قيمة غير صالحة لتنسيق ملف excel، يجب ألا تحفظ المصنف بتنسيق excel لاحقًا. وإلا قد يحدث خطأ غير متوقع في ملف excel المُنشأ.


**Returns:**
منطقي - علامة التحقق من القيود

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| checkExcelRestriction | منطقي |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


يحصل على قائمة فهارس الأوراق للتحويل.


**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


يضبط قائمة مؤشرات الأوراق للتحويل. يجب أن تكون المؤشرات صفرية الأساس


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


تعديل حجم جميع الصفوف تلقائيًا عند التحويل


**Returns:**
منطقي
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| autoFitRows | منطقي |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


إعادة تعيين مجلدات الخطوط قبل تحميل المستند.


**Returns:**
منطقي
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resetFontFolders | منطقي |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


ينسخ النسخة الحالية.


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


تقسيم ورقة العمل إلى صفحات حسب الصفوف. القيمة الافتراضية هي 0، بدون ترقيم صفحات.


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


تقسيم ورقة العمل إلى صفحات حسب الصفوف. القيمة الافتراضية هي 0، بدون ترقيم صفحات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


تقسيم ورقة العمل إلى صفحات حسب الأعمدة. القيمة الافتراضية هي 0، بدون ترقيم صفحات.


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


تقسيم ورقة العمل إلى صفحات حسب الأعمدة. القيمة الافتراضية هي 0، بدون ترقيم صفحات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| columnsPerPage | int |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


يحصل على خيار للتحكم فيما إذا كان يجب تحويل حاوية المستندات نفسها


**Returns:**
منطقي
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOwner | منطقي |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


خيار للتحكم فيما إذا كان يجب تحويل المستندات المملوكة في حاوية المستندات


**Returns:**
منطقي
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| convertOwned | منطقي |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


خيار للتحكم بعدد المستويات في العمق التي يتم فيها إجراء التحويل


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| depth | int |  |

