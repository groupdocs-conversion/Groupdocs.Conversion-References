---
title: "SpreadsheetLoadOptions sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Spreadsheet belgelerini yüklemek için seçenekler sağlar."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/
is_root: false
weight: 440
---


## SpreadsheetLoadOptions class

Spreadsheet belgelerini yüklemek için seçenekler sağlar.

SpreadsheetLoadOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/__init__/) | Yeni bir [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/) örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Mevcut örneği klonlar. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | İki nesne örneğinin eşit olup olmadığını belirler. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Varsayılan hash işlevi olarak hizmet verir. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | Bu özellik, bir sayfanın tüm sütun içeriğinin sonuçta tek bir sayfada render edilip edilmediğini belirler. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Satırlar dönüştürürken otomatik olarak sığdırılır. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | Bu özellik, hücreyle ilgili nesneler değiştirilirken Excel dosyası kısıtlamalarının kontrol edilip edilmediğini belirler. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_built_in_document_properties/) | ClearBuiltInDocumentProperties özelliği, bir elektronik tablo yüklenirken yerleşik belge özelliklerinin temizlenip temizlenmeyeceğini belirler. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_custom_document_properties/) | ClearCustomDocumentProperties özelliği. |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Bir çalışma sayfasını sayfalara bölmek için sayfa başına kullanılan sütun sayısı; varsayılan 0'dır ve bu sayfalama devre dışı bırakılır. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owned/) | Bu özellik, [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) uygular ve varsayılan olarak False'tur. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owner/) | Bu özellik, [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/) uygular. Varsayılan True'tur. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Elektronik tablo dışı bir formata dönüştürürken dönüştürülecek aralık, ör. "D1:F8". |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Dosya yüklendiğinde kullanılan sistem kültür bilgisi. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/default_font/) | Bir elektronik tablo belgesi için varsayılan yazı tipi. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/depth/) | Belge konteyneri yükleme seçeneklerinin derinliği. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/font_substitutes/) | Bir elektronik tablo belgesi dönüştürülürken kullanılan yazı tipi ikameleri. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/format/) | Giriş belge dosya türü. |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | Bu özellik, formül hesaplama hatalarının göz ardı edilip edilmeyeceğini gösterir. Hata, desteklenmeyen işlev, dış bağlantılar vb. olabilir. Varsayılan False'tur. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/margin_settings/) | Kenar boşluğu ayarları. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | Bu özellik, her sayfanın içeriğinin PDF belgesinde tek bir sayfaya dönüştürülüp dönüştürülmeyeceğini gösterir. Varsayılan değer True'tır. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | PDF'ye dönüştürürken True olarak ayarlandığında, dönüşüm baskı kalitesinden ziyade daha küçük dosya boyutu için optimize edilir. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Korunan bir belgeyi korumasız hâle getirmek için kullanılan şifre. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | PDF'ye dönüştürürken belge yapısının korunup korunmayacağını gösteren bayrak (varsayılan olarak Yanlış). |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Yorumların sayfa ile nasıl yazdırılacağı. Varsayılan PrintNoComments'tur. |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Belge yüklenmeden önce yazı tipi klasörleri sıfırlanır. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Bir çalışma sayfasını sayfalara bölmek için sayfa başına kullanılan satır sayısı; varsayılan 0, sayfalama olmadığı anlamına gelir. |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | Dönüştürülecek sayfa indekslerinin listesi. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Dönüştürülecek sayfa adı. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Excel dosyaları dönüştürülürken ızgara çizgilerini gösterme seçeneği. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Excel dosyaları dönüştürülürken gizli sayfaları gösterme seçeneği. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/size_settings/) | Boyut ayarları, [`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/) tarafından tanımlandığı gibi. |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Dönüştürürken boş satır ve sütunları atlayan ayar. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_external_resources/) | Bu özellik [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/) uygular. |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | Bu özellik, elektronik tablo belgeleri dönüştürülürken altbilgilerin atlanıp atlanmayacağını belirler. Varsayılan: False. |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | Elektronik tablo belgeleri dönüştürülürken başlıkların atlanması seçeneği. Varsayılan: False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/whitelisted_resources/) | Beyaz listeye alınan kaynaklar, [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) tarafından tanımlandığı gibi. |

### Ayrıca Bakınız
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
