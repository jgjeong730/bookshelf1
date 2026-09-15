# LP Office — The Lantern Protocol

원고를 일곱 단계의 편집 회로에 통과시키는 AI 협업 집필실입니다.

**공방**: https://jgjeong730.github.io/bookshelf1/

## Lanterning

`The Lantern Protocol (LP)`는 하나의 원고를 서로 다른 편집 관점으로 비추는
**Seven-Stage Editorial Circuit**입니다.

```text
Gather → Design → Draft → Dissect → Counsel → Revise → Seal
```

`Dissect → Counsel → Revise`는 원고가 충분히 좋아질 때까지 반복합니다.

## 목적

성인 단편소설 공모전에 제출할 원고를 만들면서 다음 세 가지를 함께 증명합니다.

- 문학적 완성도 (50%)
- AI 활용의 독창성 및 협업 과정 (30%)
- 대중성 및 확장 가능성 (20%)

최종 제출물에는 원고와 함께 프롬프트 노트, 역할별 산출물, 초고부터 개정까지의
버전 이력을 보존합니다.

## 협업 원칙

LP Office는 현재 실시간 에이전트 실행을 가장하지 않습니다. 사람이 각 단계를 검토하고
다음 단계로 넘기는 협업 설계와 기록 보드입니다. AI는 이야기를 대신 결정하지 않고,
서로 다른 편집 관점으로 원고를 비추는 역할을 수행합니다.

## 구조

```text
site/
  index.html    LP Office 화면 (정적 HTML, 외부 JS 의존성 없음)
  .nojekyll     GitHub Pages가 Jekyll로 처리하지 않도록
  stories/      기존 이야기 아카이브
  reports/      기존 협업 기록
.github/workflows/
  pages.yml     site/ 를 GitHub Pages로 배포
```

## 로컬에서 보기

```bash
cd site && python3 -m http.server 8080
```

## 출품 패키지

- 단편소설 원고: 200자 원고지 50~100매
- 로그라인·기획 의도·인물·시놉시스
- 역할별 프롬프트와 산출물
- 초고 → 해부 → 자문 → 개정 이력
- AI와 창작자가 각각 결정한 내용의 기록
