---
type: concept
title: "HFT 활용 거래전략"
aliases: ["쿠오트-매칭", "스니핑", "핑잉", "유동성 추적", "사건 차익거래", "통계적 차익거래", "페어트레이딩", "교차시장거래"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "HFT 활용 거래전략은 CFTC and SEC(2010) 분류에 앙헬·해리스·스팻(2011) 등 여러 연구자의 방식을 종합·절충해 유동성 제공/시장조성, 차익거래, 유동성 추적, 추세의 네 가지로 구분된다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
HFT 활용 거래전략은 CFTC and SEC(2010) 분류에 앙헬·해리스·스팻(2011) 등 여러 연구자의 방식을 종합·절충해 유동성 제공/시장조성, 차익거래, 유동성 추적, 추세의 네 가지로 구분된다. <sup class="src-ref">원본 p.399</sup>
들여다보는 목적에 따라 분류가 달라져 정확히 하나의 유형에 속하게끔 묶기는 어렵다. <sup class="src-ref">원본 p.399</sup>

## 왜 필요한가
HFT 자체는 전략이 아니라 전략을 수행하는 방식이나 테크놀로지 수단이며, HFT 자체를 좋다 나쁘다 말할 수는 없고 대신 시장 공정성이나 효율성을 해치는 HFT 활용 전략을 찾아내 금하거나 그러한 전략으로 영업하는 HFT 증권회사를 규제해야 한다는 주장이 제기된다. <sup class="src-ref">원본 p.398</sup> <sup class="src-ref">원본 p.408</sup>

## 내용

### 시장 패러다임 변화 ([[kcm-ch11]]) (11장)
- 유동성 제공/시장조성 전략은 매수·매도 양방향으로 주문을 동시에 제출해 유동성을 제공하며 이익을 취하고, HFT 활용 거래전략에서 대부분(약 95%)을 차지한다. <sup class="src-ref">원본 p.399</sup>
- 이 전략의 HFT 증권회사는 매수·매도 스프레드와 maker-taker/taker-maker 수수료 체계에서 거래시장이 주는 리베이트를 수익으로 취할 수 있다. <sup class="src-ref">원본 p.399-400</sup>
- 차익거래 전략은 순간적 가격 차이를 이용하며 페어트레이딩, 교차시장거래, 사건 차익거래, 통계적 차익거래, 속도 차익거래를 포함한다. <sup class="src-ref">원본 p.400</sup>
- 유동성 추적 전략은 핑잉(소량의 유인용 주문)이나 스니핑(네트워크 트래픽 도청)으로 다른 투자자의 알고리즘 정보를 취합·복원하며 쿠오트-매칭(선행매매)이 대표적이고 상당히 약탈적인 것으로 평가된다. <sup class="src-ref">원본 p.400-401</sup>
- 추세 전략은 단기 모멘텀/뉴스 추적 전략과 latency arbitrage 전략으로 나뉘며, 모멘텀 촉발은 단기 모멘텀을 조작·촉발해 이익을 취하려는 약탈적 전략이다. <sup class="src-ref">원본 p.401</sup>
- 시장에 해악을 끼치는 일부 HFT 전략의 예로 quote-matching, 모멘텀 촉발, latency arbitrage 전략이 꼽힌다. <sup class="src-ref">원본 p.405</sup>

## 관련
- [[high-frequency-trading]]
- [[latency-arbitrage]]
- [[algorithmic-trading]]
- [[market-maker]]
- [[broker-dealer]]
- [[maker-taker-fee]]
