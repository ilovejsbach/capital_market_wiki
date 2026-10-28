---
type: concept
title: "최우선호가 무시"
aliases: ["trade through"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "Trade-through는 거래시장 A가 NBBO를 게시했는데도 이를 무시하고 거래시장 B에서 거래하는 상황이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
Trade-through는 거래시장 A가 NBBO를 게시했는데도 이를 무시하고 거래시장 B에서 거래하는 상황이다. <sup class="src-ref">원본 p.294</sup>

## 왜 필요한가
Reg NMS는 NBBO로 체결해야 하는 의무를 두어 trade-through를 금지하며, 이를 못 하면 즉시 NBBO를 게시한 거래시장에 회송해야 한다. <sup class="src-ref">원본 p.294</sup>

## 내용
### 미국자본시장 주요 법제 (9장)
- Order Protection Rule(Rule 611)은 일명 "Trade-through Rule"이라 불린다. <sup class="src-ref">원본 p.293-294</sup>
- 〈표 9-1〉에 따르면 ITS Plan(1979.9)은 1981년 개정을 통해 "Trade-through Rule"을 승인했다. <sup class="src-ref">원본 p.289</sup>
- 9개 예외를 두어 trade-through를 허용하며, 가장 중요한 예외는 ISO 사용과 1초 시간 창이다. <sup class="src-ref">원본 p.294</sup>
- 예외에는 단일가매매로 가격을 결정하는 경우, 보호호가가 크로쓰된 경우, VWAP 등 벤치마크 가격이나 고객 지정가격에 체결해야 하는 경우도 있다. <sup class="src-ref">원본 p.295</sup>
- Flash Crash 때 NYSE의 LRP가 발동하자 OPR이 적용되지 않아 NYSE로 올 주문이 다른 거래시장으로 회송되었다. <sup class="src-ref">원본 p.309</sup>

## 관련
- [[order-protection-rule]]
- [[intermarket-sweep-order]]
- [[protected-quote]]
- [[kcm-ch09]]
- [[nbbo]]
- [[nyse]]
