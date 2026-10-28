---
type: metric
title: "괴리율"
aliases: []
books:
- "kcm"
symbols:
- "괴리율"
- "IV"
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["지표"]
description: "ETF 괴리율은 ETF 가격과 NAV 차이를 NAV로 나눈 절대값이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의 수식

- ETF 괴리율은 ETF 가격과 NAV 차이를 NAV로 나눈 절대값이다. <sup class="src-ref">원본 p.53</sup>
- ETN 괴리율은 IV 대비 ETN 시장가격과 IV 간 차이이며 (시장가격-IV)/IV×100으로 정의된다. <sup class="src-ref">원본 p.61</sup>

## 기호

- NAV는 ETF의 순자산가치이다. <sup class="src-ref">원본 p.52</sup>
- IV는 ETN의 지표가치로 ETF NAV에 해당한다. <sup class="src-ref">원본 p.61</sup>

## 해석

- 괴리율은 시장가격과 실제 가치의 차이로 투자할 때 중요 점검 사항이다. <sup class="src-ref">원본 p.61</sup>

## 쓰인 곳

- ETF 설명에서 가격과 NAV의 차이를 나타내는 용어로 쓰인다. <sup class="src-ref">원본 p.53</sup>
- ETN 설명에서 IV와 시장가격의 차이로 쓰이며, 2020년 4월 WTI 원유선물 레버리지 ETN 사태에서 LP가 괴리율을 조절할 수 없었다. <sup class="src-ref">원본 p.61</sup> <sup class="src-ref">원본 p.65</sup>

## 관련

- [[kcm-ch01]]
- [[net-asset-value]]
- [[exchange-traded-fund]]
- [[exchange-traded-note]]
