---
type: concept
title: "중앙청산기구"
aliases: ["CCP", "central counterparty", "집중결제상대방"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "CCP(central counterparty)는 모든 매수자에게는 매도자로서, 모든 매도자에게는 매수자로서 역할을 하는 주체(중앙청산기구)이자 서비스(집중결제상대방)를 뜻한다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

CCP(central counterparty)는 모든 매수자에게는 매도자로서, 모든 매도자에게는 매수자로서 역할을 하는 주체(중앙청산기구)이자 서비스(집중결제상대방)를 뜻한다. <sup class="src-ref">원본 p.98</sup>

## 왜 필요한가

CCP는 원래 상대방위험(상대방이 계약 의무를 제때 이행하지 못할 위험)을 통제하는 수단으로 파생상품거래에서 사용되다가 장내 증권거래로 확산됐다. <sup class="src-ref">원본 p.98</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- CCP만이 제공할 수 있는 주요 서비스는 경개, 네팅, 위험관리이다. <sup class="src-ref">원본 p.98</sup>
- 한국에서는 CCP를 문맥에 따라 청산방법일 때 집중결제상대방, 청산기관일 때 중앙청산기구/중앙청산소, 자본시장법 용어일 때 금융투자상품거래청산회사로 번역한다. <sup class="src-ref">원본 p.98</sup>
- CCP가 있으면 한 건의 매매체결은 매수·매도 두 건의 거래로 나뉘어 거래장에 등록되고 각각의 거래상대방은 CCP로 기록된다. <sup class="src-ref">원본 p.98</sup>
- 유럽주식시장에서는 LCH, Eurex Clearing, Cboe Clear Europe이 청산/청산·결제를 맡는다. <sup class="src-ref">원본 p.109</sup>
- 장외파생상품 장내 의무청산 시행에 따라 DTCC가 이 부문에 진출했다. <sup class="src-ref">원본 p.109</sup>

### 자본시장 (1장)

- 청산소는 금융상품거래의 계약이행을 보증하는 제3자로서 자본시장의 중요 인프라(FMI) 제공기관이며 별도의 독립적인 장내시장 청산기관이 없는 한국에서는 KRX 청산결제본부가 장내 청산기능을 담당한다. <sup class="src-ref">원본 p.37</sup>
- 2007\~2009년 글로벌 금융위기 이후 일정 수준 표준화한 모든 장외파생상품 거래는 의무적으로 중앙청산기구(CCP)에서 청산해야 하며 KRX도 2014년 6월 30일부터 원화이자율스왑 거래에 의무청산을 시작했다. <sup class="src-ref">원본 p.41</sup> (정정: 금융위원회, 2014-06-30)
- KRX는 국내에서 유일하게 금융위원회 인가를 받은 금융투자상품거래청산회사로서 국내 장내·외 금융/파생상품거래의 CCP 역할을 담당하며, 법령상 의무청산 대상 스왑은 원화 이자율스왑이다. <sup class="src-ref">원본 p.41</sup> (정정: 자본시장법 시행령 제186조의3 제2항, 금융투자업규정 제5-50조의5)

### EMIR의 CCP 청산의무 (10장)

- EMIR는 상대방 신용위험을 낮추려 특정 장외파생상품 거래에 CCP 청산의무를 부과했고(Article 4), 청산의무 대상 거래는 EMIR 인가 CCP에서 청산해야 한다. <sup class="src-ref">원본 p.356-357</sup>
- EU에서는 ESMA 인증(등록)을 받은 CCP만이 EU 설립 청산회원이나 거래소에 CCP 청산 서비스를 제공할 수 있고(Article 25), 제3국 CCP는 EC의 동등성 인정을 받아야 한다. <sup class="src-ref">원본 p.357</sup>
- EMIR Refit은 제3국 CCP를 tier 1(시스템적으로 중요하지 않은)과 tier 2(시스템적으로 중요한)로 나눠 감독한다. <sup class="src-ref">원본 p.361-362</sup>
- MiFID II/MiFIR는 CCP가 어느 거래시장에서 체결된 거래든 비차별적으로 청산하게 하는 상호운영성을 허용했다. <sup class="src-ref">원본 p.371</sup>

## 관련

- [[novation]]
- [[netting]]
- [[clearing]]
- [[settlement]]
- [[kcm-ch02]]
- [[financial-services-commission]]
- [[emir]]
- [[korea-exchange]]
- [[mifid-ii-mifir]]
- [[financial-investment-product]]
- [[interest-rate-swap]]
- [[capital-markets-act]]
- [[derivatives]]

## 확장 문서

- [[eu-emir-central-clearing]] — EU EMIR 중앙청산 체제
- [[london-metal-exchange]] — 런던금속거래소(LME)와 LME Clear

> [!info]- 관련 법령 조문 (자본시장법 위키 3건)
> 아래 조문은 별도 사이트인 자본시장법 위키에서 열립니다. 조문 내용은 이 사이트에 복사하지 않습니다.
>
> - [시행령 제186조의3](https://ilovejsbach.github.io/kcm_law/id/law__cma__decree__186-3.html)
> - [법 제166조의3](https://ilovejsbach.github.io/kcm_law/id/law__cma__act__166-3.html)
> - [법 제323조의3](https://ilovejsbach.github.io/kcm_law/id/law__cma__act__323-3.html)
