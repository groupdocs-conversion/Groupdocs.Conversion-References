---
title: "Интерфейс командной строки"
linkTitle: "Command Line Interface"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Конвертируйте документы напрямую из терминала с помощью инструмента командной строки groupdocs-conversion — без необходимости в Python‑скрипте. Просматривайте документы, выводите список поддерживаемых форматов и применяйте лицензию, всё из оболочки."
type: docs
url: /ru/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


Установка пакета `groupdocs-conversion-net` также размещает консольный скрипт `groupdocs-conversion` в вашем `PATH`. Это тонкая оболочка над Python API, созданная для случаев, когда запуск Python‑скрипта избыточен — конвейеры оболочки, правила Make, шаги CI и разовые конверсии.

## Prerequisites

CLI поставляется внутри пакета, поэтому дополнительная установка не требуется. Убедитесь, что `groupdocs-conversion-net` установлен (см. [Quick Start Guide]()), затем проверьте доступность консольного скрипта:

```bash
groupdocs-conversion --version
```

Вы должны увидеть напечатанную версию пакета, например `groupdocs-conversion 26.9.0`.

Если команда `groupdocs-conversion` не найдена, каталог скриптов пакета может отсутствовать в вашем `PATH`. Вы всегда можете вызвать CLI через форму модуля Python: `python -m groupdocs.conversion`. Оба варианта эквивалентны.

## Commands

CLI предоставляет четыре подкоманды. Выполните `groupdocs-conversion --help` для полного списка флагов или `groupdocs-conversion <command> --help` для конкретной подкоманды.

### convert

Конвертировать документ в другой формат. Целевой формат выводится из расширения выходного файла; передайте `--format`, чтобы переопределить его.

```bash
# Расширение определяет целевой формат
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Переопределите формат, когда имя выходного файла не содержит пригодного расширения
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Конвертировать одну страницу (нумерация с 1) — полезно для растровых целей
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Открыть защищённый паролем источник
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Опция | Описание |
| :- | :- |
| `--format` | Токен целевого формата (переопределяет расширение выхода). |
| `--password` | Пароль для защищённого исходного документа. |
| `--page` | Первая страница для конвертации, нумерация с 1. |
| `--count` | Количество страниц для конвертации. |

При успешном выполнении команда выводит путь к результату и завершается с кодом `0`.

### info

Вывести базовую информацию о документе — формат, размер, количество страниц и дату создания, если доступно.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Используйте `--password` для защищённых источников.

### list-formats

Перечислить все целевые форматы, которые движок может создать для заданного входного документа, разделённые на основные и вторичные цели.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Используйте `--password` для защищённых источников.

### list-all-formats

Вывести полную матрицу преобразования от исходного к целевому, известную движку — каждый входной формат и цели, в которые он может быть преобразован.

```bash
groupdocs-conversion list-all-formats
```

Эта команда не принимает входной файл.

## Global options

Эти параметры применяются к каждой команде:

| Опция | Описание |
| :- | :- |
| `--license PATH` | Примените файл лицензии перед запуском команды. |
| `--version` | Вывести версию CLI и выйти. |
| `--help` | Показать справку по использованию и выйти. |

Примените лицензию заранее, разместив `--license` перед подкомандой:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

CLI также учитывает переменную окружения `GROUPDOCS_LIC_PATH` — если она задана, лицензия применяется автоматически, и вы можете опустить `--license`. См. тему [Licensing]() для подробностей.

## Format tokens

`convert` сопоставляет расширение выходного файла — или значение `--format` в нижнем регистре — с соответствующими параметрами конвертации и типом файла. Поддерживаемые токены:

| Категория | Токены |
| :- | :- |
| PDF | `pdf` |
| Обработка текста | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Электронные таблицы | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Презентация | `ppt`, `pptx`, `pptm`, `odp` |
| Веб | `html`, `htm`, `mhtml` |
| Изображение | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| Электронная книга | `epub`, `mobi`, `azw3` |

Неизвестный токен приводит к завершению команды с кодом `2` и выводит список допустимых токенов.

## Exit codes

| Код | Значение |
| :- | :- |
| `0` | Успешно. |
| `2` | Ошибка пользователя — неизвестный токен формата или отсутствует входной файл. |
| `1` | Ошибка выполнения — сообщение базового исключения .NET выводится в стандартный поток ошибок. |

Эти коды упрощают ветвление CLI в оболочечных скриптах и конвейерах CI.

## When to use the Python API instead

CLI покрывает общие случаи конвертации одиночных документов. Для всего, что выходит за эти рамки — обратные вызовы per-page, потоки в памяти, водяные знаки, шрифты, параметры диапазона ячеек и иерархии контейнеров многодокументных наборов — используйте напрямую Python API. Он предоставляет более богатый набор возможностей, чем флаги CLI. См. [Руководство разработчика]() для полного набора функций.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
