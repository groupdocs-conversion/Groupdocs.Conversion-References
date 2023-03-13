---
title: EmailFileType
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Определяет форматы файлов электронной почты которые используются почтовыми приложениями для хранения их различных данных включая сообщения электронной почты вложения папки адресные книги и т. д. Включает следующие типы файлов Eml./emailfiletype/eml  Emlx./emailfiletype/emlx  Msg./emailfiletype/msg  Vcf./emailfiletype/vcf . Mbox./emailfiletype/mbox . Pst./emailfiletype/pst . Ost./emailfiletype/ost . Подробнее о форматах электронной почтыздесьhttps//wiki.fileformat.com/email .
type: docs
weight: 920
url: /ru/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Определяет форматы файлов электронной почты, которые используются почтовыми приложениями для хранения их различных данных, включая сообщения электронной почты, вложения, папки, адресные книги и т. д. Включает следующие типы файлов: [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Vcf`](./vcf) . [`Mbox`](./mbox) . [`Pst`](./pst) . [`Ost`](./ost) . Подробнее о форматах электронной почты[здесь](https://wiki.fileformat.com/email) .

```csharp
public sealed class EmailFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmailFileType](emailfiletype)() | Конструктор сериализации |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Формат файла EML представляет сообщения электронной почты, сохраненные с помощью Outlook и других соответствующих приложений. Почти все клиенты электронной почты поддерживают этот формат файла из-за его соответствия стандарту формата интернет-сообщений RFC-822. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/email/eml) . |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Формат файла EMLX реализован и разработан Apple. Приложение Apple Mail использует формат файлов EMLX для экспорта электронных писем. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/email/emlx) . |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Формат файла MBox — это общий термин, обозначающий контейнер для сбора сообщений электронной почты. Сообщения хранятся внутри контейнера вместе с вложениями. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG — это формат файла, используемый Microsoft Outlook и Exchange для хранения сообщений электронной почты, контактов, встреч и других задач. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/email/msg) . |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST или файлы автономного хранилища представляют данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/email/ost) . |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Файлы с расширением .PST представляют собой файлы личного хранилища Outlook (также называемые таблицей личного хранилища), в которых хранится разнообразная информация о пользователях. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/email/pst) . |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (формат виртуальной карты) или vCard — это цифровой формат файла для хранения контактной информации. Этот формат широко используется для обмена данными между популярными приложениями для обмена информацией. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/email/vcf) . |

### Смотрите также

* class [FileType](../filetype)
* пространство имен [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
