---
type: concept
title: "단주 주문"
aliases: ["odd-lot order"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "단주(odd-lot) 주문은 완전 거래단위(lot, 100주)보다 적은 수량의 주문이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
단주(odd-lot) 주문은 완전 거래단위(lot, 100주)보다 적은 수량의 주문이다. <sup class="src-ref">원본 p.322</sup> <sup class="src-ref">원본 p.326</sup>

## 왜 필요한가
기존 Reg NMS에서는 SIP의 NBBO가 완전 거래단위 주문 호가에 근거해 단주를 포함하지 않았으며, 2020년 개정은 단주 주문에 대한 일정 정보를 핵심 데이터에 넣는다. <sup class="src-ref">원본 p.292</sup> <sup class="src-ref">원본 p.322</sup>

## 내용
### 미국자본시장 주요 법제 (9장)
- Rule 603: SIP NBBO는 완전 거래단위 주문 호가에 근거해야 하고 단주는 포함되지 않는다. <sup class="src-ref">원본 p.292</sup> <sup class="src-ref">원본 p.297</sup>
- Rule 604: 대량매매, 단주, 내부집행주문은 고객 지정가주문 즉시 공개 의무에서 제외된다. <sup class="src-ref">원본 p.292</sup>
- Rule 610: 단주는 보호호가 크로쓰·록 금지에서 예외이다. <sup class="src-ref">원본 p.293</sup> <sup class="src-ref">원본 p.296</sup>
- 2020년 개정은 lot 정의를 가격 수준에 따라 4단계로 새로 구분한다. 각주에는 250달러 이하 100주, 250.01\~1,000달러 40주, 1,000.01\~10,000달러 10주, 10,000.01달러 이상 1주로 표기돼 있다. <sup class="src-ref">원본 p.322</sup> <sup class="src-ref">원본 p.327</sup>
- 기존 핵심 데이터의 최종 체결정보에는 단주 체결정보가 포함되나 BBO와 NBBO에는 단주가 불포함이다. <sup class="src-ref">원본 p.327</sup>
- 2023년 예정 Rule 605 수정은 단주 주문 등으로 주문 범주를 나누어 체결의 질적 수준 정보를 바꾸도록 하고, Rule 614 관련 단주 규정을 신속히 실행하며 "최우선 단주 주문"을 알아낼 수 있게 정의를 수정할 것을 촉구한다. <sup class="src-ref">원본 p.330</sup> (갱신 2026-10: 후속 기록은 보완 K-044-4)

## 관련
- [[market-data-infrastructure]]
- [[market-data-rules]]
- [[kcm-ch09]]
- [[nbbo]]
- [[securities-information-processor]]
