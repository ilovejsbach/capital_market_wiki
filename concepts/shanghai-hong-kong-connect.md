---
type: "concept"
title: "후강퉁(상하이-홍콩 스톡커넥트)"
aliases: ["Shanghai-Hong Kong Stock Connect", "Shanghai Connect", "SHSC", "滬港通"]
layer: "expansion"
status: "draft"
as_of: "2026-10"
updated: "2026-10-21"
extends: ["stock-connect"]
research: "stock-connect-trio"
tags: ["개념", "확장"]
description: "후강퉁은 홍콩거래소(HKEX), 상하이증권거래소(SSE), 중국예탁결제(ChinaClear)가 개발한 증권 매매·청산 연계 프로그램이다. 홍콩 쪽 거래소인 SEHK와 SSE가 서로 주문을 전달하는 연결을 만들고,…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

> [!note] 책 밖 확장 문서
> 이 문서는 책 본문이 아니라 웹의 공식 자료를 조사해 덧붙인 확장 문서입니다. 기준일은 2026-10입니다. 근거는 문서 끝의 출처 목록에 있고, 책에서 온 문장에는 `원본 p.N`이 붙습니다.

## 정의

후강퉁은 홍콩거래소(HKEX), 상하이증권거래소(SSE), [[china-securities-depository-and-clearing|중국예탁결제(ChinaClear)]]가 개발한 증권 매매·청산 연계 프로그램이다. 홍콩 쪽 [[trading-venue|거래소]]인 [[stock-exchange-of-hong-kong|SEHK]]와 SSE가 서로 주문을 전달하는 연결을 만들고, [[hong-kong-securities-clearing-company|HKSCC]]와 ChinaClear가 청산·결제·예탁·명의인(nominee) 서비스를 맡는다. <sup class="src-ref">출처 1</sup> 2014년 11월 17일에 시작되었다. <sup class="src-ref">출처 1</sup>

## 방향과 대상

- **북향(Northbound)**: 홍콩·해외 투자자가 상하이 상장 A주와 [[exchange-traded-fund|ETF]]를 매매한다. **남향(Southbound)**: 본토 투자자가 홍콩 상장주식을 매매한다. <sup class="src-ref">출처 1</sup>
- 북향 대상은 A주와 ETF뿐이고 B주·채권은 제외된다. A주는 SSE A주지수 구성종목 가운데 6개월 일평균 시가총액 50억 위안 이상, 일평균 거래대금 3천만 위안 이상 등의 요건을 충족해야 하며, 위험경고종목과 비위안화 거래 종목은 제외된다. A+H 동시상장 종목도 포함된다. <sup class="src-ref">출처 1</sup>
- 상하이·선전 거래소 상장 ETF는 2022년 7월 4일부터 북향 대상에 포함되었다. <sup class="src-ref">출처 1</sup>
- [[china-a-share-boards|커촹반]](STAR) 종목은 북향 대상이나 거래는 기관 전문투자자로 제한된다. <sup class="src-ref">출처 1</sup>
- 남향 대상은 항셍 종합 소형주지수 구성종목 중 시가총액 50억 홍콩달러 이상 종목이다. <sup class="src-ref">출처 1</sup>
- 차등의결권(DVR) 종목은 북향 최초 편입 시 상장 6개월 20거래일, 183일 일평균 시가총액 200억 위안 등의 추가 요건이 있다. <sup class="src-ref">출처 1</sup>

## 투자자

북향은 STAR를 제외하면 홍콩·해외의 기관과 개인에게 열려 있다. <sup class="src-ref">출처 1</sup> 남향은 본토 거래소 회원, 기관투자자, 본토 요건을 충족한 개인에게 열려 있다. <sup class="src-ref">출처 1</sup>

## 한도

- 후강퉁의 **총한도(Aggregate Quota)는 2016년 8월 16일 폐지**되었다. <sup class="src-ref">출처 1</sup>
- **일일한도는 폐지되지 않았다.** 순매수 기준으로 북향 520억 위안, 남향 420억 위안이며(연결별), 2018년 5월 1일에 각각 4배(130억→520억 위안, 105억→420억 위안)로 올랐다. <sup class="src-ref">출처 1</sup> <sup class="src-ref">출처 2</sup>

## 결제·보관과 거래 방식

- 북향 증권은 HKSCC 명의의 옴니버스 계좌로 ChinaClear에 보관된다. HKSCC는 CCASS 참가자와 그 기초 고객을 위한 명의인 보유자이며, 매도 주문은 전일 말 잔고를 기준으로 거래소가 사전 검증한다. <sup class="src-ref">출처 1</sup>
- 특별분리계좌(SPSA) 모델은 2015년 3월 30일 도입되어, 수탁기관에 보관 중인 투자자가 사전 인도 없이 최대 20개 집행 브로커를 지정해 매도할 수 있다. <sup class="src-ref">출처 1</sup>
- 북향에서 무차입 [[short-selling|공매도]]는 금지되고, 적격 종목에 한해 커버드 공매도만 허용된다. 홀수주는 매도만 가능하다. <sup class="src-ref">출처 1</sup>
- 2023년 4월 거래일 캘린더 개선으로 홍콩과 본토 시장이 모두 열린 홍콩 영업일에는 매매가 가능해졌다. <sup class="src-ref">출처 1</sup>

## 규제

본토의 [[china-securities-regulatory-commission|중국증권감독관리위원회(CSRC)]]와 홍콩 [[securities-and-futures-commission|SFC]], 그리고 각 거래소·청산기관의 규칙이 적용된다. <sup class="src-ref">출처 1</sup>

## 규모

2026년 1월 말 기준 후강퉁 북향 적격 종목은 1,539개(ETF 220개 포함)이다. <sup class="src-ref">출처 3</sup>

## 검토 중 (시행되지 않음)

리츠의 Stock Connect 편입과 남향 위안화 카운터는 HKEX가 시점을 정하지 않은 검토 과제로 기술하며, 시행되지 않았다. <sup class="src-ref">출처 3</sup>

## 책과의 관계

책은 후강퉁을 SSE와 HKEX의 교차거래로 설명하고, 상대방 거래소 상장주식을 거래하는 방식이라고 밝힌다. <sup class="src-ref">원본 p.258-260</sup> 책이 이 제도가 필요한 이유로 든 중국 자본시장의 정부 통제와 점진적 개방도 같은 맥락이다. <sup class="src-ref">원본 p.260</sup> 이 문서는 책이 다루지 않은 한도 체계, 보관·결제 구조, 대상 요건, 2022년 이후 변화를 보충한다.

## 관련

- [[stock-connect]]
- [[shenzhen-hong-kong-connect]]
- [[shanghai-london-connect]]
- [[hkex]]
- [[shanghai-stock-exchange]]

## 출처

기준일 2026-10-21. HKEX 공식 자료를 1차 출처로 사용했다.

1. HKEX, Stock Connect FAQ(2026-07-06 판): https://www.hkex.com.hk/-/media/HKEX-Market/Mutual-Market/Stock-Connect/Getting-Started/Information-Booklet-and-FAQ/FAQ/FAQ_En.pdf
2. HKEX, 일일한도 확대 발표(2018-04-11): https://www.hkex.com.hk/News/News-Release/2018/180411news
3. HKEX Insight, Stock Connect 2025 Review(2026): https://www.hkexgroup.com/Media-Centre/Insight/Insight/2026/HKEX-Insight/Stock-Connect-2025-Review?sc_lang=en
