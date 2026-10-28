---
type: concept
title: "주문흐름 대가"
aliases: ["PFOF"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "PFOF는 소매 브로커가 도매 브로커(시장조성인, HFT 증권회사)에게 주문을 몰아주고 받는 리베이트이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
PFOF는 소매 브로커가 도매 브로커(시장조성인, HFT 증권회사)에게 주문을 몰아주고 받는 리베이트이다. <sup class="src-ref">원본 p.329</sup>

## 왜 필요한가
PFOF는 2021년 "밈 주식" 사건 때 논란으로 등장했다. <sup class="src-ref">원본 p.329</sup> Reg NMS 규칙 606·607은 PFOF를 포함한 금전적 유인의 공개를 요구한다. <sup class="src-ref">원본 p.292</sup>

## 내용
### 미국자본시장 주요 법제 (9장)
- 〈표 9-2〉에 따르면 Rule 606은 상위 10개 회송 거래시장을 공개하게 하며 PFOF 또는 이익 공유를 포함해 회송 거래시장에서 받은 금전적 유인을 밝히게 한다. <sup class="src-ref">원본 p.292</sup>
- Rule 607(고객계정표)은 모든 회송 거래시장과 맺은 연간 PFOF 정책을 공표하게 한다. <sup class="src-ref">원본 p.292</sup>
- PFOF로 시장가주문 물량을 거의 독식(약 90%)하던 시장조성인의 반발이 예상된다. <sup class="src-ref">원본 p.329</sup> (갱신 2026-10: 후속 기록은 보완 K-043-1)
- 2023년 예정 Rule 610 수정은 PFOF를 무력화할 수 있다고 지적되고, Rule 615는 PFOF 대신 qualified auction operator에서 체결되게 유도하는 규칙으로 소개된다. <sup class="src-ref">원본 p.293</sup> <sup class="src-ref">원본 p.330</sup> (갱신 2026-10: 후속 기록은 보완 K-044-2, K-043-1)

### 주식시장구조 (3장)

- 미국 주식시장에서 소매 브로커-딜러(찰스슈왑, 피델리티, 로빈후드 등)는 시장가주문 유형의 소매주문 대부분을 다크풀 도매 시장조성인에게 회송하고 주문흐름 대가(PFOF)를 리베이트로 받는다. <sup class="src-ref">원본 p.133</sup>
- 도매 시장조성인은 소매주문의 약 70%(2021년 6월 기준)를 자신의 재고로 체결(내부화)하고 나머지를 다른 거래시장에 회송한다. <sup class="src-ref">원본 p.133</sup>
- 소매 내부화는 정규거래시장의 가격발견을 저해한다고 비난받으며, 2021년 초 게임스탑 주가와 관련한 Robinhood 사태에서 비난이 극에 달했다. 한편 소매 내부화 체결가격이 NBBO보다 더 낫다는 주장도 만만치 않고, 학계 연구 결과는 엇갈리지만 대체로 소매 내부화가 소매투자자의 비용을 낮춘다는 의견이 우세하다. <sup class="src-ref">원본 p.133</sup>

## 관련
- [[order-competition-rule]]
- [[access-rule]]
- [[reg-nms]]
- [[kcm-ch09]]
- [[internalization]]
- [[market-maker]]
- [[market-order]]

## 확장 문서

- [[mifid-mifir-review]] — MiFID II/MiFIR 개정(단일상한·PFOF 금지·통합시세)
