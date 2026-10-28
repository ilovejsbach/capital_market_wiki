---
type: concept
title: "결제"
aliases: ["settlement"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "결제(settlement)는 '거래 발생으로 거래상대방 각자가 부담해야 하는 채무를 이행하는 절차'이다. (증권)인도와 대금지급(DvP)으로 요약할 수 있다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

결제(settlement)는 '거래 발생으로 거래상대방 각자가 부담해야 하는 채무를 이행하는 절차'이다. (증권)인도와 대금지급(DvP)으로 요약할 수 있다. <sup class="src-ref">원본 p.100</sup>

결제와 함께 거래상대방 각자가 지닌 법적 의무는 사라지고 매수자·매도자 간 소유권 이전도 완료된다. <sup class="src-ref">원본 p.100</sup>

## 왜 필요한가

한국에서 결제는 증권결제시스템을 통해 이루어지며, 한국금융결제시스템은 한은금융망(BOKWire+), 소액결제시스템, 증권결제시스템(한국예탁결제원, 한국거래소), 외환결제시스템(CLS은행)이 긴밀하게 연계돼 있다. <sup class="src-ref">원본 p.100</sup> (갱신 2026-10: 한국은행은 2026-03-30부터 한은금융망 운영시간을 기존 9:00\~17:30에서 9:00\~20:00로 2시간 30분 연장해 시행하고 있다(한국은행 보도자료). 목적은 CLS 외환동시결제 종료 후에도 당일 증권대금 결제를 가능하게 해 외국인의 당일 결제 접근성을 높이는 것이다. 예탁결제원 채권기관결제시스템의 운영 연장 시행 여부는 확인하지 못했다.)

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 결제 주기(settlement cycle)는 매매체결(T+0)에서 DvP로 법적 의무가 소멸하기까지 걸리는 시간이다. <sup class="src-ref">원본 p.101</sup>
- 미국 주식시장에서는 결제·예탁을 NSCC의 결제지시를 받아 DTC가 담당한다. <sup class="src-ref">원본 p.109</sup>
- 한국주식시장에서는 KRX가 매매체결과 청산을, KSD가 결제·예탁을 나누어 담당한다. <sup class="src-ref">원본 p.110</sup>

## 관련

- [[delivery-versus-payment]]
- [[settlement-cycle]]
- [[clearing]]
- [[dematerialization]]
- [[real-time-gross-settlement]]
- [[kcm-ch02]]
- [[korea-exchange]]
- [[korea-securities-depository]]
- [[bok-monetary-board-and-wire]]
- [[bank-of-korea]]

## 확장 문서

- [[eu-csdr-and-refit]] — EU 중앙증권예탁기관 규정(CSDR)과 Refit 개정
