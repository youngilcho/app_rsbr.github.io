# Marketing Site

`docs/` 폴더는 GitHub Pages 배포용 정적 마케팅 페이지입니다.

## 포함 파일

- `index.html`
  - 랜딩 페이지 본문
- `styles.css`
  - 앱 디자인 톤에 맞춘 정적 스타일
- `assets/`
  - 앱 아이콘과 주요 화면 이미지

## GitHub Pages 배포

1. 저장소 Settings > Pages 로 이동
2. Source 를 `Deploy from a branch` 로 선택
3. Branch 는 배포할 브랜치, Folder 는 `/docs` 선택
4. 저장 후 GitHub Pages URL 확인

## 커스텀 도메인 사용 시

- `rsbr.kr` 루트에 연결하면 기존 사이트를 대체할 수 있으니 주의
- 별도 서브도메인 예시
  - `baby.rsbr.kr`
  - `vaccines.rsbr.kr`
- 또는 GitHub Pages 기본 주소를 먼저 연결한 뒤 DNS/CNAME 적용

## 출시 후 바꾸면 좋은 부분

- `index.html`의 `App Store 출시 준비 중` 문구를 실제 App Store 링크 버튼으로 교체
- 지원/개인정보처리방침 링크를 최종 운영 URL 기준으로 재점검
