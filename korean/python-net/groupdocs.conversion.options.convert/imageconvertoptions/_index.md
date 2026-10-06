---
title: "ImageConvertOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "문서를 이미지 파일 형식으로 변환하기 위한 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

문서를 이미지 파일 형식으로 변환하기 위한 옵션을 나타냅니다.

ImageConvertOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | 새 ImageConvertOptions 인스턴스를 초기화합니다. |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | 소스 형식에서 지원되는 경우 사용할 배경 색상. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | 이미지 밝기 조정. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | 이 속성은 페이지별 PDF 렌더링 해상도를 페이지의 기본 래스터 해상도로 제한하여, 삽입된 이미지보다 높은 DPI로 렌더링되는 것을 방지하고 최종 출력에서 페이지를 기본(작은) 픽셀 크기와 DPI로 출력합니다. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | 이미지에 적용되는 대비 조정. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | 변환 후 래스터 이미지의 잘라내기 영역. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | 이미지 플립 모드. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | 입력 문서를 변환할 원하는 파일 형식입니다. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | 이미지 감마 조정. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | 이미지를 그레이스케일로 변환할지 여부를 나타내는 옵션. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | 변환 후 원하는 이미지 높이. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | 변환 후 원하는 이미지 가로 해상도; 기본값은 입력 파일의 해상도 또는 96 dpi입니다. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | JPEG 전용 변환 옵션. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/)가 활성화된 경우 제한된 렌더 DPI에 적용되는 축별 하한값입니다. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | 변환을 시작할 페이지 번호입니다. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | 변환할 페이지 인덱스 목록입니다. 특정 페이지를 변환하려면 지정해야 합니다. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | `PageNumber`부터 변환할 페이지 수입니다. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | PSD 전용 변환 옵션. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | 이미지 회전 각도. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Tiff 전용 변환 옵션. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | UsePdf 속성입니다. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | 변환 후 원하는 이미지 세로 해상도. 기본 해상도는 입력 파일의 해상도 또는 96 dpi입니다. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | 워터마크 전용 옵션입니다. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | WebP 전용 변환 옵션. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | 변환 후 원하는 이미지 너비. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Guides
`ImageConvertOptions`를 사용하는 작업 가이드:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### 또 보기
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
