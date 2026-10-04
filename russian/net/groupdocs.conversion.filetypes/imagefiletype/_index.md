---
title: "ImageFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет типы изображений. Включает следующие типы файлов Ai./imagefiletype/ai Avif./imagefiletype/avif Bmp./imagefiletype/bmp Cdr./imagefiletype/cdr Cmx./imagefiletype/cmx Dcm./imagefiletype/dcm Dib./imagefiletype/dib DjVu./imagefiletype/djvu Dng./imagefiletype/dng Emf./imagefiletype/emf Emz./imagefiletype/emz Gif./imagefiletype/gif Heic./imagefiletype/heicIco./imagefiletype/ico J2c./imagefiletype/j2c J2k./imagefiletype/j2k Jls./imagefiletype/jls Jp2./imagefiletype/jp2 Jpc./imagefiletype/jpc Jfif./imagefiletype/jfif. Jpeg./imagefiletype/jpeg Jpf./imagefiletype/jpf Jpg./imagefiletype/jpg Jpm./imagefiletype/jpm Jpx./imagefiletype/jpx Odg./imagefiletype/odg Png./imagefiletype/png Psd./imagefiletype/psd Tif./imagefiletype/tif Tiff./imagefiletype/tiff Webp./imagefiletype/webp Wmf./imagefiletype/wmf. Wmz./imagefiletype/wmz. Узнайте больше о форматах изображений здесьhttps//wiki.fileformat.com/image."
type: docs
weight: 1170
url: /ru/net/groupdocs.conversion.filetypes/imagefiletype/
---
## ImageFileType class

Определяет типы изображений. Включает следующие типы файлов: [`Ai`](./ai), [`Avif`](./avif), [`Bmp`](./bmp), [`Cdr`](./cdr), [`Cmx`](./cmx), [`Dcm`](./dcm), [`Dib`](./dib), [`DjVu`](./djvu), [`Dng`](./dng), [`Emf`](./emf), [`Emz`](./emz), [`Gif`](./gif), [`Heic`](./heic)[`Ico`](./ico), [`J2c`](./j2c), [`J2k`](./j2k), [`Jls`](./jls), [`Jp2`](./jp2), [`Jpc`](./jpc), [`Jfif`](./jfif). [`Jpeg`](./jpeg), [`Jpf`](./jpf), [`Jpg`](./jpg), [`Jpm`](./jpm), [`Jpx`](./jpx), [`Odg`](./odg), [`Png`](./png), [`Psd`](./psd), [`Tif`](./tif), [`Tiff`](./tiff), [`Webp`](./webp), [`Wmf`](./wmf). [`Wmz`](./wmz). Узнайте больше о форматах изображений [здесь](https://wiki.fileformat.com/image).

```csharp
public sealed class ImageFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageFileType](imagefiletype)() | Конструктор сериализации |

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Семейство файлов |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |
| [IsRaster](../../groupdocs.conversion.filetypes/imagefiletype/israster) { get; } | Определяет, является ли изображение растровым |

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
| static readonly [Ai](../../groupdocs.conversion.filetypes/imagefiletype/ai) | AI, Adobe Illustrator Artwork, представляет одностраничные векторные рисунки в форматах EPS или PDF. |
| static readonly [Avif](../../groupdocs.conversion.filetypes/imagefiletype/avif) | AVIF (AV1 Image File Format) — это формат файлов изображений, который хранит изображения, сжатые с помощью AV1, в формате HEIF. Файлы AVIF сохраняются с расширением .avif. Версия 1 AVIF была завершена в феврале 2019 года. Он имеет такие возможности, как высокий динамический диапазон (HDR), поддержка глубины цвета 8, 10 и 12 бит, поддержка любого цветового пространства (ISO/IEC CICP и ICC‑профили, широкий цветовой охват) и т.д. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/image/avif/). |
| static readonly [Bmp](../../groupdocs.conversion.filetypes/imagefiletype/bmp) | BMP представляет файлы Bitmap Image, которые используются для хранения растровых цифровых изображений. Эти изображения независимы от графического адаптера и также называются форматом device independent bitmap (DIB). Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/bmp). |
| static readonly [Cdr](../../groupdocs.conversion.filetypes/imagefiletype/cdr) | Файл CDR — это векторный графический файл, который изначально создаётся в CorelDRAW для хранения цифрового изображения, закодированного и сжатого. Такой файл рисунка содержит текст, линии, формы, изображения, цвета и эффекты для векторного представления содержимого изображения. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/cdr). |
| static readonly [Cmx](../../groupdocs.conversion.filetypes/imagefiletype/cmx) | Файлы с расширением CMX — это формат графических файлов Corel Exchange, который используется для презентаций в приложениях CorelSuite. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/cmx). |
| static readonly [Dcm](../../groupdocs.conversion.filetypes/imagefiletype/dcm) | Файлы с расширением .DCM представляют собой цифровое изображение, которое хранит медицинскую информацию о пациентах, такую как МРТ, КТ‑сканы и ультразвуковые изображения. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/dcm). |
| static readonly [Dib](../../groupdocs.conversion.filetypes/imagefiletype/dib) | Файл DIB (Device Independent Bitmap) — это растровый графический файл, схожий по структуре со стандартными файлами Bitmap (BMP), но имеющий иной заголовок. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/dib). |
| static readonly [Dicom](../../groupdocs.conversion.filetypes/imagefiletype/dicom) | Файлы с расширением .DICOM представляют собой цифровое изображение, которое хранит медицинскую информацию о пациентах, такую как МРТ, КТ‑сканы и ультразвуковые изображения. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/dicom). |
| static readonly [DjVu](../../groupdocs.conversion.filetypes/imagefiletype/djvu) | DjVu — это графический формат файлов, предназначенный для отсканированных документов и книг, особенно тех, которые содержат комбинацию текста, рисунков, изображений и фотографий. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/djvu). |
| static readonly [Dng](../../groupdocs.conversion.filetypes/imagefiletype/dng) | DNG — это формат изображений цифровой камеры, используемый для хранения RAW‑файлов. Он был разработан компанией Adobe в сентябре 2004 года. По сути, он был создан для цифровой фотографии. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/dng). |
| static readonly [Emf](../../groupdocs.conversion.filetypes/imagefiletype/emf) | Формат Enhanced Metafile (EMF) хранит графические изображения независимо от устройства. Метафайлы EMF состоят из записей переменной длины в хронологическом порядке, которые могут отрисовать сохранённое изображение после разбора на любом выводном устройстве. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/emf). |
| static readonly [Emz](../../groupdocs.conversion.filetypes/imagefiletype/emz) | Файл EMZ на самом деле является сжатой версией файла Microsoft EMF. Это упрощает распространение файла в сети. Когда файл EMF сжимается с помощью алгоритма сжатия .GZIP, ему присваивается расширение .emz. |
| static readonly [Fodg](../../groupdocs.conversion.filetypes/imagefiletype/fodg) | FODG — это несжатый файл в формате XML, используемый для хранения текстовых данных OpenDocument. Расширение FODG связано с открытыми офисными пакетами LibreOffice и OpenOffice.org. |
| static readonly [Gif](../../groupdocs.conversion.filetypes/imagefiletype/gif) | GIF (Graphics Interchange Format) — это тип сильно сжатого изображения. Для каждого изображения GIF обычно допускает до 8 бит на пиксель, а всего допускается до 256 цветов. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/gif). |
| static readonly [Heic](../../groupdocs.conversion.filetypes/imagefiletype/heic) | Файл HEIC — это формат контейнерного изображения высокой эффективности, который может хранить несколько изображений как коллекцию в одном файле. Этот формат был принят Apple как вариант HEIF с выпуском iOS 11. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/image/heic/). |
| static readonly [Ico](../../groupdocs.conversion.filetypes/imagefiletype/ico) | Файлы с расширением ICO — это типы графических файлов, используемые в качестве значков для представления приложения в Microsoft Windows. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/ico). |
| static readonly [J2c](../../groupdocs.conversion.filetypes/imagefiletype/j2c) | Формат документа J2c |
| static readonly [J2k](../../groupdocs.conversion.filetypes/imagefiletype/j2k) | Файл J2K — это изображение, сжатое с помощью вейвлет‑компрессии вместо DCT‑компрессии. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/j2k). |
| static readonly [Jfif](../../groupdocs.conversion.filetypes/imagefiletype/jfif) | JFIF (JPEG File Interchange Format) — это файловый формат изображения, использующий расширение .jfif. JFIF построен на основе JIF (JPEG Interchange Format), упрощая структуру и устраняя её ограничения. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/image/jfif/). |
| static readonly [Jls](../../groupdocs.conversion.filetypes/imagefiletype/jls) | Формат документа Jls |
| static readonly [Jp2](../../groupdocs.conversion.filetypes/imagefiletype/jp2) | JPEG 2000 (JP2) — это система кодирования изображений и передовой стандарт сжатия изображений. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/jp2). |
| static readonly [Jpc](../../groupdocs.conversion.filetypes/imagefiletype/jpc) | Формат документа Jpc |
| static readonly [Jpeg](../../groupdocs.conversion.filetypes/imagefiletype/jpeg) | JPEG — это тип формата изображения, сохраняемый с помощью метода сжатия с потерями. Полученное изображение, как результат сжатия, представляет собой компромисс между размером хранилища и качеством изображения. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpf](../../groupdocs.conversion.filetypes/imagefiletype/jpf) | формат документа Jpf |
| static readonly [Jpg](../../groupdocs.conversion.filetypes/imagefiletype/jpg) | JPG — это тип формата изображения, сохраняемый с помощью метода сжатия с потерями. Полученное изображение, как результат сжатия, представляет собой компромисс между размером хранилища и качеством изображения. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/jpeg). |
| static readonly [Jpm](../../groupdocs.conversion.filetypes/imagefiletype/jpm) | формат документа Jpm |
| static readonly [Jpx](../../groupdocs.conversion.filetypes/imagefiletype/jpx) | формат документа Jpx |
| static readonly [Odg](../../groupdocs.conversion.filetypes/imagefiletype/odg) | Формат файла ODG используется приложением Draw от Apache OpenOffice для хранения элементов рисунка в виде векторного изображения. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/odg). |
| static readonly [Otg](../../groupdocs.conversion.filetypes/imagefiletype/otg) | Файл OTG — это шаблон рисунка, созданный с использованием стандарта OpenDocument, соответствующего спецификации OASIS Office Applications 1.0. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/otg). |
| static readonly [Png](../../groupdocs.conversion.filetypes/imagefiletype/png) | PNG, Portable Network Graphics, относится к типу растрового формата изображения, использующего безпотерьное сжатие. Этот формат файла был создан как замена Graphics Interchange Format (GIF) и не имеет ограничений по авторским правам. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/png). |
| static readonly [Psb](../../groupdocs.conversion.filetypes/imagefiletype/psb) | Adobe Photoshop сохраняет файлы в двух форматах. Файлы размером 30 000 × 30 000 пикселей сохраняются с расширением PSD, а файлы, превышающие PSD до 300 000 × 300 000 пикселей, сохраняются с расширением PSB, известным как "Photoshop Big". Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/image/psb). |
| static readonly [Psd](../../groupdocs.conversion.filetypes/imagefiletype/psd) | PSD, Photoshop Document, представляет собственный формат файла Adobe Photoshop, используемый для разработки и дизайна графики. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/psd). |
| static readonly [Tga](../../groupdocs.conversion.filetypes/imagefiletype/tga) | Файл с расширением .tga — это растровый графический формат, созданный компанией Truevision Inc. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/image/tga). |
| static readonly [Tif](../../groupdocs.conversion.filetypes/imagefiletype/tif) | TIF, Tagged Image File Format, представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту формата файла. Он способен описывать двууровневые, градации серого, палитровые и полноцветные данные изображения в нескольких цветовых пространствах. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/tiff). |
| static readonly [Tiff](../../groupdocs.conversion.filetypes/imagefiletype/tiff) | TIFF, Tagged Image File Format, представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту формата файла. Он способен описывать двууровневые, градации серого, палитровые и полноцветные данные изображения в нескольких цветовых пространствах. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/tiff). |
| static readonly [Webp](../../groupdocs.conversion.filetypes/imagefiletype/webp) | WebP, представленный Google, — это современный растровый веб-формат изображения, основанный на безпотерьном и с потерями сжатии. Он обеспечивает такое же качество изображения, одновременно значительно уменьшая размер файла. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/webp). |
| static readonly [Wmf](../../groupdocs.conversion.filetypes/imagefiletype/wmf) | Файлы с расширением WMF представляют Microsoft Windows Metafile (WMF) для хранения как векторных, так и растровых изображений. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/wmf). |
| static readonly [Wmz](../../groupdocs.conversion.filetypes/imagefiletype/wmz) | Файл WMZ на самом деле является сжатой версией файла Microsoft WMF. Это упрощает распространение файла в сети. Когда файл EWMFMF сжимается с помощью алгоритма сжатия .GZIP, ему присваивается расширение .wmz. |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
