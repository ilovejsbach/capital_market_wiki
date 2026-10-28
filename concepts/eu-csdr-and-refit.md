---
type: "concept"
title: "EU 중앙증권예탁기관 규정(CSDR)과 Refit 개정"
aliases: ["EU CSDR", "Regulation (EU) No 909/2014", "Regulation (EU) 2023/2845", "EU 결제규율"]
layer: "expansion"
status: "draft"
as_of: "2026-10"
updated: "2026-10-26"
extends: ["central-securities-depository", "settlement"]
research: "csdr-iex-cmim"
tags: ["개념", "확장"]
description: "CSDR(Regulation (EU) No 909/2014)은 EU의 증권결제 규율과 중앙증권예탁기관(CSD) 규율을 한꺼번에 정한 규정이다. 2014년 8월 28일 EU 관보에 게재되어 2014년 9월 17일 발…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

> [!note] 책 밖 확장 문서
> 이 문서는 책 본문이 아니라 웹의 공식 자료를 조사해 덧붙인 확장 문서입니다. 기준일은 2026-10입니다. 근거는 문서 끝의 출처 목록에 있고, 책에서 온 문장에는 `원본 p.N`이 붙습니다.

## 정의

CSDR(Regulation (EU) No 909/2014)은 EU의 증권결제 규율과 [[central-securities-depository|중앙증권예탁기관(CSD)]] 규율을 한꺼번에 정한 규정이다. 2014년 8월 28일 EU 관보에 게재되어 2014년 9월 17일 발효했다. <sup class="src-ref">출처 1</sup> 결제 기간 단축, 결제 실패에 대한 현금 벌금 같은 억지책, CSD의 조직·영업행위·건전성 요건, 역내 서비스 제공 여권, CSD와 결제 지원 은행의 건전성·감독 강화가 주요 조치다. <sup class="src-ref">출처 1</sup>

조문 가운데 확인된 것은 다음과 같다. 제5조(2)는 [[trading-venue|거래소]]·[[multilateral-trading-facility|MTF]] 거래의 결제 기간을 거래 후 2영업일로 정했고, 이를 1영업일로 줄이는 개정(Regulation (EU) 2025/2075)은 2027년 10월 11일 적용된다. <sup class="src-ref">출처 2</sup> 제6조는 결제 실패 예방, 제7조는 결제규율(현금 벌금), 제7a조는 필수 바이인(mandatory buy-in)을 다룬다. <sup class="src-ref">출처 2</sup> <sup class="src-ref">출처 4</sup> T+1 전환 자체는 [[eu-t1-settlement-cycle]]에 있으므로 여기서는 반복하지 않는다.

## 결제규율: 현금 벌금

결제 실패에 대한 현금 벌금은 2022년 2월 1일부터 EU CSD가 운영하는 결제시스템의 미결제 지시에 적용되고 있다. 실패한 쪽에 의도 결제일 이후 미결제된 영업일마다 일일 벌금을 매긴다. <sup class="src-ref">출처 1</sup> ESMA는 이후 결제 실패가 줄었으나 그 폭은 완만하며 [[exchange-traded-fund|ETF]] 등 일부 자산군은 여전히 실패율이 높다고 평가했다. <sup class="src-ref">출처 1</sup>

현행 일일 벌금율은 ESMA 보고서 표 3의 '현행' 열 기준으로 다음과 같다. 벌금은 참조가격에 요율을 곱해 산정한다. <sup class="src-ref">출처 1</sup>

| 대상 | 현행 | ESMA 권고(2024-11) |
|---|---|---|
| 유동성 있는 주식 | 1.0bp | 유지 |
| 유동성 없는 주식 | 0.5bp | 0.75bp |
| SME 성장시장 주식 | 0.25bp | 유지 |
| SME 성장시장 채무증권 | 0.15bp | 유지 |
| 국채 등 공공 발행자 채무증권 | 0.10bp | 0.20bp |
| 기타 채무증권 | 0.20bp | 0.30bp |
| 기타 금융상품(ETF 포함) | 0.5bp | 0.75bp |

현금 부족으로 인한 실패는 결제통화 중앙은행의 익일물 대출 금리를 적용하며 현행 하한은 0이다. <sup class="src-ref">출처 1</sup>

위의 '권고' 열은 확정이 아니다. ESMA가 2024년 11월 19일 최종 기술자문으로 유럽위원회에 권고한 것이고, ESMA의 CSD 페이지는 이를 'Pending adoption'으로 표시한다. 위원회가 채택했다는 근거는 찾지 못했다. <sup class="src-ref">출처 1</sup> <sup class="src-ref">출처 3</sup>

위임규정 2023/1626은 중앙청산소(CCP)가 결제에 제출한 청산 거래의 실패 벌금을 CCP가 아니라 CSD가 징수·배분하도록 바꿨고 2024년 9월 2일부터 적용된다. <sup class="src-ref">출처 8</sup> 이 적용일은 법무법인 자료 하나에만 있다.

## 필수 바이인

필수 바이인은 CSDR 원안에 있었으나 시행이 미뤄졌다. Regulation (EU) 2022/1930이 바이인 제도의 발효·적용일을 2025년 11월 2일로 미뤘다. <sup class="src-ref">출처 3</sup> Refit 이후 필수 바이인은 최후 수단이다. 위원회가 시행법으로 대상 상품·거래 범주를 정해야 하고, 벌금·참가자 정지 같은 수단이 결제 실패를 지속적으로 줄이지 못했으며 실패가 EU 금융안정에 부정적 영향을 주거나 줄 가능성이 있을 때만 쓸 수 있다. 위원회는 ESRB와 협의하며, [[securities-finance|증권금융]]거래 등은 제외된다. <sup class="src-ref">출처 4</sup> ESMA의 비용편익 분석을 거친다는 점은 법무법인 해설에 있다. <sup class="src-ref">출처 7</sup>

이 시행법은 아직 채택되지 않았다. 룩셈부르크 법무법인 Arendt의 규제 일정 정리는 위원회가 2025년 10월 6일 업데이트에서 이를 '2027년 10월 1일 이전에는 채택하지 않을' 비필수 하위 입법 목록에 두었다고 전한다. 위원회 원문과는 대조하지 못했다. <sup class="src-ref">출처 9</sup> 따라서 필수 바이인은 사실상 적용되지 않는 상태다.

## CSDR Refit(Regulation (EU) 2023/2845)

정식 제목은 결제규율, 역내 서비스 제공, 감독 협력, 은행형 부수서비스 제공, 제3국 CSD 요건에 관해 규정 909/2014를 개정하고 [[short-selling|공매도]]규정(236/2012)을 개정하는 규정이다. <sup class="src-ref">출처 1</sup>

**입법 경과.** 2020년 9월 24일 자본시장동맹 행동계획에 CSDR 검토가 들어갔고, 2021년 7월 1일 CSDR 보고서, 2022년 3월 16일 위원회 입법 제안, 2023년 6월 28일 정치적 합의를 거쳐 2023년 12월 13일 서명, 2023년 12월 27일 관보에 게재되었다. <sup class="src-ref">출처 6</sup> <sup class="src-ref">출처 1</sup>

**발효일.** 관보 게재 20일째인 2024년 1월 16일이라는 자료가 많다. 유럽위원회 C(2026)4640 본문, Norton Rose Fulbright·Arthur Cox·Societe Generale가 이 날짜를 쓴다. <sup class="src-ref">출처 2</sup> <sup class="src-ref">출처 7</sup> 반면 ESMA의 2024년 11월 보고서는 요약과 도입부에서 2024년 1월 17일이라고 적는다. <sup class="src-ref">출처 1</sup> 두 값이 갈리는 원인은 확인하지 못했다. 다만 ESMA 단일규칙집 제69조 4a·4c도 기준일로 '2024년 1월 16일'을 쓴다. <sup class="src-ref">출처 5</sup>

**주요 내용.**

- 결제규율 정비와 필수 바이인의 최후 수단화(위 절). <sup class="src-ref">출처 4</sup>
- 노터리·중앙계좌관리 서비스의 역내 여권에서 발행지 회원국법과 준거 회사법을 함께 고려한다. <sup class="src-ref">출처 7</sup>
- 은행형 부수서비스를 지정 신용기관뿐 아니라 다른 인가 CSD에서도 받을 수 있게 하고, 이를 위한 한도 기준을 EBA가 ESMA와 함께 정한다. <sup class="src-ref">출처 7</sup>
- 둘 이상 호스트 회원국에서 활동이 실질적으로 중요한 CSD에는 감독협의체(college)를 의무화한다. <sup class="src-ref">출처 7</sup>
- 제3국 CSD는 EU 회원국 법에 따라 발행된 증권의 결제 서비스를 제공하기 전에 ESMA에 통지해야 한다. 2026년 1월 17일 이전에 이미 해당 핵심 서비스를 제공한 제3국 CSD는 2026년 1월 17일까지 통지해야 했다(제69조 4b). 국가별 인정 규정은 ESMA 결정이 나오거나 2027년 1월 17일 중 먼저 오는 때까지 계속 적용된다(제69조 4a). 2024년 1월 16일 이전에 완비된 신청서를 낸 CSD는 ESMA 결정까지 국가 규정을 유지한다(제69조 4c). <sup class="src-ref">출처 5</sup>

**T+1과의 연결.** Refit은 T+1을 직접 부과하지 않고 ESMA가 결제주기 단축의 장단점을 평가해 보고하도록 했다. ESMA 평가 보고서는 2024년 11월 18일 발간되었고 <sup class="src-ref">출처 2</sup> 위원회는 2025년 2월 12일 단축 제안을, 2025년 6월 18일 정치적 합의를 발표했다. <sup class="src-ref">출처 6</sup>

**ESMA의 후속 산출물.** 2024-11-19 벌금 기술자문, 2025-02-20 CSD 실질적 중요성 RTS·검토평가·제3국 CSD 보고 개정 최종보고서, 2025-06-26 결제규율 범위 자문, 2025-10-13 결제규율 RTS 개정 최종보고서다. <sup class="src-ref">출처 3</sup>

## 결제규율 RTS 개정: 위임규정 C(2026) 4640

유럽위원회는 2026년 7월 6일 결제규율 RTS(위임규정 2018/1229)를 개정하는 위임규정 C(2026) 4640을 채택했다. 제안이 아니라 위원회가 채택한 문서다. 관보 게재 후 20일째 발효하며 2026년 12월 7일부터 적용하되, 일부 조항은 2027년 7월 1일, 일부는 2027년 10월 11일부터 적용한다. <sup class="src-ref">출처 2</sup> 관보에 공포되었는지는 확인하지 못했으므로 발효 여부는 알 수 없다.

내용은 CSD의 자동 부분결제 제공 의무, 실시간 총액결제([[real-time-gross-settlement|RTGS]]) 또는 영업일 3회 이상 배치 제공, 담보 자동화 기반 일중 현금신용 접근 지원, 소매고객 결제정보를 거래일 23:00 CET까지 [[investment-firm|투자회사]]에 전달, 결제 실패 사유 보고 강화 등이다. ESMA는 2025년 10월 13일 최종보고서(초안 RTS)를 제출했고 공개협의는 2025년 2월 13일부터 4월 14일까지였다. <sup class="src-ref">출처 2</sup> 이 규정은 벌금율이 아니라 결제규율 RTS를 고치는 것이므로 위 벌금율 권고와 별개다.

## 확인하지 못한 것

- **Refit 조항별 적용일.** Refit의 대부분은 발효와 함께 적용되나 일부는 2024년 5월 1일, 일부는 2026년 1월 17일부터 적용된다는 사실만 법무법인 자료로 확인했다. EUR-Lex 원문을 열람하지 못해 어느 조항이 어느 날짜인지 알 수 없다. 2026년 1월 17일은 제3국 CSD 통지 기한(제69조 4b)만 확인했고, 2024년 5월 1일에 적용되는 조항은 확인하지 못했다. <sup class="src-ref">출처 7</sup> <sup class="src-ref">출처 5</sup>
- **Refit 발효일 충돌.** 2024-01-16(유럽위원회 C(2026)4640, 로펌 3곳, Societe Generale)과 2024-01-17(ESMA 보고서)이 서로 다르며 원인은 확인하지 못했다.
- **현금 부족 벌금 하한의 인상 폭.** ESMA 보고서 요약은 하한을 '0에서 1로', 같은 보고서 표 3은 '1.28로' 올린다고 적어 보고서 안에서 충돌한다. 인상 방향만 확인되며 수치는 쓰지 않는다.
- **벌금율 인상의 채택 여부.** 권고 단계라는 것만 확인했고 위원회 채택 근거는 찾지 못했다.
- **C(2026) 4640의 관보 공포.** 발효 여부를 확인하지 못했다.
- **CSD 인가·감독 조문의 범위.** 제3편 제1장(제10조\~제25조)이라는 서술은 조문 목차를 보여주는 2차 자료 하나에만 있고, EUR-Lex와 ESMA 단일규칙집 목차가 막혀 확인하지 못했다. 그래서 본문에는 제5·6·7·7a조만 썼다.
- **위임규정 2021/70의 번호.** 벌금제가 2022년 2월 1일 적용된다는 것은 확인했으나, 이를 정한 위임규정이 2021/70이라는 번호는 ESMA 보고서에서 확인하지 못했다.

## 책과의 관계

책 문서 [[central-securities-depository]]와 [[settlement]]는 CSD의 기능과 결제 일반을 다루며 EU의 CSD 규율 규정은 다루지 않는다. 책 문서 [[settlement-cycle]]은 EU의 T+1 전환을 갱신 문구로 이미 적고 있다. 이 문서는 그 배경인 CSDR의 결제규율, 필수 바이인, Refit을 보충하는 것으로, 책 내용과 충돌하는 부분은 없다. 책 문서는 수정하지 않았다.

## 관련

- [[eu-t1-settlement-cycle]]
- [[central-securities-depository]]
- [[settlement]]
- [[settlement-cycle]]
- [[euroclear-clearstream-t2s]]
- [[esma]]
- [[central-counterparty]]
- [[eu-emir-central-clearing]]

## 출처

기준일 2026-10-26. EUR-Lex 원문은 열람하지 못했다. (2차)는 법무법인 해설이다.

1. ESMA, Final Report on Technical Advice on CSDR Penalty Mechanism(2024-11-19): https://www.esma.europa.eu/sites/default/files/2024-11/ESMA74-2119945925-2059_Final_Report_on_Technical_Advice_on_CSDR_Penalty_Mechanism.pdf
2. 유럽위원회, 위임규정 C(2026) 4640 final(2026-07-06): https://ec.europa.eu/transparency/documents-register/api/files/C(2026)4640_0/090166e5300db9e0
3. ESMA, Central Securities Depositories: https://www.esma.europa.eu/esmas-activities/markets-and-infrastructure/central-securities-depositories
4. ESMA 단일규칙집, CSDR 제7a조: https://www.esma.europa.eu/publications-and-data/interactive-single-rulebook/csdr/article-7a-mandatory-buy-process
5. ESMA 단일규칙집, CSDR 제69조(경과규정): https://www.esma.europa.eu/publications-and-data/interactive-single-rulebook/csdr/article-69-transitional-provisions-0
6. 유럽위원회 금융시장 총국, Central securities depositories (CSDs): https://finance.ec.europa.eu/capital-markets-union-and-financial-markets/financial-markets/post-trade-services/central-securities-depositories-csds_en
7. (2차) Norton Rose Fulbright, CSDR Refit: the key changes: https://www.nortonrosefulbright.com/en/knowledge/publications/3fec092d/csdr-refit-the-key-changes
8. (2차) Arthur Cox, CSDR targeted reforms published in Official Journal(2024-01): https://www.arthurcox.com/insights/csdr-targeted-reforms-published-in-official-journal-looking-ahead-to-2024/
9. (2차) Arendt, IFM regulatory calendar: market conduct regulation(2025-10): https://www.arendt.com/news-insights/ifm-regulatory-calendar/market-conduct-regulation/
