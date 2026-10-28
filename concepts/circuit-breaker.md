---
type: concept
title: "서킷브레이커"
aliases: ["매매거래중단제도"]
books: [kcm]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "서킷브레이커(circuit breakers, 매매거래중단제도[유가증권시장]/시장 일시중단제도[코스닥시장])는 대내외 요인으로 주가가 급락할 때 현·선물시장의 '모든' 매매거래를 일시 중단하는 제도이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

서킷브레이커(circuit breakers, 매매거래중단제도[유가증권시장]/시장 일시중단제도[코스닥시장])는 대내외 요인으로 주가가 급락할 때 현·선물시장의 '모든' 매매거래를 일시 중단하는 제도이다. <sup class="src-ref">원본 p.95</sup>

## 왜 필요한가

투자자가 냉정을 되찾고 관련 상황에 대한 정보 비대칭을 완화할 수 있게끔 시간 여유를 갖도록 하는 제도이다. <sup class="src-ref">원본 p.95</sup>

## 내용

### 주식거래과정과 기능별 인프라 제공기관 (2장)

- 서킷브레이커는 1987년 10월 19일 블랙먼데이를 경험한 미국이 고안했다. <sup class="src-ref">원본 p.95</sup> (정정: Federal Reserve History, 1987-10-19)
- KRX는 한차례 제도 변경(2015.6.15.)을 거친 뒤 3단계 서킷브레이커를 사용한다. <sup class="src-ref">원본 p.95</sup>
- 1단계 서킷브레이커는 코스피종합지수/코스닥종합지수가 전일 대비 8% 넘게 하락해 1분간 지속하면 발동한다. 이후 KRX는 20분간 거래를 중단하고 재개할 때는 10분간 임의종료 단일가매매를 실시한다. <sup class="src-ref">원본 p.95</sup>

### 미국자본시장 주요 법제 (9장)
- SEC는 블랙먼데이(1987년 10월 19일) 이후 1988년 10월 서킷브레이커를 시범 도입했고 2010년 Flash Crash로 SSCB마저 도입하면서 주가 제약을 꺼리던 완전경쟁 논리에서 어느 정도 벗어난 것 같다. <sup class="src-ref">원본 p.313</sup> <sup class="src-ref">원본 p.452</sup> (정정: Federal Reserve History, 1987-10-19)
- CME의 Stop Logic Functionality는 5초간 거래를 중단하는 "긴급 시장 안정화장치"이며 주식시장의 VI에 해당한다. <sup class="src-ref">원본 p.308</sup>
- 한 거래소에서 주가가 직전 5분간 10% 이상 하락하면 모든 거래시장이 5분간 거래를 정지하는 SSCB가 맛보기로 도입되었고, 이후 LULD가 대체했다. <sup class="src-ref">원본 p.312-313</sup>

### 시장미시구조 (15장)

- 유가증권시장은 "매매거래중단제도", 코스닥시장은 "시장 일시중단제도"라고 부른다. 코스피지수/코스닥지수가 전일종가보다 8%/15%/20% 이상 하락하면 1/2/3단계 발동을 예고하고, 1분간 지속하면 모든 종목 매매거래를 중단한다. <sup class="src-ref">원본 p.545</sup>
- 1, 2단계 발동 시 20분간 호가 접수와 매매거래를 중단하고 재개가격은 10분간 호가를 접수해 단일가매매로 정한다. 단계별 발동은 1일 1회이며 장종료 40분 전 이후에는 발동하지 않는다(3단계는 예외). 3단계는 그날 매매거래를 종료한다. <sup class="src-ref">원본 p.547</sup>
- 국제재무학계에서 서킷브레이커는 "전 종목 매매거래 (일시) 정지"만을 가리키는 용어로 쓰인다. <sup class="src-ref">원본 p.544</sup>

## 관련

- [[sidecar]]
- [[market-stabilization-measures]]
- [[price-limit-system]]
- [[volatility-interruption]]
- [[kcm-ch02]]
- [[call-auction]]
- [[kosdaq-market]]
- [[kospi-market]]
- [[random-end-call-auction]]
- [[korea-exchange]]

## 확장 문서

- [[korea-market-stabilizers]] — 한국 시장안정장치 현황과 2026년 발동 이력
