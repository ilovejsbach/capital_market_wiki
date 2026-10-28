---
type: concept
title: "최우선호가(BBO)"
aliases: ["BBO", "best buy or offer"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "최우선호가(BBO: best buy or offer)는 해당 거래시장 주문장 내의 최우선매수/매도호가이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

최우선호가(BBO: best buy or offer)는 해당 거래시장 주문장 내의 최우선매수/매도호가이다. <sup class="src-ref">원본 p.84</sup>

## 왜 필요한가

미드포인트 페그주문에서 투자자의 지정가는 BBO를 계속 추적하며 그에 맞춰 자동으로 조정·결정된다. <sup class="src-ref">원본 p.84</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 개별경쟁매매는 가장 높은 가격의 매수호가(최우선매수호가)와 가장 낮은 가격의 매도호가(최우선매도호가)가 합치할 때 약정가격으로 매매체결 하는 방식이다. <sup class="src-ref">원본 p.88</sup>
- 시장 간 싹쓸이 주문(ISO)은 특정 거래시장 A에서 현재 BBO와 자신의 (대량)주문 지정가 사이에 걸쳐 있는 호가를 자동으로 싹쓸이한다. <sup class="src-ref">원본 p.84</sup>
- 런던증권거래소의 패시브 온리 주문은 LSE 주문장 내 BBO보다 개선된 가격대에서만 체결을 지원하며 BBO는 소비하지 않는다. <sup class="src-ref">원본 p.85</sup>

## 관련

- [[order-book]]
- [[best-execution]]
- [[limit-order]]
- [[market-maker]]
- [[kcm-ch02]]
- [[intermarket-sweep-order]]
