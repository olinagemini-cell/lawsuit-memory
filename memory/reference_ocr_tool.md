---
name: OCR tool location
description: Python OCR script for scanned PDFs and images, supports Chinese, located in lawsuit folder
type: reference
---

OCR工具路径：`C:\Users\olina\Desktop\诉讼\ocr_tool.py`

依赖：rapidocr-onnxruntime, pymupdf, Pillow（已安装）

用法：
- 单文件：`python ocr_tool.py "文件.pdf" -o output.txt`
- 批量文件夹：`python ocr_tool.py "文件夹路径" -o all.txt`
- 支持格式：PNG, JPG, BMP, TIFF, WebP, PDF

**How to apply:** 分析诉讼相关扫描件、照片时，先用此工具OCR提取文字到txt，再读取txt进行分析。
