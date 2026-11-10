# NIGHT LOOP v0.6.15-station-platform QA

청각역 계단·참·열린 승강장과 화면 앞→뒤로 운행하는 열차를 최신 본게임에 연결했습니다. 승인 시안 기준의 첫 실제 통합 알파입니다.

- Source commit: d2cd4b56a2dc988e777c2edd85995e0c028c7acd
- Engine: 4.7.2.stable.official.ed1daf0bf
- Windows EXE SHA256: BB1D78822661CDCF6931312236639E2881934AD1BF0A7FF7E76E62EBA5968AEE
- Test ZIP SHA256: FBEF2863074E4844E0EEFD47454B5D5F9D5D22BC969ED162ABCF687E02B112CC
- Local complete source/build folder: v0.6.15-station-platform

## Changes

- 그림과 분리된 정규화 계단/참/승강장 경로 및 선택 필드 저장/복원.
- 게임 시간 기반 열차 진입→감속→정차→개문→대기→폐문→출발, 3개 원근 객차의 교체형 면/스킨과 문/창문/후미등.
- 기둥·난간·벤치·지붕·기단·간판/조명 독립 노드와 아틀라스/개별 이미지 교체 API.
- 기존 공통 시간·날씨·햇빛·젖음·파문·발광 반사 상태 사용. 일반 플레이 버전이며 시뮬레이터 메뉴를 추가하지 않음.
- 기존 20분 하루/스토리 날짜 자동 진행, 카메라 1~5 및 ~ 복귀 유지.

## Verification

- Full regression: 46 PASS groups, including routed 3-day story playthrough, previous shops/home, save/rollback/restart, camera, world time/weather and station tests.
- Fixed initial integration conflict with saved home stair placement; home reload regression passed after correction.
- Final native Windows Compatibility rendering passed arrival/stop/open/depart, wet/dry/light/ripple, daylight/rain and F11 fullscreen/windowed.
- Isolated mounted EXE resources passed station keyboard entry/platform/return, persistent station reload/rollback, invalid save rejection, and native rendering. No loose development asset fallback.
- Portable EXE startup, embedded resource audit, extracted ZIP checksums/startup passed. Old subway draft assets and unrelated intro files were not in the exported pack.

## Limits and records

승차·다른 역 이동·객실 탐험·NPC 승하차는 아직 포함하지 않습니다. 모바일 실기기/GPU 성능과 Steam depot는 미검증이며 APK는 사용자 요청대로 보류했습니다. 독립 점등/발광 반사는 공통 스타일 셰이더 근사입니다. 상업용 출처·원본 프롬프트·SHA256은 로컬에 기록했고, 최종 권리/계정 약관 검토는 미완료 상태를 유지합니다.

This public record contains QA text and hashes only. Game source, art and binaries remain local.
