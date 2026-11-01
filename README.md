# claude-skills

> 실무에서 Claude Code와 함께 일하며 만들고 다듬어 온 스킬 모음입니다.

Spring 백엔드 개발자로 일하면서 AI에게 같은 설명을 반복하거나, AI가 같은 실수를 되풀이할 때마다 그 절차를 스킬로 정리해 왔습니다. 회사 고유 정보는 모두 빼고, 다른 팀에서도 쓸 수 있도록 일반화해 공개합니다.

## 스킬 목록

### 코드 작업

| 스킬 | 하는 일 |
| --- | --- |
| [spring-backend-change-procedure](https://github.com/smjae96/spring-backend-change-procedure) | Spring Boot 코드를 바꿀 때 실제 파일 읽기 → 스케줄러·이벤트 리스너까지 검색 → 계획 승인 → 영향 범위 함께 수정 순서로 진행하게 합니다 |
| [step-by-step-codework](https://github.com/smjae96/step-by-step-codework) | 구현 계획을 작은 단계로 나눠 한 번에 한 단계씩 진행하고, 단계마다 커밋 메시지 예시를 줍니다 |
| [karpathy-coding-principles-modified](https://github.com/smjae96/karpathy-coding-principles-modified) | Karpathy 코딩 원칙의 한국어 수정본. 빌드를 돌릴 수 없는 환경에서는 정적 검증으로 대체하는 규칙을 추가했습니다 |

### 원인 찾기 · 판단

| 스킬 | 하는 일 |
| --- | --- |
| [cross-project-root-cause](https://github.com/smjae96/cross-project-root-cause) | 백엔드·프론트엔드가 얽힌 버그에서 증상이 보이는 쪽을 원인으로 단정하지 않고, 데이터로 확정하게 합니다 |
| [opus-5-required](https://github.com/smjae96/opus-5-required) | 반박을 어디서 멈출지(코드로 검증할 수 있는 영역 vs 사용자만 아는 영역)와 역할 범위를 넘지 않는 기준을 정합니다 |
| [grill-me-ko-modified](https://github.com/smjae96/grill-me-ko-modified) | 구현 전에 AI가 계획을 끝까지 질문하게 하는 grill-me의 한국어 진행 수정본입니다 |

### 문서 · 소통

| 스킬 | 하는 일 |
| --- | --- |
| [api-change-spec](https://github.com/smjae96/api-change-spec) | 백엔드 API 변경점을 프론트엔드 개발자에게 전달할 명세로 정리합니다 (앱 · 웹 · 어드민 영향 구분) |
| [user-flow-qa-scenario](https://github.com/smjae96/user-flow-qa-scenario) | 비개발 직원도 실제 사용자처럼 따라 할 수 있는 흐름 기반 QA 시나리오와 개발자 체크리스트를 따로 만듭니다 |
| [dev-retrospective](https://github.com/smjae96/dev-retrospective) | 개발 이슈 · 장애를 Problem / How to Solve? / Lesson 회고록으로, 비개발자도 읽을 수 있게 씁니다 |
| [weekly-dev-retro](https://github.com/smjae96/weekly-dev-retro) | 주간 개발 회고를 "무엇이 움직였나(지표)" 중심으로 정리합니다 |
| [work-summary](https://github.com/smjae96/work-summary) | 끝난 작업을 what / how / why 형식으로 정리합니다 |

## 설치

Claude Code에서는 스킬 폴더를 `~/.claude/skills/<스킬 이름>/`(개인용) 또는 프로젝트의 `.claude/skills/<스킬 이름>/`에 넣으면 됩니다.

```bash
git clone https://github.com/smjae96/<스킬 이름>.git ~/.claude/skills/<스킬 이름>
```

Claude 앱(claude.ai)에서는 스킬 폴더를 zip으로 묶어 설정 > 기능 > 스킬에서 업로드합니다.

## 만든 사람

심재윤 · Java / Spring 백엔드 개발자
- 노션: https://shy-repair-a36.notion.site/40abf7756f8180f783ccd14ce1fa3c6c
- 링크드인: https://www.linkedin.com/in/%EC%9E%AC%EC%9C%A4-%EC%8B%AC-732427448/

## License

직접 만든 스킬은 MIT 라이선스입니다. `-modified`가 붙은 스킬은 원작의 라이선스(MIT)를 따르며, 각 레포에 원작 출처를 밝혀 두었습니다.
