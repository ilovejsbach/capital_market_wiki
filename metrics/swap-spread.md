---
type: metric
title: "스왑 스프레드"
aliases: []
books:
- "kcm"
symbols:
- "스왑금리"
- "무위험채권수익률"
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["지표"]
description: "스왑금리는 고정금리(IRS 금리)이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의 수식

- (이자율)스왑 스프레드는 스왑금리와 무위험채권수익률의 차이이며 한국에서는 3년 만기 스왑금리와 3년 만기 국고채수익률 차이를 주로 사용한다. <sup class="src-ref">원본 p.42</sup>

## 기호

- 스왑금리는 고정금리(IRS 금리)이다. <sup class="src-ref">원본 p.42</sup>
- 무위험채권수익률은 한국에서 국고채수익률이 쓰인다. <sup class="src-ref">원본 p.42</sup>

## 해석

- 스왑딜러가 시장금리 하락을 예상하면 IRS 리시브 수요 증가로 스왑금리가 하락하면서 스왑 스프레드가 감소하고, 상승을 예상하면 IRS 페이 수요 증가로 스왑금리가 상승하면서 스프레드가 확대한다고 설명한다. <sup class="src-ref">원본 p.43</sup>

## 쓰인 곳

- 모든 스왑거래에서 스왑 스프레드란 해당 스왑(예: 이자율, 통화, 신용부도) 금리와 무위험채권수익률의 차이를 의미한다. <sup class="src-ref">원본 p.42-43</sup>

## 관련

- [[kcm-ch01]]
- [[interest-rate-swap]]
