# v0.5.6-time-study QA

Source: 422e6fef687c0955a1ee43fad6ef60560773f272

EXE SHA256: DC74A2BC0A6ECB1E2FD8958C292BA3155467FB04E9825DC5DD2373CA083321D8

표현 시간 상태와 자동/수동 점등 우선권, 별도 native DirectionalLight2D+LightOccluder2D 지면 그림자 패스, 해 높이 기반 유한 그림자 제한, 환경색 보정 및 기존 반사를 연결했다. 일반 게임은 밤 고정, 별도 무저장 시간 검토 씬에서 조작한다. 원본 이미지/저장 스키마를 수정하지 않는다.

기존 회귀와 시간 상태/통합 검사, native6개 시간대/그림자 ON/OFF, 기본 밤의 보관 v0.5.5 캡처 일치, EXE/ZIP/화면모드 검증을 수행한다. 수치는 docs/design_review/cafe_time_v1/RENDER_RESULT.json과 BUILD_LOGS.

낮은 색 보정 시안이며 전체 낮 작화·원화 광원 제거·모바일 성능·태양 천문 모델·전체 거리 건물 그림자·Steam 출시는 검증하지 않았다. 새 외부 에셋/라이브러리 추가 없음. GitHub 공개는 QA 텍스트뿐이다.

