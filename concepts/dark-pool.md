---
type: concept
title: "다크풀"
aliases: ["다크 거래시장", "dark pool"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "다크풀(dark pool)은 코머튼-포드·푸투닌스(2015)가 “사전적 투명성 없이 주문을 시스템적으로 매칭하는 ATS”로 정의했고, 부티·린디·베르네르(2017)는 최우선호가 주문을 CQS에 포함하지 않고 비공개…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

다크풀(dark pool)은 코머튼-포드·푸투닌스(2015)가 “사전적 투명성 없이 주문을 시스템적으로 매칭하는 ATS”로 정의했고, 부티·린디·베르네르(2017)는 최우선호가 주문을 CQS에 포함하지 않고 비공개 주문끼리 NBBO 이상의 가격에 체결하는 ATS라고 정의한다. <sup class="src-ref">원본 p.431</sup> 다크풀은 ATS(대체거래시스템)의 한 형태로 리트풀과 함께 언급된다. <sup class="src-ref">원본 p.78</sup> <sup class="src-ref">원본 p.106</sup>

## 왜 필요한가

크로씽 방식은 대부분 대량매매를 취급하는 거래시장(예: 다크풀)에서 채택된다. <sup class="src-ref">원본 p.90</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 미국의 거래시장 약 260여 군데는 17개 정규거래소, 50여 개 ATS(리트풀과 다크풀), 200여 개 내부화 IB를 포함한다. <sup class="src-ref">원본 p.78</sup>
- 그림 2-1 패널 B는 3개 정규거래소, 1개 다크풀, 1개 내부화 IB 등 5개 거래시장을 가정한 단순화 도표이다. <sup class="src-ref">원본 p.79</sup>
- 그림 2-6 설명에는 3,500개 이상의 FINRA 등록 브로커와 32개(지금은 50여 개) 다크풀이 있다. <sup class="src-ref">원본 p.107</sup>
- 거래소와 다크풀 간 경쟁이 심한 유럽에서는 거래소가 빼앗긴 유동성을 되찾으려고 일중 단일가매매를 실행한다. <sup class="src-ref">원본 p.88</sup>

### 영국자본시장, 런던증권거래소 그룹을 중심으로 (5장)

- Turquoise는 다크풀과 리트풀을 함께 운영하며 주로 다크풀이고, MiFID II/MiFIR의 다크풀 규제 강화에 대응해 Plato Partnership을 결성했다. <sup class="src-ref">원본 p.171</sup>
- MiFID II는 건당 거래량 650,000유로 이상을 대량매매(LIS)로 정의하고 다크풀 사전적 투명성 의무를 면제한다. FCA는 브렉시트 뒤 이 기준을 15,000유로로 낮췄다. <sup class="src-ref">원본 p.161</sup>

### 미국자본시장, 시장거시구조 글로벌 패러다임 리더 ([[kcm-ch06]]) (6장)
- 다크풀은 소유구조에 따라 브로커·딜러형(시장점유율 62%), 중개 브로커형(21%), EMM형(17%)으로 나뉘며, 이 구분은 로젠블랏증권사 2019년 자료에 근거한다. <sup class="src-ref">원본 p.209-210</sup>
- 2021년 5월 현재 50개 다크풀과 200여 개 내부화 IB가 총 45.2%의 역대 최고 시장점유율을 보인다. <sup class="src-ref">원본 p.210</sup> (갱신 2026-10: Cboe 집계에 따르면 2025년 미국 주식의 장외(TRF 보고) 거래는 통합거래량의 50.6%로 처음 절반을 넘었다. 이 장외 거래 중 ATS(다크풀 포함)는 18.7%(통합거래량의 약 9.5%)이고 나머지 81.3%는 주요 딜러(내부화)가 체결했다(2025년 기준, 집계기관이 달라 책의 2021년 45.2%와 단순 비교에는 주의).)
- 장점은 가격충격을 최소화하며 대량매매를 할 수 있고 가격도 정규거래소보다 낫게 얻을 수 있다는 것이다. <sup class="src-ref">원본 p.211</sup>
- 비판은 소매투자자 피해 가능성, 낮은 투명성에 따른 선행매매·약탈적 전략 피해, 건당 평균 187주(2020년 1월 기준)로 대량매매 기능을 잃었다는 점이다. <sup class="src-ref">원본 p.211</sup>

### 다크풀 각주 (8장)

- 다크풀의 설립 목표는 대량매매 보호이며, 부작용이 있다고 그 부분만 도려낼 수 없다는 취지로 정책철학의 상위개념이 강조된다. <sup class="src-ref">원본 p.271</sup>

### 미국자본시장 주요 법제 (9장)
- Sub-penny Rule 예외로 다크 거래시장(다크풀+내부화 IB)에서의 거래가 허용되며 주로 HFT가 활용한다. <sup class="src-ref">원본 p.296</sup>
- 다크풀과 HFT는 SEC 예상보다 훨씬 빠르게 진화하며 시장구조를 변모시켰다. <sup class="src-ref">원본 p.314</sup>
- Tick Size Pilot Program 테스트그룹 3에 부가된 Trade-at Rule은 다크풀이 가격을 개선해주지 못하면 리트풀로 회송하라고 규정하며, 해당 종목 다크풀 거래량은 SEC 의도대로 많이 감소했다. <sup class="src-ref">원본 p.333-334</sup>

### MiFID II/MiFIR의 다크풀 규제 (10장)

- MiFID에서 사전적 투명성을 적용받지 않는 다크풀은 사전적 투명성 면제조항을 두어 규정했다. <sup class="src-ref">원본 p.367</sup>
- MiFID II/MiFIR는 거래량 이중 상한(DVC)으로 규제를 강화했고, 2021년 11월 25일 위원회가 제안한 SVC(단일 상한 7%)로 재차 강화했고, 단일 거래량 상한(SVC)은 Regulation (EU) 2024/791(2024-03-28 발효)에 따라 2025-10-09 가동되어 이전 이중 상한을 대체했다. <sup class="src-ref">원본 p.368-369</sup> (정정: EU 위원회 COM(2021)727, 2021-11-25; ESMA, 2025-10)

### 시장구조 변화 (12장)

- "다크 거래시장"은 다크풀과 내부화 IB를 합친 용어이다. <sup class="src-ref">원본 p.429</sup>
- 미국주식시장에서 다크 거래시장 점유율은 2020년 7월 기준 약 35%(다크풀 12%, 내부화 IB 23%)이고 2009년 11월 9.6%, 2016년 6월 35.1%와 비교한다. <sup class="src-ref">원본 p.429-430</sup>
- 유럽은 2021년 3월 기준 다크 MTF(다크풀) 7.9%, 리트 MTF(리트풀) 18.9%, SI 14%이고 정규거래소 거래 비중은 총 44.6%이다. <sup class="src-ref">원본 p.430</sup>
- 다크풀은 대량매매(보통 1만 주/1백만 달러 이상 주문) 체결 메커니즘의 한계를 극복하려 도입되었고 upstairs market과 장내브로커를 ICT로 시스템화한 거래시장이다. <sup class="src-ref">원본 p.430-431</sup>
- 정의로 Comerton-Forde and Putniņš(2015)는 "사전적 투명성 없이 주문을 시스템적으로 매칭하는 ATS"라 했고 Buti, Rindi, and Werner(2017)는 최우선호가 주문을 CQS에 포함하지 않고 비공개 주문끼리 NBBO 이상의 가격에 체결하는 ATS라고 했다. <sup class="src-ref">원본 p.431</sup>
- 정책담당자는 상장주식 가격발견이 리트풀에서 이루어져야 하고 다크풀은 대량매매라는 본연의 목적에만 충실해야 한다고 생각을 굳힌 듯하다고 지적된다. <sup class="src-ref">원본 p.432-433</sup>
- 2014년 6월 미국 상위 5개 다크풀의 건당 평균 거래량은 187주에 불과했다. <sup class="src-ref">원본 p.432</sup>
- 규제로 미국은 일정 수준의 사전적 투명성 제공, 거래정보의 실시간에 가까운 배포, 일반 주문 우선 처리를 요구하고 2018년 10월 Reg ATS를 수정해 운영사항 공개를 강화했다. <sup class="src-ref">원본 p.433-434</sup>
- 학계는 Zhu(2014)의 긍정적 가격발견 효과와 Ye and Zhu(2020)의 부정적 효과로 이론 결과가 갈리며 실증연구는 리트풀 가격발견에 좋지 않은 영향을 준다는 연구가 우세해 보인다. <sup class="src-ref">원본 p.435-437</sup>

### 법제 (16장)

- 다자간매매체결회사는 미국 Reg ATS의 리트풀/다크풀에 해당한다. <sup class="src-ref">원본 p.567</sup>
- 국내에서 다크풀은 여전히 미지의 세계로 남아 있으며, 논란의 여지는 있지만 글로벌 선도자본시장에서는 경쟁매매와 비경쟁매매를 동원해 대량매매에 시장충격을 줄이면서 유동성을 제공하는 긍정적 역할을 하는 것으로 평가된다. <sup class="src-ref">원본 p.571</sup>

## 관련

- [[lit-pool]]
- [[crossing]]
- [[block-trade]]
- [[trading-venue]]
- [[internalization]]
- [[kcm-ch02]]
- [[alternative-trading-system]]
- [[mifid-ii-mifir]]
- [[market-transparency]]
- [[double-volume-cap]]
- [[regulated-market]]
- [[mifid]]
- [[price-discovery]]
- [[bbo]]
- [[competitive-trading]]
- [[consolidated-market-data-plan]]
- [[high-frequency-trading]]
- [[multilateral-trading-facility]]
- [[nbbo]]
- [[sec]]
- [[reg-ats]]
- [[mifid-mifir-review]]
