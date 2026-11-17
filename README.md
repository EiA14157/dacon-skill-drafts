# DACON Hackathon Skills

[데이콘 랭커특강 목록](https://dacon.io/hackathon#videoSection)의 공개 강의 제목 42개를 바탕으로 만든 Codex 스킬 모음입니다. 강의 주제를 재현 가능한 작업 절차로 정리했습니다. 강의 영상과 자막은 포함하지 않습니다.

| 스킬 | 강의 수 | 사용 목적 |
|---|---:|---|
| [경진대회 실험 설계와 논문 기록](dacon-competition-experiments/SKILL.md) | 17 | 가설, 베이스라인, 비교 실험, 논문 기록 |
| [데이터 EDA와 피처 엔지니어링](dacon-data-eda-features/SKILL.md) | 3 | 데이터 품질, 누수 점검, 파생 변수 검증 |
| [이미지 결함과 비전 모델 검증](dacon-vision-modeling/SKILL.md) | 1 | 이미지 결함 모델, 학습 조건, 오류 분석 |
| [시계열·금융·의료 데이터 검증](dacon-domain-forecasting/SKILL.md) | 9 | 시간·그룹 기반 분할과 베이스라인 |
| [LLM·RAG·AI 에이전트 평가](dacon-llm-rag-agents/SKILL.md) | 7 | 검색, 프롬프트, 도구 호출 평가 |
| [AI 앱·캡스톤 프로토타이핑](dacon-ai-app-prototyping/SKILL.md) | 4 | 사용자 흐름, MCP, 데이터베이스 연동 |
| [ComfyUI 이미지 생성 실험](dacon-comfyui-workflows/SKILL.md) | 1 | 모델 호환성과 생성 설정 비교 |

각 폴더에 `SKILL.md`와 Codex 표시 설정인 `agents/openai.yaml`이 있습니다. 사용할 스킬 폴더를 통째로 가져온 뒤 스킬 이름으로 호출하세요.

단국대 이미지 결함 대회에 적용할 때는 실험 설계 스킬로 공식 규칙과 분할을 확정하고, 비전 모델링 스킬로 첫 모델과 비교 실험을 실행하세요.
