---
type: "concept"
title: "CIPS 위안화 국제결제시스템"
aliases: ["CIPS", "Cross-border Interbank Payment System", "위안화 국제결제시스템", "위안화 교차결제시스템", "跨境银行间支付系统"]
layer: "expansion"
status: "draft"
as_of: "2026-10"
updated: "2026-10-26"
extends: ["real-time-gross-settlement", "delivery-versus-payment"]
research: "china-fx-payments-hk-stablecoin"
tags: ["개념", "확장"]
description: "CIPS(Cross-border Interbank Payment System)는 위안화 국경 간 지급·청산·결제를 처리하는 중국의 결제 인프라다. 운영사 CIPS Co., Ltd.(跨境银行间支付清算有限责任公司, 상…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

> [!note] 책 밖 확장 문서
> 이 문서는 책 본문이 아니라 웹의 공식 자료를 조사해 덧붙인 확장 문서입니다. 기준일은 2026-10입니다. 근거는 문서 끝의 출처 목록에 있고, 책에서 온 문장에는 `원본 p.N`이 붙습니다.

## 정의

CIPS(Cross-border Interbank Payment System)는 위안화 국경 간 지급·청산·결제를 처리하는 중국의 결제 인프라다. 운영사 CIPS Co., Ltd.(跨境银行间支付清算有限责任公司, 상하이 본사)는 인민은행([[pboc]])의 감독·관리·지도를 받으며 인민은행이 승인한 규칙에 따라 서비스를 제공한다. <sup class="src-ref">출처 1</sup> 이 문서는 시스템 구조, 참가자·처리 규모, 한국과의 접점을 정리한다. 채권·주식 시장 접근 제도는 [[china-bond-market-infrastructure]]와 [[bond-connect]]에서 다룬다.

## 설립과 연혁

- 운영 회사는 2015-07-31 설립 등기된 것으로 항셍은행 공시가 기재한다. <sup class="src-ref">출처 2</sup>
- 1단계는 2015-10-08 가동되어 직접참가자 19곳, 간접참가자 176곳(50개국·지역)으로 시작했다. 2단계는 2018-03-26 시범(직접참가자 10곳) 후 2018-05-02 전면 가동되었다. <sup class="src-ref">출처 3</sup>
- 2016-03-25 CIPS와 SWIFT는 양해각서를 체결했다. SWIFT가 CIPS와 글로벌 사용자를 잇는 보안 채널 역할을 한다는 취지이며, 당시 보도는 SWIFT MT 메시지를 CIPS가 쓰는 [[intermarket-sweep-order|ISO]] 20022 표준과 호환되도록 변환 방식을 마련 중이라고 전한다(2016년 시점 서술). <sup class="src-ref">출처 4</sup>

## 결제 구조와 업무

CIPS 공식 사이트는 실시간총액결제([[real-time-gross-settlement|RTGS]])와 지연순액결제(DNS)를 혼합한 방식이며 위안화와 홍콩달러를 지원한다고 설명한다. 단일 접속 집중 청산 모델이고 업무는 국경 간 송금, 금융시장 거래(증권-대금 동시결제 [[delivery-versus-payment|DvP]]와 PvP), 청산기관 간 자금 대출이다. <sup class="src-ref">출처 5</sup>

## 참가자

- 2025년 말 직접참가자 193곳, 간접참가자 1,573곳(124개국·지역)으로 출범 때(19/176)의 약 9\~10배다. 직접참가자는 약 10.2배, 간접참가자는 약 8.9배다(계산값). <sup class="src-ref">출처 6</sup>
- CIPS 공식 사이트는 2026년 9월 기준 직접 214곳, 간접 1,651곳을 게시한다. 간접참가자는 아시아 1,176(중국 본토 528), 유럽 271, 아프리카 112, 북미 35, 남미 32, 오세아니아 25로 구분된다(합계 1,651). 같은 페이지의 아시아 세부 구역은 직접 148, 간접 1,157(본토 542)로 적혀 있어 1,176(528)과 맞지 않으며 원인은 확인하지 못했다. <sup class="src-ref">출처 5</sup>
- 서비스 대상은 2025-09 인민은행 부총재 루레이 발언 기준 189개국·지역, 2026-03 보도 기준 190개국·지역의 5,000개 이상 은행기관이다. <sup class="src-ref">출처 6</sup><sup class="src-ref">출처 7</sup> 2026-06 기준 직접 210곳, 5,200개 이상, 191개국·지역이라는 보도도 있다. <sup class="src-ref">출처 8</sup> 시점별 증가 추이로 읽히며 단일 시계열로 이어 쓰지는 않는다.
- 2025년 6월 방콕은행, 스탠더드뱅크(남아공), 아프리카수출입은행, 퍼스트 아부다비 은행, 키르기스스탄 Eldik Bank, UOB(대화은행) 6곳이 직접참가자가 되었다(상하이시 정부 보도). <sup class="src-ref">출처 9</sup>

## 처리 규모

- 2023년 661.33만 건·123.06조 위안, 2024년 821.69만 건·175.49조 위안(전년 대비 금액 +42.6%, 건수 +24.25%)이다. <sup class="src-ref">출처 3</sup>
- 인민은행 루레이 부총재(2025-09-16)는 2025년 상반기 400만 건 이상, 약 90.2조 위안을 처리했다고 밝혔다. <sup class="src-ref">출처 7</sup>
- 2025년 연간은 약 180조 위안 안팎이라는 보도가 복수 있으나 정밀값은 아래 '확인하지 못한 것'에 둔다.
- 민간 분석기관 FXC Intelligence에 따르면 일평균 처리액은 2026-03 사상 최고인 9,205억 위안(전년 +20%), 2026-05 6,740억 위안(전년 +5%)이고 2026-04에 단일일 최고 1.22조 위안이 처리되었다. <sup class="src-ref">출처 10</sup>

## 한국과의 접점

CIPS 공식 사이트 참가자 목록에는 서울 소재 기관으로 교통은행 서울 위안화 청산은행, 중국은행·중국농업은행·중국건설은행·중국공상은행의 서울지점이 올라 있다. 모두 중국계이며 목록에서 직접/간접 유형은 구분되지 않는다. <sup class="src-ref">출처 5</sup>

## 홍콩과의 연결

2026년 7월 홍콩거래소([[hkex]])가 CIPS 운영회사와 협력 양해각서를 체결했고, 자회사 [[otc-clearing-hong-kong|OTC Clearing Hong Kong]]이 2026년 말까지 CIPS 직접참가자 신청을 할 계획이라고 보도되었다. 계획 단계이며 신청·승인은 확인되지 않았다. <sup class="src-ref">출처 8</sup>

## 확인하지 못한 것

- **2025년 연간 처리 정밀값(약 844만 건, 180.15조 위안, 일평균 약 3.19만 건)**: Wikipedia 단독이고 CIPS 공식 통계 페이지는 열리지 않았다. 금액 약 180조 위안은 복수 보도가 일치하나 건수와 정밀값은 단일 2차 출처다. Wikipedia가 적은 2025년 증가율 1.02%는 2024년 수치와 맞지 않아 쓰지 않았다(계산값 약 +2.7%).
- **운영사 주주 구성**: 최대주주 인민은행의 지분율을 Wikipedia는 16%, 다른 자료(천안차 인용)는 15.7%로 적는다. 둘 다 1차가 아니며 차이의 원인은 확인하지 못했다. 국무원 자료의 2015-09-08 정식 설립도 확인하지 못했다.
- **참가자 수 시계열**: 2024-12 168/1,461, 2025-05 174/1,509, 2026-04 194/1,597은 확인하지 못했다. Wikipedia는 2025-06 176/1,514(121개국)로 서로 다른 시점의 값이 엇갈린다. 아시아 간접참가자 1,176 대 1,157은 위 참가자 절에 두 값을 병기했다.
- **직접·간접 참가자의 정의**: 일반적 정의로 서술 가능하나 공식 자료에서 문구를 열람하지 못했고 단일 2차 출처(Wikipedia)뿐이어서 본문에 쓰지 않았다.
- **SWIFT 메시지 의존도**: Wikipedia가 CIPS 거래의 80% 이상이 SWIFT 메시지를 쓴다고 적으나 출처가 오래돼 확인하지 못했다. 현재 ISO 20022 운영 상태도 확인하지 못했다.
- **한국계 은행의 CIPS 참가 여부**: 참가자 공고 본문을 열람하지 못해 확인하지 못했다.
- **HKEX 자회사의 직접참가 신청·승인**: 보도는 계획만 전한다.

## 책과의 관계

책은 RTGS를 매매체결 즉시 전량을 직접 주고받는 방식으로 설명하고 <sup class="src-ref">원본 p.99</sup> DvP를 증권 인도와 대금 지급을 연계한 결제로 정의한다. <sup class="src-ref">원본 p.100</sup> CIPS의 RTGS+DNS 혼합 구조와 DvP·PvP 업무는 이 개념의 국경 간 위안화 적용 사례이다. 책은 CIPS를 다루지 않으므로 이 문서는 보충이며 책 서술과 충돌하는 내용은 없다.

## 관련

- [[pboc]]
- [[china-bond-market-infrastructure]]
- [[bond-connect]]
- [[real-time-gross-settlement]]
- [[delivery-versus-payment]]
- [[hkex]]
- [[otc-clearing-hong-kong]]
- [[state-administration-of-foreign-exchange]]
- [[hong-kong-stablecoins-ordinance]]

## 출처

기준일 2026-10-26. 1·5번은 CIPS 공식 사이트(1차)이고 나머지는 2차 자료다.

1. CIPS Co., Ltd., About Us: https://www.cips.com.cn/kjjqgsyyingw/gywm/index.shtml
2. (2차) 항셍은행(중국) 관련거래 공시(2026-02-13): https://www.hangseng.com.cn/content/dam/wpb/hacn/about-us/pdf/Related_txn_20260213.pdf
3. (2차) Wikipedia, Cross-Border Interbank Payment System: https://en.wikipedia.org/wiki/Cross-Border_Interbank_Payment_System
4. (2차) The Global Treasurer, SWIFT-CIPS 양해각서(2016-03-28): http://www.theglobaltreasurer.com/2016/03/28/swift-signs-mou-with-chinas-cips/
5. CIPS Co., Ltd. 공식 홈(참가자 현황·목록, 2026-09 열람): http://www.cips.com.cn/kjjqgsyyingw/index/index.shtml
6. (2차) China Daily(2026-03-03): https://epaper.chinadaily.com.cn/a/202603/03/WS69a62f82a310ec22b1fd2c2d.html
7. (2차) Central Banking, 루레이 포럼 발언(2025-09-18): https://www.centralbanking.com/central-banks/payments/7973712/china%E2%80%99s-cross-border-clearing-system-expands-to-189-countries
8. (2차) 同花顺(10jqka), HKEX-CIPS 양해각서(2026-07-07): https://stock.10jqka.com.cn/hks//20260707/c678002296.shtml
9. (2차) 상하이시 정부 영문판(2025-06-19): https://english.shanghai.gov.cn/en-ShanghaiFinancialServices/20250619/35fa7dc521dd44c599429da0d4b57759.html
10. (2차) FXC Intelligence, CIPS 처리량(2026-06): https://www.fxcintel.com/research/analysis/cips-volumes-may-2026
