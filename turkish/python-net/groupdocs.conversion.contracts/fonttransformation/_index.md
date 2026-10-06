---
title: "FontTransformation sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Belge yüklemesinden ve yazı tipi değişiminden sonra uygulanan, yazı tipi niteliklerini içeren yazı tipi dönüşüm yapılandırmasını açıklar."
type: docs
url: /tr/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Belge yüklemesinden ve yazı tipi değişiminden sonra uygulanan, yazı tipi niteliklerini içeren yazı tipi dönüşüm yapılandırmasını açıklar.

FontTransformation türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Tam font eşleşmesi (boyut ve stil eşleşmeli) ile bir font dönüşümü oluşturur. |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Yalnızca adla bir font dönüşümü oluşturur, herhangi bir boyut ve stil eşleşir, değiştirme fontu orijinal fontun boyut ve stilini korur. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Esnek eşleşme seçenekleriyle bir font dönüşümü oluşturur. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | İki nesne örneğinin eşit olup olmadığını belirler. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Varsayılan hash işlevi olarak hizmet verir. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/) tarafından miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | Bu özellik, orijinal font adı için herhangi bir font boyutunun eşleşip eşleşmediğini (true) veya `OriginalFont` içinde belirtilen tam font boyutunun eşleşip eşleşmediğini (false) gösterir. |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | Bu özellik, orijinal fontun herhangi bir font stilinin (bold, italic, underline) eşleşip eşleşmediğini (True) veya `OriginalFont` içinde belirtilen tam font stilinin gerekli olup olmadığını (False) belirler. |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | Eşleşecek ve değiştirilecek orijinal font belirtimi. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | Değiştirme fontu belirtimi. |

### Ayrıca Bakınız
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
