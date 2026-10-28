---
type: metric
title: "CDS 스프레드"
aliases: []
books:
- "kcm"
symbols:
- "CDS 프리미엄"
- "CDS 스프레드"
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["지표"]
description: "보장수수료는 CDS 프리미엄(수수료율)에 거래금액을 곱한 금액이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의 수식

- 보장수수료는 CDS 프리미엄(수수료율)에 거래금액을 곱한 금액이다. <sup class="src-ref">원본 p.44</sup>
- 각주는 CDS 프리미엄은 절대 금리를, CDS 스프레드는 CDS 프리미엄과 무위험채권수익률(한국에서는 국고채수익률)의 차이를 의미한다고 구분하면서 본문에서는 같은 것으로 볼 수 있다고 한다. <sup class="src-ref">원본 p.44</sup>

## 기호

- CDS 프리미엄은 보장수수료율이다. <sup class="src-ref">원본 p.44</sup>
- 기준스프레드는 투자등급 연 100bp(1%), 투기등급 연 500bp(5%)로 표준화되어 있고 시장스프레드는 시장에서 형성되는 CDS 스프레드이다. <sup class="src-ref">원본 p.45</sup>

## 해석

- 신용도가 높아 부도 가능성이 작을수록 CDS 프리미엄은 하락하며, 스왑베이시스와 함께 외환 건전성을 나타내는 주요 지표로 활용된다. <sup class="src-ref">원본 p.44</sup> <sup class="src-ref">원본 p.47</sup>

## 쓰인 곳

- 시장스프레드가 기준스프레드 이상이면 매수자가 매도자에게 그 차익을 분기별로 나눠 선지급한다. <sup class="src-ref">원본 p.45</sup>

## 관련

- [[kcm-ch01]]
- [[credit-default-swap]]
