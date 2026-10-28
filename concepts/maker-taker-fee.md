---
type: "concept"
title: "수수료 체계"
aliases: ["maker/taker 수수료", "maker-taker"]
books: ["kcm"]
status: "draft"
updated: "2026-10-20"
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "maker-taker 수수료 체계는 유동성을 제공하는 거래자(지정가주문 제공자)가 인센티브로 리베이트를 받고, 유동성을 취하는 거래자(시장가주문 제공자)는 이보다 조금 비싼 수수료를 치르는 체계이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

maker-taker 수수료 체계는 유동성을 제공하는 거래자(지정가주문 제공자)가 인센티브로 리베이트를 받고, 유동성을 취하는 거래자(시장가주문 제공자)는 이보다 조금 비싼 수수료를 치르는 체계이다. <sup class="src-ref">원본 p.137</sup>

## 왜 필요한가

미국 거래시장은 저마다 이질적 수수료 체계를 갖추고 유동성 경쟁을 벌인다. <sup class="src-ref">원본 p.137</sup>

이 수수료 체계가 구조적으로 이해상충이나 공정성 침해 가능성을 내포한다는 점이 문제로 지적된다. <sup class="src-ref">원본 p.137</sup>

## 내용

### 주식시장구조 (3장)

- SEC는 리베이트가 유동성, 주문회송, 시장 간 경쟁 등에 끼치는 영향을 파악해 개선하려 했고, 2012년부터 관련 논의를 시작해 2018년 3월 '거래수수료 맛보기 프로그램'을 제안했고(2018-03-14), 2018년 12월 19일 승인(Rel. 34-84875)했으며 시행은 2019년 4월 22일이었다. <sup class="src-ref">원본 p.137</sup> <sup class="src-ref">원본 p.335</sup> (정정: SEC, 2018-12-19)
- 주요 정규거래시장(NYSE, Nasdaq, Cboe Global Markets)이 SEC를 제소했고, 2020년 6월 법원이 SEC 시험운용을 권한 밖 행위라고 판결하며 맛보기 프로그램은 즉각 효력을 상실했다. <sup class="src-ref">원본 p.137</sup>
- 캐나다의 Trade-at Rule 시행 뒤 소매투자자의 가격개선효과가 나타나려면 maker-taker 수수료 체계가 먼저 개선되어야 한다고 코머튼-포드·말리노바·팍(Comerton-Forde, Malinova, and Park, 2018)은 주장한다. <sup class="src-ref">원본 p.136</sup>
- 소매주문 회송의 주문흐름 대가(PFOF) 리베이트는 거래소가 활용하는 maker-taker/taker-maker 수수료와 같은 성격이다. <sup class="src-ref">원본 p.133</sup>

### 미국자본시장 주요 법제 (9장)
- maker-taker 체계에서 유동성 제공(지정가주문) 거래자는 리베이트를 받고 유동성 소비(시장가주문) 거래자는 이보다 조금 비싼 수수료를 내며 거래시장은 차이를 수익으로 가져간다. <sup class="src-ref">원본 p.334</sup>
- taker-maker(inverse pricing)는 리베이트와 수수료 구조가 반대이며 시장 하강 국면의 투자자에게 적합한 체계로 평가된다. <sup class="src-ref">원본 p.334</sup>
- 투자자는 리베이트에 구조적 문제가 있다고 주장했고 거래시장은 정상적인 보상이라고 반박했다. <sup class="src-ref">원본 p.334</sup>
- SEC의 Transaction Fee Pilot Program(Rule 610T)은 2020년 6월 연방항소법원이 SEC 권한 남용이라며 무효로 했다. <sup class="src-ref">원본 p.335</sup>

### 시장구조 변화 (12장)

- Maker-taker 체계에서는 유동성을 제공(지정가주문 제출)하는 거래자가 리베이트를 받고 유동성을 소비하는 거래자는 이보다 좀 비싼 수수료를 내며 거래시장은 그 차이를 수익으로 가져간다. taker-maker 체계는 반대이다. <sup class="src-ref">원본 p.456</sup>
- SEC는 Transaction Fee Pilot Program을 2019년 4월 하순부터 2023년 말까지 시행할 예정이었으나 거래시장이 고소했고 2020년 6월 연방항소법원이 권한 남용을 이유로 SEC 패소 판결을 내렸다. <sup class="src-ref">원본 p.456</sup>
- maker-taker/taker-maker 수수료 체계는 이제 거래시장의 전략상 권리로 인정받으며 견제 없이 시행되고 있는 것으로 지적된다. <sup class="src-ref">원본 p.456</sup>
- 말리노바·팍(2015)의 TSX 분석에 따르면 소액투자자가 손해를 보지는 않고 제도 시행 2개월 후 순거래비용은 되레 감소했다. <sup class="src-ref">원본 p.456</sup>

## 관련

- [[payment-for-order-flow|주문흐름 대가]]
- [[trade-at-rule|Trade-at Rule]]
- [[market-microstructure|시장미시구조]]
- [[sec|증권거래위원회]]
- [[kcm-ch03|3장 주식시장구조]]
- [[limit-order]]
- [[market-order]]
