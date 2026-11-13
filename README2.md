# TIL | AI 생태계 이해: Model, Harness & Context

📅 **2026-11-13**

## 1. Why — 왜 AI 생태계를 이해해야 하는가?

AI 서비스를 단순히 사용하는 것을 넘어, 모델의 구조와 실행 환경, 활용 방식을 이해할 필요가 있다.

특히 데이터 분석가에게 중요한 것은 목적에 맞는 모델을 선택하고, 데이터와 연결하여 효율적으로 활용하는 능력이다.

## 2. What — AI 생태계의 세 가지 계층

### ① AI Model & Infrastructure

AI 모델 자체와 학습·추론에 필요한 인프라를 이해한다.

- **LLM / Transformer:** 대규모 언어 모델과 핵심 아키텍처
- **Embeddings:** 텍스트 및 데이터를 벡터로 표현
- **Fine-tuning:** 특정 목적에 맞게 모델 추가 학습
- **Local Model / GPU:** 로컬 환경에서 모델 실행
- **Frontier Models:** GPT, Claude, Gemini, Grok
- **Open-weight Models:** DeepSeek, Kimi, MiniMax, GLM
- **Infrastructure:** Hyperscaler, Neocloud

### ② Harness / Provider / API

모델을 실제로 실행하고 활용하는 환경을 이해한다.

| 생태계         | 서비스 및 도구             |
| ----------- | -------------------- |
| Anthropic   | Claude, Claude Code  |
| OpenAI      | ChatGPT, Codex, Dots |
| Open-source | OpenCode, Pi, Amp    |

**주요 고려 사항**

- 완성형 AI 서비스와 API 직접 호출의 차이
- 모델 Provider에 대한 의존성
- API 비용, 응답 속도, 안정성
- Local Model을 통한 실행 환경의 자율성

### ③ Prompt / Instruction / Skill / RAG / Context

모델을 사용자의 목적에 맞게 제어하고 최적화하는 방법이다.

- **Prompt & Instruction:** 명확한 지시와 요구사항 전달
- **Skill & Plugin:** 반복 작업 및 외부 도구 연결
- **RAG:** 외부 데이터를 검색해 답변에 활용
- **Ontology:** 데이터와 개념 간 관계 구조화
- **Context Management:** 필요한 맥락 유지 및 토큰 최적화

## 3. How — AI 모델 평가 및 비교

| 관점         | 플랫폼                                                   | 주요 목적               |
| ---------- | ----------------------------------------------------- | ------------------- |
| 테스트 중심     | [Artificial Analysis](https://artificialanalysis.ai/) | 성능, 비용, 속도, 효율성     |
| 사용자 중심     | [Arena](https://arena.ai/leaderboard)                 | 사용자 선호도 기반 평가       |
| 공급자 중심     | [OpenRouter](https://openrouter.ai/rankings)          | 모델 및 Provider 사용 현황 |
| 코딩·오픈소스 중심 | [OpenCode](https://opencode.ai/ko/data/)              | AI 코딩 도구 및 생태계      |

## 4. Key Takeaways

AI 활용 역량은 단순히 좋은 모델을 사용하는 것이 아니라, 목적에 맞는 모델과 실행 환경을 선택하고 데이터를 연결해 원하는 결과를 만드는 능력이다.

**Next Learning Goals**

- [ ] LLM과 Transformer 작동 원리 이해
- [ ] Embeddings 및 Vector Database 학습
- [ ] RAG와 Fine-tuning 비교
- [ ] Python으로 LLM API 직접 호출
- [ ] Open-weight 모델 로컬 실행
- [ ] 모델별 성능·비용·속도 비교

---

📧 minchae3784\@gmail.com
