---
title: "TxtLoadOptions sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Txt belgelerini yüklemek için seçenekler."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Txt belgelerini yüklemek için seçenekler.

Düz Metin için Yazı Tipi Yapılandırması:

TXT dosyaları yazı tipi bilgisi içermediğinden, dönüştürme sırasında düz metin içeriğini işlemek için yazı tipini belirtmek amacıyla DefaultTextFont kullanın.

TxtLoadOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Yeni bir [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) örneği başlatır. |

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
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | Dönüştürme sırasında düz metin içeriğini işlerken kullanılacak yazı tipi. Varsayılan: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | Bu özellik, bir düz metin belgesi dönüştürüldüğünde numaralı liste öğelerinin nasıl tanındığını belirtir. Varsayılan değer True'tir. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | Bir Txt belgesi yüklenirken kullanılan kodlama. None olabilir. Varsayılan None'dur. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | Giriş belge dosya türü. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | Ön boşlukları işlemek için tercih edilen seçenek. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | Kenar boşluğu ayarları, [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/) tarafından tanımlanmıştır. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | Bir TXT belgesi yüklemek için sayfa boyutu seçenekleri. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | Satır sonu boşluklarını işlemek için tercih edilen seçenek. Varsayılan değer [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### Ayrıca Bakınız
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
