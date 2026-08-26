# MabiUtils 로컬 한국어 OCR 리소스

이 폴더는 MabiUtils의 로컬 PP-OCRv5 한국어 인식에 필요합니다. 파일이 없거나 손상되면 앱은 기존 Windows OCR로 자동 전환합니다.

## 고정 파일

- `korean_PP-OCRv5_rec_mobile.onnx`
  - SHA-256: `CD6E2EA50F6943CA7271EB8C56A877A5A90720B7047FE9C41A2E541A25773C9B`
  - 출처: RapidOCR v3.9.2의 PaddleOCR PP-OCRv5 한국어 모바일 모델 변환본
  - URL: https://www.modelscope.cn/models/RapidAI/RapidOCR/resolve/v3.9.2/onnx/PP-OCRv5/rec/korean_PP-OCRv5_rec_mobile.onnx
- `ppocrv5_korean_dict.txt`
  - SHA-256: `A88071C68C01707489BAA79EBE0405B7BEB5CCA229F4FC94CC3EF992328802D7`
  - URL: https://www.modelscope.cn/models/RapidAI/RapidOCR/resolve/v3.9.2/paddle/PP-OCRv5/rec/korean_PP-OCRv5_rec_mobile/ppocrv5_korean_dict.txt
- `onnxruntime.dll`
  - 버전: Microsoft ONNX Runtime CPU 1.29.0
  - SHA-256: `69D8E6D3879A3B4001CDC74C8ED9CCC7E7F799A5B847059738323404519EC471`
  - NuGet: https://www.nuget.org/packages/Microsoft.ML.OnnxRuntime/1.29.0
- `msvcp140.dll`, `msvcp140_1.dll`, `vcruntime140.dll`, `vcruntime140_1.dll`
  - ONNX Runtime을 다른 Windows PC에서도 실행하기 위한 Microsoft Visual C++ 재배포 런타임입니다.

## 라이선스

- PaddleOCR: Apache License 2.0 — https://github.com/PaddlePaddle/PaddleOCR
- RapidOCR: Apache License 2.0 — https://github.com/RapidAI/RapidOCR
- ONNX Runtime: MIT License — 저장소의 `third_party/onnxruntime/LICENSE` 참조
- Microsoft Visual C++ Redistributable: Microsoft Visual Studio 배포 가능 코드 라이선스가 적용됩니다.
