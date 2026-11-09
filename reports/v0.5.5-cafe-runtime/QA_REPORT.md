# v0.5.5-cafe-runtime QA

Source: 38bce719d9dd0e11c9009ab7c149c03c59e36a85

EXE SHA256: 83AA6F32151B1C0F38A02CE68850ABD1AA33F0751F974FA988F2E5D81BBD43F0

합격한 도보 반사/젖음/파문을 재사용 어댑터로 분리하여 실제 게임에 기본 적용. 외부4개 PointLight2D의 소등 패치/발광/반사 동기화, 별도 문 뒤 방과 PointLight2D 램프, 문 유리 구멍과 문짝/고정 문틀 분리. 기존 대화/NPC 출입/3일 콘텐츠/저장 스키마 유지.

어댑터 부착·복원·재부착/세션 불변, native 시각 일치, 본 게임 광원/문 상태와 반사 연결, 기존 전체 회귀 및 Windows F11/EXE/ZIP 검증. 렌더 기록은 docs/design_review/cafe_runtime_v1/RENDER_RESULT.json, 전체 결과는 BUILD_LOGS.

해 위치·거리 전체 낮밤/그림자, 모바일 실기기, 물리 유체·개별 빗방울 충돌, Steam 출시는 미검증. 새 외부 조명/문 뒤 작화는 사용자 검토 대상. GitHub에는 QA 텍스트만 기록한다.

