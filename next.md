# 이어 하기 (`/new`나 새 창 뒤 첫 명령: `test/next.md 수행해`)

> 답과 파일은 모두 한국어로만 쓴다(일본어·중국어 글자 금지). Reply in Korean only.

이전 창의 대화는 이어지지 않는다. notes가 기억이다.
1. test/AGENTS.md를 읽고 이 대화 내내 따른다. user/notes/handoff.md 맨 위에 `git 사용 안 함`이 있으면 이 창에서도 git 명령을 쓰지 않는다(AGENTS.md 5항).
2. user/notes/handoff.md를 읽고, 거기 적힌 "다음에 읽을 키트 파일"(test/p2_explain.md·fin.md·par.md·p3_solve.md·p4_study.md 중 하나), user/notes/requirements.md, user/notes/status.md를 읽는다. 병렬 모드면(user/notes/windows.md가 있으면) windows.md와 contract.md 맨 위 줄도 읽는다. 보조 창 보고(user/notes/w_*.md)는 마지막 블록만 읽고 status.md에 반영한다. user/notes/tasks/가 있으면 카드 첫 줄만 보고(`grep -h "^# T" user/notes/tasks/*.md`) `보고함` 카드는 AGENTS.md 5항대로 반영한다.
3. 원본 자료, user/notes/brief.md·profile.md·manager_log.md는 통째로 다시 읽지 않는다. 필요한 부분만 찾아 연다(grep, head).
4. 화면에는 이것만 보여 준다: 첫 줄 지금 위치(예: `[3/6 검증]`) → 이어 받은 것 3줄 → 다음 선택 2~3개(추천). handoff.md에 담당자에게 아직 못 물은 것이 있으면 그것을 첫 선택지로 둔다.
