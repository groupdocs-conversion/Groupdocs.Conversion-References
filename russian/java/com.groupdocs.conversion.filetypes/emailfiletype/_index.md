---
title: "EmailFileType"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Определяет форматы файлов электронной почты, которые используются почтовыми приложениями для хранения различных данных, включая сообщения электронной почты, вложения, папки, адресные книги и т.д."
type: docs
weight: 15
url: /ru/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Определяет форматы файлов электронной почты, которые используются почтовыми приложениями для хранения различных данных, включая сообщения электронной почты, вложения, папки, адресные книги и т.д.
Включает следующие типы файлов:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
Узнайте больше о форматах электронной почты [здесь](../https://wiki.fileformat.com/email).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | Конструктор сериализации |
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [Msg](#Msg) | MSG — это формат файла, используемый Microsoft Outlook и Exchange для хранения сообщений электронной почты, контактов, встреч или других задач. |
|
|  | [Eml](#Eml) | Формат файла EML представляет собой сообщения электронной почты, сохранённые с помощью Outlook и других соответствующих приложений. |
|
|  | [Emlx](#Emlx) | Формат файла EMLX реализован и разработан компанией Apple. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) или vCard — это цифровой формат файла для хранения контактной информации. |
|
|  | [Mbox](#Mbox) | Формат файла MBox — это общее название, обозначающее контейнер для коллекции электронных сообщений. |
|
|  | [Pst](#Pst) | Файлы с расширением .PST представляют собой Outlook Personal Storage Files (также называемые Personal Storage Table), которые хранят разнообразную пользовательскую информацию. |
|
|  | [Ost](#Ost) | OST или файлы офлайн-хранилища представляют данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. |
|
|  | [Olm](#Olm) | Файл с расширением .olm — это файл Microsoft Outlook для операционной системы Mac. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Конструктор сериализации


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG — это формат файла, используемый Microsoft Outlook и Exchange для хранения сообщений электронной почты, контактов, встреч или других задач.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


Формат файла EML представляет электронные сообщения, сохранённые с помощью Outlook и других соответствующих приложений. Практически все почтовые клиенты поддерживают этот формат файла благодаря его соответствию стандарту RFC‑822 Internet Message Format.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


Формат файла EMLX реализован и разработан компанией Apple. Приложение Apple Mail использует формат EMLX для экспорта электронных писем.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) или vCard — это цифровой формат файла для хранения контактной информации. Формат широко используется для обмена данными между популярными приложениями обмена информацией.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


Формат файла MBox — это общее название, обозначающее контейнер для коллекции электронных почтовых сообщений. Сообщения хранятся внутри контейнера вместе со своими вложениями.
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


Файлы с расширением .PST представляют собой Outlook Personal Storage Files (также называемые Personal Storage Table), которые хранят разнообразную информацию пользователя. Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST или файлы офлайн-хранилища представляют данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


Файл с расширением .olm — это файл Microsoft Outlook для операционной системы Mac. Файл OLM хранит электронные сообщения, журналы, данные календаря и другие типы данных приложений. Они похожи на файлы PST, используемые Outlook в операционной системе Windows. Однако файлы OLM, созданные Outlook для Mac, не могут\\u2019t быть открыты в Outlook для Windows. Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/olm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Подготовлены параметры конвертации по умолчанию для типа файла


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
