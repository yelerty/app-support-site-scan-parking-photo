# GitHub Pages 배포 안내

이 폴더의 내용을 GitHub 저장소에 올리면 바로 앱 지원/개인정보 처리방침 페이지로 사용할 수 있습니다.

## 1) 새 공개 저장소 만들기
- 예: `app-support-site`

## 2) 파일 업로드
- 이 폴더의 모든 파일을 저장소 루트에 업로드합니다.

## 3) Pages 활성화
- GitHub 저장소 → **Settings** → **Pages**
- **Source**: `Deploy from a branch`
- **Branch**: `main` (또는 `master`) / 루트(`/`)
- 저장 후 수 분 뒤 사이트가 생성됩니다.
- 최종 URL 예시
  - 전체 사이트(지원 페이지): `https://<your-username>.github.io/app-support-site/`
  - 개인정보 처리방침: `https://<your-username>.github.io/app-support-site/privacy-policy`

## 4) App Store Connect에 등록
- **Support URL**: 전체 사이트 또는 지원 페이지 URL
- **Privacy Policy URL**: `/privacy-policy` 경로의 URL

> 필요 시 `index.md`와 `privacy-policy` 페이지의 문구를 저장소에서 직접 수정·업데이트하세요.
