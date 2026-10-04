---
title: "PageDescriptionLanguageFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет документы описания страниц. Включает следующие типы файлов Svg./pagedescriptionlanguagefiletype/svgSvgz./pagedescriptionlanguagefiletype/svgzEps./pagedescriptionlanguagefiletype/epsCgm./pagedescriptionlanguagefiletype/cgmXps./pagedescriptionlanguagefiletype/xpsTex./pagedescriptionlanguagefiletype/texPs./pagedescriptionlanguagefiletype/psPcl./pagedescriptionlanguagefiletype/pclOxps./pagedescriptionlanguagefiletype/oxps"
type: docs
weight: 1190
url: /ru/net/groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
## PageDescriptionLanguageFileType class

Определяет документы описания страниц. Включает следующие типы файлов: [`Svg`](./svg)[`Svgz`](./svgz)[`Eps`](./eps)[`Cgm`](./cgm)[`Xps`](./xps)[`Tex`](./tex)[`Ps`](./ps)[`Pcl`](./pcl)[`Oxps`](./oxps)

```csharp
public sealed class PageDescriptionLanguageFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PageDescriptionLanguageFileType](pagedescriptionlanguagefiletype)() | Конструктор сериализации |

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Семейство файлов |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

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
| static readonly [Cgm](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/cgm) | Computer Graphics Metafile (CGM) — бесплатный, независимый от платформы, международный стандартный формат метафайла для хранения и обмена векторной графикой (2D), растровой графикой и текстом. CGM использует объектно‑ориентированный подход и множество функций для создания изображений. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/page-description-language/cgm). |
| static readonly [Eps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/eps) | Файлы с расширением EPS по сути описывают программу на языке Encapsulated PostScript, которая определяет внешний вид одной страницы. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/page-description-language/eps). |
| static readonly [Oxps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/oxps) | Формат файла OXPS известен как Open XML Paper Specification. Это язык описания страниц и формат документа. Microsoft является разработчиком этого формата. Формат OXPS очень похож на PDF‑файлы. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/page-description-language/oxps). |
| static readonly [Pcl](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/pcl) | PCL расшифровывается как Printer Command Language, который является языком описания страниц, разработанным компанией Hewlett Packard (HP). Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/page-description-language/pcl). |
| static readonly [Ps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/ps) | PostScript (PS) — это язык описания страниц общего назначения, используемый в сфере настольной и электронных публикаций. Основная цель PostScript (PS) — облегчить двумерное графическое проектирование. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/page-description-language/ps). |
| static readonly [Svg](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/svg) | Файл SVG — это файл Scalable Vector Graphics, использующий основанный на XML текстовый формат для описания внешнего вида изображения. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/page-description-language/svg). |
| static readonly [Svgz](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/svgz) | Файл SVGZ фактически представляет собой сжатую версию файла SVG. Это упрощает распространение файла в сети. Когда файл SVG сжимается с помощью алгоритма сжатия .GZIP, ему присваивается расширение .svgz. |
| static readonly [Tex](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/tex) | TeX — это язык, включающий возможности программирования и разметки, используемый для наборa документов. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/page-description-language/tex). |
| static readonly [Xps](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/xps) | Файл XPS представляет файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Этот формат был разработан Microsoft как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и параметров печати документа. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/page-description-language/xps). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
