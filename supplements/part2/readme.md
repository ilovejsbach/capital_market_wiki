
> [!warning] 초안 (사람 검토 전)
> 이 문서는 사람의 검토를 거치지 않은 초안입니다. 내용이 틀렸거나 최신이 아닐 수 있습니다.

# 2부 후보 주제 (자동 조립)

`loop.py supplements`가 work/supplement 의 S7-part2-themes 조사·판정 입력으로 만든 폴더이다. 손으로 고치지 않는다.

- `themes.md` 읽는 문서(주제별 카드). `themes.jsonl` 같은 내용의 기계 판독본(정정 반영 시간표, 제외 항목, 연결 스캔 기록 포함).
- 주제 19건 (올림 18 · 보류 1). 보류 주제는 `themes.md` 끝 '보류' 절.
- 시간표는 판정자 ok=false 항목을 제외하되, 판정자가 날짜 등을 정정한 항목은 정정해 남겼다. 삭제·보류 권고 항목도 제외했다(`themes.jsonl`의 dropped_timeline).
- 연결된 스캔 기록은 스캔 기록의 part2_theme 문자열이 주제 제목과 같거나 한쪽이 다른 쪽을 포함하는 경우이다.

- 조사 범위 정보: `../coverage.json` 의 S7-part2-themes.

- 기록에서 파생한 주제(S7 외) 19건. 주제 연결은 문자열 일치 + `work/supplement/part2-assign.jsonl` 배정 + 파생 주제 구성원을 합친다(`themes.md` 각 주제의 '연결된 기록').
- 배정률: 157/164 (95.7%) — 올라간 part2_candidate 기록 중 주제에 연결된 기록 수 / 올라간 part2_candidate 기록 수. 올라가지 않은 part2_candidate(보류) 22건은 분모에서 제외.
- part2_candidate 가 아니지만 주제에 연결된 기록 225건. 연결되지 않은 part2_candidate 7건은 `unassigned.md`.
