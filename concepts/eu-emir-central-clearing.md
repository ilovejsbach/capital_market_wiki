---
type: "concept"
title: "EU EMIR 중앙청산 체제"
aliases: ["EMIR 3", "EMIR 청산 체제", "EU CCP 규제", "제3국 CCP Tier", "영국 CCP 동등성"]
layer: "expansion"
status: "draft"
as_of: "2026-10"
updated: "2026-10-26"
extends: ["emir", "central-counterparty", "equivalence-regime"]
research: "overseas-post-trade"
tags: ["개념", "확장"]
description: "EMIR(Regulation (EU) No 648/2012)은 EU의 장외파생상품, CCP, 거래정보저장소 규제다. 2012년 8월 16일 발효했고 CCP·TR 관련 기술표준은 2013년 3월 15일부터 적용되었다…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

> [!note] 책 밖 확장 문서
> 이 문서는 책 본문이 아니라 웹의 공식 자료를 조사해 덧붙인 확장 문서입니다. 기준일은 2026-10입니다. 근거는 문서 끝의 출처 목록에 있고, 책에서 온 문장에는 `원본 p.N`이 붙습니다.

## 정의

EMIR(Regulation (EU) No 648/2012)은 EU의 [[derivatives|장외파생상품]], [[central-counterparty|CCP]], [[trade-repository|거래정보저장소]] 규제다. 2012년 8월 16일 발효했고 CCP·TR 관련 기술표준은 2013년 3월 15일부터 적용되었다. <sup class="src-ref">출처 1</sup> 이 문서는 책 이후의 변화, 곧 EMIR 3, 활성계좌 요건, 영국 CCP의 시한부 동등성과 ESMA의 Tier 분류를 다룬다.

## 개정 경과

- **EMIR Refit**: Regulation (EU) 2019/834로 2019년 5월 28일 EU 관보에 게재되었다. 청산의무 임계값 조정과 비금융거래상대방의 보고 대행 등을 담았다. <sup class="src-ref">출처 2</sup>
- **EMIR 3**: Regulation (EU) 2024/2987이 2024년 12월 4일 관보에 게재되어 대부분의 조항이 2024년 12월 24일 발효했다. 일부 조항은 후속 기술표준(RTS)이 발효한 뒤 적용된다. <sup class="src-ref">출처 3</sup> EMIR 3은 Regulation (EU) No 648/2012와 함께 No 575/2013(자본요건규정, CRR), 2017/1131(MMF 규정)도 개정한다. <sup class="src-ref">출처 3</sup>

## 제3국 CCP의 Tier 분류

EMIR 2.2의 틀에서 ESMA는 제3국 CCP를 둘로 나눈다. Tier 1은 시스템적으로 중요하지 않은 CCP, Tier 2는 시스템적으로 중요한 CCP다. Tier 2는 EMIR 요건을 직접 충족하거나 '동등한 준수(comparable compliance)'로 충족해야 하며 ESMA의 감독을 받는다. <sup class="src-ref">출처 4</sup>

- 한국거래소(KRX) CCP는 EMIR 25조에 따라 ESMA의 제3국 CCP로 2016년 4월 22일 인정되어 Tier 1로 분류되어 있다. 유럽위원회 이행결정 (EU) 2015/2038의 한국 동등성이 근거다. 다만 이 사실은 ESMA 인정 목록(2025년 1월 24일 갱신본)의 검색 발췌로 확인한 것이고 목록 원문 PDF는 재확인이 필요하다. <sup class="src-ref">출처 5</sup>
- 영국 CCP 가운데 [[lch|LCH]] Ltd와 [[ice|ICE]] Clear Europe는 2020년 9월 ESMA 결정에서 Tier 2, [[london-metal-exchange|LME Clear]]는 Tier 1로 분류되었다. <sup class="src-ref">출처 6</sup>

## 영국 CCP에 대한 시한부 동등성

- 유럽위원회는 2025년 1월 31일 영국 CCP에 대한 시한부 동등성을 3년 연장해 2028년 6월 30일까지로 했고, 2025년 7월 1일부터 적용한다. 사유는 EMIR 3 이행에 필요한 시간 확보와 EU의 영국 CCP 의존 축소다. <sup class="src-ref">출처 7</sup>
- ESMA는 2025년 3월 17일 영국 CCP 3곳(ICE Clear Europe, LCH Ltd, LME Clear)의 인정과 Tier 분류 적용을 2028년 6월 30일까지 연장했다. LCH Ltd는 Tier 2, LME Clear는 Tier 1이다. ESMA와 영란은행의 개정 MoU도 같은 날 체결되었다. <sup class="src-ref">출처 8</sup> 이 페이지에는 ICE Clear Europe의 Tier가 명시되어 있지 않고, 2020년 결정에서의 Tier 2 분류는 위 출처 6에서 확인된다.
- 이 동등성은 2028년 6월 30일까지의 시한부이며 그 뒤의 처리는 정해지지 않았다.

## EMIR 3의 내용

- **활성계좌 요건(AAR)**: 청산임계값을 넘는 금융·비금융 거래상대방은 유로·폴란드즐로티 금리파생상품과 유로 단기금리파생상품 중 일정 수 이상의 거래를 EU CCP의 상시 가동 활성계좌로 청산해야 한다. <sup class="src-ref">출처 3</sup> 이를 구체화한 위임규정 (EU) 2026/305는 2026년 2월 6일 관보에 게재되어 2026년 2월 26일 발효했다. <sup class="src-ref">출처 9</sup>
- **면제와 청산의무 제외**: 비청산 단일주식·[[stock-price-index|주가지수]]옵션의 [[margin|증거금]] 면제를 영구화하고, 포트폴리오 압축 같은 사후 위험감축으로 생긴 파생계약은 청산의무에서 제외한다(조건은 후속 RTS). <sup class="src-ref">출처 3</sup>
- **감독**: [[esma|ESMA]] CCP 감독위원회에 긴급권한을 주고, 공동감독팀(JST)을 두며, 각국 당국이 EU CCP를 연 1회 이상 현장검사하도록 한다. <sup class="src-ref">출처 10</sup>

## 확인하지 못한 것

- 활성계좌 요건의 최소 청산 건수와 서비스 수는 확인하지 못했다. 이 문서는 수치를 적지 않는다.
- 활성계좌 요건의 개설 기한을 적은 자료들이 서로 달라 확정하지 못했다.
- EMIR 3 감독 개편의 개별 조문 번호는 확인하지 못했다.

## 책과의 관계

책은 EMIR의 3대 의무와 Refit(2019년 6월 17일 발효)을 설명하고 <sup class="src-ref">원본 p.353</sup> <sup class="src-ref">원본 p.355</sup>, Refit이 제3국 CCP를 tier 1·tier 2로 나눠 감독한다고 서술한다. <sup class="src-ref">원본 p.361-362</sup> 또 KRX가 2015년 11월 17일 동등성을 획득했다고 한다. <sup class="src-ref">원본 p.357</sup> 이 문서의 Tier 구분은 책과 일치하고, EMIR 3(2024년 12월)과 영국 CCP 동등성의 2028년 연장, KRX의 ESMA 인정과 Tier 1 분류는 책 이후의 보충이다. 책의 동등성 결정(2015년)과 ESMA의 CCP 인정(2016년)은 서로 다른 단계로 보인다.

## 관련

- [[emir]]
- [[central-counterparty]]
- [[equivalence-regime]]
- [[esma]]
- [[european-commission]]
- [[bank-of-england]]
- [[brexit]]
- [[korea-exchange]]
- [[lch-group]]
- [[global-fmi-pfmi]]

## 출처

기준일 2026-10-26. EUR-Lex 원문과 일부 기관 페이지는 직접 열람하지 못해 로펌·언론 자료를 함께 썼다.

1. (2차) Wikipedia, European Market Infrastructure Regulation: https://en.wikipedia.org/wiki/European_Market_Infrastructure_Regulation
2. EUR-Lex, Regulation (EU) 2019/834(EMIR Refit): https://eur-lex.europa.eu/eli/reg/2019/834/oj
3. (2차) Jones Day, EMIR 3 관보 게재(2024-12): https://www.jonesday.com/en/insights/2024/12/emir-3-published-in-the-official-journal-of-the-european-union
4. ESMA, Third-country CCPs: https://www.esma.europa.eu/supervision/tc-ccps
5. ESMA, 제3국 CCP 인정 목록(ESMA70-152-348, 2025-01-24 갱신, 검색 발췌 확인): https://www.esma.europa.eu/sites/default/files/library/third-country_ccps_recognised_under_emir.pdf
6. ESMA, 영국 CCP 3곳 2021-01-01 인정(2020-09): https://www.esma.europa.eu/press-news/esma-news/esma-recognise-three-uk-ccps-1-january-2021
7. 유럽위원회, 영국 CCP 시한부 동등성 연장(2025-01-31): https://finance.ec.europa.eu/news/commission-extends-time-limited-equivalence-uk-central-counterparties-2025-01-31_en
8. ESMA, 영국 CCP 3곳의 Tier 분류와 인정 연장(2025-03-17): https://www.esma.europa.eu/press-news/esma-news/esma-extends-tiering-and-recognition-three-uk-based-ccps
9. (2차) RegulationTomorrow, 활성계좌 RTS 관보 게재(2026-02): https://www.regulationtomorrow.com/2026/02/published-in-oj-active-account-rts/
10. (2차) 유럽의회 입법 요약(EMIR 3): https://oeil.europarl.europa.eu/oeil/en/procedure-document-summary/pdf?id=1784265
