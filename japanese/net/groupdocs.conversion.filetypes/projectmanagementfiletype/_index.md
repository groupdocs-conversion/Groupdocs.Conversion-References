---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Microsoft Project、Primavera P6 などのプロジェクト管理ソフトウェアで作成されるプロジェクトファイル形式を定義します。プロジェクトファイルは、タスク、リソース、およびスケジュールの集合で、製品やサービスという形で測定可能な成果を得るためのものです。プロジェクト管理ドキュメント。以下のファイルタイプが含まれます Mpp./projectmanagementfiletype/mpp Mpt./projectmanagementfiletype/mpt Mpx./projectmanagementfiletype/mpx. プロジェクト管理形式の詳細はここをご覧くださいhttps//wiki.fileformat.com/projectmanagement."
type: docs
weight: 1220
url: /ja/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Microsoft Project、Primavera P6 などのプロジェクト管理ソフトウェアで作成されるプロジェクトファイル形式を定義します。プロジェクトファイルは、タスク、リソース、およびスケジュールの集合で、製品やサービスという形で測定可能な成果を得るためのものです。プロジェクト管理ドキュメント。以下のファイルタイプが含まれます: [`Mpp`](./mpp), [`Mpt`](./mpt), [`Mpx`](./mpx). プロジェクト管理形式の詳細は[こちら](https://wiki.fileformat.com/project-management)をご覧ください。

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | シリアライズ コンストラクタ |

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
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP は、Microsoft Project のデータファイルで、プロジェクト管理に関する情報を統合的に保存します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/project-management/mpp)をご覧ください。 |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | Microsoft Project のテンプレートファイルは、.MPP ファイル作成のための基本情報と構造、ドキュメント設定を含みます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/project-management/mpt)をご覧ください。 |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange File Format は、Microsoft Project（MSP）と、Primavera Project Planner、Sciforma、Timerline Precision Estimating など MPX ファイル形式をサポートする他のアプリケーション間でプロジェクト情報を転送するための ASCII ファイル形式です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/project-management/mpx)をご覧ください。 |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | XER ファイル形式は、Primavera P6 のプロジェクト計画・管理アプリケーションで使用される独自のプロジェクトファイル形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/project-management/xer)をご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
