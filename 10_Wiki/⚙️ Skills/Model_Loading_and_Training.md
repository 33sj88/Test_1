---
id: [Generated_UUID_3]
category: "[[10_Wiki/⚙️ Skills]]"
confidence_score: 0.95
tags: [ModelLoading, AutoTokenizer, Trainer, TFAutoModel, HyperparameterSearch]
last_reinforced: 2026-11-23
---
# 토크나이저 및 모델 로딩·학습 (`AutoTokenizer`, `AutoModel*`, `Trainer`)
## 📌 한 줄 통찰
> 사전학습 모델을 로드하고, 이를 기반으로 미세조정(Fine-tuning)을 수행하는 데 필요한 Hugging Face 핵심 클래스 및 API를 정리합니다.
## 📖 구조화된 지식
- **사전학습 모델 로딩**:
    - 토크나이저: `AutoTokenizer.from_pretrained(...)` 사용.
    - 모델: `AutoModel...from_pretrained(...)` 계열 사용.
    - 텐서플로 호환성: TensorFlow 환경에서는 `TFAutoModel` 등을 활용하여 모델 로딩.
- **모델 초기화 전략**:
    - 스크래치 학습(10장) 시: 사전학습 가중치 대신 설정(`from_config()`)을 통해 모델을 초기화하는 방법.
- **모델 학습 및 미세조정**:
    - 학습 관리: `Trainer` API를 활용하여 학습 루프를 간소화.
    - 하이퍼파라미터 탐색: 학습 과정에서 `hyperparameter_search()` 기능을 연계하여 최적의 설정을 탐색.
## 🔗 지식 연결
- Parent: [[NLP_Transformer_Core_Patterns]]
- Related: [[HuggingFace_Ecosystem]], [[Model_Optimization]]
- Raw Source: [[00_Raw/2026-11-23/day1.md]]