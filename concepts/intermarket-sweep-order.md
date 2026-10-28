---
type: concept
title: "시장 간 싹쓸이 주문"
aliases: ["ISO 주문", "ISO"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "ISO는 대량 주문제출자가 특정 거래시장의 현재 BBO와 자신의 지정가 사이에 걸친 물량을 즉시 싹쓸이해 체결하려는 주문이며, 지정가를 동반한 브로커 시장가주문이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
ISO는 대량 주문제출자가 특정 거래시장의 현재 BBO와 자신의 지정가 사이에 걸친 물량을 즉시 싹쓸이해 체결하려는 주문이며, 지정가를 동반한 브로커 시장가주문이다. <sup class="src-ref">원본 p.294</sup>

## 왜 필요한가
ISO를 쓰면 특정 거래시장이 NBBO 게시 시장이 아닐 수 있어 OPR 위반이지만 예외로 허용된다. <sup class="src-ref">원본 p.294</sup>

## 내용
### 미국자본시장 주요 법제 (9장)
- 주문제출자는 특정 거래시장에 ISO를 접수하면서 동시에 NBBO 게시 거래시장과 그보다 우선 가격을 게시한 다른 모든 시장 BBO에도 주문을 접수해 체결해야 하며, 이에 대한 책임은 주문제출자가 진다. <sup class="src-ref">원본 p.294-295</sup>
- ISO 이해에는 몽타주(quote montage), top-of-book, depth-of-book 개념이 필요하다. <sup class="src-ref">원본 p.295</sup>
- Flash Crash 때 주가 급락에 따른 손실을 줄이려는 공격적 투자가 ISO로 몰려 폭락이 배가되었다. <sup class="src-ref">원본 p.310</sup>

## 관련
- [[trade-through]]
- [[order-protection-rule]]
- [[flash-crash]]
- [[kcm-ch09]]
- [[bbo]]
- [[nbbo]]
