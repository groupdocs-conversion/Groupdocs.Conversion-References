---
title: "命令行界面"
linkTitle: "Command Line Interface"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "使用 groupdocs-conversion 命令行工具直接在终端转换文档——无需 Python 脚本。检查文档、列出支持的格式并应用许可证，全部在 shell 中完成。"
type: docs
url: /zh/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


安装 `groupdocs-conversion-net` 包还会在你的 `PATH` 中放置一个 `groupdocs-conversion` 控制台脚本。它是对 Python API 的轻量包装，适用于不想启动 Python 脚本的场景——shell 管道、Make 规则、CI 步骤以及一次性转换。

## Prerequisites

CLI 随包一起提供，无需额外安装。确保已安装 `groupdocs-conversion-net`（参见[快速入门指南]()), 然后验证控制台脚本是否可用：

```bash
groupdocs-conversion --version
```

你应该会看到打印出的包版本，例如 `groupdocs-conversion 26.9.0`。

如果未找到 `groupdocs-conversion` 命令，可能是包的脚本目录未在你的 `PATH` 中。你仍可以通过 Python 模块形式调用 CLI：`python -m groupdocs.conversion`。两者等价。

## Commands

CLI 提供四个子命令。运行 `groupdocs-conversion --help` 查看完整标志列表，或 `groupdocs-conversion <command> --help` 查看特定子命令的帮助。

### convert

将文档转换为另一种格式。目标格式根据输出文件扩展名推断；使用 `--format` 可覆盖它。

```bash
# 扩展名决定目标格式
groupdocs-conversion convert business-plan.docx business-plan.pdf

# 当输出名称不包含可用扩展名时覆盖格式
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# 转换单页（从 1 开始索引）——对光栅目标有用
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# 打开受密码保护的源
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| 选项 | 描述 |
| :- | :- |
| `--format` | 目标格式标记（覆盖输出扩展名）。 |
| `--password` | 受保护源文档的密码。 |
| `--page` | 要转换的起始页，1 索引。 |
| `--count` | 要转换的页数。 |

成功时，命令会打印输出路径并以代码 `0` 退出。

### info

打印文档的基本信息 — 格式、大小、页数，以及（如果可用）创建日期。

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

对受保护的来源使用 `--password`。

### list-formats

列出引擎针对给定输入文档可以生成的所有目标格式，分为主要和次要目标。

```bash
groupdocs-conversion list-formats business-plan.docx
```

对受保护的来源使用 `--password`。

### list-all-formats

打印引擎已知的完整源到目标的转换矩阵 — 每种输入格式以及它可以转换到的目标。

```bash
groupdocs-conversion list-all-formats
```

此命令不接受输入文件。

## Global options

这些选项适用于每个命令：

| 选项 | 描述 |
| :- | :- |
| `--license PATH` | 在运行命令之前应用许可证文件。 |
| `--version` | 打印 CLI 版本并退出。 |
| `--help` | 显示使用帮助并退出。 |

通过在子命令前放置 `--license` 来预先应用许可证：

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

CLI 还会遵循 `GROUPDOCS_LIC_PATH` 环境变量 — 如果已设置，许可证会自动应用，你可以省略 `--license`。有关详细信息，请参阅 [Licensing]() 主题。

## Format tokens

`convert` 将输出扩展名 — 或小写的 `--format` 值 — 映射到相应的转换选项和文件类型。支持的标记如下：

| 类别 | 标记 |
| :- | :- |
| PDF | `pdf` |
| 文字处理 | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| 电子表格 | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| 演示文稿 | `ppt`, `pptx`, `pptm`, `odp` |
| 网页 | `html`, `htm`, `mhtml` |
| 图像 | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| 电子书 | `epub`, `mobi`, `azw3` |

未知的标记导致命令以代码 `2` 退出，并打印接受的标记列表。

## Exit codes

| 代码 | 含义 |
| :- | :- |
| `0` | 成功。 |
| `2` | 用户错误 — 未知的格式标记或缺少输入文件。 |
| `1` | 运行时错误 — 基础的 .NET 异常消息被打印到标准错误。 |

这些代码使得在 shell 脚本和 CI 流水线中对 CLI 进行分支判断变得容易。

## When to use the Python API instead

CLI 覆盖了常见的单文档转换情况。对于超出此范围的需求 — 每页回调、内存流、水印、字体或单元格范围选项，以及多文档容器层次结构 — 请直接使用 Python API。它提供的功能面比 CLI 标志更丰富。请参阅 [Developer Guide]() 了解完整的功能集。

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
