---
type: concept
title: "스왑체결설비"
aliases: ["SEF", "세프"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "SEF(스왑체결설비)는 장외파생상품(스왑)을 거래하는 전자 거래회사이며, DCM(파생상품거래소)이 아니라 주식시장의 ATS와 비슷하다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
SEF(스왑체결설비)는 장외파생상품(스왑)을 거래하는 전자 거래회사이며, DCM(파생상품거래소)이 아니라 주식시장의 ATS와 비슷하다. <sup class="src-ref">원본 p.214</sup>
다수의 참여자가 주문장에 매수·매도호가를 집중·게시하고 장외파생상품을 거래하는 전자 거래 시설·시스템·플랫폼이다. <sup class="src-ref">원본 p.214</sup>

## 왜 필요한가
2009년 피츠버그 정상회의에서 G20은 장외파생상품(스왑)의 전자거래와 장내 CCP 청산 의무화에 합의했고, 이로써 SEF가 미국에 새롭게 등장했다. <sup class="src-ref">원본 p.214</sup>
SEF는 장외파생상품의 사전적·사후적 투명성을 제공하며 가격발견에도 핵심 역할을 한다. <sup class="src-ref">원본 p.214</sup>
Dodd-Frank Act 7편에 따라 스왑딜러와 주요 스왑참여자는 유동성이 충분하고 표준화가 이루어진 스왑을 DCM 또는 SEF에서 매매체결해야 하고, 헤지 목적이거나 당사자 중 일방이 비금융기관이면 예외가 인정된다. <sup class="src-ref">원본 p.220</sup>

## 내용

### 미국자본시장, 시장거시구조 글로벌 패러다임 리더 ([[kcm-ch06]]) (6장)
- 장외파생상품은 거래가 자주 발생하지 않아 경쟁매매 외에 RFQ(호가 요청) 또는 협상을 통한 특정 대량매매 방식을 많이 쓰고, 익명성이 필요한 경우가 많다. <sup class="src-ref">원본 p.214</sup>
- 매매체결 후 상대방 이름을 공개하게 한 규정(post-trade name give-up)이 논란이었고, 2020년 7월 CFTC가 SEF 유동성 진작에 무게를 두고 이를 폐지해 익명성을 허용했다. <sup class="src-ref">원본 p.214</sup>
- SEF에서 거래가 발생하면 관련 정보를 (거의) 실시간으로 스왑데이터저장소에 보고하고 특정 의무사항도 CFTC에 보고해야 한다. <sup class="src-ref">원본 p.214</sup>
- 2014년 자벨린 SEF(Javelin SEF)가 최초로 CFTC 인증을 받았고, 2021년 5월 현재 CFTC 등록 SEF는 총 31개사이다. <sup class="src-ref">원본 p.214-215</sup> (갱신 2026-10: CFTC SEF 목록(2026년 10월 기준)에서 등록(Registered) 상태의 SEF는 20개사이며, 이 밖에 휴면 7개, 등록 심사중 4개, 말소 3개, 철회 3개가 있다.)
- DCM 또는 SEF가 스왑을 거래하려면 MAT(make a swap available to trade) 절차를 거치며, 이는 의무청산 대상 스왑 식별, 요건에 따른 거래 여부 결정, CFTC 인증의 세 단계이다. <sup class="src-ref">원본 p.214</sup>
- 유럽에서 이에 상응하는 기관인 OTF는 SEF보다 개념이 포괄적이다. <sup class="src-ref">원본 p.214</sup>
- 주식, 채권 또는 FX 전자 거래플랫폼을 보유한 주요 IDB는 모두 SEF도 함께 운영한다. <sup class="src-ref">원본 p.215</sup>

### 유럽판 SEF (10장)

- OTF는 채권, 구조화상품, 장외파생상품 등 비지분형상품만 재량적 방식으로 거래하는 특징 때문에 유럽판 SEF(스왑거래설비)라 불린다. <sup class="src-ref">원본 p.367</sup>

## 관련
- [[designated-contract-market]]
- [[swap-data-repository]]
- [[derivatives-clearing-organization]]
- [[cftc]]
- [[alternative-trading-system]]
- [[organized-trading-facility]]
- [[derivatives]]
