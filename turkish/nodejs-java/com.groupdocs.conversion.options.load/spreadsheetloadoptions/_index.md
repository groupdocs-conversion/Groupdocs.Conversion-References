---
title: "SpreadsheetLoadOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Elektronik tablo belgelerini yükleme seçenekleri."
type: docs
weight: 35
url: /tr/nodejs-java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable
```

Elektronik tablo belgelerini yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Yeni bir [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSheets()](#getSheets--) | Dönüştürülecek sayfa adını al |
| [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Dönüştürülecek sayfa adını ayarla |
| [getCultureInfo()](#getCultureInfo--) | Dosya yüklendiğinde sistem kültür bilgisini al |
| [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Dosya yüklendiğinde sistem kültür bilgisini ayarla |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Elektronik tablo belgesi için varsayılan yazı tipi. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Elektronik tablo belgesi için varsayılan yazı tipi. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Elektronik tablo belgesi dönüştürülürken belirli yazı tiplerini değiştir. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Elektronik tablo belgesi dönüştürülürken belirli yazı tiplerini değiştir. |
| [getShowGridLines()](#getShowGridLines--) | Excel dosyaları dönüştürülürken ızgara çizgilerini göster. |
| [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Excel dosyaları dönüştürülürken ızgara çizgilerini göster. |
| [getShowHiddenSheets()](#getShowHiddenSheets--) | Excel dosyaları dönüştürülürken gizli sayfaları göster. |
| [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Excel dosyaları dönüştürülürken gizli sayfaları göster. |
| [getOnePagePerSheet()](#getOnePagePerSheet--) | OnePagePerSheet true ise sayfanın içeriği PDF belgesinde tek sayfaya dönüştürülür. |
| [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | OnePagePerSheet true ise sayfanın içeriği PDF belgesinde tek sayfaya dönüştürülür. |
| [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | AllColumnsInOnePagePerSheet özelliğini alır |
| [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | AllColumnsInOnePagePerSheet özelliğini ayarlar |
| [getOptimizePdfSize()](#getOptimizePdfSize--) | True ise ve PDF'ye dönüştürülüyorsa dönüşüm, baskı kalitesinden daha iyi dosya boyutu için optimize edilir. |
| [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | True ise ve PDF'ye dönüştürülüyorsa dönüşüm, baskı kalitesinden daha iyi dosya boyutu için optimize edilir. |
| [getConvertRange()](#getConvertRange--) | Elektronik tablo formatı dışına dönüştürülürken belirli aralığı dönüştür. |
| [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Elektronik tablo formatı dışına dönüştürülürken belirli aralığı dönüştür. |
| [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Dönüştürürken boş satır ve sütunları atla. |
| [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Dönüştürürken boş satır ve sütunları atla. |
| [getPassword()](#getPassword--) | Korunan belgeyi korumasız hale getirmek için şifre ayarla. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Korunan belgeyi korumasız hale getirmek için şifre ayarla. |
| [getHideComments()](#getHideComments--) | Yorumları gizle. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Yorumları gizle. |
| [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Kullanıcı hücre ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamalarını kontrol edip etmeyeceği. |
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
| [getSheetIndexes()](#getSheetIndexes--) | Dönüştürülecek sayfa indekslerinin listesini alır. |
| [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Dönüştürülecek sayfa indekslerinin listesini ayarlar. |
| [isAutoFitRows()](#isAutoFitRows--) | Dönüştürürken tüm satırları otomatik sığdır. |
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
| [getResetFontFolders()](#getResetFontFolders--) | Belge yüklemeden önce yazı tipi klasörlerini sıfırla |
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
| [deepClone()](#deepClone--) | Mevcut örneği klonlar. |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Yeni bir [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) sınıfı örneği başlatır.

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


Dosya yüklendiğinde sistem kültür bilgisini al

**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Dosya yüklendiğinde sistem kültür bilgisini ayarla

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


Elektronik tablo belgesi dönüştürülürken belirli yazı tiplerini değiştir.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Elektronik tablo belgesi dönüştürülürken belirli yazı tiplerini değiştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Excel dosyaları dönüştürülürken ızgara çizgilerini göster.

**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Excel dosyaları dönüştürülürken ızgara çizgilerini göster.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Excel dosyaları dönüştürülürken gizli sayfaları göster.

**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Excel dosyaları dönüştürülürken gizli sayfaları göster.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


OnePagePerSheet true ise sayfanın içeriği PDF belgesinde tek sayfaya dönüştürülür. Varsayılan değer false'tur.

**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


OnePagePerSheet true ise sayfanın içeriği PDF belgesinde tek sayfaya dönüştürülür. Varsayılan değer false'tur.

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
boolean - tüm sütunlar tek sayfaya sığdırılırsa true
### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


AllColumnsInOnePagePerSheet özelliğini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| allColumnsInOnePagePerSheet | boolean | AllColumnsInOnePagePerSheet özelliği |

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


True ise ve PDF'ye dönüştürülüyorsa dönüşüm, baskı kalitesinden daha iyi dosya boyutu için optimize edilir.

**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


True ise ve PDF'ye dönüştürülüyorsa dönüşüm, baskı kalitesinden daha iyi dosya boyutu için optimize edilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Elektronik tablo formatı dışına dönüştürürken belirli bir aralığı dönüştürün. Örnek: "D1:F8".

**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Elektronik tablo formatı dışına dönüştürürken belirli bir aralığı dönüştürün. Örnek: "D1:F8".

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Dönüştürürken boş satırları ve sütunları atlar. Varsayılan değer True'tir.

**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Dönüştürürken boş satırları ve sütunları atlar. Varsayılan değer True'tir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Korunan belgeyi korumasız hale getirmek için şifre ayarla.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Korunan belgeyi korumasız hale getirmek için şifre ayarla.

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


Kullanıcı hücreyle ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamalarının kontrol edilip edilmediği. Örneğin, Excel 32K'dan uzun bir metin değerinin girilmesine izin vermez. 32K'dan uzun bir değer girerseniz ve bu özellik true ise bir Exception alırsınız. Bu özellik false ise, girdiğiniz metin değerini hücrenin değeri olarak kabul ederiz, böylece daha sonra CSV gibi diğer dosya formatları için tam metin değerini çıktılayabilirsiniz. Ancak, Excel dosya formatı için geçersiz bir değer ayarladıysanız, çalışma kitabını daha sonra Excel dosya formatı olarak kaydetmemelisiniz. Aksi takdirde oluşturulan Excel dosyasında beklenmeyen hatalar oluşabilir.

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


Dönüştürürken tüm satırları otomatik sığdır.

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


Belge yüklemeden önce yazı tipi klasörlerini sıfırla

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
