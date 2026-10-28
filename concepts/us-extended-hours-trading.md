---
type: "concept"
title: "미국 주식 거래시간 확대(23/5)와 24x5 청산"
aliases: ["미국 23/5 거래", "미국 야간 주식거래", "Nasdaq 23/5", "24X National Exchange", "NSCC 24x5 청산", "US 24-hour trading"]
layer: "expansion"
status: "draft"
as_of: "2026-10"
updated: "2026-10-26"
extends: ["nyse-arca", "nasdaq", "securities-information-processor", "after-hours-trading"]
research: "intl-jpx-us-exchanges"
tags: ["개념", "확장"]
description: "미국 주식시장은 정규장 외에 프리마켓·애프터마켓이 있었고, 2020년대 중반부터 거래소가 주 5일 거의 종일 거래하는 체계(23/5 등)를 추진하고 있다. 이 문서는 시장별로 승인, 개시 예정, 실제 시행을 구분한…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

> [!note] 책 밖 확장 문서
> 이 문서는 책 본문이 아니라 웹의 공식 자료를 조사해 덧붙인 확장 문서입니다. 기준일은 2026-10입니다. 근거는 문서 끝의 출처 목록에 있고, 책에서 온 문장에는 `원본 p.N`이 붙습니다.

## 정의

미국 주식시장은 정규장 외에 프리마켓·애프터마켓이 있었고, 2020년대 중반부터 [[trading-venue|거래소]]가 주 5일 거의 종일 거래하는 체계(23/5 등)를 추진하고 있다. 이 문서는 시장별로 승인, 개시 예정, 실제 시행을 구분한다. 승인은 시행이 아니며, 2026년 10월 26일 기준 야간 거래를 시작한 거래소는 확인하지 못했다.

## Nasdaq 23/5

- **승인**: SEC는 2026년 4월 10일 Nasdaq의 23/5 거래 제안(NMS 주식·ETP를 주 5일, 일 23시간)을 가속 승인했다. 주간 세션은 04:00\~20:00 ET, 야간 세션은 21:00\~04:00 ET이고 20:00\~21:00은 정지시간이다. 로펌 해설(2차)에 근거한다. <sup class="src-ref">출처 1</sup>
- **조건**: 승인은 조건부이며 야간 개시 전에 Nasdaq이 추가 규칙을 신청해야 한다. <sup class="src-ref">출처 2</sup>
- **개시 예정**: Nasdaq은 2026년 3분기 실적 보도자료(2026년 10월 22일)에서 23/5 거래를 2026년 12월 6일 개시 예정이라고 밝혔다. 개시는 SIP의 야간 운영 준비에 조건부다. SIP 사용자 인수시험(UAT)은 2026년 10월 2일부터 12월 4일 사이 6회 열리므로, 이 기간의 일정은 거래 개시가 아니라 시험이다. <sup class="src-ref">출처 2</sup>

## SIP 계획 수정

주식 데이터 플랜(SIP)의 운영시간 확장 수정안은 2026년 6월 26일 SEC 승인을 받았고, 승인명령은 23/5 개시일을 2026년 12월 6일로 설정했다. 그때까지 준비되지 않으면 Rule 608 수정이 필요하다. 2025년 12월 19일 제출 및 2026년 5월 27일 기한과의 비교는 확인하지 못했다. 이 설명은 SIFMA 의견서(2차)와 검증 시 직접 확인한 자료에 근거한다. <sup class="src-ref">출처 3</sup> [[securities-information-processor|SIP]]의 일반 개념은 책 문서를 참고한다.

## NYSE Arca

[[nyse|NYSE]] Arca는 2025년 2월 기성 거래소 최초로 22시간 연장 거래를 승인받았다. 이후 야간 세션(일\~목 21:00\~04:00)을 추가하는 23시간 체계 규칙을 2026년 5월 12일 제출했고, 2026년 5월 21일 SEC에 공고되었다(SR-NYSEARCA-2026-53). 이 공고는 즉시 효력 통지로 보이며 SEC 승인명령은 아니다. 23시간 체계가 승인명령을 받았는지는 확인하지 못했다. 개시 예정일은 2026년 12월 6일이며 데이터 플랜의 연장 시간 처리 능력에 조건부로, 아직 시행되지 않았다. <sup class="src-ref">출처 4</sup>

## 24X National Exchange

SEC는 2024년 11월 27일 24X National Exchange를 23시간 거래가 가능한 최초의 전국증권거래소로 승인했다. 1단계(04:00\~20:00 ET)는 2025년 10월 15일 개시했다. 2단계 23/5(일 20:00 ET\~금 20:00 ET, 매일 1시간 정지)는 2026년 하반기 개시가 목표이며, 2026년 10월 현재 야간 거래는 시작되지 않았다. 언론 보도(2차)에 근거한다. <sup class="src-ref">출처 5</sup>

## NSCC의 24x5 청산

DTCC 산하 NSCC는 2026년 6월 28\~29일 청산시간을 일요일 20:00 ET부터 금요일 20:00 ET까지로 확대한 24x5 청산을 가동했다. 단일 거래일 경계는 20:00 ET이며 2026년 1월에 테스트 환경이 열려 참가사 전원이 테스트를 통과했다. 언론 보도(2차)에 근거한다. <sup class="src-ref">출처 6</sup> 청산 인프라는 야간 거래 개시 이전에 준비된 상태다.

## 구분 요약

| 대상 | 상태 (2026-10-26) |
|---|---|
| Nasdaq 23/5 | SEC 조건부 승인(2026-04-10), 개시 예정 2026-12-06 |
| NYSE Arca | 22시간 승인(2025-02), 23시간안은 제출·즉시 효력 통지로 보임, 승인 여부 미확인, 개시 예정 2026-12-06 |
| 24X | 승인(2024-11-27), 1단계 가동(2025-10-15), 2단계 미시작 |
| SIP | 계획 수정 승인(2026-06-26), 개시일 2026-12-06 |
| NSCC | 24x5 청산 가동(2026-06) |

## 책과의 관계

책 문서 [[nyse-arca]]는 [[exchange-traded-fund|ETF]]와 옵션에 강한 NYSE 산하 거래시장으로, [[nasdaq]]은 1971년 [[finra|NASD]]의 호가 자동 통보시스템에서 출발한 시장으로 설명한다. <sup class="src-ref">원본 p.191-193</sup> <sup class="src-ref">원본 p.194</sup> 이 문서의 야간 거래 확대는 책 이후의 변화이므로 갱신이 아니라 보충이다. 책은 시간외 거래의 일반 개념만 다루며 23/5, SIP 계획 수정, 24x5 청산은 다루지 않는다. 한국 쪽 시간외·대체거래소 확대는 [[korea-ats-nextrade]]와 [[korea-lp-market-maker]]에서 다룬다.

## 관련

- [[nyse-arca]]
- [[nasdaq]]
- [[securities-information-processor]]
- [[after-hours-trading]]
- [[sec]]
- [[dtcc]]
- [[reg-nms]]
- [[reg-nms-amendments-2024-2026]]
- [[korea-ats-nextrade]]

## 출처

기준일 2026-10-26. SEC 승인명령 원문은 열람하지 못해 로펌·언론 해설(2차)에 의존한 항목이 있다.

1. (2차) Arnold & Porter, SEC의 Nasdaq 거래시간 확대 제안 승인(2026-04): https://www.arnoldporter.com/en/perspectives/advisories/2026/04/sec-approves-nasdaq-proposal-to-expand-trading-hours
2. Nasdaq, 2026년 3분기 실적 보도자료(SEC 제출 8-K 첨부, 2026-10-22): https://www.sec.gov/Archives/edgar/data/0001120193/000112019326000017/earningsrelease3q26ex-991.htm
3. (2차) SIFMA, Nasdaq 23/5 의견서(2026-03-19): https://www.sifma.org/wp-content/uploads/2026/03/SIFMA-Comment-Letter-Nasdaq-23-5-Nasdaq-2025-109_3.19.26.pdf
4. NYSE, 연장 거래 안내(열람 2026-10): https://www.nyse.com/trade/equities/extended-hours-trading
5. (2차) Markets Media, 24X 거래소의 다음 단계(2025): https://www.marketsmedia.com/24-exchange-eyes-next-phase-of-extended-hours-trading/
6. (2차) Crowdfund Insider, NSCC 24x5 청산 가동(2026-06-29): https://www.crowdfundinsider.com/2026/06/288575-dtccs-nscc-rolls-out-extended-24x5-clearing-hours-supporting-overnight-us-equities-trading/
