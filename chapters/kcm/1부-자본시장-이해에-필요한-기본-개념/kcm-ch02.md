---
type: chapter
title: "2장 주식거래과정과 기능별 인프라 제공기관"
aliases: ["kcm 2장", "2장 주식거래과정과 기능별 인프라 제공기관", "제2장 주식거래과정과 기능별 인프라 제공기관"]
books: [kcm]
entry_id: ch2
pdf_pages: 77-112
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["장"]
description: "책: kcm"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

책: [[kcm]]

## 요약

주식거래과정을 주문제출, 매매체결, 청산·결제, 예탁 등 기능별로 설명한 뒤, 각 기능을 담당하는 인프라 제공기관을 정리한다. <sup class="src-ref">원본 p.77-112</sup>

1절은 주문제출, 매매체결, 청산·결제 및 예탁 순으로 주식거래과정을 살피고, 2절은 금융투자회사, 거래시장, 청산기관과 결제·예탁기관, 금융데이터/지수 제공기관과 거래정보저장소를 다룬다. <sup class="src-ref">원본 p.77-112</sup>

한국처럼 거래시장이 KRX 한 군데인 시장과 미국처럼 260여 군데 거래시장이 경쟁하는 시장의 거래과정 차이를 그림 2-1로 비교한다. <sup class="src-ref">원본 p.78-79</sup>

## 흐름

- [[stock|주식]] 위주로 한정한 범위상 주식거래과정을 다루지만 [[bond|채권]], 장내·외파생상품, FX도 거래과정과 FMI 제공기관이 주식과 별 차이가 없다. <sup class="src-ref">원본 p.77</sup>
- 1절 가(주문제출)는 바이사이드와 셀사이드, 소프트 달러, 시장가·지정가·조건부지정가주문과 [[nyse|NYSE]] 130여 개 주문유형, IEX의 10개 주문유형을 다룬다. <sup class="src-ref">원본 p.80-87</sup>
- 1절 나(매매체결)는 가격·시간·수량·위탁매매 우선원칙, 단일가매매와 접속매매, 순수경쟁·수정경쟁·딜러 메커니즘, 크로씽과 대량매매, KRX 매매체결방식(표 2-1)을 설명한다. <sup class="src-ref">원본 p.87-92</sup>
- 이어 매매수량단위와 호가단위(표 2-2), [[quote-disclosure-range|호가공개범위]]와 시장 투명성, 서킷브레이커·사이드카·가격제한폭제도·VI를 다룬다. <sup class="src-ref">원본 p.92-97</sup>
- 1절 다(청산, 결제 및 예탁)는 청산, 매매확인, CCP와 경개, 네팅(그림 2-4), 결제와 예탁, 전자증권제도, 결제 주기와 STP, [[distributed-ledger-technology|블록체인]]/DLT를 다룬다. <sup class="src-ref">원본 p.97-102</sup>
- 2절 가는 금융투자회사 유형(표 2-3)과 종합금융투자사업자, 초대형 투자은행, IB를 다룬다. <sup class="src-ref">원본 p.103-105</sup>
- 2절 나는 거래시장과 ATS, 정규거래시장·비정규거래시장 구분, 유동성 외부효과와 자연독점을 다룬다. <sup class="src-ref">원본 p.105-108</sup>
- 2절 다는 미국 [[dtcc|DTCC]], 유럽 [[derivatives-clearing-organization|청산·결제기관]], 아시아 주요 거래소와 한국 KRX·KSD의 구조를 비교한다. <sup class="src-ref">원본 p.108-110</sup>
- 2절 라는 [[lseg|LSEG]] 사례(그림 2-7)로 금융데이터/지수 제공기관과 거래정보저장소를 설명한다. <sup class="src-ref">원본 p.110-112</sup>

## 다룬 개념·지표·전략

- 주식거래과정 개관: [[stock-trading-process]], [[financial-market-infrastructure]], [[trading-venue]], [[buy-side-sell-side]], [[soft-dollar]], [[broker-dealer]]
- 주문제출·주문유형: [[order-types]], [[market-order]], [[limit-order]], [[conditional-order]], [[order-conditions]], [[bbo]], [[best-execution]], [[adverse-selection]], [[order-book]]
- 매매체결: [[matching-priority]], [[call-auction]], [[continuous-trading]], [[crossing]], [[block-trade]], [[after-hours-trading]], [[market-maker]], [[dark-pool]], [[lit-pool]], [[internalization]], [[trading-unit]], [[tick-size]], [[market-depth]], [[market-quality]], [[price-discovery]], [[market-transparency]]
- 시장안정화장치: [[market-stabilization-measures]], [[circuit-breaker]], [[sidecar]], [[price-limit-system]], [[volatility-interruption]]
- 청산·결제·예탁: [[clearing]], [[trade-confirmation]], [[central-counterparty]], [[novation]], [[netting]], [[real-time-gross-settlement]], [[settlement]], [[delivery-versus-payment]], [[settlement-cycle]], [[dematerialization]]
- 기능별 인프라 제공기관: [[investment-bank]], [[integrated-securities-business]], [[prime-brokerage]], [[liquidity-externality]], [[natural-monopoly]], [[index-and-data-provider]], [[trade-repository]]

## 수식·표·그림

수식 레코드가 없다. 표·그림은 레코드가 없어 쪽으로만 가리킨다.

| 자산 | 내용 | 쪽 |
|---|---|---|
| 그림 2-1 | 한국과 미국 주식거래과정(패널 A·B) | <sup class="src-ref">원본 p.78-79</sup> |
| 그림 2-2 | 시장가주문과 지정가주문 및 기회비용과 역선택 비용 | <sup class="src-ref">원본 p.83</sup> |
| 그림 2-3 | HTS와 MTS 호가창 게시 예 | <sup class="src-ref">원본 p.86</sup> |
| 표 2-1 | KRX 거래시간과 매매체결방식 | <sup class="src-ref">원본 p.91</sup> |
| 표 2-2 | KRX 호가단위 | <sup class="src-ref">원본 p.93</sup> |
| 그림 2-4 | 차감방식별 위험감축효과 비교 | <sup class="src-ref">원본 p.99</sup> |
| 표 2-3 | 금융투자회사 유형, 업무 내용 및 주요 담당기관 | <sup class="src-ref">원본 p.103</sup> |
| 그림 2-5 | 금융투자회사 업무 개관 | <sup class="src-ref">원본 p.105</sup> |
| 그림 2-6 | 주식시장 생태계 — 미국주식시장 | <sup class="src-ref">원본 p.107</sup> |
| 그림 2-7 | LSEG 사업 부문별 이익 비중 | <sup class="src-ref">원본 p.110</sup> |

![한국 주식거래과정의 흐름도로, 회원의 호가제출부터 매매기관의 체결, 청산기관의 매매확인·채무인수·차감·결제지시를 거쳐 결제기관(예탁결제원)에서 증권은 계좌대체, 대금은 계좌이체로 처리되는 단계를 보여 준다.](p078-i1.jpg)
*책 78쪽 그림*


![미국 주식거래과정 흐름도(패널 B). 투자자의 주문이 브로커/딜러를 거쳐 NYSE, NASDAQ, BATS, 다크풀 등 거래시장으로 전달되고, 시세정보는 정보제공벤더로, 체결·청산·결제는 중앙청산소(NSCC), 예탁결제원(DTC), 결제은행으로 흐르는 과정을 주문·정보·청산/결제 흐름으로 구분해 보여 준다.](p079-i1.jpg)
*책 79쪽 그림*


![호가 단계(Offer, Bid)를 계단 모양 선으로 나타낸 도식이다. 스프레드 포착, 기회비용, 역선택 비용이 각각 어디서 생기는지 보여 준다.](p083-i1.jpg)
*책 83쪽 그림*


![HTS 호가창 화면 캡처(왼쪽). 매도호가 1,294,000~1,290,000원과 매수호가 1,289,000~1,285,000원 5단계의 잔량과 잔량합계를 보여 준다.](p086-i1.jpg)
*책 86쪽 그림*

![HTS 호가창 화면 캡처(오른쪽). 10단계 매도·매수 호가와 잔량, 현재가·거래량·시가·고가·저가·상하한가, 캔들 차트 일부를 함께 보여 준다.](p086-i2.jpg)
*책 86쪽 그림*

![MTS(모바일) 호가창 화면 캡처. 유한양행의 10단계 매도·매수 호가와 잔량, 체결강도, 총잔량, 기준가·시가·고가·저가·상하한가를 보여 준다.](p086-i3.jpg)
*책 86쪽 그림 (검수 대기)*


![A·B·C·D 네 참가자 간 거래를 네 가지 방식으로 비교한 네 칸짜리 도식이다. ① 총량결제는 모든 쌍 사이에 전량을 주고받고, ② 상대차감은 양자 간 차감, ③ 형식적 상대차감은 CCP를 개입시킨 양자 간 차감, ④ 실질적 다자간차감은 CCP와 각 참가자 간 순잔액만 남기는 구조를 보여 준다.](p099-i1.jpg)
*책 99쪽 그림*


![증권사와 자산운용사의 업무 구조를 보여 주는 도식이다. 기업·투자자·고유자산 등 고객과 자산 유형이 리테일·법인 영업, 리서치를 거쳐 IB, 위탁매매, 상품 판매, 지점창구, PI, 펀드운용 업무로 연결되는 관계를 나타낸다.](p105-i1.jpg)
*책 105쪽 그림*


![미국 주식시장 생태계를 보여 주는 도식으로, 중앙의 상장거래소를 중심으로 은행/브로커, 기업, 정규거래소, 시장조성인, 개인투자자, 헤지펀드, 자산운용사가 자본·유동성·투자·효율성 네 영역으로 배치되어 연결되어 있다. 각 상자에 규모와 비중 수치가 적혀 있다.](p107-i1.jpg)
*책 107쪽 그림*


![2020년 상반기 LSEG의 사업 부문별 총수익(£1,235m) 비중을 보여 주는 도넛 차트와 범례. 후선업무 44%, 정보서비스 35%, 매매체결 18%, IT 및 기타 3%이며, 오른쪽에 성장세가 큰 FTSE Russell(5%)과 LCH(10%)를 설명한다.](p110-i1.jpg)
*책 110쪽 그림*


## 관련

- [[investors-exchange-iex]]
