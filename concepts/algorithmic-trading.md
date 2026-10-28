---
type: concept
title: "알고리즘거래(AT)"
aliases: ["AT/algo", "algorithmic trading", "algo"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "AT(algorithmic trading)는 증권투자나 거래를 할 때 특정 매매기법을 컴퓨터 프로그램으로 완전 자동화해 거래하는 방식이며, 개념상 HFT를 포함한다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
AT(algorithmic trading)는 증권투자나 거래를 할 때 특정 매매기법을 컴퓨터 프로그램으로 완전 자동화해 거래하는 방식이며, 개념상 HFT를 포함한다. <sup class="src-ref">원본 p.398</sup>
ESMA는 HFT를 AT의 부분집합으로 보고 MiFID II/MiFIR에 명문화했으며, AT 정의도 특성만 간단히 서술한다. <sup class="src-ref">원본 p.397</sup>

## 왜 필요한가
AT는 주로 기관투자자가 고객의 대량주문을 시장충격을 최소화하며 성사시키려고 여러 거래시장에서 시간을 두고 처리할 때 쓰며, 보유기간이 수개월을 초과하기도 한다. <sup class="src-ref">원본 p.398-399</sup>

## 내용

### 시장 패러다임 변화 ([[kcm-ch11]]) (11장)
- AT와 HFT 공통 특성은 전문투자자가 활용하고, 인적 개입 없이 주문 확정·제출·회송·정정/취소를 자동으로 결정하며, 시장 데이터를 실시간으로 관측하며 거래하고, DMA를 사용하는 것이다. <sup class="src-ref">원본 p.398</sup>
- AT 고유 특성은 위탁매매, 시장충격 최소화, 특정 벤치마크 달성이라는 거래 목적, 수개월 또는 1년을 넘기기도 하는 보유기간이다. <sup class="src-ref">원본 p.398</sup>
- AT를 "HFT를 제외한 모든 자동 주문 거래"로 일반화해 정의하기도 한다. <sup class="src-ref">원본 p.398</sup>
- 거래방식을 결정하는 AT(how-to-trade)와 거래시장을 결정하는 SOR(smart order routing) AT를 결합하면 주문 결정에서 제출, 매매체결, 거래 후 업무까지 전 과정을 순식간에 처리할 수 있다. <sup class="src-ref">원본 p.395</sup>
- 미국에서 거래량 기준으로 2022년 말 현재 AT는 60\~75%를 차지한다(정의나 집계방식에 따라 달라짐). <sup class="src-ref">원본 p.395</sup>
- 뵈머·퐁·우(2021)에 따르면 AT로 유동성과 가격효율성은 좋아지지만 단기 변동성은 높아지고, 바이사이드 기관투자자의 묵시적 거래비용은 낮아진다. <sup class="src-ref">원본 p.404</sup>

## 관련
- [[high-frequency-trading]]
- [[dma]]
- [[co-location]]
- [[hft-trading-strategies]]
- [[mifid-ii-mifir]]
