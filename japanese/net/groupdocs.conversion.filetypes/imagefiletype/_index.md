---
title: "ImageFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "画像ドキュメントを定義します。以下のファイルタイプが含まれます Ai./imagefiletype/ai Avif./imagefiletype/avif Bmp./imagefiletype/bmp Cdr./imagefiletype/cdr Cmx./imagefiletype/cmx Dcm./imagefiletype/dcm Dib./imagefiletype/dib DjVu./imagefiletype/djvu Dng./imagefiletype/dng Emf./imagefiletype/emf Emz./imagefiletype/emz Gif./imagefiletype/gif Heic./imagefiletype/heic Ico./imagefiletype/ico J2c./imagefiletype/j2c J2k./imagefiletype/j2k Jls./imagefiletype/jls Jp2./imagefiletype/jp2 Jpc./imagefiletype/jpc Jfif./imagefiletype/jfif. Jpeg./imagefiletype/jpeg Jpf./imagefiletype/jpf Jpg./imagefiletype/jpg Jpm./imagefiletype/jpm Jpx./imagefiletype/jpx Odg./imagefiletype/odg Png./imagefiletype/png Psd./imagefiletype/psd Tif./imagefiletype/tif Tiff./imagefiletype/tiff Webp./imagefiletype/webp Wmf./imagefiletype/wmf. Wmz./imagefiletype/wmz. 画像フォーマットの詳細はここをご覧ください https//wiki.fileformat.com/image."
type: docs
weight: 1170
url: /ja/net/groupdocs.conversion.filetypes/imagefiletype/
---
## ImageFileType class

画像ドキュメントを定義します。以下のファイルタイプが含まれます: [`Ai`](./ai), [`Avif`](./avif), [`Bmp`](./bmp), [`Cdr`](./cdr), [`Cmx`](./cmx), [`Dcm`](./dcm), [`Dib`](./dib), [`DjVu`](./djvu), [`Dng`](./dng), [`Emf`](./emf), [`Emz`](./emz), [`Gif`](./gif), [`Heic`](./heic)[`Ico`](./ico), [`J2c`](./j2c), [`J2k`](./j2k), [`Jls`](./jls), [`Jp2`](./jp2), [`Jpc`](./jpc), [`Jfif`](./jfif). [`Jpeg`](./jpeg), [`Jpf`](./jpf), [`Jpg`](./jpg), [`Jpm`](./jpm), [`Jpx`](./jpx), [`Odg`](./odg), [`Png`](./png), [`Psd`](./psd), [`Tif`](./tif), [`Tiff`](./tiff), [`Webp`](./webp), [`Wmf`](./wmf). [`Wmz`](./wmz). 画像フォーマットの詳細は[こちら](https://wiki.fileformat.com/image)をご覧ください。

```csharp
public sealed class ImageFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [ImageFileType](imagefiletype)() | シリアライズ コンストラクタ |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイルファミリー |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |
| [IsRaster](../../groupdocs.conversion.filetypes/imagefiletype/israster) { get; } | 画像がラスタかどうかを定義します |

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
| static readonly [Ai](../../groupdocs.conversion.filetypes/imagefiletype/ai) | AI（Adobe Illustrator Artwork）は、EPS または PDF 形式の単一ページベクトルベースの図面を表します。 |
| static readonly [Avif](../../groupdocs.conversion.filetypes/imagefiletype/avif) | AVIF (AV1 Image File Format) は、AV1 で圧縮された画像を HEIF ファイル形式で保存する画像ファイル形式です。AVIF ファイルは .avif 拡張子で保存されます。AVIF のバージョン 1 は 2019 年 2 月に確定しました。HDR（ハイダイナミックレンジ）や 8、10、12 ビットの色深度、ISO/IEC CICP および ICC プロファイル、広色域など、さまざまな色空間をサポートする機能があります。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/avif/)をご覧ください。 |
| static readonly [Bmp](../../groupdocs.conversion.filetypes/imagefiletype/bmp) | BMP はビットマップ画像ファイルで、ビットマップデジタル画像を保存するために使用されます。これらの画像はグラフィックアダプタに依存せず、デバイス非依存ビットマップ（DIB）ファイル形式とも呼ばれます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/bmp)をご覧ください。 |
| static readonly [Cdr](../../groupdocs.conversion.filetypes/imagefiletype/cdr) | CDR ファイルは、CorelDRAW でネイティブに作成されるベクタードローイング画像ファイルで、デジタル画像をエンコードおよび圧縮して保存します。この描画ファイルには、テキスト、線、形状、画像、色、エフェクトが含まれ、画像内容のベクトル表現が可能です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/cdr)をご覧ください。 |
| static readonly [Cmx](../../groupdocs.conversion.filetypes/imagefiletype/cmx) | CMX 拡張子のファイルは CorelSuite アプリケーションでプレゼンテーションとして使用される Corel Exchange 画像ファイル形式です。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/cmx)で確認できます。 |
| static readonly [Dcm](../../groupdocs.conversion.filetypes/imagefiletype/dcm) | .DCM 拡張子のファイルは、MRI、CT スキャン、超音波画像など、患者の医療情報を保存するデジタル画像を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/dcm)で確認できます。 |
| static readonly [Dib](../../groupdocs.conversion.filetypes/imagefiletype/dib) | DIB（Device Independent Bitmap）ファイルは、標準のビットマップファイル（BMP）と構造が似ていますが、ヘッダーが異なるラスタ画像ファイルです。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/dib)で確認できます。 |
| static readonly [Dicom](../../groupdocs.conversion.filetypes/imagefiletype/dicom) | .DICOM 拡張子のファイルは、MRI、CT スキャン、超音波画像など、患者の医療情報を保存するデジタル画像を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/dicom)で確認できます。 |
| static readonly [DjVu](../../groupdocs.conversion.filetypes/imagefiletype/djvu) | DjVu は、テキスト、図面、画像、写真が組み合わさったスキャン文書や書籍向けに設計されたグラフィックファイル形式です。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/djvu)で確認できます。 |
| static readonly [Dng](../../groupdocs.conversion.filetypes/imagefiletype/dng) | DNG は、RAW ファイルの保存に使用されるデジタルカメラ画像形式です。2004 年 9 月に Adobe によって開発されました。基本的にデジタル写真撮影向けに開発されました。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/dng)で確認できます。 |
| static readonly [Emf](../../groupdocs.conversion.filetypes/imagefiletype/emf) | Enhanced metafile format（EMF）は、デバイスに依存しない形でグラフィック画像を保存します。EMF のメタファイルは、可変長レコードを時系列で構成しており、任意の出力デバイスで解析後に保存された画像を描画できます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/emf)で確認できます。 |
| static readonly [Emz](../../groupdocs.conversion.filetypes/imagefiletype/emz) | EMZ ファイルは実際には Microsoft の EMF ファイルを圧縮したバージョンです。これにより、オンラインでの配布が容易になります。EMF ファイルを .GZIP 圧縮アルゴリズムで圧縮すると、拡張子が .emz になります。 |
| static readonly [Fodg](../../groupdocs.conversion.filetypes/imagefiletype/fodg) | FODG は、OpenDocument のテキストデータを保存するために使用される非圧縮 XML 形式のファイルです。FODG 拡張子は、オープンソースのオフィススイートである Libre Office と OpenOffice.org に関連付けられています。 |
| static readonly [Gif](../../groupdocs.conversion.filetypes/imagefiletype/gif) | GIF（Graphical Interchange Format）は、高度に圧縮された画像形式です。GIF の各画像は通常、ピクセルあたり最大 8 ビット、全体で最大 256 色を使用できます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/gif)で確認できます。 |
| static readonly [Heic](../../groupdocs.conversion.filetypes/imagefiletype/heic) | HEIC ファイルは、単一ファイル内に複数の画像をコレクションとして保存できる High‑Efficiency Container Image 形式です。この形式は iOS 11 のリリース時に Apple によって HEIF のバリアントとして採用されました。このファイル形式の詳細は[here](https://docs.fileformat.com/image/heic/)で確認できます。 |
| static readonly [Ico](../../groupdocs.conversion.filetypes/imagefiletype/ico) | ICO 拡張子のファイルは、Microsoft Windows 上でアプリケーションを表すアイコンとして使用される画像ファイルタイプです。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/ico)で確認できます。 |
| static readonly [J2c](../../groupdocs.conversion.filetypes/imagefiletype/j2c) | J2c ドキュメント形式 |
| static readonly [J2k](../../groupdocs.conversion.filetypes/imagefiletype/j2k) | J2K ファイルは、DCT 圧縮ではなくウェーブレット圧縮を使用して圧縮された画像です。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/j2k)で確認できます。 |
| static readonly [Jfif](../../groupdocs.conversion.filetypes/imagefiletype/jfif) | JFIF（JPEG File Interchange Format）は、.jfif 拡張子を使用する画像形式ファイルです。JFIF は JIF（JPEG Interchange Format）をベースに、複雑さを減らし制限を解消しています。このファイル形式の詳細は[here](https://docs.fileformat.com/image/jfif/)で確認できます。 |
| static readonly [Jls](../../groupdocs.conversion.filetypes/imagefiletype/jls) | Jls ドキュメント形式 |
| static readonly [Jp2](../../groupdocs.conversion.filetypes/imagefiletype/jp2) | JPEG 2000（JP2）は、画像符号化システムおよび最先端の画像圧縮規格です。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jp2)で確認できます。 |
| static readonly [Jpc](../../groupdocs.conversion.filetypes/imagefiletype/jpc) | Jpc ドキュメント形式 |
| static readonly [Jpeg](../../groupdocs.conversion.filetypes/imagefiletype/jpeg) | JPEG は、非可逆圧縮方式で保存される画像形式です。圧縮の結果として得られる出力画像は、保存サイズと画質のトレードオフとなります。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jpeg)で確認できます。 |
| static readonly [Jpf](../../groupdocs.conversion.filetypes/imagefiletype/jpf) | Jpf ドキュメント形式 |
| static readonly [Jpg](../../groupdocs.conversion.filetypes/imagefiletype/jpg) | JPG は、非可逆圧縮方式で保存される画像形式です。圧縮の結果として得られる出力画像は、保存サイズと画質のトレードオフとなります。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jpeg)で確認できます。 |
| static readonly [Jpm](../../groupdocs.conversion.filetypes/imagefiletype/jpm) | Jpm ドキュメント形式 |
| static readonly [Jpx](../../groupdocs.conversion.filetypes/imagefiletype/jpx) | Jpx ドキュメント形式 |
| static readonly [Odg](../../groupdocs.conversion.filetypes/imagefiletype/odg) | ODG ファイル形式は、Apache OpenOffice の Draw アプリケーションで描画要素をベクター画像として保存するために使用されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/odg)で確認できます。 |
| static readonly [Otg](../../groupdocs.conversion.filetypes/imagefiletype/otg) | OTG ファイルは、OASIS Office Applications 1.0 仕様に準拠した OpenDocument 標準を使用して作成される描画テンプレートです。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/otg)で確認できます。 |
| static readonly [Png](../../groupdocs.conversion.filetypes/imagefiletype/png) | PNG、Portable Network Graphics は、ロスレス圧縮を使用するラスタ画像ファイル形式の一種です。このファイル形式は、Graphics Interchange Format (GIF) の代替として作成され、著作権制限がありません。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/png)をご覧ください。 |
| static readonly [Psb](../../groupdocs.conversion.filetypes/imagefiletype/psb) | Adobe Photoshop はファイルを2つの形式で保存します。サイズが30,000×30,000ピクセルのファイルは PSD 拡張子で保存され、300,000×300,000ピクセルまでの大きなファイルは PSB 拡張子で保存されます。PSB は「Photoshop Big」として知られています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/psb)をご覧ください。 |
| static readonly [Psd](../../groupdocs.conversion.filetypes/imagefiletype/psd) | PSD、Photoshop Document は、Adobe Photoshop のネイティブファイル形式で、グラフィックの設計や開発に使用されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/psd)をご覧ください。 |
| static readonly [Tga](../../groupdocs.conversion.filetypes/imagefiletype/tga) | .tga 拡張子のファイルはラスタ画像形式で、Truevision Inc. によって作成されました。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/tga)をご覧ください。 |
| static readonly [Tif](../../groupdocs.conversion.filetypes/imagefiletype/tif) | TIF、Tagged Image File Format は、さまざまなデバイスで使用できるラスタ画像を表し、このファイル形式標準に準拠しています。二値、グレースケール、パレットカラー、フルカラーの画像データを複数の色空間で記述できます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/tiff)をご覧ください。 |
| static readonly [Tiff](../../groupdocs.conversion.filetypes/imagefiletype/tiff) | TIFF、Tagged Image File Format は、さまざまなデバイスで使用できるラスタ画像を表し、このファイル形式標準に準拠しています。二値、グレースケール、パレットカラー、フルカラーの画像データを複数の色空間で記述できます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/tiff)をご覧ください。 |
| static readonly [Webp](../../groupdocs.conversion.filetypes/imagefiletype/webp) | WebP は Google によって導入された、ロスレスおよびロッシー圧縮に基づく最新のラスタウェブ画像ファイル形式です。画像品質を保ちつつ、画像サイズを大幅に削減します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/webp)をご覧ください。 |
| static readonly [Wmf](../../groupdocs.conversion.filetypes/imagefiletype/wmf) | WMF 拡張子のファイルは Microsoft Windows Metafile (WMF) を表し、ベクターおよびビットマップ形式の画像データを格納します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/wmf)をご覧ください。 |
| static readonly [Wmz](../../groupdocs.conversion.filetypes/imagefiletype/wmz) | WMZ ファイルは実際には Microsoft WMF ファイルの圧縮版です。これにより、オンラインでの配布が容易になります。EWMFMF ファイルが .GZIP 圧縮アルゴリズムで圧縮されると、.wmz 拡張子が付与されます。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
