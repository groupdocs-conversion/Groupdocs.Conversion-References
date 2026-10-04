---
title: "ТипФайлаУправленияПроектом"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет форматы файлов проектов, которые создаются программным обеспечением для управления проектами, таким как Microsoft Project, Primavera P6 и т.д. Файл проекта представляет собой набор задач, ресурсов и их расписания, позволяющий получить измеримый результат в виде продукта или услуги. Документы управления проектами. Включает следующие типы файлов: Mpp./projectmanagementfiletype/mpp Mpt./projectmanagementfiletype/mpt Mpx./projectmanagementfiletype/mpx. Узнайте больше о форматах управления проектами здесь https//wiki.fileformat.com/projectmanagement."
type: docs
weight: 1220
url: /ru/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Определяет форматы файлов проектов, которые создаются программным обеспечением для управления проектами, таким как Microsoft Project, Primavera P6 и т.д. Файл проекта представляет собой набор задач, ресурсов и их расписания, позволяющий получить измеримый результат в виде продукта или услуги. Документы управления проектами. Включает следующие типы файлов: [`Mpp`](./mpp), [`Mpt`](./mpt), [`Mpx`](./mpx). Узнайте больше о форматах управления проектами [здесь](https://wiki.fileformat.com/project-management).

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | Конструктор сериализации |

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
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP — это файл данных Microsoft Project, который хранит информацию, связанную с управлением проектом, в интегрированном виде. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | Шаблоны файлов Microsoft Project содержат базовую информацию и структуру, а также настройки документа для создания файлов .MPP. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange File Format — это ASCII‑формат файла для передачи проектной информации между Microsoft Project (MSP) и другими приложениями, поддерживающими формат MPX, такими как Primavera Project Planner, Sciforma и Timerline Precision Estimating. Узнайте больше об этом формате файлов [здесь](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | Формат файла XER — это проприетарный формат файлов проектов, используемый приложением Primavera P6 для планирования и управления проектами. Узнайте больше об этом формате файлов [здесь](https://docs.fileformat.com/project-management/xer). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
