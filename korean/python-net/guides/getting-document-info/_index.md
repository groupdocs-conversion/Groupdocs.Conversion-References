---
title: "문서 정보 가져오기"
linkTitle: "Getting Document Information"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "PDF, Word, Excel, PowerPoint, CAD, 이미지, 프로젝트 관리 및 이메일 문서에서 형식, 페이지 수, 저자, 치수, 목차 및 형식별 메타데이터를 변환 없이 읽습니다 — GroupDocs.Conversion for Python via .NET의 Converter.get_document_info()를 사용하여."
type: docs
url: /ko/python-net/guides/getting-document-info/
is_root: false
weight: 110
---


GroupDocs.Conversion for Python via .NET은 문서 정보를 얻기 위한 표준 메서드를 제공합니다. 아래와 같이 다양한 형식에 대해 기본 문서 정보 또는 상세 정보를 검색할 수 있습니다.

## Example 1: Get Basic Document Info

문서 정보를 검색하려면 `Converter.get_document_info()` 메서드를 사용하십시오. 이 메서드는 형식, 생성 날짜, 크기 및 페이지 수와 같이 지원되는 모든 문서 유형에 공통적인 세부 정보를 포함하는 [`DocumentInfo`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/) 객체를 반환합니다.

{{< tabs "code-example-1">}}
{{< tab "get_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_document_info():
    # 문서를 로드하고 정보를 검색합니다
    with Converter("./lorem-ipsum.txt") as converter:
        info = converter.get_document_info()
    
        # 기본 문서 정보를 출력합니다
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size, bytes:", info.size)

if __name__ == "__main__":
    get_document_info()
```
{{< /tab >}}

{{< tab "lorem-ipsum.txt" >}}

`lorem-ipsum.txt`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/lorem-ipsum.txt)를 클릭하세요.

{{< /tab >}}
{{< tab "get-document-info.txt" >}}
```text
Format: txt
Pages count: 3
Creation date: 0001-01-01T00:00:00.0000000
Size, bytes: 7794
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_document_info/get-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Get PDF Document Info

{{< tabs "code-example-2">}}
{{< tab "get_pdf_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_pdf_document_info():
    # 문서를 로드하고 정보를 검색합니다
    with Converter("sample-with-toc.pdf") as converter:
        doc_info = converter.get_document_info()

        # PDF 문서 정보를 출력합니다
        print("Author:", doc_info.author)
        print("Creation Date:", doc_info.creation_date)
        print("Title:", doc_info.title)
        print("Version:", doc_info.version)
        print("Pages Count:", doc_info.pages_count)
        print("Width:", doc_info.width)
        print("Height:", doc_info.height)
        print("Is Landscaped:", doc_info.is_landscape)
        print("Is Password-Protected:", doc_info.is_password_protected)
        print("Table of contents:")
        for toc_item in doc_info.table_of_contents:
            print(f" Page {toc_item.page}: Title: {toc_item.title}")

if __name__ == "__main__":
    get_pdf_document_info()
```
{{< /tab >}}
{{< tab "sample-with-toc.pdf" >}}

`sample-with-toc.pdf`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/sample-with-toc.pdf)를 클릭하세요.

{{< /tab >}}
{{< tab "get-pdf-document-info.txt" >}}
```text
Author: None
Creation Date: 2020-08-12T16:41:29.0000000
Title: None
Version: 1.7
Pages Count: 5
Width: 612
Height: 792
Is Landscaped: False
Is Password-Protected: False
Table of contents:
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_pdf_document_info/get-pdf-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Get Word Processing Document Info

이 형식군에 속하는 파일 유형은 [Word Processing]() 문서 섹션에서 확인할 수 있습니다.

{{< tabs "code-example-3">}}
{{< tab "get_wp_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_wp_document_info():
    # 문서를 로드하고 정보를 검색합니다
    with Converter("./business-plan.doc") as converter:
        doc_info = converter.get_document_info()

        # DOC 문서 정보를 출력합니다
        print("Author:", doc_info.author)
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Is Password Protected:", doc_info.is_password_protected)
        print("Lines:", doc_info.lines)
        print("Pages Count:", doc_info.pages_count)
        print("Size, bytes:", doc_info.size)
        print("Title:", doc_info.title)
        print("Words:", doc_info.words)
        print("Table of contents:")
        for toc_item in doc_info.table_of_contents:
            print(f" Page {toc_item.page}: Title: {toc_item.title}")

if __name__ == "__main__":
    get_wp_document_info()
```
{{< /tab >}}
{{< tab "business-plan.doc" >}}

`business-plan.doc`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/business-plan.doc)를 클릭하세요.

{{< /tab >}}
{{< tab "get-wp-document-info.txt" >}}
```text
Author: GroupDocs
Creation Date: 2024-11-03T10:05:00.0000000Z
Format: doc
Is Password Protected: False
Lines: 180
Pages Count: 19
Size, bytes: 414208
Title: 
Words: 3789
Table of contents:
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_wp_document_info/get-wp-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 4: Get Project Management Document Info

이 형식군에 속하는 파일 유형을 [Project Management]() 문서 섹션에서 찾을 수 있습니다.

{{< tabs "code-example-4">}}
{{< tab "get_pm_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_pm_document_info():
    # 문서를 로드하고 정보를 검색합니다
    with Converter("./weekly-plan.mpp") as converter:
        doc_info = converter.get_document_info()

        # MPP 문서 정보를 출력합니다
        print("Creation Date:", doc_info.creation_date)
        print("Start Date:", doc_info.start_date)
        print("End Date:", doc_info.end_date)
        print("Format:", doc_info.format)
        print("Size, bytes:", doc_info.size)
        print("Tasks Count:", doc_info.tasks_count)

if __name__ == "__main__":
    get_pm_document_info()
```
{{< /tab >}}
{{< tab "weekly-plan.mpp" >}}

`weekly-plan.mpp`은 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/weekly-plan.mpp)를 클릭하십시오.

{{< /tab >}}
{{< tab "get-pm-document-info.txt" >}}
```text
Creation Date: 2026-04-15T20:19:14.5231130Z
Start Date: 2017-10-06T09:00:00.0000000Z
End Date: 2017-10-14T18:00:00.0000000Z
Format: mpp
Size, bytes: 236544
Tasks Count: 5
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_pm_document_info/get-pm-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 5: Get Image Info

이 형식군에 속하는 파일 유형을 [Image]() 문서 섹션에서 찾을 수 있습니다.

{{< tabs "code-example-5">}}
{{< tab "get_image_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_image_info():
    # 문서를 로드하고 정보를 검색합니다
    with Converter("./infographic-elements.tiff") as converter:
        doc_info = converter.get_document_info()

        # TIFF 문서 정보를 출력합니다
        print("Bits per Pixel:", doc_info.bits_per_pixel)
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Height:", doc_info.height)
        print("Width:", doc_info.width)
        print("Size, bytes:", doc_info.size)

if __name__ == "__main__":
    get_image_info()
```
{{< /tab >}}
{{< tab "infographic-elements.tiff" >}}

`infographic-elements.tiff`은 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/infographic-elements.tiff)를 클릭하십시오.

{{< /tab >}}
{{< tab "get-image-info.txt" >}}
```text
Bits per Pixel: 32
Creation Date: 2026-04-15T20:19:15.4324761Z
Format: tiff
Height: 2000
Width: 1500
Size, bytes: 1734560
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_image_info/get-image-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 6: Get Presentation Document Info

이 형식군에 속하는 파일 유형을 [Presentation]() 문서 섹션에서 찾을 수 있습니다.

{{< tabs "code-example-6">}}
{{< tab "get_pres_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_pres_document_info():
    # 문서를 로드하고 정보를 검색합니다
    with Converter("./presentation-template.pptx") as converter:
        doc_info = converter.get_document_info()

        # PPTX 문서 정보를 출력합니다
        print("Author:", doc_info.author)
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Is Password Protected:", doc_info.is_password_protected)
        print("Pages Count:", doc_info.pages_count)
        print("Size, bytes:", doc_info.size)
        print("Title:", doc_info.title)

if __name__ == "__main__":
    get_pres_document_info()
```
{{< /tab >}}
{{< tab "presentation-template.pptx" >}}

`presentation-template.pptx`은 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/presentation-template.pptx)를 클릭하십시오.

{{< /tab >}}
{{< tab "get-pres-document-info.txt" >}}
```text
Author: GroupDocs
Creation Date: 2023-03-04T14:58:10.0000000Z
Format: pptx
Is Password Protected: False
Pages Count: 3
Size, bytes: 35210
Title: TEST
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_pres_document_info/get-pres-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 7: Get Spreadsheet Document Info

이 형식군에 속하는 파일 유형을 [Spreadsheets]() 문서 섹션에서 찾을 수 있습니다.

{{< tabs "code-example-7">}}
{{< tab "get_sp_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_sp_document_info():
    # 문서를 로드하고 정보를 검색합니다
    with Converter("./cost-analysis.xlsx") as converter:
        doc_info = converter.get_document_info()

        # XLSX 문서 정보 출력
        print("Author:", doc_info.author)
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Is Password Protected:", doc_info.is_password_protected)
        print("Pages Count:", doc_info.pages_count)
        print("Size, bytes:", doc_info.size)
        print("Title:", doc_info.title)
        print("Worksheets Count:", doc_info.worksheets_count)

if __name__ == "__main__":
    get_sp_document_info()
```
{{< /tab >}}
{{< tab \"cost-analysis.xlsx\" >}}

`cost-analysis.xlsx`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/cost-analysis.xlsx) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"get-sp-document-info.txt\" >}}
```text
Author: GroupDocs
Creation Date: 2023-02-23T18:52:46.0000000+02:00
Format: xlsx
Is Password Protected: False
Pages Count: 0
Size, bytes: 78940
Title: Cost Analysis
Worksheets Count: 1
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_sp_document_info/get-sp-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 8: Get CAD Drawing Info

이 형식군에 속하는 파일 유형은 [CAD]() 문서 섹션에서 찾을 수 있습니다.

{{< tabs \"code-example-8\">}}
{{< tab \"get_cad_document_info.py\" >}}
```python
from groupdocs.conversion import Converter

def get_cad_document_info():
    # 문서를 로드하고 정보를 검색합니다
    with Converter("./blocks-and-tables.dwg") as converter:
        doc_info = converter.get_document_info()

        # DWG 문서 정보 출력
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Height:", doc_info.height)
        print("Width:", doc_info.width)
        print("Size, bytes:", doc_info.size)
        
        print("Layouts:")
        for layout in doc_info.layouts:
            print(" Layout:", layout)
        
        print("Layers:")
        for layer in doc_info.layers:
            print(" Layer:", layer)

if __name__ == "__main__":
    get_cad_document_info()
```
{{< /tab >}}
{{< tab \"blocks-and-tables.dwg\" >}}

`blocks-and-tables.dwg`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/blocks-and-tables.dwg) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"get-cad-document-info.txt\" >}}
```text
Creation Date: 2026-04-15T20:19:18.9521534Z
Format: dwg
Height: 16
Width: 26
Size, bytes: 258848
Layouts:
 Layout: Model
 Layout: ISO A1
Layers:
 Layer: Text
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_cad_document_info/get-cad-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 9: Get Email Message Info

이 형식군에 속하는 파일 유형은 [Email]() 문서 섹션에서 찾을 수 있습니다.

{{< tabs \"code-example-9\">}}
{{< tab \"get_email_document_info.py\" >}}
```python
from groupdocs.conversion import Converter

def get_email_document_info():
    # 문서를 로드하고 정보를 검색합니다
    with Converter("./invitation.eml") as converter:
        doc_info = converter.get_document_info()

        # EML 문서 정보 출력
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Is Encrypted:", doc_info.is_encrypted)
        print("Is Body in HTML:", doc_info.is_html)
        print("Is Signed:", doc_info.is_signed)
        print("Size:", doc_info.size)
        print("Attachments Count:", doc_info.attachments_count)

        for attachment_name in doc_info.attachments_names:
            print("Attachment Name:", attachment_name)

if __name__ == "__main__":
    get_email_document_info()
```
{{< /tab >}}
{{< tab \"invitation.eml\" >}}

`invitation.eml`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/invitation.eml) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"get-email-document-info.txt\" >}}
```text
Creation Date: 2017-04-25T11:28:29.0000000Z
Format: eml
Is Encrypted: False
Is Body in HTML: True
Is Signed: False
Size: 91948
Attachments Count: 1
Attachment Name: bg_pattern.gif
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_email_document_info/get-email-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

DocumentInfo 객체는 문서 형식에 따라 달라지는 방대한 메타데이터 세트를 제공합니다. 추가 형식별 문서 메타데이터 세부 정보를 보려면 [API 참조](https://reference.groupdocs.com/conversion/python-net/) 를 참조하십시오.
