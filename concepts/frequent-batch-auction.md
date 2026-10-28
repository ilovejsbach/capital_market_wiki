---
type: concept
title: "FBA"
aliases: ["frequent batch auction", "일중 반복적 정기 단일가매매", "이산적 단일가매매"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "FBA(frequent batch auction)는 '일중 반복적 정기 단일가매매' 또는 '이산적 단일가매매'라고 옮겨지는, 연속경쟁매매(접속매매)를 대체하자고 제안된 거래 메커니즘이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
FBA(frequent batch auction)는 "일중 반복적 정기 단일가매매" 또는 "이산적 단일가매매"라고 옮겨지는, 연속경쟁매매(접속매매)를 대체하자고 제안된 거래 메커니즘이다. <sup class="src-ref">원본 p.406</sup>

## 왜 필요한가
부디쉬·크램튼·존 심(2015)과 비애·푸코·모니아즈(2015)는 latency arbitrage로 유동성제공자가 손해를 보고 ICT에 과대투자가 생기는 문제에 대해, speed bump로 거래 속도를 인위적으로 늦추면서 동시에 거래 메커니즘을 연속경쟁매매에서 FBA로 바꾸거나, 아니면 HFT 거래세(피구세)를 부과해 원인 제공자에게 사회적 비용을 부담시키는 방책을 제안했다. <sup class="src-ref">원본 p.406</sup>

## 내용

### 시장 패러다임 변화 ([[kcm-ch11]]) (11장)
- 부디쉬·리·존 심(2021)은 speed bump나 FBA 같은 시장 설계상 혁신적 조치를 거래시장이 자발적으로 도입할 유인이 크지만, 최초 거래시장의 혁신을 기존 거래시장이 비용 없이 따라 하면 최초 거래시장이 손실을 볼 수 있다고 본다. <sup class="src-ref">원본 p.406-407</sup>
- SEC는 부디쉬가 참여한 연구의 주장을 정책에 반영하고 있으며, 중소형/비유동성 종목 거래에 FBA 적용을 권장하고 도입 거래소 상장종목에 UTP Plan을 적용하지 않는 안을 긍정적으로 검토 중이다. <sup class="src-ref">원본 p.407-408</sup> (갱신 2026-10: 후속 기록은 보완 K-061-1)

## 관련
- [[latency-arbitrage]]
- [[speed-bump]]
- [[high-frequency-trading]]
- [[call-auction]]
- [[competitive-trading]]
