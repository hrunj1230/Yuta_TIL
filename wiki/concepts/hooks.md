---
type: concept
created: 2026-08-22
updated: 2026-08-22
sources:
  - "[[sources/2026_08_18_2c4c13]]"
tags: [method]
aliases:
  - "hook"
  - "Hooks"
  - "훅"
generation_complete: true
---


# Hooks

## 정의
Hooks는 특정 이벤트가 발생했을 때 미리 정해진 작업을 자동으로 실행하는 메커니즘이다. 개발 워크플로우에서는 코드 수정, 저장, 커밋 등의 이벤트를 계기로 줄맞춤 같은 반복 작업을 자동화하는 방식으로 활용된다.

## 주요 특징
- 이벤트 발생을 조건으로 작업을 자동 실행한다.
- 반복적이고 규칙적인 개발 작업을 자동화하는 데 적합하다.
- 코드 수정 시 자동 줄맞춤처럼 사용자의 명시적 실행 없이 동작할 수 있다.
- 이벤트 발생 조건과 실행 설정은 [[entities/setting-json|setting-json]]에서 다루는 것으로 설명된다.
- [[concepts/skills|skills]]가 명시적 작업 능력을 정의한다면, Hooks는 해당 작업을 이벤트 기반으로 자동 실행하는 방식이다.
- [[concepts/plugins|plugins]]의 구성요소로 묶여 확장 기능의 일부로 동작할 수 있다.

## 응용
- 코드 변경 시 자동 줄맞춤 또는 포맷팅 실행
- 파일 저장, 수정, 배포 전 단계에서 반복 작업 자동 수행
- 개발자가 직접 명령하지 않아도 특정 조건에서 도구나 작업 실행
- [[concepts/에이전트|에이전트]] 기반 시스템에서 이벤트에 반응하는 자동 작업 흐름 구성

## 관련 개념
- [[concepts/skills|skills]]
- [[concepts/plugins|plugins]]
- [[concepts/에이전트|에이전트]]

## 관련 엔티티
- 없음

## 소스 내 언급
- [[sources/2026_08_18_2c4c13]]: 제공된 개념 요약에 따르면 Hooks는 특정 이벤트가 발생했을 때 자동으로 작업을 실행하는 메커니즘으로 설명된다.

## 출처 언급

- "hook - 코드를 고칠때마다 자동으로 줄맞춤" (hook - 코드를 고칠때마다 자동으로 줄맞춤) — [[Today I Learn/2026_08_18|2026_08_18]]
- "Hooks
이벤트 발생 setting.json" (Hooks
이벤트 발생 setting.json) — [[Today I Learn/2026_08_18|2026_08_18]]
- "plugins
skills ,agent ,hook, mcp 
자원을 하나의 설치, 업데이트 단위로 묶은 패키지" (plugins
skills ,agent ,hook, mcp 
자원을 하나의 설치, 업데이트 단위로 묶은 패키지) — [[Today I Learn/2026_08_18|2026_08_18]]