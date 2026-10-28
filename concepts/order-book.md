---
type: concept
title: "주문장"
aliases: ["public order-book system", "순수경쟁매매 메커니즘"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "주문장(order book)은 거래소에서 주문이 전환·체결되는 곳이다(조건부지정가주문 설명)."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

주문장(order book)은 거래소에서 주문이 전환·체결되는 곳이다(조건부지정가주문 설명). <sup class="src-ref">원본 p.82</sup>

순수경쟁매매 메커니즘(pure auction mechanism)은 투자자가 다른 투자자들의 지정가주문 상황을 지켜보면서 주문을 제출하고, 시장조성인의 개입 없이 자동 매매체결시스템을 통해 투자자 간에 매매체결되는 방식이며 주문장제도(public order-book system)라고도 부른다. <sup class="src-ref">원본 p.89</sup>

## 왜 필요한가

세계 주요 주식시장 대부분이 한 종류의 거래 메커니즘만 채택하지 않고 기업 규모, 특성 등에 따라 여러 메커니즘을 혼용(hybrid market)한다. <sup class="src-ref">원본 p.89</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 순수경쟁매매 메커니즘을 쓰는 주요 거래시장으로 독일거래소(DB), LSE SETS 시스템, 유로넥스트, 미국 ECN(리트풀), 토론토증권거래소(TSX), 도쿄증권거래소(TSE), 한국거래소(KRX)가 꼽힌다. <sup class="src-ref">원본 p.89-90</sup>
- 조건부지정가주문은 상황에 따라 거래소 주문장에서 시장가주문으로 자동 전환되는 주문이다. <sup class="src-ref">원본 p.82</sup>
- 최우선매수/매도호가(BBO)는 해당 거래시장 주문장 내의 호가를 기준으로 한다. <sup class="src-ref">원본 p.84</sup>

## 관련

- [[limit-order]]
- [[bbo]]
- [[market-maker]]
- [[continuous-trading]]
- [[kcm-ch02]]
- [[competitive-trading]]
- [[conditional-order]]
- [[japan-exchange-group]]
- [[korea-exchange]]
