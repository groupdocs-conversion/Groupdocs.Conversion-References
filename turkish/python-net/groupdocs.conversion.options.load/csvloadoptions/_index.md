---
title: "CsvLoadOptions sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "CSV belgelerini yüklemek için seçenekler sağlar."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/csvloadoptions/
is_root: false
weight: 80
---


## CsvLoadOptions class

CSV belgelerini yüklemek için seçenekler sağlar.

CsvLoadOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/__init__/) | Yeni bir [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/) örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Mevcut örneği klonlar. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) üzerinden devralınmıştır) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | İki nesne örneğinin eşit olup olmadığını belirler. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Varsayılan hash işlevi olarak hizmet verir. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_built_in_document_properties/) | Bu özellik, belgeden yerleşik meta veri özelliklerini kaldırır. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_custom_document_properties/) | Belgeden özel meta veri özelliklerini kaldıran özellik. |
| [convert_date_time_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_date_time_data/) | Özellik, dosyadaki dizgenin tarihe dönüştürülüp dönüştürülmediğini gösterir. Varsayılan değer True'tır. |
| [convert_numeric_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_numeric_data/) | Dosyadaki dizgelerin sayısal değerlere dönüştürülüp dönüştürülmediğini gösteren bayrak. Varsayılan değer True'tır. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owned/) | Belge konteynerindeki sahip olunan belgelerin dönüştürülüp dönüştürülmeyeceğini kontrol eden seçenek. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owner/) | Belge konteynerinin kendisinin dönüştürülüp dönüştürülmeyeceğini kontrol eden seçenek; true ise, konteyner ilk dönüştürülen belge olacaktır. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/default_font/) | Bir yazı tipi eksik olduğunda kullanılacak yazı tipi. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/depth/) | Derinlik seçeneği, dönüşümün kaç seviyede yapılacağını kontrol eder. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/encoding/) | CSV dosyaları için kullanılan kodlama. Varsayılan değer `Encoding.Default`. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/font_substitutes/) | Yazı tipi ikameleri. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/format/) | Giriş belge dosya türü. |
| [has_formula](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/has_formula/) | Özellik, metnin "=" ile başlıyorsa bir formül olup olmadığını gösterir. |
| [is_multi_encoded](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/is_multi_encoded/) | Özellik, dosyanın birden fazla kodlama içerip içermediğini gösterir. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/margin_settings/) | Sayfa kenar boşluğu ayarları. |
| [separator](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/separator/) | CSV dosyasının ayırıcı karakteri. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/size_settings/) | Sayfa boyutu ayarları. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/skip_external_resources/) | Özellik, harici kaynakların yüklenip yüklenmeyeceğini gösterir. True ise, [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) listesinde bulunanlar dışındaki tüm harici kaynaklar yüklenmez. Varsayılan: True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/whitelisted_resources/) | Her zaman yüklenecek harici kaynaklar. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | Bu özellik, bir sayfanın sonucunda bir sayfada tüm sütun içeriğinin render edilip edilmediğini belirler. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) üzerinden devralınmıştır) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Dönüştürürken satırlar otomatik olarak sığdırılır. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) üzerinden devralınmıştır) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | Bu özellik, hücreyle ilgili nesneler değiştirilirken Excel dosyası kısıtlamalarının kontrol edilip edilmediğini belirler. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) üzerinden devralınmıştır) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Bir çalışma sayfasını sayfalara bölmek için sayfa başına kullanılan sütun sayısı; varsayılan 0'dır ve sayfalama devre dışı bırakılır. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) üzerinden devralınmıştır) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Elektronik tablo dışı bir formata dönüştürürken dönüştürülecek aralık, ör. "D1:F8". ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) üzerinden devralınmıştır) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Dosya yüklendiğinde kullanılan sistem kültür bilgisi. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | Bu özellik, formül hesaplama hatalarının göz ardı edilip edilmediğini gösterir. Hata, desteklenmeyen işlev, dış bağlantılar vb. olabilir. Varsayılan değer False'tur. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | Bu özellik, her sayfanın içeriğinin PDF belgesinde tek bir sayfaya dönüştürülüp dönüştürülmediğini gösterir. Varsayılan değer True'tır. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | Dönüştürme, PDF'ye dönüştürürken True olarak ayarlandığında baskı kalitesinden ziyade daha küçük dosya boyutu için optimize edilir. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Korunan bir belgeyi korumasını kaldırmak için kullanılan şifre. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | PDF'ye dönüştürürken belge yapısının korunup korunmayacağını gösteren işaret (varsayılan False'tur). ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Yorumların sayfa ile birlikte nasıl yazdırılacağı. Varsayılan PrintNoComments'tir. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Belge yüklenmeden önce yazı tipi klasörleri sıfırlanır. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Bir çalışma sayfasını sayfalara bölmek için sayfa başına kullanılan satır sayısı; varsayılan 0, sayfalama olmadığını gösterir. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | Dönüştürülecek sayfa indekslerinin listesi. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Dönüştürülecek sayfanın adı. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Excel dosyalarını dönüştürürken ızgara çizgilerini gösterme seçeneği. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Excel dosyalarını dönüştürürken gizli sayfaları gösterme seçeneği. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Dönüştürürken boş satır ve sütunları atlayan ayar. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | Bu özellik, elektronik tablo belgelerini dönüştürürken altbilgilerin atlanıp atlanmayacağını belirler. Varsayılan: False. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | Elektronik tablo belgelerini dönüştürürken üstbilgileri atlama seçeneği. Varsayılan: False. ([`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) 'den devralınmıştır) |

### Ayrıca Bakınız
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
