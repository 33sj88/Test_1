---
id: [Generated_UUID_2]
category: "[[10_Wiki/🛠️ Projects]]"
confidence_score: 0.9
tags: [Pipeline, TextGeneration, Inference]
last_reinforced: 2026-11-23
---
# 파이프라인 기반 빠른 추론 (`pipeline`)
## 📌 한 줄 통찰
> `pipeline`은 복잡한 모델 학습 없이도 텍스트 분류, 요약, 텍스트 생성 등 다양한 NLP 태스크를 가장 적은 코드로 실행할 수 있게 해주는 Hugging Face의 핵심 기능입니다.
## 📖 구조화된 지식
- **목표**: 최소 코드로 주요 NLP 태스크 실행.
- **주요 사용법**: `pipeline("task_name", model="model_name")` 형태로 파이프라인을 생성.
- **예시 (텍스트 생성)**:
    1. `pipeline("text-generation", model="gpt2-xl")`로 파이프라인 생성.
    2. 프롬프트(`TL;DR:` 등)를 입력으로 제공.
    3. 결과를 얻은 후, 입력 길이만큼 슬라이싱하여 생성 텍스트만 추출하여 활용.
## 🔗 지식 연결
- Parent: [[NLP_Transformer_Core_Patterns]]
- Related: [[TextGeneration]], [[Inference]]
- Raw Source: [[00_Raw/2026-11-23/day1.md]]