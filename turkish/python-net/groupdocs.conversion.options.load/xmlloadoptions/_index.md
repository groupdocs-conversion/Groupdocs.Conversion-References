---
title: "XmlLoadOptions sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "XML belgelerini yüklemek için seçenekler."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/xmlloadoptions/
is_root: false
weight: 590
---


## XmlLoadOptions class

XML belgelerini yüklemek için seçenekler.

XmlLoadOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/__init__/) | Yeni bir [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/) örneği başlatır. |

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
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/custom_css_style/) | Dönüştürme sırasında belgeye uygulanacak özel CSS stili. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/format/) | Giriş belge dosya türü. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/margin_settings/) | Sayfa kenar boşluğu ayarları. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/orientation_settings/) | Sayfa yönlendirme ayarları. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_layout_options/) | Belge yüklenirken uygulanacak sayfa düzeni ölçeklemesi. Varsayılan: Yok. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_numbering/) | Dönüştürülen belge için sayfa numaralandırma oluşturma bayrağı (varsayılan: False). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/size_settings/) | Sayfa boyutu ayarları. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/) | Bu özellik dış kaynakların yüklenip yüklenmediğini gösterir. |
| [use_as_data_source](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/use_as_data_source/) | XML belgesi bir veri kaynağı olarak kullanılır. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/whitelisted_resources/) | Her zaman yüklenecek harici kaynaklar. |
| [xsl_fo_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xsl_fo_factory/) | XML'i bir XSL-FO işaretleme dosyası kullanarak dönüştürmek için XSL-FO belge akışı. |
| [xslt_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xslt_factory/) | XML'i HTML'ye XSL dönüşümü uygulayarak dönüştürmek için XSLT belge akışı. |
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | HTML için temel yol/url. (şu sınıftan devralınmıştır [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | İstek başlıklarını yapılandırmak için kullanılan eylem, burada ilk parametre Uri'dir. (şu sınıftan devralınmıştır [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Uri için kimlik bilgileri sağlayıcısı. (şu sınıftan devralınmıştır [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | Web belgesi yüklenirken kullanılacak kodlama. Eğer None olarak ayarlanırsa, kodlama belgenin karakter seti özniteliğinden belirlenecektir. (şu sınıftan devralınmıştır [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | HTML renderleme modu, HTML içeriğinin nasıl render edildiğini kontrol eder. Varsayılan: AbsolutePositioning. (şu sınıftan devralınmıştır [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | Harici kaynakların yüklenmesi için zaman aşımı. (şu sınıftan devralınmıştır [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | Bu özellik, dönüşüm için PDF kullanılıp kullanılmayacağını gösterir (varsayılan: False). (şu sınıftan devralınmıştır [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | Dönüştürmeden önce belgenin `<body>` etiketine yüzde olarak uygulanan yakınlaştırma seviyesi, belgenin görsel görünümünü ölçeklendirir. (şu sınıftan devralınmıştır [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |

### Ayrıca Bakınız
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
