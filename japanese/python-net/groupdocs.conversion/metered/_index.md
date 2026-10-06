---
title: "Metered クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "従量課金（使用量に応じた支払い）ライセンスを管理します。"
type: docs
url: /ja/python-net/groupdocs.conversion/metered/
is_root: false
weight: 210
---


## Metered class

従量課金（使用量に応じた支払い）ライセンスを管理します。

Metered ライセンスは実際の使用量に基づいて課金されます（通常はページまたは
処理されたドキュメント）。公開/非公開キーのペアは一度だけ設定してください
アプリケーションの起動時に；ラッパーは使用状況を GroupDocs に報告します
バックグラウンドでライセンスサーバーへ送信します。

Metered 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [get_consumption_credit](/conversion/python-net/groupdocs.conversion/metered/get_consumption_credit/) | 現在のキーに対する残りのメータクレジットを返します。 |
| [get_consumption_quantity](/conversion/python-net/groupdocs.conversion/metered/get_consumption_quantity/) | これまでに消費された合計メータ量を返します。 |
| [set_metered_key](/conversion/python-net/groupdocs.conversion/metered/set_metered_key/#public_key-private_key) | 指定された公開/非公開キーのペアでメータ課金を有効化します。 |

### 関連項目
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
