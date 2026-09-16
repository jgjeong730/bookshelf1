# Lantern Protocol — Personal Writing System

모든 집필 프로젝트에 적용하는 개인 창작 프로토콜과 AI 협업 공방입니다.

**LP Office**: https://jgjeong730.github.io/bookshelf1/

## Lanterning

`The Lantern Protocol (LP)`는 장르·분량·매체와 관계없이 하나의 프로젝트를 서로 다른 편집 관점으로 비추는 집필 프로세스입니다.

```text
Gather → Design → Draft → Dissect → Counsel → Revise → Seal
```

`Dissect → Counsel → Revise`는 원고가 충분히 좋아질 때까지 반복합니다.

### 단계별 담당

| 단계 | 담당자 | 역할 |
|---|---|---|
| Gather · 채집 | 강민재 (Min Jae Kang) · Researcher | 소재·자료·사실성·유사성 확인 |
| Design · 기획 | 서윤아 (Mira Seo) · Planner | 핵심 질문·독자·서사 방향 설계 |
| Draft · 집필 | 한도겸 (Theo Han) · Writer | 기획을 장면과 문장으로 전환 |
| Dissect · 해부 | 윤채린 (Clara Yoon) · Dissector | 구조·인물·문체의 문제 분석 |
| Counsel · 자문 | 이서현 (Sora Lee) · Counsel | 문학성·윤리성·완결성 자문 |
| Revise · 개정 | 이도현 (Daniel Lee) · Reviser | 승인된 진단을 개정 원고로 반영 |
| Seal · 봉인 | 문하진 (Hazel Moon) · Archivist | 최종 원고·버전·협업 기록 보존 |

오유진 (Yujin Oh) · Reader는 초고와 개정본을 읽고 독자 경험·대중성·확장 가능성을 점검하는 상시 독자 게이트입니다.

## 역할

- Planner: 질문·독자·서사 방향 설계
- Writer: 기획을 장면과 문장으로 전환
- Dissector: 구조·인물·문체의 문제 분석
- Counsel: 문학성·윤리성·완결성 자문
- Reviser: 진단을 실제 개정으로 반영
- Researcher: 사실성·유사성·저작권 리스크 확인
- Reader: 대중성·독자성·확장 가능성 검토
- Archivist: 프롬프트·버전·판정 근거 보존

## 프로젝트별 운영

목적, 독자, 장르, 분량, 제출물은 프로젝트마다 `CURRENT PROJECT`에서 교체합니다.
완료한 작품만 `THE SHELF`에 추가하고, 각 프로젝트의 원고·리서치·리뷰·프롬프트·개정 이력은 별도 폴더에 보존합니다.

## 저장소 구조

```text
.claude/agents/       역할별 서브 에이전트 정의
.claude/commands/     Lanterning 작업 안내
planning/             Gather·Design 산출물
drafts/               버전별 원고
reviews/              Dissect·Counsel·Reader 검토
research/             사실성·유사성 조사
logs/                 단계별 협업 기록
submission/           최종 출품용 패키지
site/                 LP Office와 프로젝트 서재
```

## 원칙

LP Office는 자동으로 일하는 척하지 않습니다. 창작자가 프로젝트를 선택하고 각 단계를 승인합니다.
AI가 만든 내용과 창작자가 결정한 내용을 구분해 기록하는 것이 이 프로토콜의 핵심입니다.
