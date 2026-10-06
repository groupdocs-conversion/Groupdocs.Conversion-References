---
title: "FinanceFileType sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Finans belge türlerini tanımlar."
type: docs
url: /tr/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

Finans belge türlerini tanımlar.

Aşağıdaki türleri içerir: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). Finans formatları hakkında daha fazla bilgi için buraya bakın: https://docs.fileformat.com/finance/.

FinanceFileType türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | Serileştirme için bir FinanceFileType başlatır. |

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
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL, dijital iş raporlaması için dünya çapında yaygın olarak kullanılan açık bir uluslararası standarttır. XBRL öğeleri, etiket olarak bilinen, iş verisinin her öğesini tanımlamak ve rapor sıralama ve analiz için veriyi düzenlemek amacıyla kullanan XML tabanlı bir dildir. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | iXBRL içinde, XBRL içeriği XML etiketleri kullanan xHTML dosya formatında paketlenir. XBRL gibi, iXBRL dosyalarının kök öğesidir. XHTML formatı, içeriğini farklı belge türleri ve modüllerin bir koleksiyonu olarak temsil eder. XHTML'deki tüm dosyalar XML dosya formatına dayanır ve XML belge standartlarına uyar. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange (OFX), Microsoft'un Open Financial Connectivity (OFC) ve Intuit'in Open Exchange dosya formatlarından evrimleşen finansal bilgi alışverişi için bir veri akışı formatıdır. Bu dosya formatı hakkında daha fazla bilgi için buraya bakın. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Bilinmeyen dosya türü (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Ayrıca Bakınız
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
