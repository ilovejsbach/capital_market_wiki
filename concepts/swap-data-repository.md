---
type: concept
title: "스왑데이터저장소"
aliases: ["SDR", "SBSDR"]
books: ["kcm"]
status: draft
updated: 2026-10-20
built_with: {program: "v1.5", prompt_sha: "344e45e", wikikit: "0.5.0"}
tags: ["개념"]
description: "SDR(swap data repository)은 글로벌 금융위기 재발을 막으려 제정한 Dodd-Frank Act(2010년) 7편에 따라 신설된 실시간 스왑 거래정보 제공기관이다."
---

> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

## 정의
SDR(swap data repository)은 글로벌 금융위기 재발을 막으려 제정한 Dodd-Frank Act(2010년) 7편에 따라 신설된 실시간 스왑 거래정보 제공기관이다. <sup class="src-ref">원본 p.220</sup>
유럽과 한국에서는 TR(거래정보저장소)이라는 일반 용어를 쓰지만, 미국에서는 용어를 스왑거래에 특정해 SDR로 명명했다. <sup class="src-ref">원본 p.220</sup>

## 왜 필요한가
스왑딜러와 주요 스왑참여자(MSP)는 유동성이 충분하고 표준화가 이루어진 스왑(예: CDS)을 DCM/SEF에서 매매체결하고 DCO에서 청산·결제하며, 거래 관련 모든 데이터를 SDR에 보고해야 한다. <sup class="src-ref">원본 p.220</sup>
거래 목적이 헤지이거나 당사자 중 일방이 비금융기관이면 예외로 인정된다. <sup class="src-ref">원본 p.220</sup>

## 내용

### 미국자본시장, 시장거시구조 글로벌 패러다임 리더 ([[kcm-ch06]]) (6장)
- SEF에서 거래가 발생하면 관련 정보를 (거의) 실시간으로 SDR에 보고한다. <sup class="src-ref">원본 p.214</sup>
- DDR(DTCC Data Repository)을 제외하고 미국과 유럽의 모든 SDR은 거래소 또는 전자 거래플랫폼 운영기관 소속이다. <sup class="src-ref">원본 p.220</sup>
- CME SDR(CME 소유), DDR(DTCC 소유), ICE 트레이드볼트(ICE 소유)가 미국을 대표하는 SDR이다. <sup class="src-ref">원본 p.220</sup>
- 2021년 5월 DDR은 미국 최초로 SEC에게서 증권기초 스왑용 SDR(SBSDR) 허가를 받았고, 2021년 11월 증권기초 스왑 거래보고 의무가 시행되었다. <sup class="src-ref">원본 p.220</sup>
- 미국에서 증권기초 스왑은 SEC가, 이외 모든 스왑은 CFTC가 관할한다. <sup class="src-ref">원본 p.220</sup>
- CME의 장외파생상품 거래보고 서비스는 CME 스왑데이터저장소(CME SDR)를 통해 제공된다. <sup class="src-ref">원본 p.212-213</sup>

## 관련
- [[swap-execution-facility]]
- [[derivatives-clearing-organization]]
- [[trade-repository]]
- [[dtcc]]
- [[cftc]]
- [[financial-services-commission]]
- [[cme-group]]
- [[ice]]
- [[sec]]
