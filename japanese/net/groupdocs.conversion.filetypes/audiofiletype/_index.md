---
title: "AudioFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "オーディオドキュメントを定義します。以下のタイプが含まれます Mp3./audiofiletype/mp3 Aac./audiofiletype/aac Aiff./audiofiletype/aiff Flac./audiofiletype/flac M4a./audiofiletype/m4a Wma./audiofiletype/wma Ac3./audiofiletype/ac3 Ogg./audiofiletype/ogg Wav./audiofiletype/wav オーディオ形式の詳細は herehttps//docs.fileformat.com/audio/ をご覧ください。"
type: docs
weight: 1060
url: /ja/net/groupdocs.conversion.filetypes/audiofiletype/
---
## AudioFileType class

オーディオドキュメントを定義します。以下のタイプが含まれます: [`Mp3`](./mp3)、[`Aac`](./aac)、[`Aiff`](./aiff)、[`Flac`](./flac)、[`M4a`](./m4a)、[`Wma`](./wma)、[`Ac3`](./ac3)、[`Ogg`](./ogg)、[`Wav`](./wav)。オーディオ形式の詳細は[こちら](https://docs.fileformat.com/audio/)をご覧ください。

```csharp
public sealed class AudioFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [AudioFileType](audiofiletype)() | シリアライズ コンストラクタ |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイルファミリー |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他と比較します。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) を実装します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 文字列表現 |

## Fields

| 名前 | 説明 |
| --- | --- |
| static readonly [Aac](../../groupdocs.conversion.filetypes/audiofiletype/aac) | AAC（Advanced Audio Coding）は、非可逆圧縮に基づくオーディオファイルを表すデジタルオーディオ符号化標準です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/aac/)をご覧ください。 |
| static readonly [Ac3](../../groupdocs.conversion.filetypes/audiofiletype/ac3) | .ac3 拡張子のファイルは Dolby Laboratories が導入した Audio Codec 3 ファイルです。最大6チャンネルのオーディオ出力を含むことができるオーディオ形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/ac3/)をご覧ください。 |
| static readonly [Aiff](../../groupdocs.conversion.filetypes/audiofiletype/aiff) | AIFF（Audio Interchange File Format）は、Apple が1998年に開発した非圧縮オーディオファイル形式で、EA IFF 85 に基づいています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/aiff/)をご覧ください。 |
| static readonly [Flac](../../groupdocs.conversion.filetypes/audiofiletype/flac) | FLAC（Free Lossless Audio Codec）は、Xiph.Org Foundation が開発したロスレス圧縮オーディオ符号化形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/flac/)をご覧ください。 |
| static readonly [M4a](../../groupdocs.conversion.filetypes/audiofiletype/m4a) | M4A ファイル形式は、非可逆圧縮として知られる AAC（Advanced Audio Coding）を使用して作成されたオーディオファイルです。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/m4a/)をご覧ください。 |
| static readonly [Mp3](../../groupdocs.conversion.filetypes/audiofiletype/mp3) | .mp3 拡張子のファイルは、MPEG-1 Audio Layer III または MPEG-2 Audio Layer III に正式に基づくデジタルエンコードされたオーディオファイル形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/mp3/)をご覧ください。 |
| static readonly [Ogg](../../groupdocs.conversion.filetypes/audiofiletype/ogg) | OGG は .ogg 拡張子で保存される Ogg Vorbis 圧縮オーディオファイルです。OGG ファイルはオーディオデータの保存に使用され、アーティストやトラック情報、メタデータも含めることができます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/ogg/)をご覧ください。 |
| static readonly [Wav](../../groupdocs.conversion.filetypes/audiofiletype/wav) | WAV（WAVE：Waveform Audio File Format）は、デジタルオーディオファイルの保存用に Microsoft の Resource Interchange File Format（RIFF）仕様のサブセットです。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/ogg/)をご覧ください。 |
| static readonly [Wma](../../groupdocs.conversion.filetypes/audiofiletype/wma) | .wma 拡張子のファイルは、Advanced Systems Format（ASF）形式で保存されたオーディオファイルを表します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/wma/)をご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
