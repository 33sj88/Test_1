---
id: [Generated_UUID_4]
category: "[[10_Wiki/⚙️ Skills]]"
confidence_score: 0.9
tags: [Datasets, DataProcessing, Streaming, Tokenization]
last_reinforced: 2026-11-23
---
# 대규모 데이터 처리 및 스트리밍 (`datasets`)
## 📌 한 줄 통찰
> 대용량 데이터셋을 효율적으로 처리하고 메모리 사용량을 최소화하기 위한 Hugging Face `datasets` 라이브러리 활용법을 다룹니다.
## 📖 구조화된 지식
- **대용량 데이터셋 로딩**:
    - `load_dataset(...)` 함수를 사용하여 데이터셋을 불러옵니다.
    - **메모리 최적화**: 대용량 데이터셋 처리 시 `streaming=True` 옵션을 반드시 사용하여 메모리 부담을 최소화합니다.
- **효율적인 전처리**:
    - 데이터셋의 전처리 및 토큰화 작업은 `.map()` 함수를 활용하여 효율적으로 수행합니다.
## 🔗 지식 연결
- Parent: [[NLP_Transformer_Core_Patterns]]
- Related: [[DataProcessing]], [[Streaming]]
- Raw Source: [[00_Raw/2026-11-23/day1.md]]