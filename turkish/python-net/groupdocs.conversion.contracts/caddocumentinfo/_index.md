---
title: "CadDocumentInfo sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Cad belge meta verilerini içerir."
type: docs
url: /tr/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Cad belge meta verilerini içerir.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Açık [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) belirtilmediğinde, bu sayfalar model alanıdır; her zaman çizilebilir ve bu nedenle her zaman bir sayfadır, ayrıca depolanmış sayfa ayarı pozitif bir genişlik ve yüksekliğe sahip olan her kağıt-uzayı düzeni, [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) ile daraltılır. Açık düzen adları bunun yerine doğrudan kazanır: sayfalar daha sonra çizimin taşıdığı, sıralı olarak eşleşen sağlanan adlar olur, ne kapsam ne de sayfa ayarı onları süzmez.

DWF için yayınlanan sayfa kümesi raporlanır. Birin altındaki tek sayı sıfırdır; istenen kapsam, bir sayfa sunan bir çizimin hiçbir sayfasıyla eşleşmediğinde raporlanır: meta veri hâlâ çizimi tanımlar ve sıfır, kapsamın hiçbir şey seçtiğini, çizimin ne içerdiğini soran çağıranı başarısız etmediğini belirtir. Aynı yük seçenekleriyle bir dönüşüm başarısız olur.

Bu nedenle sayı, [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) boyutu değildir; bu, çizimin taşıdığı her çizim yapılandırmasını, sayfa yayımlanamayanları da dahil ederek listeler ve belirli bir dönüşümün kaç sayfa üreteceğini tahmin etmez.

CadDocumentInfo türü aşağıdaki üyeleri ortaya çıkar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | Belgenin oluşturulma tarihi. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | Belge formatı. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | CAD belgesinin yüksekliği. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | Belgedeki katmanlar. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | Belgedeki düzenler. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | Belge sayfa sayısı. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | Mevcut belge bilgisi için alınabilecek tüm özelliklerin enumerable'ı. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | Belge boyutu (bayt cinsinden). |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | CAD belgesinin genişliği. |

### Ayrıca Bakınız
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
