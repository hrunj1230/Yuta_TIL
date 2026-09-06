---
type: concept
created: 2026-08-22
updated: 2026-08-22
sources:
  - "[[sources/2026_08_18_2c4c13]]"
tags: [standard]
aliases:
  - "model context protocol"
  - "mcp"
  - "MCP"
generation_complete: true
---


# MCP

## 정의
MCP는 `model context protocol`로 풀어 쓰이는 표준으로, [[concepts/에이전트|에이전트]]를 외부 시스템과 연결하기 위한 프로토콜이다. 에이전트가 단독 대화에 머무르지 않고 업무 시스템, 코드 저장소, 지식 기반, 장애 알림 시스템 등과 상호작용하도록 하는 연결 계층으로 설명된다.

## 주요 특징
- [[concepts/에이전트|에이전트]]와 외부 시스템 사이의 상호작용을 가능하게 하는 프로토콜이다.
- 업무 시스템, 코드 저장소, 지식 기반, 장애 알림 시스템 등 다양한 외부 자원을 연결할 수 있다.
- 에이전트가 단순 응답을 넘어 실제 업무 대행, 요약, 장애 분석 같은 작업을 수행하도록 돕는다.
- [[concepts/plugins|plugins]], [[concepts/skills|skills]], [[concepts/Hooks|Hooks]], [[concepts/에이전트|에이전트]]와 함께 설치·업데이트 가능한 패키지 구성요소로 언급된다.

## 응용
MCP는 에이전트 기반 시스템이 외부 도구와 데이터를 활용해야 하는 상황에 적용된다. 예를 들어 [[entities/boost-mcp|boost-mcp]]는 업무 대행과 외부 시스템 연동 사례로 볼 수 있고, [[entities/boost-kb|boost-kb]]와 결합하면 지식 기반 조회와 요약에 활용될 수 있다. [[entities/troubleshooter-mcp|troubleshooter-mcp]]는 장애 알림이나 운영 정보를 분석하여 문제 해결을 지원하는 용도로 사용될 수 있다.

## 관련 개념
- [[concepts/에이전트|에이전트]]
- [[concepts/plugins|plugins]]
- [[concepts/skills|skills]]
- [[concepts/Hooks|Hooks]]

## 관련 엔티티
- [[entities/boost-mcp|boost-mcp]]
- [[entities/boost-kb|boost-kb]]
- [[entities/troubleshooter-mcp|troubleshooter-mcp]]

## 소스 내 언급
- [[sources/2026_08_18_2c4c13]]: "model context protocol"
- [[sources/2026_08_18_2c4c13]]: "boost-mcp"
- [[sources/2026_08_18_2c4c13]]: "troubleshooter - mcp"

## 출처 언급

- "프롬프트 -> rules.md claude.md -> skills,hooks -> mcp" (프롬프트 -> rules.md claude.md -> skills,hooks -> mcp) — [[Today I Learn/2026_08_18|2026_08_18]]
- "MCP
model context protocol
에이전트 -> mcp -> 외부 시스템" (MCP
model context protocol
에이전트 -> mcp -> 외부 시스템) — [[Today I Learn/2026_08_18|2026_08_18]]
- "mcp로 연결해서 대신 업무나 요약 boost-mcp
boost-kb" (mcp로 연결해서 대신 업무나 요약 boost-mcp
boost-kb) — [[Today I Learn/2026_08_18|2026_08_18]]