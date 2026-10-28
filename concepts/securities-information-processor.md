---
type: concept
title: "증권정보프로세서"
aliases: ["SIP"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "SIP(증권정보프로세서, 증권정보제공회사)는 상장증권을 거래하는 모든 시장의 데이터를 실시간으로 통합해 스트리밍하는 기관이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
SIP(증권정보프로세서, 증권정보제공회사)는 상장증권을 거래하는 모든 시장의 데이터를 실시간으로 통합해 스트리밍하는 기관이다. <sup class="src-ref">원본 p.289</sup> <sup class="src-ref">원본 p.322</sup>

## 왜 필요한가
기존 체제에서 NYSE와 Nasdaq이 각각 하나씩 SIP를 운영한다. <sup class="src-ref">원본 p.289</sup> NMS 주식 상장거래소는 체결 즉시 데이터를 SIP에 보내기만 하면 되고 전송 시간 의무는 없다. <sup class="src-ref">원본 p.323</sup>

## 내용
### 미국자본시장 주요 법제 (9장)
- 〈표 9-1〉에서 NASDAQ UTP Plan(1990.6)은 NASDAQ 등록증권 시장 데이터의 통합 제공을 관장하며, 실시간 스트리밍하는 SIP가 핵심 역할을 한다. <sup class="src-ref">원본 p.289</sup>
- Rule 601은 정규거래소가 SIP에 직접 보고하고 장외거래시장(ATS 포함)은 TRF를 설립해 보고하도록 한다. <sup class="src-ref">원본 p.292</sup> <sup class="src-ref">원본 p.297</sup>
- Rule 609는 "Form SIP"에 기재해 SIP를 등록하게 한다. <sup class="src-ref">원본 p.293</sup>
- 2020년 12월 개정(Rule 614)은 기존 SIP를 competing consolidator와 self-aggregator로 대체하며, 이를 3단계로 나누어 실행할 예정으로 제시된다. <sup class="src-ref">원본 p.322</sup> <sup class="src-ref">원본 p.326</sup> (갱신 2026-10: 후속 기록은 보완 K-047-1)
- 기존 "독점적 SIP 모형"에서는 NYSE와 Nasdaq이 자사 상장주식의 모든 거래시장 데이터를 각자 위임받아 운영하는 SIP에 전달한다. <sup class="src-ref">원본 p.325</sup>
- SIP에 의무적으로 보내는 핵심 데이터는 현실 수요를 반영하기에 매우 부족하다고 지적된다. <sup class="src-ref">원본 p.323</sup>

### 미국자본시장, 시장거시구조 글로벌 패러다임 리더 ([[kcm-ch06]]) (6장)
- NMS Plan에 따라 NMS 주식을 취급하는 모든 정규거래소는 호가와 체결정보를 SIP에 전송하고, SIP는 이를 통합·가공해 핵심 데이터(BBO, 체결정보, NBBO)로 최종 금융소비자에게 제공한다. <sup class="src-ref">원본 p.218</sup>
- 현재 NYSE와 Nasdaq만이 SIP이며 각자의 상장주식 정보를 별도로 관리하고, NYSE 관리 SIP는 Tape A와 Tape B, Nasdaq 관리 SIP는 Tape C를 취급한다. <sup class="src-ref">원본 p.218</sup>
- 2010년 5월 6일 Flash Crash 이후 SIP 개혁 요구가 거세졌으며, SIP의 정보 전달은 직접 공급(direct feed)보다 15마이크로초 늦다. <sup class="src-ref">원본 p.218</sup>

## 관련
- [[competing-consolidator]]
- [[market-data-infrastructure]]
- [[market-data-rules]]
- [[kcm-ch09]]
- [[nasdaq]]
- [[nyse]]
- [[regulated-market]]

## 검토 필요

- 단위 표기가 원문에서 혼재한다: SIP의 정보 전달이 직접 공급보다 “15마이크로초(ms. 15/1,000초)” 늦다고 표기돼 있어 마이크로초와 ms가 섞여 있다. 값은 원문 그대로 두고 단위는 단정하지 않는다. <sup class="src-ref">원본 p.218</sup>

## 확장 문서

- [[us-extended-hours-trading]] — 미국 주식 거래시간 확대(23/5)와 24x5 청산
