---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Elektronik Tablo belgelerini tanımlar. Aşağıdaki dosya türlerini içerir Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. Elektronik Tablo formatları hakkında daha fazla bilgi edinin buradahttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /tr/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Elektronik Tablo belgelerini tanımlar. Aşağıdaki dosya türlerini içerir: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Elektronik Tablo formatları hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Serileştirme yapıcısı |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dosya türü açıklaması |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Dosya uzantısı |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Dosya ailesi |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Dosya formatı |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Mevcut nesneyi diğerine karşılaştırır. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) uygular. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Dize temsili |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | CSV (Virgülle Ayrılmış Değerler) uzantılı dosyalar, virgülle ayrılmış değerlerle veri kayıtları içeren düz metin dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF, elektronik tablolar verilerini farklı uygulamalar arasında içe/dışa aktarmak için kullanılan Data Interchange Format (Veri Değişim Formatı) anlamına gelir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel, ZIP paketi yerine düz bir XML dosyasında depolanan Office Open XML SpreadsheetML'dir. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | .fods uzantılı bir dosya, verileri satır ve sütunlarda depolayan bir OpenDocument Elektronik Tablo belge formatıdır. Bu format, OASIS tarafından yayınlanan ve sürdürülen ODF 1.2 spesifikasyonlarının bir parçası olarak tanımlanmıştır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | .numbers uzantılı dosyalar elektronik tablo dosyası türü olarak sınıflandırılır, bu yüzden .xlsx dosyalarına benzer; ancak Numbers dosyaları Apple iWork Numbers elektronik tablo yazılımı kullanılarak oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | ODS uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablo Belge formatını temsil eder. Veri, ODF dosyası içinde satır ve sütunlara depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | .ots uzantılı bir dosya, Apache OpenOffice içinde bulunan Calc uygulama yazılımı ile oluşturulan bir OpenDocument Elektronik Tablo Şablonu dosyasıdır. Calc uygulama yazılımı, Microsoft Office'te bulunan Excel'e benzer. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | SXC (Sun XML Calc) dosya formatı, OpenOffice.org adlı bir ofis paketine aittir. Bu format, XML tabanlı bir elektronik tablo dosyası olduğu için kullanıcıların elektronik tablo ihtiyaçlarını karşılar. SXC formatı formüller, işlevler, makrolar ve grafikler ile birlikte DataPilot'ı da destekler. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Sekmelerle Ayrılmış Değerler (TSV) dosya formatı, düz metin formatında sekmelerle ayrılmış verileri temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM, elektronik tablolara yeni işlevler eklemek için kullanılan Makro Etkin Eklenti dosyasıdır. Bir Eklenti, ek kod çalıştıran ve elektronik tablolara ek işlevsellik sağlayan yardımcı bir programdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS, Excel İkili Dosya Formatını temsil eder. Bu tür dosyalar Microsoft Excel tarafından ve OpenOffice Calc veya Apple Numbers gibi benzer elektronik tablo programlarıyla oluşturulabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB dosya formatı, Excel çalışma kitabı içeriğini belirten kayıt ve yapılar koleksiyonu olan Excel İkili Dosya Formatını tanımlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM, makroları destekleyen bir elektronik tablo dosyası türüdür. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX, Microsoft Office 2007'nin çıkışıyla Microsoft tarafından tanıtılan Microsoft Excel belgeleri için yaygın bir formattır. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | .XLT uzantılı dosyalar, Microsoft Office paketinin bir parçası olan bir elektronik tablo uygulaması Microsoft Excel ile oluşturulan şablon dosyalarıdır. Microsoft Office 97-2003, yeni XLT dosyaları oluşturmayı ve bu dosyaları açmayı destekliyordu. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM dosya uzantısı, Microsoft Excel tarafından Makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları, yapısal olarak XLTX dosyalarına benzer, ancak XLTX makrolu şablon dosyaları oluşturmayı desteklemez. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX dosyası, Office OpenXML dosya formatı spesifikasyonlarına dayanan Microsoft Excel Şablonunu temsil eder. Aynı ayarları içeren XLSX dosyaları üretmek için kullanılabilecek standart bir şablon dosyası oluşturmak amacıyla kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/spreadsheet/xltx). |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
