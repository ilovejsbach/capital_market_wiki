---
type: "institution"
title: "홍콩증권결제회사(HKSCC)와 CCASS"
aliases: ["HKSCC", "Hong Kong Securities Clearing Company", "CCASS", "중앙청산결제시스템"]
layer: "expansion"
status: "draft"
as_of: "2026-10"
updated: "2026-10-26"
extends: ["hkex"]
research: "hk-china-infrastructure"
tags: ["기관", "확장"]
description: "홍콩증권결제회사(HKSCC)는 HKEX의 100% 자회사로 홍콩 증권시장의 청산·결제·예탁을 맡는 인가청산소이며, 전산 시스템 CCASS를 운영한다. 스톡커넥트에서는 본토 청산기관 중국예탁결제와 연결되는 홍콩 측…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

> [!note] 책 밖 확장 문서
> 이 문서는 책 본문이 아니라 웹의 공식 자료를 조사해 덧붙인 확장 문서입니다. 기준일은 2026-10입니다. 근거는 문서 끝의 출처 목록에 있고, 책에서 온 문장에는 `원본 p.N`이 붙습니다.

## 정의

홍콩증권결제회사(HKSCC)는 HKEX의 100% 자회사로 홍콩 증권시장의 청산·결제·예탁을 맡는 인가청산소이며, 전산 시스템 CCASS를 운영한다. 스톡커넥트에서는 본토 청산기관 중국예탁결제와 연결되는 홍콩 측 창구다.

## 지위

- HKSCC는 SFO상 인가청산소(recognised [[clearing|clearing]] house)이며 HKEX의 100% 자회사로, 증권 청산·결제·예탁·공동 명의인 서비스를 제공한다. CCASS와 CCASS 예탁소를 소유·운영하고, 100% 자회사 HKSCC Nominees Limited가 예탁된 주식의 공동 명의인이다. <sup class="src-ref">출처 1</sup>
- CCASS는 홍콩 증권시장 거래를 위한 전산 장부 청산·결제 시스템으로 1992년 6월 가동됐다. 증서 부동화(immobilisation)를 기반으로 하고 계좌 장부 대체로 결제하며 자금결제는 HKICL 시스템으로 한다. <sup class="src-ref">출처 1</sup>

## 참가자와 자격

- HKSCC 참가자는 7종이다: 직접청산(DCP), 일반청산(GCP), 수탁(Custodian), 대주(Stock Lender), 질권자(Stock Pledgee), 청산기구(Clearing Agency), 투자자(Investor) 참가자. DCP·GCP를 합쳐 청산참가자(CP)라 한다. <sup class="src-ref">출처 1</sup>
- DCP는 [[trading-venue|거래소]]참가자이면서 SFO 유형1 인가법인이어야 하고, GCP는 유형1 인가법인·등록기관 등으로 청산 사업 능력이 있어야 한다. 수탁참가자는 인가 금융기관·신탁회사·유형1 인가법인(거래소참가자 아님) 등이며 HK$100m 상당 결함증권 책임 담보를 요구받을 수 있다. 가입비는 DCP HK$50,000(거래권당), 수탁 HK$1,000,000, 대주·질권자 HK$200,000이다. <sup class="src-ref">출처 1</sup>

## 청산·결제 구조

- HKSCC는 거래소 거래를 CNS 결제로 수락하면 노바이션([[novation|novation]])으로 매도 CP와 HKSCC(매수자), 매수 CP와 HKSCC(매도자) 두 개의 시장계약으로 대체한다. 이로써 HKSCC가 CNS 거래의 보편적 상대방(중앙청산 위험부담자)이 된다. <sup class="src-ref">출처 2</sup>
- CCASS 결제지시(SI) 거래는 참가자가 대금 지급 연동(DVP) 또는 실시간 DVP(RDP: 은행 자금결제 직후 증권결제)로 지정할 수 있다. CNS 거래의 자금 결제는 HKICL 시스템을 통한다. <sup class="src-ref">출처 2</sup>

## 규모와 재원

- 2025-12-31 HKSCC 보증기금(Guarantee Fund)은 HK$6,377mn(2024년 말 6,382mn)이다. HKSCC CNS 자금채권은 HK$43,088mn, ChinaClear에 예치한 결제준비금·결제보증기금 HK$20,867mn이다. <sup class="src-ref">출처 3</sup>
- CCASS 예탁 증권시장가치는 2026-09 월말 HK$31,246.02bn으로 허용증권 시총의 64.72%이고 편입 증권은 16,222종이다. (2024-06 비교치는 미확인으로 삭제) <sup class="src-ref">출처 4</sup>

## 스톡커넥트 청산 링크

- 후강퉁·선강퉁에서 HKSCC와 ChinaClear는 상호 참가자가 되는 청산 링크를 구축했다. HKSCC는 ChinaClear 참가자로서 A주 결제를 상하이·선전에서 ChinaClear와 하고, 홍콩에서는 CP들과 CCASS CNS로 결제한다. 이때 A주는 ChinaClear 내 HKSCC 옴니버스 증권계좌에 보유된다. <sup class="src-ref">출처 5</sup>
- HKSCC는 스톡커넥트로 매수한 [[shanghai-stock-exchange|SSE]]·[[shenzhen-stock-exchange|SZSE]] 증권의 '명의인 보유자(nominee holder)'로 ChinaClear에 증권계좌를 열고 상장사 주주명부에 등재된다. 투자자는 주주권을 HKSCC를 통해 CCASS 규칙에 따라 행사한다. <sup class="src-ref">출처 5</sup>

## 시행 예정 (확정이 아님)

- 홍콩 현물시장은 [[settlement-cycle|T+2]]이며 HKEX는 CCASS 운영 변경을 포함한 T+1 정보문서를 2026-10-16 최초 발행했다. 목표 시행은 2028년 하반기이고 규제 승인·시장 준비에 달려 있다. <sup class="src-ref">출처 6</sup>
- USM 시행(2026-11-16 예정) 이후에도 CCASS 내 기존 명의인 구조는 유지된다고 SFC가 밝혔다. 예탁·인출 절차 변경과 중개사·수탁사의 고객문서·가격 조정 필요는 법률사무소 Charltons의 분석이다. HKEX 예탁·명의인 수수료는 SFC 승인으로 개정됐다. <sup class="src-ref">출처 7</sup>

## 책과의 관계

이 위키에는 이전까지 HKSCC를 다룬 문서가 없었다. 이 문서는 참가자 구조, 노바이션 기반 청산, 보증기금, 스톡커넥트 연결을 보충한다. 일반 개념은 [[central-securities-depository]]에서 다룬다.

## 관련

- [[hkex]]
- [[stock-exchange-of-hong-kong]]
- [[china-securities-depository-and-clearing]]
- [[stock-connect]]
- [[shanghai-hong-kong-connect]]
- [[central-securities-depository]]
- [[securities-and-futures-commission]]

## 출처

기준일 2026-10-26. 사실은 독립 검증을 거쳤으며 (2차) 표시는 언론·법률사무소 자료다. 증권및선물조례 원문은 열지 못해 법적 지위는 HKEX·SFC 공식 자료로 대조했다.

1. HKSCC, Becoming a HKSCC Participant (Aug 2025); HKEX Regulatory Framework page (2025-08): https://www.hkex.com.hk/-/media/HKEX-Market/Services/Clearing/Securities/Getting-Started/Become-a-HKSCC-Participant/hkscc.pdf
2. HKSCC General Rules (Rule 3301-3303) (2026): https://www.hkex.com.hk/-/media/HKEX-Market/Services/Rules-and-Forms-and-Fees/Rules/HKSCC/Whole_HKSCCGR_e.pdf
3. HKEX 2025 Annual Results announcement (2025-12-31): https://www.hkex.com.hk/-/media/HKEX-Market/News/News-Release/2026/2602262news/2602262news_eng.pdf
4. HKEX Securities Depository Statistics (updated 2026-10-14) (2026-09-30): https://www.hkex.com.hk/Market-Data/Statistics/Clearing-and-Settlement-and-Depository/Securities-Depository-Statistics
5. HKEX Stock Connect FAQ (6 Jul 2026) (2026-07-06): https://www.hkex.com.hk/-/media/HKEX-Market/Mutual-Market/Stock-Connect/Getting-Started/Information-Booklet-and-FAQ/FAQ/FAQ_En.pdf
6. HKEX Information Paper on Accelerated Settlement (16 Oct 2026) (2026-10-16): https://www.hkex.com.hk/-/media/HKEX-Market/Services/Settlement-and-Depository/Accelerated-Settlement-for-the-Hong-Kong-Cash-Market-T1/T1-Information-Paper.pdf
7. (2차) Charltons Law (SFC announcement summary) (2026-03-30): https://www.charltonslaw.com/hong-kong-uncertificated-securities-market-regime-sfc-targets-launch-on-16-november-2026/
