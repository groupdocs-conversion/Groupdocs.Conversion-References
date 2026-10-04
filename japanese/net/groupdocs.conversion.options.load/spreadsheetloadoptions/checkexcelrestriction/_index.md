---
title: "CheckExcelRestriction"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ユーザーがセル関連オブジェクトを変更する際に、Excel ファイルの制限をチェックするかどうかを指定します。たとえば、Excel は 32KB を超える文字列の入力を許可しません。このプロパティが true の場合、32KB を超える値を入力すると例外がスローされます。false の場合、入力した文字列をセルの値として受け入れ、後で CSV などの他のファイル形式に完全な文字列を出力できます。ただし、Excel ファイル形式として無効な値を設定した場合、後で Excel ファイル形式でブックを保存すべきではありません。そうしないと、生成された Excel ファイルで予期しないエラーが発生する可能性があります。"
type: docs
weight: 40
url: /ja/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

ユーザーがセル関連オブジェクトを変更したときに Excel ファイルの制限をチェックするかどうかを指定します。たとえば、Excel は 32K を超える文字列の入力を許可しません。32K を超える値を入力した場合、このプロパティが true であれば例外がスローされます。false の場合、入力した文字列をセルの値として受け入れ、後で CSV など他のファイル形式に完全な文字列を出力できるようにします。ただし、Excel ファイル形式として無効な値を設定した場合、後でブックを Excel 形式で保存すべきではありません。そうしないと、生成された Excel ファイルで予期しないエラーが発生する可能性があります。

```csharp
public bool CheckExcelRestriction { get; set; }
```

### 関連項目

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
