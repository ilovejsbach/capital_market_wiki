---
type: concept
title: "사이드카"
aliases: []
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "사이드카(sidecar)는 서킷브레이커와 유사한 시장안정화장치로, 한국에 특수하게 존재하는 제도이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

사이드카(sidecar)는 서킷브레이커와 유사한 시장안정화장치로, 한국에 특수하게 존재하는 제도이다. <sup class="src-ref">원본 p.95</sup>

## 왜 필요한가

선물시장 영향력이 현물시장에 과도하게 미치지 않게끔 설계한 장치로, 관련 종목에 동시 적용하지만 강도는 서킷브레이커보다 많이 약하다. <sup class="src-ref">원본 p.95</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 코스피200지수[코스닥150지수] 선물가격이 5%[6%] 이상 급등락해 1분간 지속하면 프로그램매매 호가 효력을 5분간 일시 정지한다. <sup class="src-ref">원본 p.95</sup>

### 시장미시구조 (15장)

- 선물시장이 급등락할 때 해당 현물시장의 프로그램매매 호가 효력을 5분간 정지하는 제도이다. 코스피200선물은 ±5%, 코스닥150선물은 ±6% 이상(+코스닥150지수 전일 대비 ±3% 이상) 변동해 1분 이상 지속되면 발동한다. <sup class="src-ref">원본 p.546</sup> <sup class="src-ref">원본 p.548</sup>
- 프로그램매매만 제한하고 직접매매는 허용하므로 효과는 제한적이며, 이를 고안한 미국에서는 일찌감치 폐지했다. <sup class="src-ref">원본 p.546</sup>
- 시장별 1일 1회만 발동하며 장종료 40분 전 이후에는 발동하지 않는다. <sup class="src-ref">원본 p.548</sup>

## 관련

- [[circuit-breaker]]
- [[market-stabilization-measures]]
- [[kcm-ch02]]
- [[program-trading]]

## 확장 문서

- [[korea-market-stabilizers]] — 한국 시장안정장치 현황과 2026년 발동 이력
