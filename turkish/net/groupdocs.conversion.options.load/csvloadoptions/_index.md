---
title: CsvLoadOptions
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Csv belgelerini yükleme seçenekleri.
type: docs
weight: 1860
url: /tr/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

Csv belgelerini yükleme seçenekleri.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | Yeni örneğini başlatır[`CsvLoadOptions`](../csvloadoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde excel dosyasının kısıtlamasının kontrol edilip edilmeyeceği. Örneğin, excel 32K'dan daha uzun bir dizi değeri girilmesine izin vermez. 32K'dan daha uzun bir değer girdiğinizde, bu özellik doğruysa, bir İstisna alırsınız. Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra CSV gibi diğer dosya formatları için tam dize değerini çıktı olarak alabilirsiniz. Ancak excel dosya formatı için geçersiz bir değer belirlediyseniz çalışma kitabını daha sonra excel dosya formatında kaydetmemelisiniz. Aksi takdirde, oluşturulan excel dosyası için beklenmeyen bir hata olabilir. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | Dosyadaki dizenin tarihe dönüştürülüp dönüştürülmediğini gösterir. Varsayılan True. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | Dosyadaki dizgenin sayıya dönüştürülüp dönüştürülmediğini gösterir. Varsayılan True. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Elektronik tablo biçiminden farklı bir biçime dönüştürürken belirli aralığı dönüştürün. Örnek: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Dosya yüklendiğinde sistem kültürü bilgisini alın veya ayarlayın |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Elektronik tablo belgesi için varsayılan yazı tipi. Bir yazı tipi eksikse aşağıdaki yazı tipi kullanılacaktır. |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | Kodlama. Varsayılan Encoding.Default. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Elektronik tablo belgesini dönüştürürken belirli yazı tiplerini değiştirin. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Girdi belgesi dosya türü. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Girdi belgesi dosya türü. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | Metnin "=". ile başlıyorsa formül olup olmadığını gösterir. |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Yorumları gizle. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True, dosyanın birkaç kodlama içerdiği anlamına gelir. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | OnePagePerSheet true ise, sayfanın içeriği PDF belgesinde bir sayfaya dönüştürülür. Varsayılan değer true. 'dir. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | True ise ve PDF'ye dönüştürülüyorsa, dönüştürme, baskı kalitesinden daha iyi dosya boyutu için optimize edilir. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Korunan belgenin korumasını kaldırmak için parola belirleyin. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Csv dosyasının sınırlayıcısı. |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Dönüştürülecek sayfa adı |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Excel dosyalarını dönüştürürken ızgara çizgilerini göster. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Excel dosyalarını dönüştürürken gizli sayfaları göster. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Dönüştürürken boş satırları ve sütunları atlar. Varsayılan True. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Geçerli örneği klonlar. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |

### Ayrıca bakınız

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* ad alanı [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
