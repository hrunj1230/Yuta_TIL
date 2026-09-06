---
type: concept
created: 2026-08-22
updated: 2026-08-22
sources:
  - "[[sources/2026_08_18_2c4c13]]"
tags: [term]
aliases:
  - "plugin"
  - "플러그인"
  - "plugins"
generation_complete: true
---


# plugins

## 정의
plugins는 [[concepts/skills|skills]], [[concepts/에이전트|에이전트]], [[concepts/hooks|Hooks]], [[concepts/mcp|MCP]] 같은 자원을 하나의 설치 및 업데이트 단위로 묶은 패키지이다. 개인이나 팀이 만든 에이전트 기능을 조직 내에서 공유하고 재사용 가능하게 배포하는 상위 구성요소로 사용된다.

## 주요 특징
- 여러 자원을 단일 패키지로 묶어 설치와 업데이트를 단순화한다.
- [[concepts/skills|skills]]와 [[concepts/hooks|Hooks]]처럼 서로 다른 기능 단위를 함께 배포할 수 있다.
- 개인이 만든 [[concepts/에이전트|에이전트]] 기능을 팀이나 조직 단위로 공유하는 데 적합하다.
- 에이전트 기반 워크플로우를 표준화하고 확산하는 배포 단위로 활용된다.
- 단일 기능이 아니라 관련 자원들의 묶음이라는 점에서 개별 [[concepts/skills|skills]]나 [[concepts/hooks|Hooks]]보다 상위 개념이다.

## 응용
plugins는 특정 작업에 필요한 [[concepts/skills|skills]], 이벤트 자동화를 위한 [[concepts/hooks|Hooks]], 외부 도구 연동을 위한 [[concepts/mcp|MCP]], 그리고 관련 [[concepts/에이전트|에이전트]] 구성을 함께 묶어 배포할 때 사용된다. 이를 통해 팀은 반복적으로 사용하는 에이전트 기능을 공통 패키지로 관리하고, 구성원 간 동일한 워크플로우를 쉽게 설치·업데이트·재사용할 수 있다.

## 관련 개념
- [[concepts/skills|skills]]
- [[concepts/hooks|Hooks]]
- [[concepts/mcp|MCP]]
- [[concepts/에이전트|에이전트]]

## 관련 엔티티
없음

## 소스 내 언급
- [[sources/2026_08_18_2c4c13]]: 소스에서 plugins는 팀원들과 공유할 수 있는 설치 및 업데이트 단위로 언급되며, 여러 에이전트 관련 자원을 하나의 패키지로 묶는 개념으로 설명된다.

## 출처 언급

- "에이전트 - 역할 특화
mcp 에이전트를 활용하여 외부와 연결
plugin 팀원들과 공유" (에이전트 - 역할 특화
mcp 에이전트를 활용하여 외부와 연결
plugin 팀원들과 공유) — [[Today I Learn/2026_08_18|2026_08_18]]
- "plugins
skills ,agent ,hook, mcp 
자원을 하나의 설치, 업데이트 단위로 묶은 패키지" (plugins
skills ,agent ,hook, mcp 
자원을 하나의 설치, 업데이트 단위로 묶은 패키지) — [[Today I Learn/2026_08_18|2026_08_18]]
- "프롬프트 -> rules.md claude.md -> skills,hooks -> mcp" (프롬프트 -> rules.md claude.md -> skills,hooks -> mcp) — [[Today I Learn/2026_08_18|2026_08_18]]