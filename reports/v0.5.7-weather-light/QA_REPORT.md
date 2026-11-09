# v0.5.7-weather-light QA

Source: a97a33b329b7fe61dd0c378784fbd2269c19e5ad

EXE SHA256: 84988E4D570E4B74B1D1230E9469DD63D0D45354DF4E76C87F242E0A728849A6

별도 WeatherLightingState/설정으로 맑음·흐림·비, 구름량, 완만한 전환, 구름 통과 일조량을 추가했다. 시간의 해 방향/높이와 독립이며 native 방향광 energy/그림자, 주변 환경광, 젖음·반사·강수 표시와 연결한다. 수동 점등/젖음은 날씨 전환으로 초기화하지 않는다.

기존 회귀+날씨 상태/통합 검사, native 같은시간/젖음의 조도 순서, 맑음의 보관 v0.5.6 일치, 밤의 전등 반사 불변, 구름 변화, 화면모드/EXE/ZIP 검증. 수치는 weather_light_v1/RENDER_RESULT.json 및 BUILD_LOGS에 보관.

일반 게임 밤 상태/저장 스키마 유지. 낮 원화/전체 거리/물리 유체/모바일·Steam 검증은 미완료. GitHub 공개 범위는 QA 텍스트뿐이다.

