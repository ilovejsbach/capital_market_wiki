---
type: concept
title: "통합검사추적시스템"
aliases: ["CAT", "캣"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "CAT(통합검사추적시스템)은 모든 시장참여자와 거래시장에 걸쳐 모든 주문·체결·수정 데이터를 수집·통합해 제공하는 시스템이며 Reg NMS Rule 613으로 추가되었다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
CAT(통합검사추적시스템)은 모든 시장참여자와 거래시장에 걸쳐 모든 주문·체결·수정 데이터를 수집·통합해 제공하는 시스템이며 Reg NMS Rule 613으로 추가되었다. <sup class="src-ref">원본 p.293</sup>

## 왜 필요한가
CTS·CQS·TRF 등을 운영했는데도 SEC가 Flash Crash 원인조차 제대로 규명하지 못했으며, 모든 개별시장(다크 거래시장 포함)의 데이터를 수집·통합·추적하는 시스템이 필요하다고 SEC가 판단했다. <sup class="src-ref">원본 p.313</sup>

## 내용
### 미국자본시장 주요 법제 (9장)
- Rule 613은 2012년 7월 11일 Reg NMS에 추가되었고 2022년 12월 12일 완전 가동되었다(〈표 9-2〉). <sup class="src-ref">원본 p.293</sup>
- 2012년 7월 SEC가 Rule 613을 신규 제정했고, 전국증권거래소와 FINRA가 공동 마련한 CAT NMS Plan을 2016년 7월 승인했다. <sup class="src-ref">원본 p.331</sup>
- CAT은 NMS와 OTC 주식, 상장옵션 거래 활동을 추적·감시하고 유사시 재구성하기를 바라는 시스템이다. <sup class="src-ref">원본 p.331</sup>
- CAT은 세계 최대 증권거래저장소로서 완전 운영에 들어갔고, 하루 약 580억 건(적어도 50ms까지 동기화 요구)의 과정을 추적할 수 있다. <sup class="src-ref">원본 p.331</sup>
- 설립부터 본격 운영까지의 비용과 책임은 SRO 컨소시엄이 부담했다. 2017년 1월 Plan Processor로 더시스(Thesys Technologies)를 선택했으나 2019년 2월 FINRA로 변경했다. <sup class="src-ref">원본 p.331</sup>
- 주식거래 데이터는 SRO가 2018년 11월 25일, 브로커·딜러(소규모 회원 제외)가 2020년 6월 22일부터 제공하기 시작했다. 옵션은 SRO와 브로커·딜러(소규모 회원 제외) 모두 2020년 7월 20일부터이다. <sup class="src-ref">원본 p.313</sup>
- 2022년 12월 12일부터 브로커·딜러가 CAT 고객·계좌정보시스템(CAIS)으로 고객과 계좌정보를 보고하면서 완전 가동이 시작되었다. <sup class="src-ref">원본 p.313-314</sup>
- 처음에는 증권회사 고객의 SSN, 생년월일, 계좌번호 등을 포함하려 했으나 개인정보 누출 논란으로 CAT ID 번호, 출생연도, 이름과 주소만 포함하기로 변경했다. <sup class="src-ref">원본 p.332</sup>
- 2021년 9월 1일부터 CAT이 OATS를 대체했다. <sup class="src-ref">원본 p.331</sup>

### 주식시장구조 (3장)

- CAT은 SEC 인가를 받은 중앙거래저장소로, 브로커·딜러, 거래시장, SRO가 적격증권을 주문제출에서 결제·예탁까지 거래 전 과정에서 어떻게 다뤘는지에 대한 정보를 담는다. <sup class="src-ref">원본 p.129</sup>
- Reg NMS Rule 613을 제정하며 2012년부터 설립을 추진했으나 설립비용 때문에 지연되다 2022년 12월 12일 본격 운영에 들어갔고, SRO가 컨소시엄 형태로 공동 소유·운영한다. <sup class="src-ref">원본 p.129</sup>

### 미국자본시장, 시장거시구조 글로벌 패러다임 리더 ([[kcm-ch06]]) (6장)
- SEC는 2019년 3월 CAT 설립을 추진하기 시작했고, CAT은 2022년 12월 12일 완전한 형태로 운영을 시작했다. <sup class="src-ref">원본 p.219</sup>
- 이로써 미국은 모든 상장주식과 옵션거래(비상장주식 장외거래 포함) 전 과정을 추적할 수 있게 되었다. <sup class="src-ref">원본 p.219</sup>
- CAT 설립과 시행·유지 제도(CAT NMS Plan)는 2012년 7월 Rule 613으로 Reg NMS에 추가되었다. <sup class="src-ref">원본 p.219</sup>

## 관련
- [[reg-nms]]
- [[flash-crash]]
- [[kcm-ch09]]
- [[self-regulation]]
- [[sec]]
- [[consolidated-market-data-plan]]
- [[finra]]
