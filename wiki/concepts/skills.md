---
type: concept
created: 2026-08-22
updated: 2026-08-22
sources:
  - "[[sources/2026_08_18_2c4c13]]"
tags: [method]
aliases:
  - "skill"
  - "Skills"
  - "스킬"
generation_complete: true
---


# skills

## 정의
skills는 [[concepts/에이전트|에이전트]] 환경에서 특정 작업을 정해진 형식과 절차에 따라 수행하도록 정의하는 재사용 가능한 기능 단위이다. 예를 들어 정해진 양식으로 git PR을 생성하거나, `/weekly-report`처럼 이번 주 커밋과 작업 기록을 모아 보고서 초안을 작성하는 방식으로 활용된다.

## 주요 특징
- 특정 작업을 반복 가능하고 일관된 방식으로 수행하도록 캡슐화한다.
- 작업 결과의 형식, 절차, 참고 기준을 명시해 [[concepts/에이전트|에이전트]]의 실행 품질을 높인다.
- 수동 호출과 자동 호출을 모두 지원할 수 있다.
- 자동 호출은 단순 키워드 매칭이 아니라 `skills.md`의 설명을 참조해 필요한 skill을 선택하는 방식으로 정리된다.
- [[concepts/hooks|Hooks]] 및 [[concepts/plugins|plugins]]와 함께 개발 생산성을 높이는 핵심 구성요소로 사용된다.
- 팀이나 프로젝트에서 반복되는 작업 방식을 공유 가능한 지식 단위로 만들 수 있다.

## 응용
- 정해진 형식으로 git PR 제목, 본문, 체크리스트를 작성한다.
- [[concepts/weekly-report|/weekly-report]]처럼 커밋 기록과 작업 로그를 모아 주간 보고서 초안을 만든다.
- 코드 리뷰, 릴리스 노트, 작업 요약 등 반복적인 개발 문서 작업을 표준화한다.
- 프로젝트별 규칙을 반영한 자동화된 에이전트 작업 흐름을 구성한다.
- [[concepts/hooks|Hooks]], [[concepts/plugins|plugins]]와 결합해 개발 환경 내 자동화와 품질 관리를 강화한다.

## 관련 개념
- [[concepts/에이전트|에이전트]]
- [[concepts/hooks|Hooks]]
- [[concepts/plugins|plugins]]
- [[concepts/weekly-report|/weekly-report]]

## 관련 엔티티
관련 엔티티 없음

## 소스 내 언급
- 출처: [[sources/2026_08_18_2c4c13]]
  - “skills는 에이전트 환경에서 특정 작업을 정해진 형식으로 수행하도록 만드는 기능 단위로 설명된다.”
  - “정해진 format으로 git PR을 생성하는 사례와 weekly-report처럼 이번 주 커밋과 작업 기록을 모아 초안을 작성하는 사례가 언급된다.”
  - “호출 방식은 수동 호출과 자동 호출이 있으며, 자동 호출은 단순 키워드 방식이 아니라 skills.md의 description을 참조해 이루어진다고 정리된다.”

## 출처 언급

- "skill 정해진 format 으로 git pr 생성" (skill 정해진 format 으로 git pr 생성) — [[Today I Learn/2026_08_18|2026_08_18]]
- "skills 많이 만들어 보기

/weekly-report
이번주 커밋과 작업 기록 모으고 초안작성 등등.." (skills 많이 만들어 보기

/weekly-report
이번주 커밋과 작업 기록 모으고 초안작성 등등..) — [[Today I Learn/2026_08_18|2026_08_18]]
- "skills
수동호출 /skills-name
자동호출 -> skills.md 에 description 을 참조해 자동호출 
키워드 방식이 아니다" (skills
수동호출 /skills-name
자동호출 -> skills.md 에 description 을 참조해 자동호출 
키워드 방식이 아니다) — [[Today I Learn/2026_08_18|2026_08_18]]