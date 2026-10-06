---
title: "비밀번호로 보호된 파일 로드"
linkTitle: "Load Password-Protected File"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "비밀번호가 설정된 Word, Excel, PowerPoint 및 PDF 문서를 GroupDocs.Conversion for Python via .NET의 Converter 생성자에 비밀번호 속성이 포함된 LoadOptions 인스턴스를 전달하여 잠금을 해제하고 변환합니다."
type: docs
url: /ko/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


*GroupDocs.Conversion for Python via .NET*를 사용하면 비밀번호로 보호된 문서를 로드하고 변환할 수 있습니다. 이 기능은 내용에 접근하기 위해 인증이 필요한 문서를 처리해야 할 때 유용합니다.

비밀번호로 보호된 문서를 로드하고 변환하려면 아래 코드 예제에 설명된 단계를 따르세요:

{{< tabs "code-example">}}
{{< tab \"load_password_protected_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # 파일 경로 설정
    file_path = "./password-protected.docx"
    
    # LoadOptions를 인스턴스화하고 비밀번호를 설정합니다
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # 소스 파일 스트림과 LoadOptions를 지정합니다
    converter = Converter(file_path, wp_load_options)
    
    # 출력 파일 위치 및 변환 옵션 지정
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # 변환하고 출력 경로에 저장
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab \"password-protected.docx\" >}}

`password-protected.docx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx)를 클릭하세요.

{{< /tab >}}
{{< tab \"password-protected.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

제공된 비밀번호가 올바르지 않은 경우 런타임 오류가 발생합니다. 예상되는 오류와 오류 메시지는 다음과 같습니다:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: 비밀번호로 보호된 문서의 파일 경로가 지정됩니다. 이 예제에서는 문서 이름이 `password-protected.docx`라고 가정합니다.

2. **Load Options**: [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)의 인스턴스를 생성하고, 문서를 열기 위해 필요한 비밀번호를 설정합니다.

3. **Converter Initialization**: 파일 경로와 비밀번호를 포함한 로드 옵션을 사용하여 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 인스턴스를 생성합니다.

4. **Convert Options**: 변환 프로세스를 위해 [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) 인스턴스를 생성합니다. 필요에 따라 결과 PDF의 출력 비밀번호도 설정할 수 있습니다.

4. **Conversion Execution**: 마지막으로, [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 인스턴스에서 `convert` 메서드를 호출하여 비밀번호가 보호된 문서를 PDF로 변환하고 저장합니다.

### Conclusion

이 예제는 GroupDocs.Conversion for Python API를 사용하여 비밀번호가 보호된 문서를 효율적으로 로드하고 변환하는 방법을 보여줍니다. 코드를 실행하기 전에 비밀번호와 파일 경로를 실제 값으로 교체하십시오.
