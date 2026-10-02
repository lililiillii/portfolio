# 임베디드개발 기술포트폴리오 | 홍진기

GitHub Pages 배포용 정적 포트폴리오입니다.

## 배포 방법

1. GitHub에서 새 저장소를 생성합니다.
   - 예: `portfolio`
2. 이 폴더의 파일을 저장소 최상위에 업로드합니다.
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment**
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. 저장 후 잠시 기다리면 Pages 주소가 생성됩니다.

예상 URL:
`https://<GitHub아이디>.github.io/portfolio/`

## 구성

- `index.html`: 포트폴리오 본문
- `.nojekyll`: Jekyll 처리 비활성화
- `README.md`: 배포 안내

별도 서버, 빌드 도구, CDN 없이 실행되는 단일 HTML 포트폴리오입니다.
