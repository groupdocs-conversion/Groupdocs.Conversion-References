---
title: "EmailFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "メールアプリケーションがメールメッセージ、添付ファイル、フォルダー、アドレス帳などのさまざまなデータを保存するために使用するメールファイル形式を定義します。以下のファイルタイプが含まれます：Eml./emailfiletype/eml、Emlx./emailfiletype/emlx、Msg./emailfiletype/msg、Vcf./emailfiletype/vcf、Mbox./emailfiletype/mbox、Pst./emailfiletype/pst、Ost./emailfiletype/ost、Olm./emailfiletype/olm。このメール形式の詳細は[こちら](https://wiki.fileformat.com/email)をご覧ください。"
type: docs
weight: 1120
url: /ja/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

メールアプリケーションがメールメッセージ、添付ファイル、フォルダー、アドレス帳などのさまざまなデータを保存するために使用するメールファイル形式を定義します。以下のファイルタイプが含まれます：[`Eml`](./eml)、[`Emlx`](./emlx)、[`Msg`](./msg)、[`Vcf`](./vcf)。[`Mbox`](./mbox)。[`Pst`](./pst)。[`Ost`](./ost)。[`Olm`](./olm)。メール形式の詳細は[こちら](https://wiki.fileformat.com/email)をご覧ください。

```csharp
public sealed class EmailFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [EmailFileType](emailfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | EML ファイル形式は、Outlook やその他の関連アプリケーションで保存されたメールメッセージを表します。ほぼすべてのメールクライアントが RFC-822 インターネットメッセージ形式標準に準拠しているため、このファイル形式をサポートしています。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/email/eml)をご覧ください。 |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | EMLX ファイル形式は Apple によって実装・開発されました。Apple Mail アプリケーションはメールのエクスポートに EMLX ファイル形式を使用します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/email/emlx)をご覧ください。 |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | ICS（iCalendar）ファイル形式は、イベント、TODO、空き時間情報などのカレンダーおよびスケジュール情報の表現と交換に使用されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/email/ics)をご覧ください。 |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox ファイル形式は、電子メールメッセージのコレクションを格納するコンテナを表す一般的な用語です。メッセージは添付ファイルとともにコンテナ内に保存されます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/email/mbox/)をご覧ください。 |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG は Microsoft Outlook および Exchange がメールメッセージ、連絡先、予定、その他のタスクを保存するために使用するファイル形式です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/email/msg)をご覧ください。 |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | .olm 拡張子のファイルは、Mac 用 Microsoft Outlook のファイルです。OLM ファイルはメールメッセージ、ジャーナル、カレンダー データ、その他のアプリケーションデータを保存します。これは Windows 用 Outlook の PST ファイルに似ていますが、Mac 用 Outlook で作成された OLM ファイルは Windows 用 Outlook では開けません。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/email/olm)をご覧ください。 |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST（オフライン ストレージ ファイル）は、Microsoft Outlook を使用して Exchange Server に登録した際に、ローカルマシン上でオフラインモードのユーザーのメールボックス データを表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/email/ost)をご覧ください。 |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | .PST 拡張子のファイルは、Outlook の個人用ストレージ ファイル（Personal Storage Table とも呼ばれる）を表し、さまざまなユーザー情報を保存します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/email/pst)をご覧ください。 |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF（Virtual Card Format）または vCard は、連絡先情報を保存するデジタルファイル形式です。この形式は、一般的な情報交換アプリケーション間でのデータ交換に広く使用されています。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/email/vcf)をご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
