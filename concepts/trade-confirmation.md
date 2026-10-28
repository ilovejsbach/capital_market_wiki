---
type: concept
title: "거래확인"
aliases: ["trade confirmation", "거래등록"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "매매확인(trade matching/confirmation)은 의도치 않은 오류를 방지하고자 매수자·매도자 양측의 세부 거래조건(예: 종목, 가격, 수량)을 비교 확인하는 청산기능의 업무이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

매매확인(trade matching/confirmation)은 의도치 않은 오류를 방지하고자 매수자·매도자 양측의 세부 거래조건(예: 종목, 가격, 수량)을 비교 확인하는 청산기능의 업무이다. <sup class="src-ref">원본 p.97</sup>

거래확인(trade confirmation)은 매수자/매도자 일방이 입력한 매매 기록을 상대방이 청산기관 매매확인시스템을 통해 확인해주는 방식이다. 매매대조(trade matching)는 매매 양측이 각자 입력한 기록을 청산기관 시스템에서 대조하는 방식이며 일반적인 방식이다. <sup class="src-ref">원본 p.97-98</sup>

## 왜 필요한가

두 방식 모두 매수자/매도자가 기관투자자 주문을 위탁받은 증권회사(브로커)라면 기관투자자의 주문 지시 내용과 자신의 매매 기록도 청산기관 매매확인시스템에서 대조/확인한다. <sup class="src-ref">원본 p.98</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 거래등록(trade registration)은 실시간 포지션관리 중 하나로 체결된 거래를 체결장(trade book)에 등록하는 업무이다. <sup class="src-ref">원본 p.98</sup>
- 매매대조 방식은 보통 체결시점 매매확인시스템을 사용하므로 원칙적으로 모든 거래가 매매체결시점에서 구속력을 가지며 자동 확정된다. <sup class="src-ref">원본 p.97-98</sup>

## 관련

- [[clearing]]
- [[central-counterparty]]
- [[netting]]
- [[kcm-ch02]]
