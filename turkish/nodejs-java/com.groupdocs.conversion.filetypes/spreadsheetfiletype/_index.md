---
title: "SpreadsheetFileType"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Elektronik tablo belgelerini tanımlar."
type: docs
weight: 25
url: /tr/nodejs-java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

Elektronik tablo belgelerini tanımlar. Aşağıdaki dosya türlerini içerir: [Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Csv), [Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Fods), [Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Ods), [Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Ots), [Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Tsv), [Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlam), [Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xls), [Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlsb), [Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlsm), [Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlsx), [Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xlt), [Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xltm), [Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype\#Xltx). Elektronik tablo formatları hakkında daha fazla bilgi için [buraya][].


[here]: https://wiki.fileformat.com/spreadsheet
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SpreadsheetFileType()](#SpreadsheetFileType--) | Serileştirme yapıcısı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Xls](#Xls) | XLS, Excel İkili Dosya Biçimini temsil eder. |
| [Xlsx](#Xlsx) | XLSX, Microsoft Office 2007'nin yayınlanmasıyla Microsoft tarafından tanıtılan, Microsoft Excel belgeleri için yaygın bir biçimdir. |
| [Xlsm](#Xlsm) | XLSM, makroları destekleyen bir elektronik tablo dosyası türüdür. |
| [Xlsb](#Xlsb) | XLSB dosya biçimi, Excel çalışma kitabı içeriğini belirten kayıtlar ve yapılar koleksiyonu olan Excel İkili Dosya Biçimini tanımlar. |
| [Ods](#Ods) | ODS uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablo Belgesi formatını temsil eder. |
| [Ots](#Ots) | .ots uzantılı bir dosya, Apache OpenOffice içinde bulunan Calc uygulamasıyla oluşturulan bir OpenDocument Elektronik Tablo Şablonu dosyasıdır. |
| [Xltx](#Xltx) | XLTX dosyası, Office OpenXML dosya formatı özelliklerine dayanan Microsoft Excel Şablonunu temsil eder. |
| [Xlt](#Xlt) | .XLT uzantılı dosyalar, Microsoft Office paketinin bir parçası olan bir elektronik tablo uygulaması Microsoft Excel ile oluşturulan şablon dosyalarıdır. |
| [Xltm](#Xltm) | XLTM dosya uzantısı, Microsoft Excel tarafından Makro‑etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. |
| [Tsv](#Tsv) | Sekme Ayrılmış Değerler (TSV) dosya formatı, sekmelerle ayrılmış verileri düz metin formatında temsil eder. |
| [Xlam](#Xlam) | XLAM, elektronik tablolara yeni işlevler eklemek için kullanılan Makro‑etkin Eklenti dosyasıdır. |
| [Csv](#Csv) | CSV (Virgül Ayrılmış Değerler) uzantılı dosyalar, virgüllerle ayrılmış veri kayıtları içeren düz metin dosyalarını temsil eder. |
| [Fods](#Fods) | .fods uzantılı bir dosya, verileri satır ve sütunlarda depolayan bir OpenDocument Elektronik Tablo belge formatıdır. |
| [Dif](#Dif) | DIF, farklı uygulamalar arasında elektronik tablo verilerini içe/dışa aktarmak için kullanılan Veri Değişim Formatı anlamına gelir. |
| [Sxc](#Sxc) | SXC (Sun XML Calc) dosya formatı, OpenOffice.org adlı bir ofis paketine aittir. |
| [Numbers](#Numbers) | .numbers uzantılı dosyalar elektronik tablo dosyası türü olarak sınıflandırılır, that\\u2019s why they are similar to the .xlsx files; ancak Numbers dosyaları Apple iWork Numbers elektronik tablo yazılımı kullanılarak oluşturulur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


Serileştirme yapıcısı

### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS, Excel İkili Dosya Formatını temsil eder. Bu dosyalar Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi benzer elektronik tablo programlarıyla da oluşturulabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX, Microsoft Office 2007'nin yayınlanmasıyla Microsoft tarafından tanıtılan Microsoft Excel belgeleri için tanınmış bir formattır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM, makroları destekleyen bir elektronik tablo dosyası türüdür. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


XLSB dosya formatı, Excel çalışma kitabı içeriğini belirten kayıt ve yapılar koleksiyonunu içeren Excel İkili Dosya Formatını tanımlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


ODS uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablo Belge formatını temsil eder. Veri, ODF dosyası içinde satır ve sütunlara depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


.ots uzantılı bir dosya, Apache OpenOffice içinde bulunan Calc uygulama yazılımı ile oluşturulan bir OpenDocument Elektronik Tablo Şablonu dosyasıdır. Calc uygulama yazılımı, Microsoft Office'te bulunan Excel'e benzer. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


XLTX dosyası, Office OpenXML dosya formatı özelliklerine dayanan Microsoft Excel Şablonunu temsil eder. XLTX dosyasında belirtilen aynı ayarları taşıyan XLSX dosyaları oluşturmak için kullanılabilecek standart bir şablon dosyası oluşturmak amacıyla kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


.XLT uzantılı dosyalar, Microsoft Office paketinin bir parçası olan elektronik tablo uygulaması Microsoft Excel ile oluşturulan şablon dosyalarıdır. Microsoft Office 97-2003, yeni XLT dosyaları oluşturmayı ve bu dosyaları açmayı desteklemiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


XLTM dosya uzantısı, Microsoft Excel tarafından Makro‑etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları, yapısal olarak XLTX dosyalarına benzer; ancak XLTX makrolu şablon dosyaları oluşturmayı desteklemez. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Sekme Ayrılmış Değerler (TSV) dosya formatı, sekmelerle ayrılmış verileri düz metin formatında temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM, elektronik tablolara yeni işlevler eklemek için kullanılan Makro‑etkin Eklenti dosyasıdır. Bir Eklenti, ek kod çalıştıran ve elektronik tablolara ek işlevsellik sağlayan yardımcı bir programdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][]


[here]: https://docs.fileformat.com/spreadsheet/xlam/

### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


CSV (Virgül Ayrılmış Değerler) uzantılı dosyalar, virgüllerle ayrılmış veri kayıtları içeren düz metin dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


.fods uzantılı bir dosya, verileri satır ve sütunlarda depolayan bir OpenDocument Elektronik Tablo belge formatıdır. Bu format, OASIS tarafından yayınlanan ve sürdürülen ODF 1.2 spesifikasyonlarının bir parçası olarak tanımlanmıştır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF, farklı uygulamalar arasında elektronik tablo verilerini içe/dışa aktarmak için kullanılan Data Interchange Format anlamına gelir. Bunlar arasında Microsoft Excel, OpenOffice Calc, StarCalc ve daha fazlası bulunur. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/dif

### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


SXC (Sun XML Calc) dosya formatı, OpenOffice.org adlı bir ofis paketine aittir. Bu format, XML tabanlı bir elektronik tablo dosya formatı olduğu için genellikle kullanıcıların elektronik tablo ihtiyaçlarını karşılar. SXC formatı formülleri, fonksiyonları, makroları ve grafikleri DataPilot ile birlikte destekler. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


.numbers uzantılı dosyalar elektronik tablo dosya türü olarak sınıflandırılır, bu yüzden .xlsx dosyalarına benzer; ancak Numbers dosyaları Apple iWork Numbers elektronik tablo yazılımı kullanılarak oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/spreadsheet/numbers

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Dosya türü için varsayılan dönüştürme seçenekleri hazırlandı

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
