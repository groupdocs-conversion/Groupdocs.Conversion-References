---
title: CompressionFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет форматы сжатия. Включает следующие типы файлов Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . Подробнее о форматах сжатияздесьhttps//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /ru/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Определяет форматы сжатия. Включает следующие типы файлов: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . Подробнее о форматах сжатия[здесь](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Конструктор сериализации |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Файл family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит хеш-функцией по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 — это сжатые файлы, созданные с использованием метода сжатия с открытым исходным кодом BZIP2, в основном в системах UNIX или Linux. Он используется для сжатия одного файла и не предназначен для архивирования нескольких файлов. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Файл с расширением .cab относится к CAB-файлу Windows, который относится к категории системных файлов. Это файл, который сохраняется в формате архивного файла в версиях Microsoft Windows, которые поддерживают алгоритмы сжатия данных, такие как LZX, Quantum и ZIP. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio — это обычная утилита архиватора файлов и связанный с ней формат файлов. Он в основном устанавливается на Unix-подобные компьютерные операционные системы. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Файл GZ представляет собой сжатый архив, созданный с использованием стандартного алгоритма сжатия gzip (GNU zip). Он может содержать несколько сжатых файлов, каталогов и файлов-заглушек. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Файл Gzip представляет собой сжатый архив, созданный с использованием стандартного алгоритма сжатия gzip (GNU zip). Он может содержать несколько сжатых файлов, каталогов и файлов-заглушек. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Файл с расширением .lz — это сжатый архивный файл, созданный с помощью Lzip, бесплатного инструмента командной строки для сжатия. Он поддерживает конкатенацию для сжатия файлов поддержки. Файлы LZ имеют тип носителя application/lzip и поддерживают более высокую степень сжатия, чем BZ2. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Файл с расширением .lzma представляет собой сжатый архивный файл, созданный с использованием метода сжатия LZMA (цепной алгоритм Лемпеля-Зива-Маркова). Они в основном встречаются/используются в операционной системе Unix и аналогичны другим алгоритмам сжатия, таким как ZIP, для минимизации размера файла. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Файлы с расширением .rar представляют собой архивные файлы, которые создаются для хранения информации в сжатом или обычном виде. RAR, что означает формат файла Roshal ARchive. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z — формат архивации для сжатия файлов и папок с высокой степенью сжатия. Он основан на архитектуре с открытым исходным кодом, что позволяет использовать любые алгоритмы сжатия и шифрования. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Файлы с расширением .tar представляют собой архивы, созданные утилитой на основе Unix для сбора одного или нескольких файлов. Несколько файлов хранятся в несжатом формате с поддержкой добавления файлов, а также папок в архив. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ — это сжатый формат файла, использующий алгоритм сжатия LZMA2. Он был разработан в качестве замены популярных форматов gzip и bzip2 и предлагает ряд преимуществ по сравнению со старыми стандартами. Узнайте больше об этом формате файлов.[здесь](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Файл AZ — это категория файлов, принадлежащих файлам сжатых данных UNIX. Сжатые файлы Unix являются наиболее популярным и широко используемым типом расширения файла Z. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Файл с расширением .zip — это архив, который может содержать один или несколько файлов или каталогов. Включенные в архив файлы могут быть сжаты, чтобы уменьшить размер ZIP-файла. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/compression/zip/) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
