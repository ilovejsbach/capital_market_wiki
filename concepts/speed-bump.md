---
type: concept
title: "Speed Bump(과속방지턱)"
aliases: ["Speed bump", "과속방지턱", "스피드 범프"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "Speed bump(과속방지턱)는 거래 속도를 인위적으로 늦추는 장치이며, IEX가 세계 최초로 아이디어를 제공했다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
Speed bump(과속방지턱)는 거래 속도를 인위적으로 늦추는 장치이며, IEX가 세계 최초로 아이디어를 제공했다. <sup class="src-ref">원본 p.406</sup> <sup class="src-ref">원본 p.409</sup>
IEX는 매칭 엔진 앞에 광섬유 코일 38마일을 감아 주문접수와 호가/체결정보 송출을 일부러 350μs 늦췄다. <sup class="src-ref">원본 p.409-411</sup> (갱신 2026-10: IEX의 speed bump는 현재도 350마이크로초 지연이며 약 44마일의 코일 광케이블로 구현된다. 2024년 주 데이터센터 이전 전에는 38마일이었고 같은 지연을 유지하려고 늘렸다.)

## 왜 필요한가
IEX는 다크풀 시절 페그 주문을 체결하려는 순간 상대방 주문이 사라지는 상황을 수도 없이 겪었고, 조사 결과 이는 다른 브로커·딜러가 co-lo로 더 빠른 정보를 받아 앞서 저격했기 때문이었다. <sup class="src-ref">원본 p.409</sup>
IEX는 전통적 투자자를 보호하고 latency arbitrage를 방지하겠다고 선언했다. <sup class="src-ref">원본 p.409-411</sup>

## 내용

### 시장 패러다임 변화 ([[kcm-ch11]]) (11장)
- IEX는 2013년 10월 다크풀로 출범해 2015년 4월 top-of-book 방식 리트풀 기능을 추가하고 2016년 6월 미국 13번째 정규거래소로 전환했다. <sup class="src-ref">원본 p.409</sup>
- 수많은 시뮬레이션 끝에 IEX는 350μs 정도의 speed bump면 현행 시장구조에서 latency arbitrage가 야기하는 왜곡 현상을 무력화할 수 있다고 판단했다. <sup class="src-ref">원본 p.411</sup>
- NYSE와 Nasdaq 등의 격렬한 반대로 두 차례 연기한 끝에 SEC는 IEX를 정규거래소로 허가하고 speed bump 시행도 허용했다. <sup class="src-ref">원본 p.411</sup>
- 표 11-2에 따르면 실행 중인 것은 IEX(주식, 2016년 6월, 350μs), Nasdaq(주식, 2017년 9월, M-ELO 주문, 500ms), Eurex(파생상품, 2019년 6월, 1 또는 3ms) 등이다. <sup class="src-ref">원본 p.410</sup> (갱신 2026-10: 후속 기록은 보완 NA-03-1)
- 표 11-2에서 시도 및 중지는 CHX(신청 철회, 2018년 7월), Cboe EDGA(신청 기각, 2020년 2월, 4ms), NYSE American(2017년 7월 도입 후 2019년 11월 폐기, 시장 질적 수준 악화 이유)이다. <sup class="src-ref">원본 p.410</sup>
- NYSE American이 실행을 중단하고 Nasdaq이 추가 설치에 소극적으로 돌아선 것은 speed bump가 시장의 질적 수준을 낮춘다는 자사 통계 때문인 것으로 설명되며, 파생상품 시장에서는 FX 거래를 중심으로 설치가 늘고 있다. <sup class="src-ref">원본 p.411</sup>
- 일부 거래시장이 speed bump나 일중 단일가매매 등을 제도화하기 시작했다. <sup class="src-ref">원본 p.403</sup>
- Speed bump를 쓰는 거래시장이 늘면서 바이사이드 투자자도 원자시계를 사용하기까지 하며 대응한다. <sup class="src-ref">원본 p.411</sup>

## 관련
- [[latency-arbitrage]]
- [[frequent-batch-auction]]
- [[co-location]]
- [[high-frequency-trading]]
- [[nasdaq]]
- [[nyse]]
- [[dark-pool]]
- [[regulated-market]]
- [[derivatives]]
- [[investors-exchange-iex]]

## 확장 문서

- [[investors-exchange-iex]] — IEX(Investors Exchange)
- [[us-hft-speed-bump-internalization]] — 미국 장외 체결 비중·IEX 속도 지연·딜러 규칙
