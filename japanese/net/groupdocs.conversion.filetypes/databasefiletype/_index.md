---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "データベース文書を定義します。以下のファイルタイプが含まれます Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql"
type: docs
weight: 1090
url: /ja/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

データベース文書を定義します。以下のファイルタイプ: [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | 拡張子 .log のファイルはタイムスタンプ付きのプレーンテキストのリストを含みます。通常、ソフトウェアや OS が特定のアクティビティの詳細を記録し、開発者やユーザーが特定の期間に何が起きたかを追跡できるようにします。このファイル形式の詳細は[こちら](https://docs.fileformat.com/database/log)で確認できます。 |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | 拡張子 .nsf（Notes Storage Facility）のファイルは、IBM Notes（旧 Lotus Notes）で使用されるデータベース形式です。メール、予定、ドキュメント、フォーム、ビューなどさまざまなオブジェクトを格納するスキーマを定義します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/database/nsf)で確認できます。 |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | 拡張子 .sql のファイルは Structured Query Language（SQL）ファイルで、リレーショナルデータベースを操作するコードが含まれます。データベースに対する CRUD（作成、読み取り、更新、削除）操作のための SQL 文を書く際に使用されます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/database/sql)で確認できます。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
