---
title: "SpreadsheetFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Elektronik tablo belgelerini tanımlar."
type: docs
weight: 25
url: /tr/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

Spreadsheet belgelerini tanımlar. Aşağıdaki dosya türlerini içerir:
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
Spreadsheet formatları hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Xls](#Xls) | XLS, Excel Binary File Format'ı temsil eder. |
|
|  | [Xlsx](#Xlsx) | XLSX, Microsoft Office 2007'nin yayınlanmasıyla Microsoft tarafından tanıtılan Microsoft Excel belgeleri için yaygın bilinen bir formattır. |
|
|  | [Xlsm](#Xlsm) | XLSM, makroları destekleyen bir Spreadsheet dosya türüdür. |
|
|  | [Xlsb](#Xlsb) | XLSB dosya formatı, Excel çalışma kitabı içeriğini belirten kayıtlar ve yapılar koleksiyonu olan Excel Binary File Format'ı tanımlar. |
|
|  | [Ods](#Ods) | ODS uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Spreadsheet Document formatını temsil eder. |
|
|  | [Ots](#Ots) | .ots uzantılı bir dosya, Apache OpenOffice içinde bulunan Calc uygulama yazılımı ile oluşturulan bir OpenDocument Spreadsheet Şablonu dosyasıdır. |
|
|  | [Xltx](#Xltx) | XLTX dosyası, Office OpenXML dosya formatı spesifikasyonlarına dayanan Microsoft Excel Şablonunu temsil eder. |
|
|  | [Xlt](#Xlt) | .XLT uzantılı dosyalar, Microsoft Office paketinin bir parçası olan bir spreadsheet uygulaması Microsoft Excel ile oluşturulan şablon dosyalarıdır. |
|
|  | [Xltm](#Xltm) | XLTM dosya uzantısı, Microsoft Excel tarafından Makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. |
|
|  | [Tsv](#Tsv) | Sekme Ayrılmış Değerler (TSV) dosya formatı, düz metin formatında sekmelerle ayrılmış verileri temsil eder. |
|
|  | [Xlam](#Xlam) | XLAM, elektronik tablolara yeni işlevler eklemek için kullanılan Makro Etkin Eklenti dosyasıdır. |
|
|  | [Csv](#Csv) | CSV (Virgül Ayrılmış Değerler) uzantılı dosyalar, virgülle ayrılmış değerlerle veri kayıtları içeren düz metin dosyalarını temsil eder. |
|
|  | [Fods](#Fods) | .fods uzantılı bir dosya, verileri satır ve sütunlarda depolayan bir OpenDocument Spreadsheet belge formatı türüdür. |
|
|  | [Dif](#Dif) | DIF, farklı uygulamalar arasında elektronik tablo verilerini içe/dışa aktarmak için kullanılan Data Interchange Format'ın kısaltmasıdır. |
|
|  | [Sxc](#Sxc) | SXC (Sun XML Calc) dosya formatı, OpenOffice.org adlı bir ofis paketine aittir. |
|
|  | [Numbers](#Numbers) | .numbers uzantılı dosyalar elektronik tablo dosyası türü olarak sınıflandırılır, bu yüzden .xlsx dosyalarına benzer; ancak Numbers dosyaları Apple iWork Numbers elektronik tablo yazılımı kullanılarak oluşturulur. |
|
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


XLS, Excel Binary File Format'ı temsil eder. Bu tür dosyalar Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi benzer elektronik tablo programlarıyla da oluşturulabilir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xls).


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX, Microsoft Office 2007'nin yayınlanmasıyla Microsoft tarafından tanıtılan Microsoft Excel belgeleri için yaygın bilinen bir formattır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xlsx).


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM, makroları destekleyen bir Spreadsheet dosya türüdür.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xlsm).


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


XLSB dosya formatı, Excel çalışma kitabı içeriğini belirten kayıtlar ve yapılar koleksiyonu olan Excel Binary File Format'ı tanımlar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xlsb).


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


ODS uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Spreadsheet Document formatını temsil eder. Veriler ODF dosyası içinde satır ve sütunlara kaydedilir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/ods).


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


.ots uzantılı bir dosya, Apache OpenOffice içinde bulunan Calc uygulama yazılımı ile oluşturulan bir OpenDocument Spreadsheet Şablon dosyasıdır. Calc uygulama yazılımı, Microsoft Office'te bulunan Excel'e benzer.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/ots).


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


XLTX dosyası, Office OpenXML dosya formatı spesifikasyonlarına dayanan bir Microsoft Excel Şablonunu temsil eder. Bu, XLTX dosyasında belirtilen aynı ayarları taşıyan XLSX dosyaları oluşturmak için kullanılabilecek standart bir şablon dosyası yaratmak amacıyla kullanılır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xltx).


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


.XLT uzantılı dosyalar, Microsoft Office paketinin bir parçası olan elektronik tablo uygulaması Microsoft Excel ile oluşturulan şablon dosyalarıdır. Microsoft Office 97-2003, yeni XLT dosyaları oluşturmayı ve bu dosyaları açmayı desteklemiştir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xlt).


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


XLTM dosya uzantısı, Microsoft Excel tarafından Makro‑etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları, yapı olarak XLTX dosyalarına benzer; ancak XLTX makrolu şablon dosyaları oluşturmayı desteklemez.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xltm).


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


Sekme Ayrılmış Değerler (TSV) dosya formatı, düz metin formatında sekmelerle ayrılmış verileri temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/tsv).


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM, elektronik tablolara yeni işlevler eklemek için kullanılan Makro‑etkin Eklenti dosyasıdır. Bir Eklenti, ek kod çalıştıran ve elektronik tablolara ek işlevsellik sağlayan yardımcı bir programdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


CSV (Virgül Ayrılmış Değerler) uzantılı dosyalar, virgülle ayrılmış değerlerle veri kayıtları içeren düz metin dosyalarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/csv).


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


.fods uzantılı bir dosya, satır ve sütunlarda veri depolayan bir OpenDocument Spreadsheet belge formatı türüdür. Bu format, OASIS tarafından yayınlanan ve sürdürülen ODF 1.2 spesifikasyonlarının bir parçası olarak tanımlanmıştır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/fods).


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF, farklı uygulamalar arasında elektronik tablo verilerini içe/dışa aktarmak için kullanılan Data Interchange Format'ın kısaltmasıdır. Bunlar arasında Microsoft Excel, OpenOffice Calc, StarCalc ve daha birçokları bulunur. Bu dosya formatı hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/spreadsheet/dif).


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


SXC (Sun XML Calc) dosya formatı, OpenOffice.org adlı bir ofis paketine aittir. Bu format, XML tabanlı bir elektronik tablo dosyası olduğu için genellikle kullanıcıların elektronik tablo ihtiyaçlarını karşılar. SXC formatı, formüller, işlevler, makrolar ve grafiklerin yanı sıra DataPilot'ı da destekler. Bu dosya formatı hakkında daha fazla bilgi edinin [here](../https://wiki.fileformat.com/spreadsheet/sxc).


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


.numbers uzantılı dosyalar elektronik tablo dosyası türü olarak sınıflandırılır, that\\u2019s why .xlsx dosyalarına benzer; ancak Numbers dosyaları Apple iWork Numbers elektronik tablo yazılımı kullanılarak oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin [here](../https://docs.fileformat.com/spreadsheet/numbers).


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
