---
title: "ILogger"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ロギングを実行するために使用されるメソッドを定義します。"
type: docs
weight: 1700
url: /ja/net/groupdocs.conversion.logging/ilogger/
---
## ILogger interface

ロギングを実行するために使用されるメソッドを定義します。

```csharp
public interface ILogger
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Error](../../groupdocs.conversion.logging/ilogger/error)(string, Exception) | エラーログメッセージを書き込みます；エラーログメッセージは、アプリケーションフローでの回復不能なイベントに関する情報を提供します。 |
| [Trace](../../groupdocs.conversion.logging/ilogger/trace)(string) | トレースログメッセージを書き込みます；トレースログメッセージは、アプリケーションフローに関する一般的に有用な情報を提供します。 |
| [Warning](../../groupdocs.conversion.logging/ilogger/warning)(string) | 警告ログメッセージを書き込みます；警告ログメッセージは、アプリケーションフローでの予期せぬ回復可能なイベントに関する情報を提供します。 |

### 関連項目

* namespace [GroupDocs.Conversion.Logging](../../groupdocs.conversion.logging)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
