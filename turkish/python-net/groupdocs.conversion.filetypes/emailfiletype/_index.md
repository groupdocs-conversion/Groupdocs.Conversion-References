---
title: "EmailFileType sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "E-posta uygulamaları tarafından mesajları, ekleri, klasörleri, adres defterlerini ve diğer verileri depolamak için kullanılan e-posta dosya formatlarını tanımlar."
type: docs
url: /tr/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

E-posta uygulamaları tarafından mesajları, ekleri, klasörleri, adres defterlerini ve diğer verileri depolamak için kullanılan e-posta dosya formatlarını tanımlar.

Aşağıdaki dosya türlerini içerir:
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

E-posta formatları hakkında daha fazla bilgi için https://wiki.fileformat.com/email adresine bakın.

EmailFileType türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | Serileştirme için yeni bir EmailFileType başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Mevcut nesneyi diğerine karşılaştırır. ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) sınıfından kalıtılmıştır.) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) sınıfından kalıtılmıştır.) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) tarafından tanımlanan eşitlik karşılaştırmasını uygular. ([`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)`'dan kalıtılmıştır.) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) sınıfından kalıtılmıştır.) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) sınıfından kalıtılmıştır.) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Sağlanan dosya uzantısı için FileType'ı alır. (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Belirtilen file_name için FileType döndürür. (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Sağlanan belge akışı için FileType döndürür. (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) sınıfından kalıtılmıştır.) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Varsayılan hash işlevini sağlar. ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) sınıfından kalıtılmıştır.) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Dosya türünün dize temsili. (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Dosya türü açıklaması. (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Dosya uzantısı. (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Dosya ailesi. (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Dosya biçimi. (kalıtılmış [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişi, randevu veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | EML dosya formatı, Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder. Neredeyse tüm e-posta istemcileri, RFC-822 Internet Message Format Standardına uyumu nedeniyle bu dosya formatını destekler. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | EMLX dosya formatı Apple tarafından uygulanıp geliştirilmiştir. Apple Mail uygulaması e-postaları dışa aktarmak için EMLX dosya formatını kullanır. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF (Virtual Card Format) veya vCard, iletişim bilgilerini depolamak için dijital bir dosya formatıdır. Bu format, popüler bilgi değişim uygulamaları arasında veri alışverişi için yaygın olarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | MBox dosya formatı, elektronik posta mesajlarının bir koleksiyonunu içeren bir kapsayıcıyı temsil eden genel bir terimdir. Mesajlar, ekleriyle birlikte kapsayıcı içinde saklanır. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | .PST uzantılı dosyalar, çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyalarını (Personal Storage Table olarak da bilinir) temsil eder. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST veya Offline Storage Files, Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | .olm uzantılı bir dosya, Mac İşletim Sistemi için Microsoft Outlook dosyasıdır. OLM dosyası e-posta mesajları, günlükler, takvim verileri ve diğer uygulama verilerini depolar. Bunlar, Windows İşletim Sistemi'nde Outlook tarafından kullanılan PST dosyalarına benzer. Ancak, Mac için Outlook tarafından oluşturulan OLM dosyaları Windows için Outlook'ta açılamaz. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | ICS (iCalendar) dosya formatı, etkinlikler, yapılacaklar ve müsait/meşgul verileri gibi takvim ve planlama bilgilerini temsil etmek ve değiştirmek için kullanılır. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Bilinmeyen dosya türü (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Ayrıca Bakınız
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
