---
title: "명령줄 인터페이스"
linkTitle: "Command Line Interface"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "groupdocs-conversion 명령줄 도구를 사용해 터미널에서 직접 문서를 변환합니다 — Python 스크립트가 필요 없습니다. 문서를 검사하고, 지원되는 형식 목록을 확인하며, 라이선스를 적용하는 모든 작업을 셸에서 수행할 수 있습니다."
type: docs
url: /ko/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


`groupdocs-conversion-net` 패키지를 설치하면 `groupdocs-conversion` 콘솔 스크립트가 `PATH`에 추가됩니다. 이는 Python API 위에 얇게 감싼 래퍼로, Python 스크립트를 실행하기엔 과도한 경우—쉘 파이프라인, Make 규칙, CI 단계, 일회성 변환 등에 맞게 만들어졌습니다.

## Prerequisites

CLI는 패키지에 포함되어 있어 별도의 설치가 필요 없습니다. `groupdocs-conversion-net`이 설치되어 있는지 확인하세요([Quick Start Guide]() 참조), 그런 다음 콘솔 스크립트가 사용 가능한지 확인하십시오:

```bash
groupdocs-conversion --version
```

예를 들어 `groupdocs-conversion 26.9.0`와 같이 패키지 버전이 출력됩니다.

`groupdocs-conversion` 명령을 찾을 수 없으면 패키지의 스크립트 디렉터리가 `PATH`에 포함되지 않았을 수 있습니다. 대신 Python 모듈 형태로 CLI를 호출할 수 있습니다: `python -m groupdocs.conversion`. 두 방법은 동일합니다.

## Commands

CLI는 네 개의 하위 명령을 제공합니다. 전체 플래그 목록을 보려면 `groupdocs-conversion --help`를 실행하고, 특정 하위 명령에 대한 도움말은 `groupdocs-conversion <command> --help`를 실행하십시오.

### convert

문서를 다른 형식으로 변환합니다. 대상 형식은 출력 파일 확장자에서 추론되며, `--format`을 사용해 이를 재정의할 수 있습니다.

```bash
# 확장자가 대상 형식을 선택합니다
groupdocs-conversion convert business-plan.docx business-plan.pdf

# 출력 파일 이름에 사용 가능한 확장자가 없을 때 형식을 재정의합니다
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# 단일 페이지(1부터 시작) 변환 — 래스터 대상에 유용합니다
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# 비밀번호로 보호된 소스 열기
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| 옵션 | 설명 |
| :- | :- |
| `--format` | 대상 형식 토큰(출력 확장자를 재정의합니다). |
| `--password` | 보호된 소스 문서의 비밀번호. |
| `--page` | 변환할 첫 페이지, 1부터 시작. |
| `--count` | 변환할 페이지 수. |

성공하면 명령이 출력 경로를 표시하고 코드 `0`으로 종료합니다.

### info

문서에 대한 기본 정보를 출력합니다 — 형식, 크기, 페이지 수 및 가능한 경우 생성 날짜.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

보호된 소스에 대해 `--password`를 사용합니다.

### list-formats

주어진 입력 문서에 대해 엔진이 생성할 수 있는 모든 대상 형식을 기본 대상과 보조 대상으로 구분하여 나열합니다.

```bash
groupdocs-conversion list-formats business-plan.docx
```

보호된 소스에 대해 `--password`를 사용합니다.

### list-all-formats

엔진이 알고 있는 전체 소스-대상 변환 매트릭스를 출력합니다 — 모든 입력 형식과 변환 가능한 대상.

```bash
groupdocs-conversion list-all-formats
```

이 명령은 입력 파일을 받지 않습니다.

## Global options

이 옵션은 모든 명령에 적용됩니다:

| 옵션 | 설명 |
| :- | :- |
| `--license PATH` | 명령을 실행하기 전에 라이선스 파일을 적용합니다. |
| `--version` | CLI 버전을 출력하고 종료합니다. |
| `--help` | 사용법 도움말을 표시하고 종료합니다. |

`--license`를 서브커맨드 앞에 배치하여 미리 라이선스를 적용합니다:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

CLI는 `GROUPDOCS_LIC_PATH` 환경 변수를 또한 인식합니다 — 설정된 경우 라이선스가 자동으로 적용되며 `--license`를 생략할 수 있습니다. 자세한 내용은 [Licensing]() 항목을 참조하십시오.

## Format tokens

`convert`는 출력 확장자를 — 또는 소문자로 변환된 `--format` 값을 — 해당 변환 옵션 및 파일 유형에 매핑합니다. 지원되는 토큰은 다음과 같습니다:

| 카테고리 | 토큰 |
| :- | :- |
| PDF | `pdf` |
| 워드 프로세싱 | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| 스프레드시트 | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| 프레젠테이션 | `ppt`, `pptx`, `pptm`, `odp` |
| 웹 | `html`, `htm`, `mhtml` |
| 이미지 | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| 전자책 | `epub`, `mobi`, `azw3` |

알 수 없는 토큰이 명령을 종료 코드 `2`와 함께 종료시키고 허용된 토큰 목록을 출력합니다.

## Exit codes

| 코드 | 의미 |
| :- | :- |
| `0` | 성공. |
| `2` | 사용자 오류 — 알 수 없는 형식 토큰 또는 입력 파일이 누락되었습니다. |
| `1` | 런타임 오류 — 기본 .NET 예외 메시지가 표준 오류에 출력됩니다. |

이 코드들은 셸 스크립트와 CI 파이프라인에서 CLI를 쉽게 분기하도록 합니다.

## When to use the Python API instead

CLI는 일반적인 단일 문서 변환 사례를 다룹니다. 그 외의 경우 — 페이지별 콜백, 메모리 스트림, 워터마크, 글꼴 또는 셀 범위 옵션, 그리고 다중 문서 컨테이너 계층 구조 — 는 Python API를 직접 사용하십시오. CLI 플래그보다 더 풍부한 기능을 제공합니다. 전체 기능 세트를 보려면 [Developer Guide]()를 참조하세요.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
