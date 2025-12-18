# 📊 AI-Driven Technical Document Audit & Evaluation

## 💡 Project Overview
반도체 장비 기술 에스컬레이션(Technical Escalation) 데이터의 품질 평가 Workflow를 LLM을 통해 자동으로 평가하고 시각화하는 솔루션입니다.

## 🚀 Key Impact
- **Efficiency:** 수동 Audit의 **87% 자동화** 및 주당 **10시간 이상의 업무 시간 절감** (PBG별) 
- **Speed:** 연간 28,000건의 데이터 검토 시간을 **80% 이상 단축** 
- **Accuracy:** 프롬프트 엔지니어링 및 피드백 루프를 통해 **90% 이상의 정확도** 달성 

## 🖼️ Visualization (UI)


## ⚙️ Technical Workflow
```mermaid
graph LR
    A[Unstructured Text] --> B{GPT-4 Evaluation}
    B --> C[JSON Structuring via Pydantic]
    C --> D[Data Visualization Dashboard]
    D --> E[Human Feedback Loop]
