---
type: concept
title: "부채담보부증권"
aliases:
- "CDO"
- "CBO"
- "CLO"
- "CDO-squared"
books:
- "kcm"
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "ABS는 기초자산 종류나 특성에 따라 구분하며 기초자산이 채권이면 부채담보부증권(CBO/CDO), 은행 대출금이면 대출채권담보부증권(CLO)이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의

- ABS는 기초자산 종류나 특성에 따라 구분하며 기초자산이 채권이면 부채담보부증권(CBO/CDO), 은행 대출금이면 대출채권담보부증권(CLO)이다. <sup class="src-ref">원본 p.69</sup>
- 현실 세계의 CDO와 CLO는 일반적으로 투기등급 고위험-고수익 채권과 신용도가 낮은 기업의 무수익 미회수 여신채권(NPL)을 각각 기초자산으로 한다. <sup class="src-ref">원본 p.69-70</sup>

## 왜 필요한가

- 풋백옵션이 없다면 자산보유자는 이들 위험자산을 SPC에 완전매각하므로 재무상태표에 기재할 필요가 없어 재무구조 개선 효과를 볼 수 있다. <sup class="src-ref">원본 p.70</sup>

## 내용

### 자본시장 (1장)

- 페이-스루 구조를 지닌 상품을 망라해 CXO라 하며 C는 collateralized, O는 obligation, X는 기초자산에 해당하는 '그 무엇'이다. <sup class="src-ref">원본 p.69</sup>
- 2008년 글로벌 금융위기를 초래한 합성 CDO 중에는 선순위증권과 중순위증권(메자닌)에 투자한 다음 이를 한데 묶어 재차 ABS를 발행한 CDO-squared(CDO$^2$)와 3차 발행한 CDO-tripled(CDO$^3$)도 있었다. <sup class="src-ref">원본 p.71</sup>
- 추후 밝혀진 일부 CDO$^2$와 CDO$^3$의 최초 기초자산은 CDS였다. <sup class="src-ref">원본 p.71</sup>

## 관련

- [[asset-backed-securities]]
- [[synthetic-cdo]]
- [[pass-through-and-pay-through]]
- [[seniority]]
- [[kcm-ch01]]
- [[financial-services-commission]]
