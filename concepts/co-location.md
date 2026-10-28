---
type: concept
title: "Co-lo 서비스"
aliases: ["Co-lo", "co-location"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "Co-lo(co-location)는 증권회사나 거래자가 거래시장 데이터 센터의 일정 공간과 회선을 임대받아 자신의 서버를 설치할 수 있는 서비스이며, 일반투자자보다 호가 정보를 더 빨리 얻을 수 있다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
Co-lo(co-location)는 증권회사나 거래자가 거래시장 데이터 센터의 일정 공간과 회선을 임대받아 자신의 서버를 설치할 수 있는 서비스이며, 일반투자자보다 호가 정보를 더 빨리 얻을 수 있다. <sup class="src-ref">원본 p.395</sup>

## 왜 필요한가
Co-lo와 DMA 등이 활발해지면서 증권거래에 초저지연·초고속 현상이 일반화되었다. <sup class="src-ref">원본 p.395</sup>

## 내용

### 시장 패러다임 변화 ([[kcm-ch11]]) (11장)
- ESMA의 HFT 특성 첫째는 co-lo, 근접 호스팅(proximity hosting), DMA 중 하나로 거래 지연을 최소화하는 것이다. <sup class="src-ref">원본 p.397</sup>
- HFT 고유 특성으로 저지연이 필수이며 Co-lo와 개별 데이터 피드를 동원한다. <sup class="src-ref">원본 p.398</sup>
- 속도 차익거래는 거래시장에서 데이터를 직접 받거나 co-lo, DMA 등을 동원한다. <sup class="src-ref">원본 p.401</sup>
- 부디쉬·리·존 심(2021)에 따르면 거래시장은 co-lo와 맞춤형 데이터 제공으로 HFT 증권회사의 latency arbitrage 활동에서 이미 이득을 보고 있다. <sup class="src-ref">원본 p.406</sup>
- IEX가 다크풀이던 시절, 다른 브로커·딜러가 매칭 엔진을 상장거래소 데이터센터 내부/주변에 설치하고 co-lo로 최신 정보를 얻어 IEX 주문을 먼저 저격했다. <sup class="src-ref">원본 p.409</sup>
- NYSE와 Nasdaq은 speed bump를 처음의 상업적 입장대로 co-lo 수익을 방해하는 조치로 본다. <sup class="src-ref">원본 p.411</sup>

## 관련
- [[high-frequency-trading]]
- [[dma]]
- [[latency-arbitrage]]
- [[speed-bump]]
- [[broker-dealer]]
- [[investors-exchange-iex]]
