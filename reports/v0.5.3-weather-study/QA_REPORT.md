# v0.5.3-weather-study QA

Source: 7cbf25d116bec497e1bc4942e449e0574bd57211

EXE SHA256: D28FA28424C9D2049FAA01E1300812766BB8BAEAFBE62667DABCDFBE32255F84

원래의 v0.5.0 합성 실내/NPC/문을 유지하는 별도 카페 조명·날씨 검토 씬. 실내2등의 밝기·소등, 실제 실내 viewport 기반 젖은 도보 반사, 비/건조 상태, 최대12개 파문·물보라, 원본 비교 기능을 검증한다. 저장/스토리 상태를 쓰지 않는다.

기존 전체 회귀와 새 상태/연결 검사를 수행한다. Windows 실제 렌더에서 실내등 ON/OFF에 따른 도보 픽셀 변화와 ON 밝기 증가를 검사한다. 결과는 docs/design_review/cafe_weather_v1/RENDER_RESULT.json 및 BUILD_LOGS에 보관.

전체 물리 유체, 개별 빗방울 충돌, 전체 카페 조명 분리, 낮밤 최종 작화, 책방 수정, 모바일 실기기·Steam 검증은 미완료. 코드 셰이더 시연이며 완성 에셋 승인본이 아니다. GitHub에는 QA 텍스트만 기록한다.

