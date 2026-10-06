---
title: "Класс FontSubstitutionContext"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Описывает одну замену шрифта, произошедшую при загрузке или рендеринге исходного документа."
type: docs
url: /ru/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Описывает одну замену шрифта, произошедшую при загрузке или рендеринге исходного документа.

Экземпляры передаются в [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

Тип FontSubstitutionContext раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Инициализирует новый FontSubstitutionContext. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | Имя шрифта, на которое ссылается исходный документ, но недоступное для конвейера преобразования. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | Сообщение о замене точно так, как оно сообщается конвейером преобразования, дословно и без разбора. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | Имя файла исходного документа, который преобразуется. Когда источник предоставлен в виде потока, который не является `io.RawIOBase`, здесь содержится сгенерированный идентификатор, а не реальное имя файла. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | Имя шрифта, используемого в качестве замены. Может быть None для документов, у которых движок сообщает о замене только как описательный текст — в этом случае читайте [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### См. также
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
