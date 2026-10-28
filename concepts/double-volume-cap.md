---
type: concept
title: "거래량 상한"
aliases: ["DVC", "Double Volume Cap", "SVC", "single volume cap", "다크풀 거래량 이중 상한제도"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "DVC(Double Volume Caps, 다크풀 거래량 이중 상한제도)는 MiFID II/MiFIR가 강화한 사전적 투명성 면제조항으로, 다크풀 거래량 상한 기준을 개별 다크풀 거래량과 EU 전체 다크풀 총거래량…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

DVC(Double Volume Caps, 다크풀 거래량 이중 상한제도)는 MiFID II/MiFIR가 강화한 사전적 투명성 면제조항으로, 다크풀 거래량 상한 기준을 개별 다크풀 거래량과 EU 전체 다크풀 총거래량으로 나누어 규제한다. <sup class="src-ref">원본 p.368</sup>

## 왜 필요한가

MiFID Review 결과 EC는 다크풀이 시장 분할의 부정적 측면을 우려할 만큼 많아졌고 거래량이 리트풀 가격발견을 저해할 정도로 커졌다고 평가했다. <sup class="src-ref">원본 p.367</sup>

## 내용

### 거래량 상한(DVC·SVC) (10장)

- 한도: 개별 다크풀은 종목당 직전 12개월(12-month rolling period) 거래량이 EU 전체 거래시장 총거래량의 4%를 초과할 수 없고, EU 전체 다크풀 총거래량은 종목당 8%를 초과할 수 없다. <sup class="src-ref">원본 p.368</sup>
- 위반 시: 4%[8%] 상한을 위반하면 해당 개별 다크풀[EU 모든 다크풀]은 6개월간 해당 종목을 거래할 수 없다. <sup class="src-ref">원본 p.368</sup>
- 현황: EU 전체 다크풀 거래 비중이 2020년 말 기준 8% 상한(4.5조 유로)에 육박했다. 2022년 12월 시점 ESMA 통계로 개별 다크풀에서는 112개 종목, EU 전체 다크풀에서는 439개 종목이 거래정지를 받은 상태였다. <sup class="src-ref">원본 p.368</sup>
- 면제: LIS(대량매매)와 일중 단일가매매(trading in auction)는 DVC 적용을 받지 않는다. <sup class="src-ref">원본 p.368</sup>
- 시행: DVC 시행은 2018년 3월 12일이다. 일중 단일가매매에는 온디맨드와 일중 정기 단일가매매 형태가 있다. <sup class="src-ref">원본 p.369</sup>
- SVC: 2021년 11월 25일 EU 위원회가 개정을 제안(COM(2021)727, 단일 상한 7%)해 개별 다크풀 4% 상한을 없애는 SVC(single volume cap, 단일 거래량 상한제도)를 내놓았고, 단일 거래량 상한(SVC)은 Regulation (EU) 2024/791(2024-03-28 발효)에 따라 2025-10-09 가동되어 이전 이중 상한을 대체했다. <sup class="src-ref">원본 p.369</sup> (정정: EU 위원회 COM(2021)727, 2021-11-25; ESMA, 2025-10)
- 영국: 브렉시트로 EU와 규제체제를 달리하게 된 영국은 DVC 제도 자체를 폐지하는 중이다. <sup class="src-ref">원본 p.369</sup> (갱신 2026-10: 후속 기록은 보완 K-060-2, K-060-1)
- 각주: 사전적 투명성 면제조항은 가격결정 방식에 따라 RPW(기준가격 면제조항)와 NTW(협상거래 면제조항)로 구분된다. <sup class="src-ref">원본 p.368</sup>
- MiFIR Article 5가 Volume cap mechanism이다. <sup class="src-ref">원본 p.390</sup>

### 주식시장구조 (3장)

- DVC(Double Volume Caps)는 다크풀 거래량을 두 가지 조건으로 제한하는 유럽의 제도이다. <sup class="src-ref">원본 p.136</sup>
- MiFID II/MiFIR는 투명성을 전제로 하므로 사전적 투명성이 없는 다크풀은 '사전적 투명성 면제조항'을 따르는 금융기관이며, 2018년 EU는 MiFID를 MiFID II로 개정하면서 이 면제조항을 강화했다. <sup class="src-ref">원본 p.136-137</sup>
- 4%[8%] 상한을 초과해 위반하면 해당 다크풀[EU의 모든 다크풀]은 해당 종목을 6개월간 거래할 수 없고, 제도명은 SVC로 바뀐다. <sup class="src-ref">원본 p.137</sup> (정정: ESMA, 2025-10, 2025-10-09 SVC 가동)

### 시장구조 변화 (12장)

- EU는 2018년 3월부터 DVC(다크풀 거래량 이중 상한제도)를 시작했다. 종목별 단일 다크풀 거래량은 EU 총거래량의 4%, EU 전체 다크풀은 8%[원문 표기 그대로]를 초과할 수 없고 LIS 주문이나 일중 단일가매매는 적용 예외이다. <sup class="src-ref">원본 p.434-435</sup>
- EU 위원회는 2021년 11월 25일 기존 8% 기준을 7%로 낮추고 단일 다크풀 4% 상한을 없애는 SVC(단일 거래량 상한제도) 개정을 제안했고(COM(2021)727), 단일 거래량 상한(SVC)은 Regulation (EU) 2024/791(2024-03-28 발효)에 따라 2025-10-09 가동되어 이전 이중 상한을 대체했다. <sup class="src-ref">원본 p.435</sup> (정정: EU 위원회 COM(2021)727, 2021-11-25; ESMA, 2025-10)
- 브렉시트로 EU와 별도 규제체제를 갖게 된 영국은 DVC 제도 자체를 없애려고 한다. <sup class="src-ref">원본 p.435</sup> (갱신 2026-10: 후속 기록은 보완 K-060-2, K-060-1)

## 관련

- [[dark-pool]]
- [[large-in-scale]]
- [[mifid-ii-mifir]]
- [[market-transparency]]
- [[kcm-ch10]]
- [[mifid]]
- [[call-auction]]
- [[esma]]
- [[intraday-call-auction]]
- [[brexit]]
- [[mifid-mifir-review]]

## 확장 문서

- [[mifid-mifir-review]] — MiFID II/MiFIR 개정(단일상한·PFOF 금지·통합시세)
