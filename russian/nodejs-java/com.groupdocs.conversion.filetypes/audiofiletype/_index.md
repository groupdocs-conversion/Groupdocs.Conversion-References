---
title: "AudioFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет аудиодокументы. Включает следующие типы. Узнайте больше о аудиоформатах здесь."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

Определяет аудиодокументы. Включает следующие типы: , , , , , , , , , Узнайте больше о аудиоформатах [here][].


[here]: https://docs.fileformat.com/audio/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AudioFileType()](#AudioFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Mp3](#Mp3) | Файлы с расширением .mp3 — это цифрово закодированные форматы файлов аудио, официально основанные на MPEG-1 Audio Layer III или MPEG-2 Audio Layer III. |
| [Aac](#Aac) | AAC (Advanced Audio Coding) — это стандарт цифрового аудиокодирования, представляющий аудиофайлы на основе сжатия с потерями. |
|  | [Aiff](#Aiff) | AIFF (Audio Interchange File Format) — это несжатый аудиоформат, разработанный Apple в 1998 году, но основанный на EA IFF 85. Узнайте больше об этом формате файла [here][]. |


[here]: https://docs.fileformat.com/audio/aiff/ |
|  | [Flac](#Flac) | FLAC (Free Lossless Audio Codec) — это формат аудиокодирования с безпотерянным сжатием, разработанный Xiph.Org Foundation. Узнайте больше об этом формате файла [here][]. |


[here]: https://docs.fileformat.com/audio/flac/ |
| [M4a](#M4a) | Формат файла M4A — это аудиофайл, созданный с использованием AAC (Advanced Audio Coding), известного как сжатие с потерями. |
| [Wma](#Wma) | Файл с расширением .wma представляет собой аудиофайл, сохранённый в формате Advanced Systems Format (ASF). |
| [Ac3](#Ac3) | Файл с расширением .ac3 — это файл Audio Codec 3, представленный компанией Dolby Laboratories. |
| [Ogg](#Ogg) | OGG — это сжатый аудиофайл Ogg Vorbis, сохраняемый с расширением .ogg. |
| [Wav](#Wav) | WAV, известный как WAVE (Waveform Audio File Format), является подмножеством спецификации Resource Interchange File Format (RIFF) компании Microsoft\\u2019s для хранения цифровых аудиофайлов. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


Конструктор сериализации

### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


Файлы с расширением .mp3 — это цифрово закодированные форматы файлов аудио, официально основанные на MPEG-1 Audio Layer III или MPEG-2 Audio Layer III. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/audio/mp3/

### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) — это стандарт цифрового аудиокодирования, представляющий аудиофайлы на основе сжатия с потерями. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/audio/aac/

### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


AIFF (Audio Interchange File Format) — это несжатый аудиоформат, разработанный Apple в 1998 году, но основанный на EA IFF 85. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/audio/aiff/

### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC (Free Lossless Audio Codec) — это формат аудиокодирования с безпотерянным сжатием, разработанный Xiph.Org Foundation. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/audio/flac/

### M4a {#M4a}
```
public static final AudioFileType M4a
```


Формат файла M4A — это аудиофайл, созданный с использованием AAC (Advanced Audio Coding), известного как сжатие с потерями. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/audio/m4a/

### Wma {#Wma}
```
public static final AudioFileType Wma
```


Файл с расширением .wma представляет собой аудиофайл, сохранённый в формате Advanced Systems Format (ASF). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/audio/wma/

### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


Файл с расширением .ac3 — это файл Audio Codec 3, представленный компанией Dolby Laboratories. Это аудиоформат, который может содержать до шести каналов звука. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/audio/ac3/

### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG — это сжатый аудиофайл Ogg Vorbis, сохраняемый с расширением .ogg. Файлы OGG используются для хранения аудиоданных и могут включать информацию об исполнителе, треке и метаданные. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/audio/ogg/

### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, известный как WAVE (Waveform Audio File Format), является подмножеством спецификации Resource Interchange File Format (RIFF) компании Microsoft\\u2019s для хранения цифровых аудиофайлов. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/audio/ogg/

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
