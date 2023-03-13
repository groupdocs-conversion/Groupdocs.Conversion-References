---
title: SpreadsheetFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Elektronik Tablo belgelerini tanımlar. Aşağıdaki dosya türlerini içerir Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . Etablo biçimleri hakkında daha fazla bilgi edininBuradahttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 1050
url: /tr/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Elektronik Tablo belgelerini tanımlar. Aşağıdaki dosya türlerini içerir: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . E-tablo biçimleri hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Serileştirme oluşturucu |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dosya türü açıklaması |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Dosya uzantısı |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | family dosyası |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Dosya biçimi |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Geçerli nesneyi diğeriyle karşılaştırır. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Dizi gösterimi |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | CSV (Virgülle Ayrılmış Değerler) uzantılı dosyalar, virgülle ayrılmış değerler içeren veri kayıtlarını içeren düz metin dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF, elektronik tablo verilerini farklı uygulamalar arasında içe/dışa aktarmak için kullanılan Veri Değişim Biçimi anlamına gelir. Bunlara Microsoft Excel, OpenOffice Calc, StarCalc ve diğerleri dahildir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | .fods uzantılı bir dosya, verileri satırlar ve sütunlar halinde depolayan bir OpenDocument Elektronik Tablo belge biçimi türüdür. Biçim, OASIS tarafından yayınlanan ve sürdürülen ODF 1.2 belirtimlerinin bir parçası olarak belirtilmiştir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/fods) . |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | .numbers uzantılı dosyalar elektronik tablo dosya türü olarak sınıflandırılır, bu nedenle .xlsx dosyalarına benzerler; ancak Numbers dosyaları, Apple iWork Numbers elektronik tablo yazılımı kullanılarak oluşturulur. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | ODS uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablo Belge biçimi anlamına gelir. Veriler, ODF dosyası içinde satırlar ve sütunlar halinde depolanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | .ots uzantılı bir dosya, Apache OpenOffice'te bulunan Calc uygulama yazılımıyla oluşturulan bir OpenDocument Elektronik Tablo Şablonu dosyasıdır. Calc uygulama yazılımı, Microsoft Office'te bulunan Excel'e benzer. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/ots) . |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | SXC(Sun XML Calc) dosya biçimi, OpenOffice.org adlı bir ofis paketine aittir. Bu biçim, XML tabanlı bir elektronik tablo dosya biçimi olduğundan, genellikle kullanıcıların elektronik tablo ihtiyaçlarını karşılar. SXC biçimi, DataPilot ile birlikte formülleri, işlevleri, makroları ve çizelgeleri destekler. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/sxc) . |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Sekmeyle Ayrılmış Değerler (TSV) dosya biçimi, düz metin biçiminde sekmelerle ayrılmış verileri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM, elektronik tablolara yeni işlevler eklemek için kullanılan Makro Etkin bir Eklenti dosyasıdır. Eklenti, ek kod çalıştıran ve elektronik tablolar için ek işlevsellik sağlayan tamamlayıcı bir programdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/xlam/) . |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS, Excel İkili Dosya Biçimini temsil eder. Bu tür dosyalar, Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi diğer benzer elektronik tablo programları tarafından oluşturulabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB dosya formatı, Excel çalışma kitabı içeriğini belirten bir kayıt ve yapı koleksiyonu olan Excel İkili Dosya Formatını belirtir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM, makroları destekleyen bir Elektronik Tablo dosyası türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX, Microsoft tarafından Microsoft Office 2007'nin piyasaya sürülmesiyle sunulan Microsoft Excel belgeleri için iyi bilinen bir biçimdir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | .XLT uzantılı dosyalar, Microsoft Office paketinin bir parçası olarak gelen bir elektronik tablo uygulaması olan Microsoft Excel ile oluşturulan şablon dosyalarıdır. Microsoft Office 97-2003, yeni XLT dosyaları oluşturmayı ve bunları açmayı destekledi. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM dosya uzantısı, Microsoft Excel tarafından Makro özellikli şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları, daha sonra makrolarla şablon dosyaları oluşturmayı desteklememesi dışında yapı olarak XLTX'e benzer. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX dosyası, Office OpenXML dosya biçimi belirtimlerini temel alan Microsoft Excel Şablonunu temsil eder. XLTX dosyasında belirtilen ayarların aynısını sergileyen XLSX dosyaları oluşturmak için kullanılabilecek standart bir şablon dosyası oluşturmak için kullanılır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xltx) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
