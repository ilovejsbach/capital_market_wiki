---
type: concept
title: "고빈도거래"
aliases: ["HFT", "초단타매매", "스캘핑"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "HFT(high frequency trading)는 보유기간을 초단기(주로 1일)로 잡고 그사이 순간적(ms, μs 단위) 거래를 반복 구사하는 전략에 동원하는 거래방식이나 세련된 형태의 테크놀로지 수단이며, HF…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
HFT(high frequency trading)는 보유기간을 초단기(주로 1일)로 잡고 그사이 순간적(ms, μs 단위) 거래를 반복 구사하는 전략에 동원하는 거래방식이나 세련된 형태의 테크놀로지 수단이며, HFT 자체가 전략은 아니다. <sup class="src-ref">원본 p.397-398</sup>
ESMA는 HFT를 세 특성을 띤 초단타 알고리즘 거래 기법으로 MiFID II/MiFIR에 명문화한다: 미리 정해놓은 알고리즘으로 주문을 자동 제출할 때 co-lo, 근접 호스팅, DMA 중 하나로 거래 지연을 최소화하고, 주문 설계부터 체결까지 인적 개입이 없거나 최소화되며, 주문 제출과 취소/정정에 일중 엄청난 양의 메시지를 활용한다. <sup class="src-ref">원본 p.397</sup>

## 왜 필요한가
HFT는 대개 질적/서술적 방식으로 정의하며, "종목당 하루 10,000회(임의로 정함) 이상 주문 활동을 하는 거래자"라는 정량 기준에는 9,999회 주문 거래자를 제외하는 한계가 있다. <sup class="src-ref">원본 p.396</sup>
미국 SEC는 컨셉 릴리즈로 특성만 확인할 뿐 HFT를 공식적으로 정의하지 않는다. <sup class="src-ref">원본 p.396-397</sup>

## 내용

### 시장 패러다임 변화 ([[kcm-ch11]]) (11장)
- HFT 고유 특성은 고유계정거래, 유동성이 풍부한 종목, 당일 거래 종료와 함께 포지션 해소, 엄청나게 많은 주문 건수와 95% 이상의 시장조성 전략 사용, 저지연 필수(Co-lo와 개별 데이터 피드 동원)이다. <sup class="src-ref">원본 p.398</sup>
- HFT는 레버리지를 거의 활용하지 않고 일중 포지션을 평균에 회귀하도록 하다가 장 마감 직전 대부분 청산한다. <sup class="src-ref">원본 p.399</sup>
- HFT가 주식거래에서 차지하는 비중은 2019년 중반 미국 50%, 유럽 24\~43%이며, 2017년에는 미국 56\~73%, 유럽 38\~40%였다. <sup class="src-ref">원본 p.402</sup>
- 미국은 2009년을 정점으로 내림세, 유럽은 서서히 증가하다 균형에 다다른 느낌이다. <sup class="src-ref">원본 p.402</sup>
- 이유로는 속도만으로 비교우위를 갖기 어려워진 점, 변동성·유동성·저금리 환경 악화에 따른 수익성 악화, 약탈적 전략에 대한 사회적 압박 강화가 꼽힌다. <sup class="src-ref">원본 p.402-403</sup>
- Virtu Financial은 KCG Holdings를 합병해(2017년 7월) 도매 시장조성 부문에 진출했다. <sup class="src-ref">원본 p.402</sup>
- HFT 평가는 Flash Crash 전후로 엇갈리며, 사태 전에는 학계와 업계 모두 유동성과 호가 정보성을 향상한다고 우호적으로 평가했다. <sup class="src-ref">원본 p.404</sup>
- Flash Crash 이후 학계 연구에 따르면 HFT는 Flash Crash를 야기하지 않았고, 정상 시장에서 대부분의 HFT는 시장의 질적 수준에 유용하지만 일부 HFT 전략은 해악을 끼친다. <sup class="src-ref">원본 p.405</sup>
- 어느 시대건 HFT는 존재했고 HFT 자체를 좋다·나쁘다고 말할 수 없으며, 시장 공정성이나 효율성을 해치는 활용 전략과 그 전략으로 영업하는 증권회사를 규제해야 한다는 것이 미국과 유럽 정책담당자의 자세이다. <sup class="src-ref">원본 p.408</sup>

### 자본시장 (1장)

- ELW 시장의 스캘핑(초단타매매)을 당시 국내 매체는 부정적으로만 봤으나 요즘은 고빈도거래(HFT)라는 명칭을 쓰고 HFT의 전략이 매우 다양하며 시장조성전략의 순기능에 주목한다. <sup class="src-ref">원본 p.59</sup>
- HFT의 약탈적 전략이 여전히 이따금 사회적 물의를 일으키며(제11장 1절 참조), 외환시장에서 스캘퍼는 일반적으로 시장조성인을 뜻한다. <sup class="src-ref">원본 p.59</sup>

## 관련
- [[algorithmic-trading]]
- [[hft-trading-strategies]]
- [[latency-arbitrage]]
- [[co-location]]
- [[speed-bump]]
- [[flash-crash]]
- [[mifid-ii-mifir]]

## 확장 문서

- [[us-hft-speed-bump-internalization]] — 미국 장외 체결 비중·IEX 속도 지연·딜러 규칙
