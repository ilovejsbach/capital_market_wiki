---
type: concept
title: "주문 제출 조건"
aliases: ["FOK", "IOC", "GTC", "fill-or-kill", "immediate-or-cancel", "good-till-cancelled"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "주문 제출 조건은 기본 주문유형에 덧붙여 투자자가 주문을 다양하게 제출할 수 있게 하는 체결조건(execution condition), 주문유효기간조건(validity constraint), 매매시간대유효조건(tr…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

주문 제출 조건은 기본 주문유형에 덧붙여 투자자가 주문을 다양하게 제출할 수 있게 하는 체결조건(execution condition), 주문유효기간조건(validity constraint), 매매시간대유효조건(trading restriction)이다. <sup class="src-ref">원본 p.83</sup>

## 왜 필요한가

세계 주요 주식거래시장은 이러한 조건을 덧붙여 투자자에게 편의를 제공한다. <sup class="src-ref">원본 p.83</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 체결조건의 예로 IOC(immediate-or-cancel, 즉시 충족할 수 있으면 전량이든 일부든 충족하고 나머지는 취소)와 FOK(fill-or-kill, 전량충족조건)가 있다. <sup class="src-ref">원본 p.83</sup>
- 주문유효기간조건의 예로 당일유효(Day)와 GTC(good-till-cancelled, 주문제출자가 직접 취소할 때까지 유효)가 있다. <sup class="src-ref">원본 p.83</sup>
- 매매시간대유효조건의 예로 개장 단일가매매에서만 유효(opening auction only)와 정규거래시간 중 발생하는 단일가매매 시간대에만 유효(auctions in main trading phase only)가 있다. <sup class="src-ref">원본 p.83</sup>

## 관련

- [[order-types]]
- [[market-order]]
- [[limit-order]]
- [[kcm-ch02]]
- [[execution-conditions]]
- [[call-auction]]
