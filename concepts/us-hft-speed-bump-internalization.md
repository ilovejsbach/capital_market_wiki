---
type: "concept"
title: "미국 장외 체결 비중·IEX 속도 지연·딜러 규칙"
aliases: ["미국 고빈도거래 규제", "IEX speed bump", "미국 내부체결 비중", "딜러 규칙 무효화", "Rule 15c3-5"]
layer: "expansion"
status: "draft"
as_of: "2026-10"
updated: "2026-10-26"
extends: ["high-frequency-trading", "speed-bump", "internalization"]
research: "us-market-structure"
tags: ["개념", "확장"]
description: "이 문서는 미국 주식시장 구조 가운데 확인된 사실이 있는 부분만 다룬다. 장외(off-exchange) 체결 비중, IEX의 속도 지연 장치, 고빈도 유동성공급자를 딜러로 등록시키려던 규칙의 무효화, 시장접근규칙(…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

> [!note] 책 밖 확장 문서
> 이 문서는 책 본문이 아니라 웹의 공식 자료를 조사해 덧붙인 확장 문서입니다. 기준일은 2026-10입니다. 근거는 문서 끝의 출처 목록에 있고, 책에서 온 문장에는 `원본 p.N`이 붙습니다.

## 범위

이 문서는 미국 주식시장 구조 가운데 확인된 사실이 있는 부분만 다룬다. 장외(off-exchange) 체결 비중, [[investors-exchange-iex|IEX]]의 속도 지연 장치, 고빈도 [[liquidity-provider|유동성공급자]]를 딜러로 등록시키려던 규칙의 무효화, 시장접근규칙(Rule 15c3-5), [[trading-venue|거래소]]의 소매 대응 상품이다. 고빈도거래 일반론과 전략은 책 문서 [[high-frequency-trading]]·[[hft-trading-strategies]]에 있다.

## 거래량과 장외 체결 비중

- **거래량**: Cboe 집계에 따르면 2025년 미국 주식 일평균 거래량은 전년 대비 44.6% 증가한 176억 주였고 일평균 거래대금은 1.1조 달러(43.3% 증가)였다. 최고 거래일은 2025년 4월 9일로 309.8억 주, 1.86조 달러였다. <sup class="src-ref">출처 1</sup>
- **장외 비중**: Cboe 집계 기준 2025년 전체 TRF(장외 보고) 점유율은 총 통합거래량의 50.6%로 전년보다 361bp 늘어 처음으로 절반을 넘었다. TRF 거래량 중 [[alternative-trading-system|ATS]] 비중은 18.7%, 주 거래 딜러(내부체결 등)가 81.3%였다. <sup class="src-ref">출처 1</sup> [[trade-reporting-facility|TRF]]는 장외 체결이 보고되는 곳이다.
- **2026년**: Cboe 월간 브리핑은 2026년 7월 장외(off-exchange) 비중을 50.1%로 전했다. <sup class="src-ref">출처 2</sup>

Cboe는 경쟁 거래소 운영자이므로 이 수치는 Cboe 자체 집계다. 정의(총 통합거래량 대비 TRF)가 다른 집계의 '장외 비중'과 다를 수 있어 직접 비교하면 안 된다. 용어도 TRF와 off-exchange가 혼용되어 있어 같은 기준으로 이어진 수치인지 확인하지 못했다.

## 거래소의 소매 대응 상품

Cboe는 2025년 BYX의 RPI(소매가격개선) 주문 체결량이 6.95억 주(전년 대비 68% 증가)였고 정기 경매(Periodic Auctions) 거래량이 109% 증가했다고 밝혔다. <sup class="src-ref">출처 1</sup> 이 상품들을 장외 내부체결에 대한 거래소의 대응으로 볼지는 해석의 문제이며 이 문서는 판단하지 않는다.

## IEX와 속도 지연(speed bump)

- **장치**: IEX의 speed bump는 입력 주문·메시지에 350마이크로초 지연을 주며, 현재 약 44마일의 코일 광케이블로 구현된다. 2024년 주 데이터센터를 옮기기 전에는 38마일이었고 같은 지연을 유지하려고 늘렸다. 목적은 다른 지연 없는 시장 데이터를 반영해 가격을 갱신할 시간을 확보하는 것이다. <sup class="src-ref">출처 3</sup>
- **IEX Signal**: Crumbling Quote Indicator는 전국 최우선 매수호가 하락 또는 매도호가 상승 가능성을 예측하며, 켜지면 2밀리초 또는 가격 변동 시까지 유지된다. D-Peg·D-Limit 주문이 이 신호를 쓰고, D-Limit은 신호가 켜지면 한 틱 바깥으로 재호가한다. <sup class="src-ref">출처 3</sup>
- **거래소 승인**: [[sec|SEC]]는 2016년 6월 17일 IEX의 거래소 등록을 승인하면서 소폭 지연(speed bump)이 있는 호가를 [[protected-quote|보호호가]]로 인정하는 해석을 함께 발표했다. <sup class="src-ref">출처 4</sup> 1밀리초 미만 지연을 de minimis로 본다는 설명은 언론 보도에 근거하며 SEC 해석 원문은 직접 열람하지 못했다.

## 딜러 규칙 무효화

SEC의 '딜러 규칙'(Rule 3a5-4, 3a44-2)은 고빈도 유동성공급자 등을 딜러로 등록시키려던 안이었다. 텍사스 북부 연방지방법원이 2024년 11월 이 규칙을 권한 초과로 무효화했고(날짜 표기가 자료마다 달라 월까지만 쓴다), SEC는 항소를 냈다가 2025년 2월 자진 취하했다. <sup class="src-ref">출처 5</sup> 따라서 이 규칙은 효력이 없다.

## 시장접근규칙(Rule 15c3-5)

SEC는 2010년 11월 3일 Rule 15c3-5를 채택해 시장접근을 제공하는 브로커·딜러에게 위험관리 통제를 요구했다. 2010년 11월 15일 연방공보에 게재되었고 2011년 1월 14일 발효했으며 준수일은 2011년 7월 14일이다. 2011년 6월 30일 릴리스가 채권 관련 요건과 15c3-5(c)(1)(i)에 한해 준수일을 2011년 11월 30일로 연장했다. <sup class="src-ref">출처 6</sup> 2026년 6월 제안된 [[order-protection-rule|Rule 611]] 폐지안은 보호호가를 인용하는 이 규칙의 후속 수정도 포함한다. 제안 단계다. <sup class="src-ref">출처 7</sup>

## 확인하지 못한 것

2026년 8\~10월 장외 비중, 2026년 3월 수치, [[flash-crash|Flash Crash]] 원인 논의 이후의 고빈도거래 규제 변화는 이번 조사에서 확인하지 못했다.

## 책과의 관계

책은 IEX가 2013년 10월 다크풀로 출범해 2016년 6월 [[regulated-market|정규거래소]]가 되었고, 38마일 코일로 350μs 지연을 건다고 설명한다. <sup class="src-ref">원본 p.409-411</sup> 현재 IEX 사이트는 케이블 길이를 44마일로 밝히므로 38마일은 2024년 이전 값으로 갱신해야 한다. 책은 HFT 비중을 2019년 중반 미국 50%로 제시하며 <sup class="src-ref">원본 p.402</sup>, 소매 주문의 약 70%를 도매 [[market-maker|시장조성인]]이 내부화했다고 쓴다(2021년 6월 기준). <sup class="src-ref">원본 p.133</sup> 이 문서의 2025년 장외 비중 50.6%는 집계 기준이 다르므로 이어 붙이지 않는다. 책은 speed bump 사례로 [[nasdaq|Nasdaq]] M-ELO, [[eurex|Eurex]], 중단된 [[nyse|NYSE]] American 등을 든다. <sup class="src-ref">원본 p.410</sup>

## 관련

- [[high-frequency-trading]]
- [[speed-bump]]
- [[internalization]]
- [[payment-for-order-flow]]
- [[dark-pool]]
- [[trade-reporting-facility]]
- [[latency-arbitrage]]
- [[reg-nms-amendments-2024-2026]]
- [[us-best-execution-duty]]

## 출처

기준일 2026-10-26. 1·2번은 거래소 운영자 Cboe의 자체 집계다. (2차)는 법무법인 해설이다.

1. Cboe Insights, 2025 U.S. Equities Year in Review: https://www.cboe.com/insights/posts/2025-u-s-equities-year-in-review
2. Cboe Insights, U.S. Cash Equities July Volume Briefing(2026-08): https://www.cboe.com/insights/posts/market-metrics-that-matter-u-s-cash-equities-july-volume-briefing
3. IEX, Technology: https://www.iex.io/technology
4. SEC, 보도자료 2016-123(IEX 거래소 등록 승인): https://www.sec.gov/news/press-release/2016-123
5. (2차) Baker McKenzie, 딜러 규칙 자진 취하 해설(2025-02-24): https://blockchain.bakermckenzie.com/2025/02/24/the-secs-strategic-retreat-implications-of-voluntary-dismissals-in-the-dealer-rule/
6. Federal Register, 시장접근 위험관리 통제 규칙 관련 릴리스(2011-06-30): https://www.federalregister.gov/documents/2011/06/30/2011-16467/risk-management-controls-for-brokers-or-dealers-with-market-access
7. (2차) Sidley Austin, SEC 주문보호규칙 폐지 제안 해설(2026-06): https://www.sidley.com/en/insights/newsupdates/2026/06/sec-proposes-rescission-of-the-order-protection-rule
