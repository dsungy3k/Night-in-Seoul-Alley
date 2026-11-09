# v0.5.4-pavement-test QA

Source: 6857b0692f9a640515a04ccb348212afe34ae99e

EXE SHA256: ECE5DBBBABBBDF95B2F089BBCCAC0184DC587CF27661FE969B44D4F64DBC5A64

원래 그림의 도보(A), 반사 제거 도보(B), 실시간 반사만 적용(C)을 동일 카메라·시간·인물 상태에서 비교하는 별도 무저장 씬이다. 기존 합성 실내/문/NPC를 보존한다. 새 생성 원화에서는1672x189 도보만 추출한다. 생성된 건물 이미지를 사용하지 않는다.

상태/통합/기존3일 회귀, Native Windows A/B/C 비교, EXE/ZIP/내장 리소스 검사를 수행한다. 화면 비교에서 도보 밖 변화0을 검사한다. 수치는 docs/design_review/pavement_test_v1/RENDER_RESULT.json 및 BUILD_LOGS 참조.

파문은 셰이더 효과, 외벽 반사는 절차적 층이며 물리 유체나 최종 광학 시뮬레이션이 아니다. 모바일·Steam·낮밤 최종 아트·전체 카페 소등은 검증하지 않았다. GitHub 업로드 범위는 QA 텍스트뿐이다.

