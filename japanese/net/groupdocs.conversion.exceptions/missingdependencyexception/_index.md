---
title: "MissingDependencyException"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "GroupDocs の例外で、依存しているアセンブリがアプリケーションの出力に存在しないために変換を実行できない場合にスローされます。ドキュメント自体に問題はありません。"
type: docs
weight: 1030
url: /ja/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

変換が実行できないのは、依存しているアセンブリがアプリケーションの出力に存在しないためであり、ドキュメントに問題はありません。この場合にスローされるGroupDocs例外

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | デフォルトコンストラクタ |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | メッセージを指定して例外インスタンスを作成します |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | メッセージを指定して例外インスタンスを作成し、内部例外を伝播させます |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | ロードできなかったアセンブリの名前を指定して例外インスタンスを作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | ロードできなかったアセンブリの単純名、または特定できなかった場合は null |

### 関連項目

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
