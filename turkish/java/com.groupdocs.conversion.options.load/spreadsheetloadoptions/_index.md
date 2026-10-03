---
title: "SpreadsheetLoadOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Elektronik tablo belgelerini yükleme seçenekleri."
type: docs
weight: 31
url: /tr/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

Elektronik tablo belgelerini yükleme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Yeni bir [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) sınıfının örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSheets()](#getSheets--) | Dönüştürülecek sayfa adını al |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Dönüştürülecek sayfa adını ayarla |
|
|  | [getCultureInfo()](#getCultureInfo--) | Dosya yüklendiği anda sistem kültür bilgisini al |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Dosya yüklendiği anda sistem kültür bilgisini ayarla |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Elektronik tablo belgesi için varsayılan yazı tipi. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Elektronik tablo belgesi için varsayılan yazı tipi. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Elektronik tablo belgesini dönüştürürken belirli yazı tiplerini değiştir. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Elektronik tablo belgesini dönüştürürken belirli yazı tiplerini değiştir. |
|
|  | [getShowGridLines()](#getShowGridLines--) | Excel dosyalarını dönüştürürken ızgara çizgilerini göster. |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Excel dosyalarını dönüştürürken ızgara çizgilerini göster. |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | Excel dosyalarını dönüştürürken gizli sayfaları göster. |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Excel dosyalarını dönüştürürken gizli sayfaları göster. |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | OnePagePerSheet true ise, sayfanın içeriği PDF belgesinde tek sayfaya dönüştürülür. |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | OnePagePerSheet true ise, sayfanın içeriği PDF belgesinde tek sayfaya dönüştürülür. |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | AllColumnsInOnePagePerSheet özelliğini alır |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | AllColumnsInOnePagePerSheet özelliğini ayarlar |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | True ise ve Pdf'ye dönüştürülüyorsa, dönüşüm baskı kalitesinden daha iyi dosya boyutu için optimize edilir. |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | True ise ve Pdf'ye dönüştürülüyorsa, dönüşüm baskı kalitesinden daha iyi dosya boyutu için optimize edilir. |
|
|  | [getConvertRange()](#getConvertRange--) | Elektronik tablo formatı dışındaki bir formata dönüştürürken belirli bir aralığı dönüştür. |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Elektronik tablo formatı dışındaki bir formata dönüştürürken belirli bir aralığı dönüştür. |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Dönüştürürken boş satırları ve sütunları atlar. |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Dönüştürürken boş satırları ve sütunları atlar. |
|
|  | [getPassword()](#getPassword--) | Korunan belgeyi korumasız hale getirmek için şifre belirle. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Korunan belgeyi korumasız hale getirmek için şifre belirle. |
|
|  | [getHideComments()](#getHideComments--) | Yorumları gizle. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | Yorumları gizle. |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde excel dosyasının kısıtlamalarını kontrol edip etmeyeceği. |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | Dönüştürülecek sayfa indekslerinin listesini alır. |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Dönüştürülecek sayfa indekslerinin listesini ayarlar |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | Dönüştürürken tüm satırları otomatik olarak sığdır. |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | Belgeyi yüklemeden önce yazı tipi klasörlerini sıfırla |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | Mevcut örneği klonlar. |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | Bir çalışma sayfasını satırlara göre sayfalara böl. |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | Bir çalışma sayfasını satırlara göre sayfalara böl. |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | Bir çalışma sayfasını sütunlara göre sayfalara böl |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | Bir çalışma sayfasını sütunlara göre sayfalara böl |
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


Yeni bir [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) sınıfının örneğini başlatır.


### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Dönüştürülecek sayfa adını al


**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Dönüştürülecek sayfa adını ayarla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfalar | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Dosya yüklendiği anda sistem kültür bilgisini al


**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Dosya yüklendiği anda sistem kültür bilgisini ayarla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Girdi belge dosya türü


**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Elektronik tablo belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Elektronik tablo belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Elektronik tablo belgesini dönüştürürken belirli yazı tiplerini değiştir.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Elektronik tablo belgesini dönüştürürken belirli yazı tiplerini değiştir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Excel dosyalarını dönüştürürken ızgara çizgilerini göster.


**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Excel dosyalarını dönüştürürken ızgara çizgilerini göster.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Excel dosyalarını dönüştürürken gizli sayfaları göster.


**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Excel dosyalarını dönüştürürken gizli sayfaları göster.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


OnePagePerSheet true ise, sayfanın içeriği PDF belgesinde tek sayfaya dönüştürülecektir. Varsayılan değer false'tur.


**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


OnePagePerSheet true ise, sayfanın içeriği PDF belgesinde tek sayfaya dönüştürülecektir. Varsayılan değer false'tur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


AllColumnsInOnePagePerSheet özelliğini alır


**Returns:**
boolean - tüm sütunları tek sayfaya sığdırıyorsa true

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


AllColumnsInOnePagePerSheet özelliğini ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | boolean | AllColumnsInOnePagePerSheet özelliği |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


True ise ve Pdf'ye dönüştürülüyorsa, dönüşüm baskı kalitesinden daha iyi dosya boyutu için optimize edilir.


**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


True ise ve Pdf'ye dönüştürülüyorsa, dönüşüm baskı kalitesinden daha iyi dosya boyutu için optimize edilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Elektronik tablo formatı dışına dönüştürürken belirli bir aralığı dönüştür. Örnek: "D1:F8".


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Elektronik tablo formatı dışına dönüştürürken belirli bir aralığı dönüştür. Örnek: "D1:F8".


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Dönüştürürken boş satır ve sütunları atlar. Varsayılan değer True'tır.


**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Dönüştürürken boş satır ve sütunları atlar. Varsayılan değer True'tır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Korunan belgeyi korumasız hale getirmek için şifre belirle.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Korunan belgeyi korumasız hale getirmek için şifre belirle.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Yorumları gizle.


**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Yorumları gizle.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Kullanıcı hücre ile ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamalarının kontrol edilip edilmediği. Örneğin, Excel 32K'dan uzun bir metin değerinin girilmesine izin vermez. 32K'dan uzun bir değer girerseniz, bu özellik true ise bir İstisna alırsınız. Bu özellik false ise, girdiğiniz metin değerini hücrenin değeri olarak kabul ederiz, böylece daha sonra CSV gibi diğer dosya formatları için tam metin değerini çıktılayabilirsiniz. Ancak, Excel dosya formatı için geçersiz bir değer ayarladıysanız, çalışma kitabını daha sonra Excel dosya formatı olarak kaydetmemelisiniz. Aksi takdirde oluşturulan Excel dosyasında beklenmeyen hatalar oluşabilir.


**Returns:**
boolean - kısıtlama kontrol bayrağı

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Dönüştürülecek sayfa indekslerinin listesini alır.


**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Dönüştürülecek sayfa indekslerinin Listesini ayarlar. İndeksler sıfır tabanlı olmalıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


Dönüştürürken tüm satırları otomatik olarak sığdır.


**Returns:**
boolean
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| autoFitRows | boolean |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Belgeyi yüklemeden önce yazı tipi klasörlerini sıfırla


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resetFontFolders | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mevcut örneği klonlar.


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


Çalışma sayfasını satırlara göre sayfalara böl. Varsayılan değer 0, sayfalama yok.


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


Çalışma sayfasını satırlara göre sayfalara böl. Varsayılan değer 0, sayfalama yok.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


Çalışma sayfasını sütunlara göre sayfalara böl. Varsayılan değer 0, sayfalama yok.


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


Çalışma sayfasını sütunlara göre sayfalara böl. Varsayılan değer 0, sayfalama yok.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnsPerPage | int |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Belge konteynerinin kendisinin dönüştürülüp dönüştürülmeyeceğini kontrol etmek için seçeneği alır


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Belge konteynerindeki sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini kontrol etme seçeneği


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Dönüştürmenin kaç derinlik seviyesinde yapılacağını kontrol etme seçeneği


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| depth | int |  |

