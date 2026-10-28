---
type: concept
title: "거래정보저장소"
aliases: ["TR", "trade repository"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "거래정보저장소(TR: trade repository)는 장내·외파생상품 거래의 양방 당사자가 거래 후 세부 사항을 보고하는 기관이다. 유럽에서는 ESMA가 인증한 TR에 보고한다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

거래정보저장소(TR: trade repository)는 장내·외파생상품 거래의 양방 당사자가 거래 후 세부 사항을 보고하는 기관이다. 유럽에서는 ESMA가 인증한 TR에 보고한다. <sup class="src-ref">원본 p.111</sup>

## 왜 필요한가

2009년 피츠버그 G20 정상회담 의무 합의사항에 따라 모든 장내·외파생상품 거래의 양방 당사자가 TR에 거래 후 세부 사항을 보고해야 했다. <sup class="src-ref">원본 p.111</sup>

이 때문에 유럽에서 TR이라는 인프라 제공기관이 새롭게 등장하며 금융데이터산업과 지수산업 시대를 열었다고 평가된다. <sup class="src-ref">원본 p.111</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- LSEG는 유나비스타(UnaVista)를 새로 설립해 글로벌 TR로 운영한다. <sup class="src-ref">원본 p.112</sup>
- 미국은 2010년 도드-프랭크법에 SDR(swap data repository) 설립을 법규화했다. <sup class="src-ref">원본 p.112</sup>
- 일본(2013년 4월), 호주(2013년 10월), 싱가포르(2014년 4월), 홍콩(2015년 7월) 등 아시아 주요 자본시장도 TR을 구축·운영했다. <sup class="src-ref">원본 p.112</sup>
- 한국은 KRX를 거래정보저장소(KRX-TR)로 선정하고 2021년 4월 출범해 운영에 들어갔다. <sup class="src-ref">원본 p.112</sup>

### 영국자본시장, 런던증권거래소 그룹을 중심으로 (5장)

- UnaVista는 LSEG 산하 글로벌 TR로 2008년 출범해 2013년 11월 TR로 인정받았다. <sup class="src-ref">원본 p.179</sup>
- MiFID II/MiFIR에 따라 유럽의 모든 장내·외파생상품 거래 당사자는 ESMA가 인정한 TR에 거래 전·후 세부 사항을 보고해야 한다. <sup class="src-ref">원본 p.179</sup>

### EU 자본시장 (7장)

- TR은 유럽판 SDR이며, 장외파생상품(대부분 스왑) 거래의 세부 정보를 중앙집중해 수집·보관·관리하는 FMI 제공기관이다. <sup class="src-ref">원본 p.251</sup>
- 2009년 피츠버그 정상회담에서 G20 국가는 모든 장외파생상품 거래의 관련 정보 보고를 의무화했다. <sup class="src-ref">원본 p.251</sup>
- ESMA는 EMIR에 정해진 TR 보고 대상 자료와 운영 기준을 근거로 TR 영업을 허가한다. <sup class="src-ref">원본 p.251</sup>
- 유럽은 2019년 1월 MiFID II/MiFIR를 시행하며 TR 제도를 보강해 ARM에 APA, CTP를 추가했고, TR 수익성이 없어졌으며 자생력 전망이 비관적이라고 평가된다. <sup class="src-ref">원본 p.252</sup>
- 유럽의 대표 TR로 LSEG UnaVista, Regis-TR, BXTR, DDR, ICE Trade Vault 등이 있다. <sup class="src-ref">원본 p.252</sup>

### EMIR의 TR 보고의무 (10장)

- EMIR 체제에서 모든 장내·외파생상품 거래 양방 당사자는 거래 후 세부 사항을 ESMA 인증 TR에 보고·저장해야 하며(Article 9), 보고 기한은 T+1, 데이터 필드는 125개에 이른다. <sup class="src-ref">원본 p.357</sup>
- EMIR Refit에서 NFC- 거래는 상대방 FC가 대신 보고하고 보고 필드 수는 203개로 증가했다. <sup class="src-ref">원본 p.360</sup>

## 관련

- [[index-and-data-provider]]
- [[financial-market-infrastructure]]
- [[clearing]]
- [[kcm-ch02]]
- [[mifid-ii-mifir]]
- [[esma]]
- [[emir]]
- [[lseg]]
- [[swap-data-repository]]
- [[g20-summit]]
- [[korea-exchange]]
- [[mifid]]
- [[derivatives]]
