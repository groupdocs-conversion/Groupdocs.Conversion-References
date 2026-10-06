---
title: "Komut Satırı Arayüzü"
linkTitle: "Command Line Interface"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "groupdocs-conversion komut satırı aracıyla belgeleri doğrudan terminalden dönüştürün — Python betiği gerekmez. Belgeleri inceleyin, desteklenen formatları listeleyin ve bir lisans uygulayın, hepsi kabuktan."
type: docs
url: /tr/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


`groupdocs-conversion-net` paketini kurmak aynı zamanda `groupdocs-conversion` konsol betiğini `PATH`'inize ekler. Bu, Python API'si üzerinde ince bir sarmalayıcıdır ve bir Python betiği çalıştırmanın gereksiz olduğu durumlar için tasarlanmıştır — kabuk boru hatları, Make kuralları, CI adımları ve tek seferlik dönüşümler.

## Prerequisites

CLI paket içinde gelir, bu yüzden ekstra kurulum gerekmez. `groupdocs-conversion-net`'in kurulu olduğundan emin olun (bkz. [Quick Start Guide]()), ardından konsol betiğinin mevcut olduğunu doğrulayın:

```bash
groupdocs-conversion --version
```

Paket sürümünün yazdırıldığını görmelisiniz, örneğin `groupdocs-conversion 26.9.0`.

`groupdocs-conversion` komutu bulunamazsa, paketin betik dizini `PATH`'inizde olmayabilir. Bunun yerine CLI'yı Python modülü biçiminde her zaman çalıştırabilirsiniz: `python -m groupdocs.conversion`. İkisi de eşdeğerdir.

## Commands

CLI dört alt komut sunar. Tam bayrak listesini görmek için `groupdocs-conversion --help` komutunu çalıştırın, ya da belirli bir alt komut için `groupdocs-conversion <command> --help` komutunu kullanın.

### convert

Bir belgeyi başka bir formata dönüştürün. Hedef format, çıktı dosyası uzantısından çıkarılır; `--format` ile geçersiz kılabilirsiniz.

```bash
# Uzantı hedef formatı seçer
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Çıktı adı kullanılabilir bir uzantı içermediğinde formatı geçersiz kıl
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Tek bir sayfayı dönüştür (1‑indeksli) — raster hedefler için yararlıdır
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Şifre korumalı bir kaynağı aç
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Seçenek | Açıklama |
| :- | :- |
| `--format` | Hedef format belirteci (çıktı uzantısını geçersiz kılar). |
| `--password` | Korunan bir kaynak belgesi için şifre. |
| `--page` | Dönüştürülecek ilk sayfa, 1‑indeksli. |
| `--count` | Dönüştürülecek sayfa sayısı. |

Başarılı olduğunda komut çıktı yolunu yazdırır ve `0` koduyla çıkar.

### info

Bir belge hakkında temel bilgileri yazdır — format, boyut, sayfa sayısı ve mevcut olduğunda oluşturulma tarihi.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Korunan kaynaklar için `--password` kullanın.

### list-formats

Belirli bir giriş belgesi için motorun üretebileceği tüm hedef formatları, birincil ve ikincil hedefler olarak listeleyin.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Korunan kaynaklar için `--password` kullanın.

### list-all-formats

Motorun bildiği tam kaynak‑hedef dönüşüm matrisini yazdır — her giriş formatı ve dönüştürülebileceği hedefler.

```bash
groupdocs-conversion list-all-formats
```

Bu komut herhangi bir giriş dosyası almaz.

## Global options

Bu seçenekler her komuta uygulanır:

| Seçenek | Açıklama |
| :- | :- |
| `--license PATH` | Komutu çalıştırmadan önce bir lisans dosyası uygulayın. |
| `--version` | CLI sürümünü yazdır ve çık. |
| `--help` | Kullanım yardımını göster ve çık. |

Alt komuttan önce `--license` ekleyerek önceden bir lisans uygulayın:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

CLI ayrıca `GROUPDOCS_LIC_PATH` ortam değişkenine saygı gösterir — ayarlıysa lisans otomatik olarak uygulanır ve `--license`'ı atlayabilirsiniz. Ayrıntılar için [Licensing]() konusuna bakın.

## Format tokens

`convert` çıktı uzantısını — ya da `--format` değerini, küçük harfe dönüştürülmüş hâlini — eşleşen dönüştürme seçeneklerine ve dosya tipine eşler. Desteklenen belirteçler şunlardır:

| Kategori | Belirteçler |
| :- | :- |
| PDF | `pdf` |
| Kelime işleme | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Elektronik tablo | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Sunum | `ppt`, `pptx`, `pptm`, `odp` |
| Web | `html`, `htm`, `mhtml` |
| Görsel | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| eKitap | `epub`, `mobi`, `azw3` |

Bilinmeyen bir token, komutun `2` kodu ile çıkmasına ve kabul edilen tokenların listesini yazdırmasına neden olur.

## Exit codes

| Kod | Anlam |
| :- | :- |
| `0` | Başarılı. |
| `2` | Kullanıcı hatası — bilinmeyen format tokenı veya eksik giriş dosyası. |
| `1` | Çalışma zamanı hatası — temel .NET istisna mesajı standart hataya yazdırılır. |

Bu kodlar, CLI'yi kabuk betiklerinde ve CI boru hatlarında dallandırmayı kolaylaştırır.

## When to use the Python API instead

CLI, yaygın tek belge dönüştürme durumlarını kapsar. Bunun ötesindeki her şey için — sayfa başı geri aramalar, bellek içi akışlar, filigran, yazı tipi veya hücre aralığı seçenekleri ve çok belge konteyner hiyerarşileri — doğrudan Python API'sını kullanın. CLI bayraklarından daha zengin bir arayüz sunar. Tam özellik seti için [Developer Guide]() sayfasına bakın.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
