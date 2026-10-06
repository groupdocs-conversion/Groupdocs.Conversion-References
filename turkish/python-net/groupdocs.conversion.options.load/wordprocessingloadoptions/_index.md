---
title: "WordProcessingLoadOptions sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "WordProcessing belgelerini yüklemek için seçenekler sağlar."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

WordProcessing belgelerini yüklemek için seçenekler sağlar.

Yazı Tipi İşleme Boru Hattı:

Aşama 1 - Yazı Tipi Değiştirme (belge yüklenirken):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

Aşama 2 - Yazı Tipi Değiştirme (belge yüklendikten sonra):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

WordProcessingLoadOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | Yeni bir [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | İki nesne örneğinin eşit olup olmadığını belirler. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Varsayılan hash işlevi olarak hizmet verir. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | auto_detect_rtl_direction özelliği, çoğunlukla sağdan sola metin içeren paragrafların ve koşulların (runs) dönüştürmeden önce bidi bayraklarının onarılıp onarılmayacağını belirler. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | Yer imleri seçenekleri. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | Word işleme belgesi yüklenirken yerleşik belge özelliklerinin temizlenip temizlenmeyeceğini gösteren bayrak. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | ClearCustomDocumentProperties özelliği. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | Yorum görüntüleme modu, yorumların çıktı belgesinde nasıl gösterileceğini belirtir. Varsayılan `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | Bu özellik, [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) uygular. Varsayılan False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | convert_owner bayrağı, belge sahibinin dönüştürülüp dönüştürülmeyeceğini gösterir. Varsayılan True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | WordProcessing belgesi için varsayılan yazı tipi. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | Belge konteyneri yükleme seçeneklerinin derinliği. Varsayılan 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | embed_true_type_fonts özelliği, gerçek tip (TrueType) yazı tiplerinin çıktı belgesine gömülüp gömülmeyeceğini belirler. Varsayılan True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | Bu özellik, sistem FontConfig'ine dayalı eksik yazı tiplerinin otomatik olarak değiştirilmesini etkinleştirir. Varsayılan False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | Belgedeki FontInfo'a dayalı eksik yazı tiplerinin otomatik olarak değiştirilmesini sağlayan bayrak. Varsayılan: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | Bu özellik, eksik yazı tiplerinin yazı tipi adına göre otomatik olarak değiştirilip değiştirilmediğini gösterir. Varsayılan: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | WordProcessing belgesi dönüştürülürken kullanılan yazı tipi ikameleri. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | Belge yüklendikten ve yazı tipi ikamesi tamamlandıktan sonra uygulanan yazı tipi dönüşümleri, belge içindeki tüm yazı tiplerinin, başarıyla yüklenenler dahil, değiştirilmesine izin verir. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | Giriş belge dosya türü. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | hide_word_tracked_changes özelliği, Word belgeleri için işaretlemeyi ve değişiklik izlemeyi gizler. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | WordProcessing belgeleri için heceleme seçenekleri. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | keep_date_field_original_value özelliği, tarih alanının orijinal değerinin korunup korunmayacağını belirler. Varsayılan False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | Kenar boşluğu ayarları. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | Dönüştürülen belge için sayfa numaralandırma oluşturma bayrağı (varsayılan: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | Korunan bir belgeyi korumasız hâle getirmek için şifre. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | PDF'ye dönüştürürken belge yapısının korunup korunmayacağını gösteren bayrak (varsayılan olarak Yanlış). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | Bu özellik, Microsoft Word form alanlarının sonuç PDF'de form alanı olarak korunup korunmayacağını veya metne dönüştürülüp dönüştürülmeyeceğini gösterir. Varsayılan değer Yanlış. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | Tam yorumcu adı, True olarak ayarlandığında yorumlarda gösterilir. Varsayılan değer Yanlış. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | WordProcessing belgesi için boyut ayarları ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | Bir belge yüklenirken dış kaynakların atlanıp atlanmayacağını belirleyen bayrak. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | Yükleme sonrası alanları güncelleme seçeneği. Varsayılan: Yanlış. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | Yükleme sonrası sayfa düzeni güncellenir. Varsayılan: Yanlış. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | Bu özellik, daha iyi kerning gösterimi için bir metin şekillendirici kullanılıp kullanılmayacağını gösterir. Varsayılan değer Yanlış. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | Dış içerik yüklemek için beyaz listeye alınan kaynaklar, [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) uygulanarak. |

### Örnek

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
`WordProcessingLoadOptions` kullanan görev kılavuzları:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Ayrıca Bakınız
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
