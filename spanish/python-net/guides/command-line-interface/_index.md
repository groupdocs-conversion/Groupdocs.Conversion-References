---
title: "Interfaz de Línea de Comandos"
linkTitle: "Command Line Interface"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Convertir documentos directamente desde la terminal con la herramienta de línea de comandos groupdocs-conversion — no se requiere script de Python. Inspeccionar documentos, listar formatos compatibles y aplicar una licencia, todo desde la consola."
type: docs
url: /es/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


Instalar el paquete `groupdocs-conversion-net` también coloca un script de consola `groupdocs-conversion` en tu `PATH`. Es una capa ligera sobre la API de Python, creada para los casos en que iniciar un script de Python es excesivo — canalizaciones de shell, reglas Make, pasos de CI y conversiones puntuales.

## Prerequisites

El CLI se incluye dentro del paquete, por lo que no se necesita instalación adicional. Asegúrate de que `groupdocs-conversion-net` esté instalado (consulta la [Guía de Inicio Rápido]()), luego verifica que el script de consola esté disponible:

```bash
groupdocs-conversion --version
```

Deberías ver la versión del paquete impresa, por ejemplo `groupdocs-conversion 26.9.0`.

Si no se encuentra el comando `groupdocs-conversion`, es posible que el directorio de scripts del paquete no esté en tu `PATH`. Siempre puedes invocar el CLI a través del módulo Python en su lugar: `python -m groupdocs.conversion`. Ambos son equivalentes.

## Commands

El CLI expone cuatro subcomandos. Ejecuta `groupdocs-conversion --help` para ver la lista completa de opciones, o `groupdocs-conversion <command> --help` para un subcomando específico.

### convert

Convertir un documento a otro formato. El formato de destino se infiere de la extensión del archivo de salida; pasa `--format` para sobrescribirlo.

```bash
# La extensión elige el formato de destino
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Sobrescribir el formato cuando el nombre de salida no tiene una extensión utilizable
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Convertir una sola página (indexada desde 1) — útil para objetivos raster
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Abrir una fuente protegida con contraseña
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Opción | Descripción |
| :- | :- |
| `--format` | Token de formato de destino (sobrescribe la extensión de salida). |
| `--password` | Contraseña para un documento fuente protegido. |
| `--page` | Primera página a convertir, indexada desde 1. |
| `--count` | Número de páginas a convertir. |

Al tener éxito, el comando muestra la ruta de salida y termina con el código `0`.

### info

Imprime información básica sobre un documento — formato, tamaño, número de páginas y fecha de creación cuando esté disponible.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Use `--password` para fuentes protegidas.

### list-formats

Enumere cada formato de destino que el motor puede producir para un documento de entrada dado, dividido en destinos primarios y secundarios.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Use `--password` para fuentes protegidas.

### list-all-formats

Imprima la matriz completa de conversión de origen a destino conocida por el motor — cada formato de entrada y los destinos a los que puede convertirse.

```bash
groupdocs-conversion list-all-formats
```

Este comando no requiere archivo de entrada.

## Global options

Estas opciones se aplican a cada comando:

| Opción | Descripción |
| :- | :- |
| `--license PATH` | Aplique un archivo de licencia antes de ejecutar el comando. |
| `--version` | Imprima la versión del CLI y salga. |
| `--help` | Muestre la ayuda de uso y salga. |

Aplique una licencia al inicio colocando `--license` antes del subcomando:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

El CLI también respeta la variable de entorno `GROUPDOCS_LIC_PATH` — si está establecida, la licencia se aplica automáticamente y puede omitir `--license`. Consulte el tema [Licensing]() para más detalles.

## Format tokens

`convert` asigna la extensión de salida — o el valor `--format`, en minúsculas — a las opciones de conversión y tipo de archivo correspondientes. Los tokens admitidos son:

| Categoría | Tokens |
| :- | :- |
| PDF | `pdf` |
| Procesamiento de texto | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Hoja de cálculo | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Presentación | `ppt`, `pptx`, `pptm`, `odp` |
| Web | `html`, `htm`, `mhtml` |
| Imagen | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| eBook | `epub`, `mobi`, `azw3` |

Un token desconocido hace que el comando salga con el código `2` y muestre la lista de tokens aceptados.

## Exit codes

| Código | Significado |
| :- | :- |
| `0` | Éxito. |
| `2` | Error de usuario — token de formato desconocido o archivo de entrada faltante. |
| `1` | Error de tiempo de ejecución — el mensaje de excepción subyacente de .NET se imprime en la salida de error estándar. |

Estos códigos facilitan la ramificación del CLI en scripts de shell y pipelines de CI.

## When to use the Python API instead

El CLI cubre los casos comunes de conversión de un solo documento. Para cualquier cosa más allá de eso — devoluciones de llamada por página, flujos en memoria, marca de agua, fuente, o opciones de rango de celdas, y jerarquías de contenedores multi‑documento — use la API de Python directamente. Proporciona una superficie más rica que las banderas del CLI. Consulte la [Developer Guide]() para el conjunto completo de funciones.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
