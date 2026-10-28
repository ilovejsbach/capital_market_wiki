---
type: concept
title: "시장가주문"
aliases: ["market order"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "시장가주문(market order)은 투자자가 가격을 지정하지 않고 자신이 거래시장에 주문을 제출할 때 형성된 가격으로 즉시 체결을 원하는 주문이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

시장가주문(market order)은 투자자가 가격을 지정하지 않고 자신이 거래시장에 주문을 제출할 때 형성된 가격으로 즉시 체결을 원하는 주문이다. <sup class="src-ref">원본 p.82</sup>

## 왜 필요한가

시장가주문은 가격을 정하지 않고 지금 형성돼 있는 가격에 가능한 빨리 체결을 바라는 주문이므로, 거래시장이 시장가주문을 지정가주문에 우선해 체결한다. <sup class="src-ref">원본 p.87</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 시장가주문, 지정가주문, 조건부지정가주문은 세계 거의 모든 주식거래시장이 기본으로 제공하는 전통적인 주문유형이다. <sup class="src-ref">원본 p.82</sup>
- 즉시 체결하려면 시장가주문을 제출하며, 매도호가 1단계 또는 매수물량이 많으면 2, 3단계를 훑으며 체결되고 스프레드만큼 비용을 지급한다(그림 2-2, 번호 있음, 레코드 없음, 쪽 인용). <sup class="src-ref">원본 p.83</sup>
- 미국에서는 시장가주문과 거의 같은 형태의 브로커 시장가주문(marketable limit order)을 활발히 사용하며, 시장가의 시점이 다르다. <sup class="src-ref">원본 p.82</sup>
- KRX는 근 30여 년간 시장가주문, 지정가주문, 조건부지정가주문 외에 이렇다 할 기본 주문유형을 추가하지 않았다. <sup class="src-ref">원본 p.87</sup>

## 관련

- [[limit-order]]
- [[conditional-order]]
- [[order-types]]
- [[matching-priority]]
- [[kcm-ch02]]
