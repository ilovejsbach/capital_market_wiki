---
type: "concept"
title: "전국 최우선매수·매도호가"
aliases: ["NBBO"]
books: ["kcm"]
status: "draft"
updated: "2026-10-20"
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "NBBO(National Best Bid and Offer)는 전국 최우선매수·매도호가이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

NBBO(National Best Bid and Offer)는 전국 최우선매수·매도호가이다. <sup class="src-ref">원본 p.133</sup>

미국 정규거래소들에서 생성된 호가와 체결정보가 SIP로 보내져 마치 1개 거래소에서 이루어진 것처럼 미국 전체 최우선매수·매도호가(NBBO)를 형성한다. <sup class="src-ref">원본 p.124</sup>

## 왜 필요한가

(원자료에 없음) NBBO가 필요한 이유를 직접 설명한 문장은 없다. 3장은 NBBO가 게시된 리트풀로 주문을 회송하게 하는 규칙의 맥락에서 이를 쓴다. <sup class="src-ref">원본 p.136</sup>

## 내용

### 주식시장구조 (3장)

- 2020년 7월 현재 총 13개 정규거래소의 호가와 체결정보가 SIP로 보내진다(〈그림 3-1〉 주석). <sup class="src-ref">원본 p.124</sup> (갱신 2026-10: SEC 전국증권거래소 목록(2026년 1월 7일 갱신)에는 옵션 전용 거래소를 포함해 29개가 등재되어 있어 2020년 7월의 주식 거래소 13개와 직접 비교할 수 없다. 2020년 이후 MEMX, LTSE, 24X, Nasdaq Texas, NYSE Texas, Texas Stock Exchange(2026년 7월 거래 개시) 등 신규 주식 거래소가 등록되어 주식 거래소 수는 늘었으나, SIP 참여 주식 거래소의 정확한 현재 수는 확인되지 않았다.)
- 소매 내부화 체결가격이 리트풀의 NBBO보다 더 낫다는 주장도 만만치 않다고 지적된다(자본시장규정위원회, 2021). <sup class="src-ref">원본 p.133</sup>
- Trade-at Rule의 기본 내용은 다크 거래시장이 유입된 주문의 가격을 의미 있게(예: 5센트) 개선해 체결했다고 증명하지 못하면 NBBO가 게시된 리트풀로 회송해야 한다는 것이다. <sup class="src-ref">원본 p.136</sup>

### 미국자본시장 주요 법제 (9장)
- 1975년 개정의 목표는 기관이나 개인투자자가 NBBO(전국 최우선매수·매도호가)에 거래할 수 있게 하는 것이었다. <sup class="src-ref">원본 p.287</sup>
- Reg NMS에서 SIP NBBO는 완전 거래단위 주문 호가에 근거해야 하며 단주는 포함하지 않는다. <sup class="src-ref">원본 p.292</sup> <sup class="src-ref">원본 p.297</sup>
- 2020년 개정 후에는 competing consolidator가 각자 NBBO를 계산해 제공할 수 있어 NBBO가 여러 개 나타날 수 있다. <sup class="src-ref">원본 p.322</sup>

## 관련

- [[trade-at-rule|Trade-at Rule]]
- [[securities-information-processor|증권정보프로세서]]
- [[bbo|최우선호가(BBO)]]
- [[payment-for-order-flow|주문흐름 대가]]
- [[lit-pool|리트풀]]
- [[kcm-ch03|3장 주식시장구조]]
- [[regulated-market]]
- [[ice-nyse-group]]
