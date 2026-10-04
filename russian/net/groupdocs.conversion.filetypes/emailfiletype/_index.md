---
title: "EmailFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет форматы файлов электронной почты, которые используются почтовыми приложениями для хранения различных данных, включая сообщения электронной почты, вложения, папки, адресные книги и т.д. Включает следующие типы файлов Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. Узнайте больше о форматах электронной почты здесьhttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /ru/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Определяет форматы файлов электронной почты, которые используются почтовыми приложениями для хранения различных данных, включая сообщения электронной почты, вложения, папки, адресные книги и т.д. Включает следующие типы файлов: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). Узнайте больше о форматах электронной почты [здесь](https://wiki.fileformat.com/email).

```csharp
public sealed class EmailFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmailFileType](emailfiletype)() | Конструктор сериализации |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Формат файла EML представляет сообщения электронной почты, сохранённые с помощью Outlook и других соответствующих приложений. Практически все почтовые клиенты поддерживают этот формат файла благодаря его соответствию стандарту RFC-822 Internet Message Format. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Формат файла EMLX реализован и разработан компанией Apple. Приложение Apple Mail использует формат файла EMLX для экспорта электронных писем. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | Формат файла ICS (iCalendar) используется для представления и обмена информацией о календарях и расписании, такой как события, задачи и данные о занятости/свободном времени. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Формат файла MBox — это общий термин, обозначающий контейнер для коллекции электронных сообщений. Сообщения хранятся внутри контейнера вместе с их вложениями. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG — это формат файла, используемый Microsoft Outlook и Exchange для хранения сообщений электронной почты, контактов, встреч или других задач. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | Файл с расширением .olm — это файл Microsoft Outlook для операционной системы macOS. Файл OLM хранит сообщения электронной почты, журналы, данные календаря и другие типы данных приложения. Они похожи на файлы PST, используемые Outlook в операционной системе Windows. Однако файлы OLM, созданные Outlook для Mac, нельзя открыть в Outlook для Windows. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST или Offline Storage Files представляют данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с помощью Microsoft Outlook. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Файлы с расширением .PST представляют Outlook Personal Storage Files (также называемые Personal Storage Table), которые хранят разнообразную пользовательскую информацию. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) или vCard — это цифровой формат файла для хранения контактной информации. Формат широко используется для обмена данными между популярными приложениями обмена информацией. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/email/vcf). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
