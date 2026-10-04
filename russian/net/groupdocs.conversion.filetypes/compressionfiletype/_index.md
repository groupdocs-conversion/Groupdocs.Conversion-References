---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет форматы сжатия. Включает следующие типы файлов Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. Узнайте больше о форматах сжатия здесь https//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /ru/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Определяет форматы сжатия. Включает следующие типы файлов: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). Узнайте больше о форматах сжатия [здесь](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Семейство файлов |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Определяет, поддерживает ли формат несколько файлов/папок в одном архиве. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Реализует [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | Файл с расширением .aar — это Apple Archive, контейнер, который Apple поставляет с macOS для группировки файлов и папок. Каждая запись сжимается отдельно, обычно с помощью LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | Файл с расширением .alz — это архив ALZip, формат от ESTsoft, широко используемый в Южной Корее. Записи могут быть зашифрованы паролем индивидуально. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 — это сжатые файлы, созданные с использованием открытого метода сжатия BZIP2, в основном в системах UNIX или Linux. Он используется для сжатия отдельного файла и не предназначен для архивирования нескольких файлов. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Файл с расширением .cab относится к файлам Windows Cabinet, которые относятся к категории системных файлов. Это файл, сохраняемый в формате архива в версиях Microsoft Windows, поддерживающих алгоритмы сжатия данных, такие как LZX, Quantum и ZIP. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio — это универсальная утилита архивирования файлов и соответствующий ей формат. Она в основном устанавливается в операционных системах, похожих на Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Файл GZ — это сжатый архив, созданный с использованием стандартного алгоритма сжатия gzip (GNU zip). Он может содержать несколько сжатых файлов, каталоги и заглушки файлов. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Файл Gzip — это сжатый архив, созданный с использованием стандартного алгоритма сжатия gzip (GNU zip). Он может содержать несколько сжатых файлов, каталоги и заглушки файлов. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | Файл с расширением .iso — это не сжатый архивный образ диска, который представляет содержимое всех данных на оптическом диске, таком как CD или DVD. Основанный на стандарте ISO-9660, формат образа ISO содержит данные диска вместе с информацией о файловой системе, хранящейся в нём. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | Файл с расширением .lzh и .lha обычно относится к формату архивного сжатия. Этот формат такой же, как и другие форматы сжатия файлов, такие как ZIP, RAR и т.д. Основная цель этих форматов — уменьшить размер файлов для удобной отправки, а также хранить их вместе в сжатом виде. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Файл с расширением .lz — это сжатый архив, созданный с помощью Lzip, бесплатного инструмента командной строки для сжатия. Он поддерживает конкатенацию для сжатия вспомогательных файлов. Файлы LZ имеют тип media application/lzip и обеспечивают более высокий уровень сжатия, чем BZ2. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | Файл с расширением .lz4 — это сжатый архив, созданный приложениями/утилитами, поддерживающими сжатие L4. Алгоритм LZ4 ориентирован на компромисс между скоростью и коэффициентом сжатия. Сжатые архивы LZ4 можно создавать с помощью утилиты командной строки LZ4 и распаковывать её же. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Файл с расширением .lzma — это сжатый архив, созданный с использованием метода сжатия LZMA (Lempel‑Ziv‑Markov chain Algorithm). Такие файлы в основном встречаются/используются в операционных системах Unix и похожи на другие алгоритмы сжатия, такие как ZIP, для уменьшения размера файлов. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Файлы с расширением .rar — это архивные файлы, создаваемые для хранения информации в сжатом или обычном виде. RAR, что расшифровывается как Roshal ARchive file format. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z — это формат архивирования для сжатия файлов и папок с высоким коэффициентом сжатия. Он основан на открытой архитектуре, что позволяет использовать любые алгоритмы сжатия и шифрования. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Файлы с расширением .tar — это архивы, создаваемые с помощью утилиты на базе Unix для объединения одного или нескольких файлов. Несколько файлов хранятся в несжатом формате с поддержкой добавления файлов и папок в архив. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Uuencoded‑архив — это файл или набор файлов, закодированных с использованием схемы кодирования Unix-to-Unix (uuencode). Этот метод кодирования преобразует двоичные данные в текстовый формат, что упрощает отправку файлов через каналы, поддерживающие только текст, например электронную почту. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | Файл с расширением .wim — это архив Windows Imaging Format, образ диска на основе файлов, который Microsoft использует для развертывания Windows. Один архив содержит один или несколько образов и хранит каждый файл единожды, независимо от количества образов, которые его используют. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | Файл с расширением .xar — это eXtensible ARchive, формат, построенный вокруг таблицы содержимого, хранящейся в виде сжатого XML. Он используется для распространения пакетов установщика macOS и хранит каждую запись сжатой отдельно. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ — это сжатый файловый формат, использующий алгоритм сжатия LZMA2. Он был разработан как замена популярным форматам gzip и bzip2 и предлагает ряд преимуществ перед этими более старыми стандартами. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Файл Z — это категория файлов, принадлежащих к UNIX‑сжатым данным. Сжатые Unix‑файлы являются самым популярным и широко используемым типом расширения для файлов Z. Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Файл с расширением .zip — это архив, который может содержать один или несколько файлов или каталогов. К архиву может быть применено сжатие включённых файлов, чтобы уменьшить размер ZIP‑файла. Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | Файл ZST — это сжатый файл, созданный с помощью алгоритма сжатия Zstandard (zstd). Это сжатый файл, созданный без потерь алгоритмом. Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/compression/zst/). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
