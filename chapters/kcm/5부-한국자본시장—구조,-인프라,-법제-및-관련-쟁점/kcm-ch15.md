---
type: chapter
title: "15장 시장미시구조"
aliases: ["kcm 15장", "15 시장미시구조"]
books: [kcm]
status: draft
updated: 2026-10-20
entry_id: ch15
pdf_pages: "537-556"
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["장"]
description: "책: kcm"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

책: [[kcm]]

## 요약

이 장은 KRX 주식시장(거래소시장)의 규정과 제도를 중심으로 매매거래 절차·시간·체결방식, [[order-types|주문유형]], [[matching-priority|매매체결원칙]], 호가단위, 호가공개범위, [[market-stabilization-measures|시장안정화장치]]를 정리한다. <sup class="src-ref">원본 p.537-548</sup>
이어 한국주식시장 미시구조에 대한 단상과, 글로벌 선도자본시장 특징과 한국 상황을 비교한 부록 표를 싣는다. <sup class="src-ref">원본 p.549-556</sup>

## 흐름

- 들어가는 말: [[market-microstructure|시장미시구조]]는 거래 관련 제도나 메커니즘, 현상 등을 가리키는 용어로 쓰이며, KRX 주식시장의 규정과 제도 중심으로 주요 내용만 간추린다. <sup class="src-ref">원본 p.537</sup>
- 매매거래 일반절차: 일반투자자는 [[broker-dealer|증권회사]](회원)를 통해야 하며 투자자는 T+2일(체결일 포함 3영업일)까지 대금·증권을 납부한다. <sup class="src-ref">원본 p.538</sup>
- 시간과 체결방식: 정규시장은 9시\~15시 30분, 호가는 8시 30분부터 접수(2019년 4월 29일 변경)한다. 시간외시장에는 종가매매 2종, 시간외 단일가매매, 경쟁대량매매 등이 있다. <sup class="src-ref">원본 p.539</sup> <sup class="src-ref">원본 p.540</sup>
- 주문유형: 5개 주문유형과 IOC·FOK 2개 체결조건을 사용한다. <sup class="src-ref">원본 p.540-541</sup>
- 체결원칙·호가단위·호가공개: [[market-order|시장가주문]] 우선, 가격·시간·수량 우선, 위탁매매 우선 원칙이 적용되고, 호가단위는 다층적 구조이며 2002년 1월 2일부터 10단계 호가를 공개한다. <sup class="src-ref">원본 p.542-544</sup>
- 시장안정화장치: 서킷브레이커, 개별종목 매매거래정지 및 재개, 가격제한폭, 변동성완화장치, 사이드카, 단기과열완화장치를 두며 시장조성자와 LP도 둔다. <sup class="src-ref">원본 p.544-548</sup>
- 단상: 글로벌 선도거래시장 미시구조 특징 11개 가운데 KRX가 갖고 있다고 할 수 있는 것은 ①, ⑤의 일부([[special-purpose-acquisition-company|SPAC]]), ⑨ 정도로 평가된다. <sup class="src-ref">원본 p.549-550</sup>
- 부록: 글로벌 선도자본시장 특징과 한국 상황·시사점을 표로 비교한다. <sup class="src-ref">원본 p.555-556</sup>

## 다룬 개념·지표·전략

- 소유 개체: [[liquidity-provider]] · [[most-favorable-order]] · [[top-priority-order]] · [[short-term-overheating-mitigation]] · [[trading-halt]]
- 새 제안: [[random-end-call-auction]] · [[a-blox]] · [[relative-tick-size]] · [[quote-disclosure-range]] · [[program-trading]] · [[execution-conditions]]
- 부분 조각: [[volatility-interruption]] · [[circuit-breaker]] · [[sidecar]] · [[price-limit-system]] · [[tick-size]] · [[market-maker]] · [[crossing]] · [[call-auction]]

## 수식·표·그림

레코드가 없어 쪽만 가리킨다.

| 자산 | 위치 |
|---|---|
| 표 15-1 KRX 주식시장 매매거래 시간과 매매체결방식 | <sup class="src-ref">원본 p.539</sup> |
| 그림 15-1 KRX 상대호가단위—2010년 10월 이전 | <sup class="src-ref">원본 p.543</sup> |
| 표 15-2 [[kospi-market\|유가증권시장]] 호가공개범위 변천 | <sup class="src-ref">원본 p.544</sup> |
| 표 15-3 유가증권시장과 [[kosdaq-market\|코스닥시장]] 주요 시장안정화장치 | <sup class="src-ref">원본 p.547-548</sup> |
| 부록 표 15-1 글로벌 선도자본시장 특징과 한국 상황 | <sup class="src-ref">원본 p.555-556</sup> |

![KRX 주식시장의 하루 매매거래 시간대를 막대 타임라인으로 보여 주고, 정규 거래시간·장시작 전·장종료 후·시간외 단일가·예약 주문의 조건을 말풍선으로 설명한 도식이다.](p539-i1.jpg)
*책 539쪽 그림*

![유가증권시장·코스닥시장·코넥스시장별로 정규시장과 시간외시장의 매매거래 시간, 수량단위, 주문유형, 가격제한폭, 매매체결방식, 경쟁대량매매 조건을 비교한 표이다.](p539-i2.jpg)
*책 539쪽 그림 (검수 대기)*


![가격 구간별 상대호가단위(%)가 톱니 모양으로 변하는 선 그래프로, 2010년 10월 이전 KRX의 상대호가단위를 보여 준다. 0.5% 수준의 회색 점선, 1,000원 미만 구간의 점선 네모, 최저 상대호가단위를 표시한 굵은 타원이 함께 그려져 있다.](p543-i1.jpg)
*책 543쪽 그림*


## 검토 필요

- 시장조성자제도 시행 시점이 본문 각주(2016년 3월 도입)와 부록 표(2016.1.4.)에서 다르게 표기돼 있다. <sup class="src-ref">원본 p.550</sup> <sup class="src-ref">원본 p.556</sup>
- 부록 표에 "주식시장시장", "HTF"처럼 보이는 표기가 있다(원문 그대로). <sup class="src-ref">원본 p.555</sup>
