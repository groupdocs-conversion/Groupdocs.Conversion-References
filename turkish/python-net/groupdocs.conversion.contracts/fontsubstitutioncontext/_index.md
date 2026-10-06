---
title: "FontSubstitutionContext sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Kaynak belge yüklenirken veya işlenirken gerçekleşen tek bir yazı tipi değişimini açıklar."
type: docs
url: /tr/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Kaynak belge yüklenirken veya işlenirken gerçekleşen tek bir yazı tipi değişimini açıklar.

Örnekler [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) olayına iletilir.

FontSubstitutionContext türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Yeni bir FontSubstitutionContext başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | Kaynak belge tarafından başvurulan ancak dönüşüm hattı için mevcut olmayan yazı tipinin adı. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | Dönüştürme hattı tarafından bildirilen ikame mesajı tam olarak, kelimesi kelimesine ve ayrıştırılmamış olarak. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | Dönüştürülen kaynak belgenin dosya adı. Kaynak, `io.RawIOBase` olmayan bir akış olarak sağlandığında, bu gerçek bir dosya adı yerine oluşturulmuş bir tanımlayıcı içerir. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | İkame olarak kullanılan yazı tipinin adı. Motor, ikameyi yalnızca açıklayıcı metin olarak rapor eden belgeler için None olabilir — bu durumda [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) okuyun. |

### Ayrıca Bakınız
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
