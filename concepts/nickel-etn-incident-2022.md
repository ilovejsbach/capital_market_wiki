---
type: "concept"
title: "2022년 니켈 ETN 사태"
aliases: ["니켈 ETN 사태", "니켈 곱버스 사태", "대신 인버스 2X 니켈선물 ETN 사태", "2022 nickel ETN incident"]
layer: "expansion"
status: "draft"
as_of: "2026-10"
updated: "2026-10-26"
extends: ["exchange-traded-note"]
research: "korea-etf-etn"
tags: ["개념", "확장"]
description: "2022년 3월 런던금속거래소(LME) 니켈 선물이 하루 만에 급등하면서 니켈 인버스 레버리지 ETN의 기초지수가 0이 되어 매매가 정지된 사건이다. 2020년 4월 WTI 원유선물 레버리지 ETN 사태와 함께 책…"
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

> [!note] 책 밖 확장 문서
> 이 문서는 책 본문이 아니라 웹의 공식 자료를 조사해 덧붙인 확장 문서입니다. 기준일은 2026-10입니다. 근거는 문서 끝의 출처 목록에 있고, 책에서 온 문장에는 `원본 p.N`이 붙습니다.

## 개요

2022년 3월 [[london-metal-exchange|런던금속거래소]](LME) 니켈 선물이 하루 만에 급등하면서 니켈 인버스 레버리지 ETN의 기초지수가 0이 되어 매매가 정지된 사건이다. 2020년 4월 WTI 원유선물 레버리지 ETN 사태와 함께 책이 반복되는 사건으로 든다. <sup class="src-ref">출처 1</sup> ETN의 구조와 시장 규모는 [[korea-etn-market]]에서 다룬다.

## 경과

| 시점 | 사건 |
|---|---|
| 2022-03-07 | LME 니켈 선물이 전일 대비 66.25% 급등해 'S&P GSCI Nickel 2X Inverse TR' 지수가 0이 됨 <sup class="src-ref">출처 2</sup> |
| 2022-03-08 | 한국거래소가 '대신 인버스 2X 니켈선물 ETN(H)'(대신증권 발행)의 매매를 정지. 지표가치가 일일 변동률로 산출되어 0에서 회복할 수 없으므로 원금 대부분 손실과 상장폐지 가능성이 제기됨 <sup class="src-ref">출처 2</sup> |
| 2022-05 | 거래소가 ETN 조기청산 요건 개정: 2020년 원유 ETN 사태 뒤 신설했던 '괴리율 +100% 이상' 삭제, 상환가격을 사유 발생 전 3거래일 평균에서 사유 발생 다음 날 지표가치로 변경, 지수 연속성 요건 삭제 <sup class="src-ref">출처 3</sup> |

## 구조적 원인

인버스 2배 상품은 [[indicative-value|지표가치]]를 일일 변동률의 배수로 계산하므로 기초지수가 하루에 100% 이상 오르면 0이 된다. 0이 된 지표가치는 회복할 수 없다. ETN은 발행 증권사의 신용에 기대는 증권이어서 투자자는 손실을 그대로 지고 증권사 신용위험도 함께 안는다. 이 점은 책이 ETN의 약점으로 설명한 부분과 같다. <sup class="src-ref">원본 p.61</sup> <sup class="src-ref">원본 p.65</sup>

## 확인하지 못한 것

대신 인버스 ETN의 상장폐지 일자, 상환금액, 투자자 손실액은 확인하지 못했다. 사태 직후 ETN 제도 전체에 직접 이어진 개선이 있었는지도 확인하지 못했으며, 위 2022년 5월 개정이 확인된 변경이다.

## 이후의 흐름

2026년 단일종목 레버리지 상품이 허용되면서 [[exchange-traded-fund|ETF]]·ETN의 괴리율 관리와 레버리지 규제가 다시 쟁점이 되었다. [[korea-etf-market]]과 [[korea-etn-market]]에서 다룬다.

## 책과의 관계

책은 2020년 4월 WTI 원유선물 레버리지 ETN 사태에서 [[trading-venue|거래소]] 규정 때문에 LP가 괴리율을 조절할 수 없었다고 설명하고 <sup class="src-ref">원본 p.65</sup>, 반복되는 사건으로 2022년 니켈 '곱버스' ETN 사태를 든다. <sup class="src-ref">원본 p.62</sup> 이 문서는 사건의 경과와 이후의 조기청산 요건 개정을 보충한다.

## 관련

- [[exchange-traded-note]]
- [[korea-etn-market]]
- [[korea-etf-market]]
- [[derivatives-linked-securities]]
- [[liquidity-provider]]
- [[differential-rate]]
- [[korea-exchange]]

## 출처

기준일 2026-10-26. [[korea-etn-market]]에서 이미 독립 검증을 거친 사실만 모았다. 2·3번은 언론 보도(2차)다.

1. 이 위키의 책 기반 문서 `derivatives-linked-securities`(책 p62).
2. (2차) 비즈워치, 니켈 인버스 ETN 매매정지(2022-03-14): https://news.bizwatch.co.kr/article/market/2022/03/14/0017
3. (2차) 비즈워치, ETN 조기청산 요건 개정(2022-05-18): https://news.bizwatch.co.kr/article/market/2022/05/18/0022
