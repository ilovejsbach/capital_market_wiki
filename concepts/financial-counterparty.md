---
type: concept
title: "금융기관·비금융기관 구분(FC·NFC)"
aliases: ["FC", "NFC", "financial counterparty", "non-financial counterparty"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "EMIR는 거래상대방을 FC(financial counterparty, 금융기관)와 NFC(non-financial counterparty, 비금융기관)로 구분해 의무를 적용한다. FC는 EU 규제를 받는 투자회사…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

EMIR는 거래상대방을 FC(financial counterparty, 금융기관)와 NFC(non-financial counterparty, 비금융기관)로 구분해 의무를 적용한다. FC는 EU 규제를 받는 투자회사, 은행, 보험/재보험회사, EU 인가 매니저의 운용 펀드(UCITS), 기업연금 등이고, 이외 EU에서 장외파생상품을 거래하는 모든 기관은 NFC이다. <sup class="src-ref">원본 p.356</sup>

## 왜 필요한가

EMIR 청산의무는 거래상대방 구성(FC와 NFC+ 조합)에 따라 대상이 정해진다. <sup class="src-ref">원본 p.356</sup>

## 내용

### FC·NFC 구분 (10장)

- NFC 중에서 투기적 장외파생상품을 상한선 넘어 거래하면 NFC+, 그렇지 않으면 NFC-로 구분한다. <sup class="src-ref">원본 p.356</sup>
- 청산의무 대상 거래는 ① 양방 모두 FC, ② 일방이 FC이고 상대방이 NFC+, ③ 양방 모두 NFC+, ④ 제3국 기관으로 ①\~③에 해당하고 계약이 EU에 직접적이고 중요하며 예측할 수 있는 영향을 미치는 경우이다. <sup class="src-ref">원본 p.356</sup>
- 위험 완화 조치 중 일일 평가, 증거금 요건, 담보 교환과 자본금 요건은 FC와 NFC+에 적용한다. <sup class="src-ref">원본 p.359</sup>
- EMIR Refit: 일정 AIF를 FC에 추가하고 소형금융기관(SFC)을 신설해 청산의무에서 제외한다(위험완화 조치는 계속). NFC- 거래는 상대방 FC가 대신 보고한다. <sup class="src-ref">원본 p.360</sup>
- 표 10-3은 Dodd-Frank Act 제7편이 스왑 딜러와 주요 스왑 참여자(MPS) 중심인 데 비해 EMIR는 FC·NFC로 구분한다고 비교한다. <sup class="src-ref">원본 p.361</sup>

## 관련

- [[emir]]
- [[central-counterparty]]
- [[trade-repository]]
- [[kcm-ch10]]
- [[securities-and-futures-commission]]
- [[derivatives]]
