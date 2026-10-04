---
title: "ImageFileType"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "이미지 문서를 정의합니다. 다음 파일 형식을 포함합니다 Ai./imagefiletype/ai Avif./imagefiletype/avif Bmp./imagefiletype/bmp Cdr./imagefiletype/cdr Cmx./imagefiletype/cmx Dcm./imagefiletype/dcm Dib./imagefiletype/dib DjVu./imagefiletype/djvu Dng./imagefiletype/dng Emf./imagefiletype/emf Emz./imagefiletype/emz Gif./imagefiletype/gif Heic./imagefiletype/heicIco./imagefiletype/ico J2c./imagefiletype/j2c J2k./imagefiletype/j2k Jls./imagefiletype/jls Jp2./imagefiletype/jp2 Jpc./imagefiletype/jpc Jfif./imagefiletype/jfif. Jpeg./imagefiletype/jpeg Jpf./imagefiletype/jpf Jpg./imagefiletype/jpg Jpm./imagefiletype/jpm Jpx./imagefiletype/jpx Odg./imagefiletype/odg Png./imagefiletype/png Psd./imagefiletype/psd Tif./imagefiletype/tif Tiff./imagefiletype/tiff Webp./imagefiletype/webp Wmf./imagefiletype/wmf. Wmz./imagefiletype/wmz. 이미지 형식에 대해 자세히 알아보려면 herehttps//wiki.fileformat.com/image."
type: docs
weight: 1170
url: /ko/net/groupdocs.conversion.filetypes/imagefiletype/
---
## ImageFileType class

이미지 문서를 정의합니다. 다음 파일 형식을 포함합니다: [`Ai`](./ai), [`Avif`](./avif), [`Bmp`](./bmp), [`Cdr`](./cdr), [`Cmx`](./cmx), [`Dcm`](./dcm), [`Dib`](./dib), [`DjVu`](./djvu), [`Dng`](./dng), [`Emf`](./emf), [`Emz`](./emz), [`Gif`](./gif), [`Heic`](./heic)[`Ico`](./ico), [`J2c`](./j2c), [`J2k`](./j2k), [`Jls`](./jls), [`Jp2`](./jp2), [`Jpc`](./jpc), [`Jfif`](./jfif). [`Jpeg`](./jpeg), [`Jpf`](./jpf), [`Jpg`](./jpg), [`Jpm`](./jpm), [`Jpx`](./jpx), [`Odg`](./odg), [`Png`](./png), [`Psd`](./psd), [`Tif`](./tif), [`Tiff`](./tiff), [`Webp`](./webp), [`Wmf`](./wmf). [`Wmz`](./wmz). 이미지 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image).

```csharp
public sealed class ImageFileType : FileType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageFileType](imagefiletype)() | 직렬화 생성자 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 파일 유형 설명 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 파일 확장자 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 파일 패밀리 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 파일 형식 |
| [IsRaster](../../groupdocs.conversion.filetypes/imagefiletype/israster) { get; } | 이미지가 래스터인지 정의합니다 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 현재 객체를 다른 객체와 비교합니다. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | `[`Equals`](../../groupdocs.conversion.contracts/enumeration/equals)`를 구현합니다. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 기본 해시 함수로 사용됩니다. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 문자열 표현 |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Ai](../../groupdocs.conversion.filetypes/imagefiletype/ai) | AI(Adobe Illustrator Artwork)는 EPS 또는 PDF 형식 중 하나로 단일 페이지 벡터 기반 그림을 나타냅니다. |
| static readonly [Avif](../../groupdocs.conversion.filetypes/imagefiletype/avif) | AVIF(AV1 Image File Format)는 AV1로 압축된 이미지를 HEIF 파일 형식으로 저장하는 이미지 파일 형식입니다. AVIF 파일은 .avif 확장자를 사용합니다. AVIF 버전 1은 2019년 2월에 최종 확정되었습니다. 고동적 범위(HDR), 8, 10, 12 비트 색 깊이 지원, 모든 색 공간 지원(ISO/IEC CICP 및 ICC 프로파일, 와이드 컬러 gamut) 등 다양한 기능을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/image/avif/). |
| static readonly [Bmp](../../groupdocs.conversion.filetypes/imagefiletype/bmp) | BMP는 비트맵 디지털 이미지를 저장하는 Bitmap Image 파일을 나타냅니다. 이러한 이미지는 그래픽 어댑터와 무관하며 디바이스 독립 비트맵(DIB) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/bmp). |
| static readonly [Cdr](../../groupdocs.conversion.filetypes/imagefiletype/cdr) | CDR 파일은 CorelDRAW에서 기본적으로 생성되는 벡터 드로잉 이미지 파일로, 디지털 이미지를 인코딩하고 압축하여 저장합니다. 이러한 드로잉 파일에는 텍스트, 선, 도형, 이미지, 색상 및 효과가 포함되어 이미지 내용을 벡터 형태로 표현합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/cdr). |
| static readonly [Cmx](../../groupdocs.conversion.filetypes/imagefiletype/cmx) | CMX 확장자를 가진 파일은 CorelSuite 애플리케이션에서 프레젠테이션용으로 사용되는 Corel Exchange 이미지 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/cmx)를 방문하세요. |
| static readonly [Dcm](../../groupdocs.conversion.filetypes/imagefiletype/dcm) | .DCM 확장자를 가진 파일은 MRI, CT 스캔 및 초음파 이미지와 같은 환자의 의료 정보를 저장하는 디지털 이미지입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/dcm)를 클릭하세요. |
| static readonly [Dib](../../groupdocs.conversion.filetypes/imagefiletype/dib) | DIB(Device Independent Bitmap) 파일은 표준 비트맵 파일(BMP)과 구조가 유사하지만 헤더가 다른 래스터 이미지 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/dib)를 방문하세요. |
| static readonly [Dicom](../../groupdocs.conversion.filetypes/imagefiletype/dicom) | .DICOM 확장자를 가진 파일은 MRI, CT 스캔 및 초음파 이미지와 같은 환자의 의료 정보를 저장하는 디지털 이미지입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/dicom)를 클릭하세요. |
| static readonly [DjVu](../../groupdocs.conversion.filetypes/imagefiletype/djvu) | DjVu는 텍스트, 그림, 이미지 및 사진이 결합된 스캔 문서와 책을 위해 설계된 그래픽 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/djvu)를 방문하세요. |
| static readonly [Dng](../../groupdocs.conversion.filetypes/imagefiletype/dng) | DNG는 RAW 파일 저장을 위해 사용되는 디지털 카메라 이미지 형식이며, 2004년 9월 Adobe에 의해 개발되었습니다. 기본적으로 디지털 사진 촬영을 위해 만들어졌습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/dng)를 클릭하세요. |
| static readonly [Emf](../../groupdocs.conversion.filetypes/imagefiletype/emf) | Enhanced metafile format(EMF)은 장치에 독립적으로 그래픽 이미지를 저장합니다. EMF 메타파일은 순차적인 가변 길이 레코드로 구성되어 있어, 어떤 출력 장치에서도 파싱 후 저장된 이미지를 렌더링할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/emf)를 방문하세요. |
| static readonly [Emz](../../groupdocs.conversion.filetypes/imagefiletype/emz) | EMZ 파일은 실제로 Microsoft EMF 파일을 압축한 버전이며, 이를 통해 파일을 온라인에서 더 쉽게 배포할 수 있습니다. EMF 파일을 .GZIP 압축 알고리즘으로 압축하면 .emz 파일 확장자가 부여됩니다. |
| static readonly [Fodg](../../groupdocs.conversion.filetypes/imagefiletype/fodg) | FODG는 OpenDocument 텍스트 데이터를 저장하기 위해 사용되는 비압축 XML 형식 파일이며, LibreOffice와 OpenOffice.org와 같은 오픈 소스 오피스 생산성 제품군과 연관된 확장자입니다. |
| static readonly [Gif](../../groupdocs.conversion.filetypes/imagefiletype/gif) | GIF(그래픽 인터체인지 포맷)는 고도로 압축된 이미지 형식으로, 일반적으로 픽셀당 최대 8비트, 전체 이미지에 최대 256색을 허용합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/gif)를 클릭하세요. |
| static readonly [Heic](../../groupdocs.conversion.filetypes/imagefiletype/heic) | HEIC 파일은 하나의 파일에 여러 이미지를 컬렉션으로 저장할 수 있는 고효율 컨테이너 이미지 형식이며, iOS 11 출시와 함께 Apple이 HEIF의 변형으로 채택했습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/image/heic/)를 방문하세요. |
| static readonly [Ico](../../groupdocs.conversion.filetypes/imagefiletype/ico) | ICO 확장자를 가진 파일은 Microsoft Windows에서 애플리케이션을 나타내는 아이콘으로 사용되는 이미지 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/ico)를 클릭하세요. |
| static readonly [J2c](../../groupdocs.conversion.filetypes/imagefiletype/j2c) | J2c 문서 형식 |
| static readonly [J2k](../../groupdocs.conversion.filetypes/imagefiletype/j2k) | J2K 파일은 DCT 압축이 아닌 웨이브렛 압축을 사용하여 압축된 이미지이며, 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/j2k)를 클릭하세요. |
| static readonly [Jfif](../../groupdocs.conversion.filetypes/imagefiletype/jfif) | JFIF(JPEG File Interchange Format)는 .jfif 확장자를 사용하는 이미지 형식 파일이며, JIF(JPEG Interchange Format)의 복잡성을 줄이고 제한점을 해결한 형태입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/image/jfif/)를 방문하세요. |
| static readonly [Jls](../../groupdocs.conversion.filetypes/imagefiletype/jls) | Jls 문서 형식 |
| static readonly [Jp2](../../groupdocs.conversion.filetypes/imagefiletype/jp2) | JPEG 2000(JP2)은 최신 이미지 코딩 시스템이자 이미지 압축 표준입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/jp2)를 클릭하세요. |
| static readonly [Jpc](../../groupdocs.conversion.filetypes/imagefiletype/jpc) | Jpc 문서 형식 |
| static readonly [Jpeg](../../groupdocs.conversion.filetypes/imagefiletype/jpeg) | JPEG은 손실 압축 방식을 사용하여 저장되는 이미지 형식이며, 압축 결과물은 저장 용량과 이미지 품질 사이의 균형을 이룹니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/jpeg)를 클릭하세요. |
| static readonly [Jpf](../../groupdocs.conversion.filetypes/imagefiletype/jpf) | Jpf 문서 형식 |
| static readonly [Jpg](../../groupdocs.conversion.filetypes/imagefiletype/jpg) | JPG는 손실 압축 방식을 사용하여 저장되는 이미지 형식이며, 압축 결과물은 저장 용량과 이미지 품질 사이의 균형을 이룹니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/jpeg)를 클릭하세요. |
| static readonly [Jpm](../../groupdocs.conversion.filetypes/imagefiletype/jpm) | Jpm 문서 형식 |
| static readonly [Jpx](../../groupdocs.conversion.filetypes/imagefiletype/jpx) | Jpx 문서 형식 |
| static readonly [Odg](../../groupdocs.conversion.filetypes/imagefiletype/odg) | ODG 파일 형식은 Apache OpenOffice의 Draw 애플리케이션에서 벡터 이미지로 그림 요소를 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/odg)를 클릭하세요. |
| static readonly [Otg](../../groupdocs.conversion.filetypes/imagefiletype/otg) | OTG 파일은 OASIS Office Applications 1.0 사양을 따르는 OpenDocument 표준을 사용해 만든 그림 템플릿입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/otg)를 클릭하세요. |
| static readonly [Png](../../groupdocs.conversion.filetypes/imagefiletype/png) | PNG, Portable Network Graphics는 무손실 압축을 사용하는 래스터 이미지 파일 형식의 일종을 의미합니다. 이 파일 형식은 Graphics Interchange Format(GIF)을 대체하기 위해 만들어졌으며 저작권 제한이 없습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/png). |
| static readonly [Psb](../../groupdocs.conversion.filetypes/imagefiletype/psb) | Adobe Photoshop은 파일을 두 가지 형식으로 저장합니다. 30,000 × 30,000 픽셀 크기의 파일은 PSD 확장자로 저장되고, PSD보다 큰 300,000 × 300,000 픽셀까지의 파일은 “Photoshop Big”이라고 알려진 PSB 확장자로 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/image/psb). |
| static readonly [Psd](../../groupdocs.conversion.filetypes/imagefiletype/psd) | PSD, Photoshop Document는 그래픽 디자인 및 개발에 사용되는 Adobe Photoshop의 고유 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/psd). |
| static readonly [Tga](../../groupdocs.conversion.filetypes/imagefiletype/tga) | .tga 확장자를 가진 파일은 래스터 그래픽 형식이며 Truevision Inc.에서 만들었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/image/tga). |
| static readonly [Tif](../../groupdocs.conversion.filetypes/imagefiletype/tif) | TIF, Tagged Image File Format은 다양한 장치에서 사용하도록 설계된 래스터 이미지를 나타냅니다. 이 형식은 이진, 그레이스케일, 팔레트 색상 및 풀 컬러 이미지 데이터를 여러 색 공간에서 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/tiff). |
| static readonly [Tiff](../../groupdocs.conversion.filetypes/imagefiletype/tiff) | TIFF, Tagged Image File Format은 다양한 장치에서 사용하도록 설계된 래스터 이미지를 나타냅니다. 이 형식은 이진, 그레이스케일, 팔레트 색상 및 풀 컬러 이미지 데이터를 여러 색 공간에서 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/tiff). |
| static readonly [Webp](../../groupdocs.conversion.filetypes/imagefiletype/webp) | WebP는 Google이 도입한 현대적인 래스터 웹 이미지 파일 형식으로, 무손실 및 손실 압축을 기반으로 합니다. 동일한 이미지 품질을 유지하면서 이미지 크기를 크게 줄여줍니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/webp). |
| static readonly [Wmf](../../groupdocs.conversion.filetypes/imagefiletype/wmf) | WMF 확장자를 가진 파일은 벡터와 비트맵 형식 이미지 데이터를 저장하기 위한 Microsoft Windows Metafile(WMF)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/wmf). |
| static readonly [Wmz](../../groupdocs.conversion.filetypes/imagefiletype/wmz) | WMZ 파일은 실제로 Microsoft WMF 파일의 압축 버전입니다. 이는 파일을 온라인에서 더 쉽게 배포할 수 있게 합니다. EWMFMF 파일을 .GZIP 압축 알고리즘으로 압축하면 .wmz 파일 확장자가 부여됩니다. |

### 또 보기

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
