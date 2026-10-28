---
type: concept
title: "네팅"
aliases: ["netting"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "네팅(netting, 차감)은 '일정 사유의 발생을 이유로 거래상대방 간의 채권·채무를 차감 계산하여 잔존채권·채무만을 거래상대방 간의 채권·채무로 확정하는 일련의 절차'로 법적으로 정의된다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

네팅(netting, 차감)은 '일정 사유의 발생을 이유로 거래상대방 간의 채권·채무를 차감 계산하여 잔존채권·채무만을 거래상대방 간의 채권·채무로 확정하는 일련의 절차'로 법적으로 정의된다. <sup class="src-ref">원본 p.99</sup>

## 왜 필요한가

불특정 다수가 참여하는 장내거래(예: 주식, 장내파생상품)에서는 다자간 네팅(multilateral netting)을 사용한다. <sup class="src-ref">원본 p.99</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 같은 종목에서 발생한 모든 매수·매도 상대방 간 거래를 대개 네팅을 거쳐 매수자/매도자별 단일 채권·채무로 산출한다. <sup class="src-ref">원본 p.97</sup>
- 경개로 CCP가 모든 거래에서 거래상대방이 되면 CCP는 자신과 각 거래상대방의 채권·채무를 네팅한 뒤 잔존채권[잔존채무]만을 확정한다. <sup class="src-ref">원본 p.99</sup>
- 그림 2-4는 총량결제, 상대차감, 형식적 상대차감, 실질적 다자간차감의 위험감축효과를 비교하며 실질적 다자간차감이 차감 효과 최대이다(번호 있음, 레코드 없음, 쪽 인용). <sup class="src-ref">원본 p.99</sup>

## 관련

- [[novation]]
- [[central-counterparty]]
- [[real-time-gross-settlement]]
- [[clearing]]
- [[kcm-ch02]]
