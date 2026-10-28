---
type: "concept"
title: "MiFID II/MiFIR 개정(단일상한·PFOF 금지·통합시세)"
aliases: ["MiFIR 리뷰", "MiFIR review", "단일 거래량 상한", "EU 통합시세", "EU consolidated tape"]
layer: "expansion"
status: "draft"
as_of: "2026-10"
updated: "2026-10-26"
extends: ["mifid-ii-mifir", "double-volume-cap", "consolidated-tape-provider", "systematic-internaliser", "payment-for-order-flow", "mifid-ii-quick-fix-directive"]
research: "europe-uk-market-structure"
tags: ["개념", "확장"]
description: "Quick Fix 지침((EU) 2021/338)은 코로나19 회복 패키지의 하나로 2021년 2월 16일 채택되어 2월 26일 관보(OJ L 68)에 실렸고, 직전 36개월 시가총액이 10억 유로 이하인 발행기업…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

> [!note] 책 밖 확장 문서
> 이 문서는 책 본문이 아니라 웹의 공식 자료를 조사해 덧붙인 확장 문서입니다. 기준일은 2026-10입니다. 근거는 문서 끝의 출처 목록에 있고, 책에서 온 문장에는 `원본 p.N`이 붙습니다.

## 정의와 배경

[[mifid|MiFID]] II(지침 2014/65/EU)와 MiFIR(규정 600/2014)는 원래 2017년 1월 3일 적용 예정이었으나 데이터 인프라 준비 지연으로 1년 미뤄져 2018년 1월 3일부터 적용되었다. <sup class="src-ref">출처 1</sup> 이 문서는 그 뒤의 변화, 곧 2021년 Quick Fix와 2024년 MiFIR 개정(개정 규정 (EU) 2024/791, 개정 지침 (EU) 2024/790)을 다룬다. 개정 규정과 지침은 2024년 3월 28일 발효했고 규정은 즉시 효력이 있으며 지침 이행기한은 2025년 9월 29일이다. <sup class="src-ref">출처 3</sup>

## Quick Fix(2021)

Quick Fix 지침((EU) 2021/338)은 코로나19 회복 패키지의 하나로 2021년 2월 16일 채택되어 2월 26일 관보(OJ L 68)에 실렸고, 직전 36개월 시가총액이 10억 유로 이하인 발행기업의 리서치 비용을 묶음으로 지급(소프트달러)하는 것을 허용했다. <sup class="src-ref">출처 2</sup> 이 문서는 지침 적용일(2022년 2월 28일)은 확인하지 못했다. <sup class="src-ref">출처 2</sup>

## 단일 거래량 상한(SVC)

- **내용**: 이중거래상한(DVC: 개별 [[dark-pool|다크풀]] 4%, 전체 8%)이 단일상한(SVC)으로 대체되었다. 기준가격 면제(RPW) 하의 거래는 직전 12개월 EU 전체 거래량의 7%로 제한되고, 초과하면 해당 면제가 3개월 정지된다. <sup class="src-ref">출처 4</sup>
- **전환 일정**: ESMA는 2025년 9월 공표분이 마지막 DVC 공표이며 DVC에 따른 모든 정지는 늦어도 2025년 9월 28일까지라고 안내했다. SVC의 첫 정지 파일은 2025년 10월 9일 공표되었고 정지 기간은 2025년 10월 14일\~2026년 1월 13일이다. 이후 분기 단위로 공표·정지한다. <sup class="src-ref">출처 4</sup>
- **영국**: 영국은 [[financial-services-and-markets-act-2000|FSMA]] 2023에 따른 UK MiFIR 개정으로 이중거래상한(UK MiFIR 제5조)을 삭제했고 2023년 8월 29일 효력이 발생했다. <sup class="src-ref">출처 10</sup>

## 주식 거래의무(STO)

개정 MiFIR 제23조는 EEA ISIN 주식의 거래를 [[regulated-market|규제시장]]·MTF·SI·동등 제3국 거래소에서 하도록 요구한다. 예외는 제3국 거래소에서의 현지·비EEA 통화 거래와 적격·전문 상대방 간 가격형성에 기여하지 않는 거래 둘뿐이며, 종전의 비체계적·임시·불규칙·비빈번 거래 예외는 없다. ESMA 단일룰북 통합본 기준이며 개정 규정 2024/791의 EUR-Lex 본문과는 대조하지 못했다. <sup class="src-ref">출처 14</sup>

## 주문흐름 대가(PFOF) 금지

개정 MiFIR 제39a조는 소매 고객과 상향 선택(opt-up) 전문투자자 고객의 주문을 특정 [[trading-venue|거래시장]]에서 집행하거나 제3자에게 전달하는 대가로 금전·비금전 이익을 받는 것을 금지한다. PFOF 관행이 있던 회원국은 2026년 6월 30일까지 예외를 둘 수 있었다. <sup class="src-ref">출처 3</sup> 독일의 예외는 이 날짜에 끝나 2026년 7월 1일부터 독일에서도 금지가 적용된다. <sup class="src-ref">출처 5</sup>

## 체계적 내부체결(SI) 투명성

ESMA는 2025년 10월 8일 개정 RTS 1의 신규 사전투명성 요건과 사후투명성 항목 개정을 2026년 3월 2일부터 적용한다고 공지했다. SI의 최소 호가 크기·투명성 문턱 변경과 give-up/give-in 거래의 사후투명성 제외는 관보 게재 20일 후 적용되며, 표준시장규모(SMS) 공표는 적용 전날로 예정되었다. <sup class="src-ref">출처 6</sup>

## 통합시세(Consolidated Tape)

- **설계**: 개정 MiFIR에 따라 ESMA가 자산군(채권, 주식·[[exchange-traded-fund|ETF]], 장외파생)별로 경쟁 선정 절차를 열어 단일 통합시세제공자(CTP)를 5년 기간으로 선정한다. 거래시장과 [[approved-publication-arrangement|APA]]는 가능한 한 실시간으로 데이터를 CTP에 제공해야 한다. <sup class="src-ref">출처 7</sup>
- **채권**: ESMA가 2025년 1월 3일 선정 절차를 시작해 Ediphy(fairCT)를 선정했고, 2026년 4월 기준 인가 절차가 진행 중이었다. 이후 인가·개시는 확인하지 못했다. <sup class="src-ref">출처 7</sup>
- **주식·ETF**: 2025년 6월 20일 절차를 시작해 2025년 12월 19일 EuroCTP를 선정했다. <sup class="src-ref">출처 7</sup> 2026년 7월 27일 인가되었고 이행기간은 2026년 9월 30일까지다. 개시 계획일은 2026년 9월 14일이며, 실제 가동했다는 보도는 있으나 1차 출처로는 확인하지 못했다. <sup class="src-ref">출처 8</sup>
- **장외파생**: 2026년 1월 5일 절차를 시작해 7월 Etrading Software (Netherlands) B.V.를 선정했다고 발표했다. <sup class="src-ref">출처 7</sup>
- **데이터 제공 의무**: ESMA는 2026년 4월 1일 Q&A에서 거래시장과 APA가 통합시세 개시일부터 CTP에 데이터를 보낼 법적 의무가 있다고 밝히고, 인가 전에도 CTP와 접속·테스트를 준비하라고 안내했다. <sup class="src-ref">출처 9</sup>

## 영국의 통합시세와 결제 주기

- **채권**: 2026년 6월 22일 영국 채권 통합시세가 개시되었다는 보도가 있다. Etrading Software의 ETS Connect UK가 FCA 인가를 받았고(정확한 인가일은 확인하지 못함) 기여자 커버리지는 명목거래액 기준 98%라고 보도되었다. <sup class="src-ref">출처 11</sup>
- **주식(확정 단계)**: FCA는 2026년 7월 31일 영국 주식 통합시세 프레임워크를 정책성명으로 확정했다. 계약 요건(2026년 9월 18일 마감)과 SI 호가 포함 여부(2026년 10월 16일 마감)에 대한 후속 의견수렴은 마감되었으나, 사업자 선정과 개시는 아직 이루어지지 않았다. <sup class="src-ref">출처 12</sup>
- **T+1(시행 예정)**: 영국과 EU는 결제 주기를 [[settlement-cycle|T+1]]로 줄이는 전환일을 2027년 10월 11일로 정했다. EU는 입법이 채택되었고 영국은 법정문서를 마련 중이며 시행은 예정 단계다. <sup class="src-ref">출처 13</sup>

## 확인하지 못한 것

개정 MiFIR의 [[trading-obligations|거래의무]] 중 [[derivatives|파생상품]] 거래의무와 [[emir|EMIR]] 청산의무의 연동, 지침 (EU) 2024/2811(리서치 비용 관련)의 세부는 확인하지 못했으므로 쓰지 않았다. EuroCTP·채권 CTP의 실제 가동 상태도 확인하지 못했다.

## 책과의 관계

책은 MiFID II/MiFIR의 2018년 시행, 규제거래시장 3유형(RM·[[multilateral-trading-facility|MTF]]·[[organized-trading-facility|OTF]]), DVC, SI, APA·CTP 추가, Best Execution, Research Unbundling을 설명한다. <sup class="src-ref">원본 p.364</sup> <sup class="src-ref">원본 p.366-367</sup> <sup class="src-ref">원본 p.371-373</sup> 위 2018년 시행 연기 경위는 책과 일치한다. 책은 DVC(4%/8%, 위반 시 6개월 정지)를 서술하는데, 이는 SVC(7%, 3개월 정지)로 갱신되었다. <sup class="src-ref">원본 p.368</sup> 책의 Quick Fix 서술(36개월 시가총액 10억 유로 이하 리서치 면제)은 일치한다. <sup class="src-ref">원본 p.382</sup> 책은 통합시세 부재를 문제로 제기하는 데 그쳤고, 이 문서가 ESMA의 CTP 선정과 인가 경과를 보충한다. <sup class="src-ref">원본 p.386</sup> PFOF는 책에서 미국 맥락으로만 다루므로 EU의 금지는 새 내용이다. <sup class="src-ref">원본 p.329</sup>

## 관련

- [[mifid-ii-mifir]]
- [[double-volume-cap]]
- [[consolidated-tape-provider]]
- [[systematic-internaliser]]
- [[payment-for-order-flow]]
- [[research-unbundling]]
- [[mifid-ii-quick-fix-directive]]
- [[settlement-cycle]]
- [[esma]]
- [[fca]]
- [[brexit]]

## 출처

기준일 2026-10-26. 유럽 규정 원문(EUR-Lex)은 열람하지 못해 법무법인 요약(2차)에 의존한 항목이 있다.

1. European Parliament Legislative Observatory, MiFID II 적용 연기 지침 요약(2016-06-30): https://oeil.europarl.europa.eu/oeil/en/document-summary?id=1444194
2. (2차) McCann FitzGerald, 리서치 비용 묶음 지급 복귀(2023): https://www.mccannfitzgerald.com/knowledge/financial-services-regulation/the-long-and-winding-road-back-to-bundling-mifid-ii-research-payments
3. (2차) Dillon Eustace, MiFID/MiFIR 개정 발효(2024-04): https://www.dilloneustace.com/insights/mifid-mifir-review-changes-now-in-force
4. ESMA, Double Volume Cap Mechanism 종료 및 SVC 안내: https://www.esma.europa.eu/node/200113
5. (2차) PwC Legal Germany, 독일 PFOF 금지 전면 시행(2026-07): https://legal.pwc.de/en/news/articles/germanys-pfof-ban-is-now-fully-in-force
6. ESMA, SMS 갱신과 신규 호가 의무 공지(2025-10): https://www.esma.europa.eu/press-news/esma-news/updated-standard-market-size-sms-new-quoting-obligations-systematic
7. ESMA, Consolidated Tape Providers(2026): https://www.esma.europa.eu/node/206377
8. (2차) The TRADE, EuroCTP 인가(2026-07-27): https://www.thetradenews.com/euroctp-secures-esma-authorisation-to-operate-eu-shares-and-etfs-consolidated-tape/
9. ESMA, 통합시세 개시 기대사항 Q&A(2026-04-01): https://www.esma.europa.eu/press-news/esma-news/esma-clarifies-expectations-run-launch-eus-consolidated-tapes
10. (2차) Regulation Tomorrow(Norton Rose Fulbright), FCA 투명성 체제 정책 갱신(2023-08): https://www.regulationtomorrow.com/2023/08/fca-updates-statements-of-policy-on-the-operation-of-the-mifid-transparency-regime/
11. (2차) fi-desk, 영국 채권 통합시세 개시(2026-06-22): https://www.fi-desk.com/uk-bond-tape-launches-with-98-coverage/
12. (2차) LexisNexis, FCA 주식 통합시세 협의(2026-07-31): https://www.lexisnexis.co.uk/legal/news/fca-launches-two-consultations-supporting-an-equity-consolidated-tape
13. FCA, T+1 결제 안내(2025): https://fca.org.uk/markets/about-t1-settlement
14. ESMA, 단일룰북 MiFIR 제23조 주식 거래의무: https://www.esma.europa.eu/publications-and-data/interactive-single-rulebook/mifir/article-23-trading-obligation-investment
