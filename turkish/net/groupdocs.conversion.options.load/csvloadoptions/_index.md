---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Csv belgelerini yükleme seçenekleri."
type: docs
weight: 2450
url: /tr/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

Csv belgelerini yükleme seçenekleri.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | Yeni bir [`CsvLoadOptions`](../csvloadoptions) sınıf örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | AllColumnsInOnePagePerSheet true ise, bir sayfanın tüm sütun içeriği sonuçta yalnızca bir sayfaya çıkacaktır. pagesetup'ın kağıt boyutu genişliği geçersiz olur, ancak pagesetup'ın diğer ayarları hâlâ etkili olur. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | Dönüştürürken tüm satırları otomatik olarak sığdırır |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Kullanıcı hücre ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamalarının kontrol edilip edilmediği. Örneğin, Excel 32K'dan uzun bir metin değerinin girilmesine izin vermez. 32K'dan uzun bir değer girdiğinizde, bu özellik true ise bir Exception alırsınız. Bu özellik false ise, girdiğiniz metin değerini hücrenin değeri olarak kabul ederiz, böylece daha sonra CSV gibi diğer dosya formatları için tam metin değerini çıktılayabilirsiniz. Ancak, Excel dosya formatı için geçersiz bir değer ayarladıysanız, çalışma kitabını daha sonra Excel dosya formatı olarak kaydetmemelisiniz. Aksi takdirde oluşturulan Excel dosyasında beklenmeyen hatalar ortaya çıkabilir. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | Belgeden yerleşik meta veri özelliklerini kaldırır. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | Belgeden özel meta veri özelliklerini kaldırır. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | Bir çalışma sayfasını sütunlara göre sayfalara böl. Varsayılan değer 0, sayfalama yok. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | Dosyadaki dizeyin tarihe dönüştürülüp dönüştürülmediğini gösterir. Varsayılan değer True'tir. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | Dosyadaki dizeyin sayısala dönüştürülüp dönüştürülmediğini gösterir. Varsayılan değer True'tir. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | Uygular [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Varsayılan: false |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | Uygular [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Varsayılan: true |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Elektronik tablo formatı dışına dönüştürürken belirli bir aralığı dönüştür. Örnek: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Dosya yüklendiğinde sistem kültür bilgisini al veya ayarla |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Elektronik tablo belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | Uygular [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Varsayılan: 1 |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | Kodlama. Varsayılan değer Encoding.Default. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Elektronik tablo belgesini dönüştürürken belirli yazı tiplerini değiştir. |
| [Format](../../groupdocs.conversion.options.load/csvloadoptions/format) { get; } | Girdi belge dosya türü. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Girdi belge dosya türü. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | Metnin "=" ile başlıyorsa formül olup olmadığını gösterir. |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | Formül hesaplama hatalarının göz ardı edilip edilmeyeceğini gösterir. Hata, desteklenmeyen işlev, dış bağlantılar vb. olabilir. Varsayılan değer false. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True, dosyanın birden fazla kodlama içerdiği anlamına gelir. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | Sayfa kenar boşluğu ayarları |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | OnePagePerSheet true ise, sayfanın içeriği PDF belgesinde tek bir sayfaya dönüştürülür. Varsayılan değer true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | True ise ve PDF'ye dönüştürülüyorsa, dönüşüm baskı kalitesinden daha iyi dosya boyutu için optimize edilir. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Korunan belgeyi korumasız hâle getirmek için şifre ayarlar. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | PDF'ye dönüştürülürken belge yapısının korunup korunmayacağını belirler (varsayılan false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | Yorumların sayfa ile birlikte nasıl yazdırılacağını temsil eder. Varsayılan değer PrintNoComments. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | Belgeyi yüklemeden önce yazı tipi klasörlerini sıfırla |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | Bir çalışma sayfasını satırlara göre sayfalara böl. Varsayılan değer 0, sayfalama yok. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Csv dosyasının ayırıcı karakteri. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Dönüştürülecek sayfa indekslerinin listesi. İndeksler sıfır tabanlı olmalıdır |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Dönüştürülecek sayfa adı |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Excel dosyalarını dönüştürürken ızgara çizgilerini göster |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Excel dosyalarını dönüştürürken gizli sayfaları göster |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | Sayfa boyutu ayarları |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Dönüştürürken boş satır ve sütunları atlar. Varsayılan değer True. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | Uygular [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | Elektronik tablo belgelerini dönüştürürken altbilgileri atla. Varsayılan: false. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | Elektronik tablo belgelerini dönüştürürken üstbilgileri atla. Varsayılan: false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | Uygular [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Mevcut örneği klonlar. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |

### Ayrıca Bakınız

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
