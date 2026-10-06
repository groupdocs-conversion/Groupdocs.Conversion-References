---
title: "WatermarkTextOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환된 문서에 텍스트 워터마크를 설정하기 위한 옵션."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/watermarktextoptions/
is_root: false
weight: 590
---


## WatermarkTextOptions class

변환된 문서에 텍스트 워터마크를 설정하기 위한 옵션.

워터마크 외관 구성을 나타냅니다. 다음 속성을 구성할 수 있습니다:

- `text`: The text to be used for the watermark.
- `font`: The font name used for the watermark text.
- `color`: The color of the watermark text.
- `top`: The top offset of the watermark.
- `left`: The left offset of the watermark.
- `width`: The width of the watermark.
- `height`: The height of the watermark.
- `background`: Whether the watermark is rendered in the background.

WatermarkTextOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/#text) | 지정된 워터마크 텍스트로 WatermarkTextOptions 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/clone/) | 현재 인스턴스를 복제합니다. (상속받음: [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 두 객체 인스턴스가 같은지 여부를 결정합니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 기본 해시 함수로 사용됩니다. ([`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)에서 상속됨) |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [color](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/color/) | 텍스트 워터마크가 적용된 경우 워터마크 글꼴 색상입니다. |
| [text](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/text/) | 워터마크 텍스트입니다. |
| [watermark_font](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/watermark_font/) | 텍스트 워터마크가 적용될 때 사용되는 워터마크 글꼴입니다. |
| [auto_align](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/auto_align/) | 워터마크는 True로 설정하면 페이지 크기에 맞게 자동으로 스케일됩니다. (inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [background](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/background/) | 워터마크는 배경으로 스탬프됩니다; True이면 하단에 배치되고, 그렇지 않으면 상단에 배치됩니다 (기본값은 False). (inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/height/) | 워터마크 높이. (inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [left](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/left/) | 워터마크 왼쪽 위치. (inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [rotation_angle](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/rotation_angle/) | 워터마크 회전 각도. (inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [top](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/top/) | 워터마크 상단 위치. (inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [transparency](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/transparency/) | 워터마크 투명도. 0과 1 사이의 값입니다. 값 0은 완전히 보이며, 값 1은 보이지 않습니다. (inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/width/) | 워터마크 너비. (inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |

### 예제

```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

with Converter("./professional-services.docx") as converter:
    watermark = WatermarkTextOptions("DRAFT")
    watermark.color = Color.from_argb(128, 211, 211, 211)  # lite gray
    watermark.top = 10
    watermark.left = 10
    watermark.width = 300
    watermark.height = 300
    watermark.background = True

    options = PdfConvertOptions()
    options.pages_count = 1
    options.watermark = watermark

    converter.convert("./professional-services.pdf", options)
```

### Guides
`WatermarkTextOptions`를 사용하는 작업 가이드:

* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)

### 또 보기
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
