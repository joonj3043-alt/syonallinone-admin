SYON ALL IN ONE 관리자 연결 버전
기존 GitHub 저장소 루트에 index.html, app.js, style.css 업로드. 기존 CNAME 파일 유지.
HTTPS 필수. 공개 키만 포함. 실제 로그인 및 RLS 테스트 전 고객 정보 입력 금지.
세션은 탭의 sessionStorage에 유지하며 새로고침 시 서버에서 관리자 권한을 재확인합니다. 로그아웃 또는 만료 시 삭제합니다. 목록은 최대 서버 응답 제한까지 조회하는 초기 버전.
