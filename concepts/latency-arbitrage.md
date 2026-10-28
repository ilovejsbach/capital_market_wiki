---
type: concept
title: "속도 차익거래"
aliases: ["latency arbitrage"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "속도 차익거래(latency arbitrage)는 다른 투자자와의 거래 속도 차이로 발생하는 가격 차이를 이익으로 삼는 거래이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
속도 차익거래(latency arbitrage)는 다른 투자자와의 거래 속도 차이로 발생하는 가격 차이를 이익으로 삼는 거래이다. <sup class="src-ref">원본 p.400</sup>
이는 거래시장 가격 데이터를 조금이라도 먼저 받아 거래정보 우위를 활용하려는 추세 전략으로도 설명된다. <sup class="src-ref">원본 p.401</sup>

## 왜 필요한가
이 전략이 많아지면 지정가주문 제출(유동성 공급)의 위험성이 커지고 위험 대비 보상이 감소하며, 거래시장 간 속도 경쟁을 유발해 사회적 자원 낭비를 초래한다. <sup class="src-ref">원본 p.401</sup>
"속도가 느린 주문을 저격"(stale quotes sniping)한다고 하여 사회적으로 분란을 가장 크게 일으킨 약탈적 전략으로 평가된다. <sup class="src-ref">원본 p.401</sup>

## 내용

### 시장 패러다임 변화 ([[kcm-ch11]]) (11장)
- 다른 투자자(특히 바이사이드)의 거래 가격에 악영향을 미칠 가능성이 농후하고, 연속경쟁매매 메커니즘(예: KRX 접속매매)에서는 이 전략의 발생이 불가피하다. <sup class="src-ref">원본 p.401</sup>
- 글로벌 주식시장에서 HFT가 이 전략으로 연간 거둬들이는 이익은 약 50억 달러(6조 원)로 추산되며 이는 거래 건당 0.5bp 세금 부과와 맞먹는 액수이다. <sup class="src-ref">원본 p.401</sup>
- 약탈적 전략의 원인 제공자로 고소당한 주요 거래소들은 2022년 3월 혐의를 벗었다. <sup class="src-ref">원본 p.401</sup>
- 부디쉬·크램튼·존 심(2015)과 비애·푸코·모니아즈(2015)는 이 전략으로 유동성제공자가 손해를 보고 관련 ICT에 과대투자가 발생한다며, speed bump와 FBA 도입 또는 HFT 거래세를 제안했다. <sup class="src-ref">원본 p.406</sup>
- 부디쉬·리·존 심(2021)은 이 전략을 없애면 사회적 후생이 증가한다고 보고, 거래시장의 자발적 혁신 유인이 약해 정책담당자의 밀어붙임이 필요하다고 주장한다. <sup class="src-ref">원본 p.406-407</sup>
- IEX는 이 전략을 구사한 HFT에 계속 체결을 빼앗겼다고 판단해 350μs의 speed bump를 도입했다. <sup class="src-ref">원본 p.409-411</sup>

## 관련
- [[hft-trading-strategies]]
- [[speed-bump]]
- [[frequent-batch-auction]]
- [[co-location]]
- [[high-frequency-trading]]
- [[investors-exchange-iex]]
