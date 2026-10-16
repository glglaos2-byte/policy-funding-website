# 바른자금 — 정책자금 컨설팅 홈페이지 초안

네이비·화이트 반응형 4페이지 정적 프로젝트. 임시 브랜드와 예시 콘텐츠를 사용합니다.

## 미리보기
압축을 푼 후 `index.html`을 브라우저에서 열면 됩니다. CSS/JS 파일도 같은 폴더 구조로 유지하세요. 관리자 초안 저장은 브라우저 정책에 따라 파일 열기에서 제한될 수 있으므로 아래 서버 실행을 권장합니다.

```sh
cd /workspace/policy-funding-website
python3 -m http.server 3000 --bind 0.0.0.0
```

별도 설치·빌드·환경변수·API 키가 필요하지 않습니다. 서버 시작 후 메인과 세 하위 페이지를 열어 확인하세요.

## 수정 위치
- `index.html` / `information.html` / `consultation.html` / `admin.html`: 페이지와 문구
- `assets/style.css`: 색상, 레이아웃, 760/1050px 반응형
- `assets/app.js`: 검색·폼·기사 데모 동작
- `docs/preview-desktop.png`, `docs/preview-mobile.png`: 실제 브라우저 캡처
- `docs/DEPLOYMENT.md`: 서버/API/검색엔진 연결 안내

상담은 실제 접수되지 않습니다. AI는 템플릿 시연입니다. 관리자 인증과 서버 저장은 아직 없습니다.
