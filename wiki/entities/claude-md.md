---
type: entity
created: 2026-08-22
updated: 2026-08-22
sources:
  - "[[sources/2026_08_18_2c4c13]]"
tags: [other]
aliases:
  - "claude.md"
  - "CLAUDE.md"
  - "Claude 지침 파일"
generation_complete: true
---


# claude.md

## 설명
claude.md는 소스에서 [[entities/rules-md|rules.md]]와 함께 프롬프트와 실행 기능 사이에 놓이는 지침 파일로 언급된다. Claude 기반 에이전트 환경에서 프로젝트별 규칙, 작업 방식, 응답 형식 등을 지정하는 문서로 해석된다. 소스는 [[concepts/프롬프트|프롬프트]]가 단순 입력에 머무르지 않고 claude.md 같은 지침 파일을 거쳐 실행 기능으로 연결된다고 설명한다. 따라서 claude.md는 에이전트의 행동을 안정적으로 제어하고 반복 가능한 [[concepts/워크-플로우|워크 플로우]]를 만드는 데 중요한 구성 요소로 볼 수 있다.

## 관련 엔티티
- [[entities/rules-md|rules.md]]

## 관련 개념
- [[concepts/프롬프트|프롬프트]]
- [[concepts/워크-플로우|워크 플로우]]

## 소스 내 언급
- [[sources/2026_08_18_2c4c13]]: “claude.md는 소스에서 rules.md와 함께 프롬프트와 실행 기능 사이에 놓이는 지침 파일로 언급된다.”
- [[sources/2026_08_18_2c4c13]]: “소스는 프롬프트가 단순 입력에 머무르지 않고 claude.md 같은 지침 파일을 거쳐 skills, hooks, mcp로 연결된다고 설명한다.”

## 출처 언급

- "대화 -> 지침 -> 워크 플로우 -> 도구" (대화 -> 지침 -> 워크 플로우 -> 도구) — [[Today I Learn/2026_08_18|2026_08_18]]
- "프롬프트 -> rules.md claude.md -> skills,hooks -> mcp" (프롬프트 -> rules.md claude.md -> skills,hooks -> mcp) — [[Today I Learn/2026_08_18|2026_08_18]]