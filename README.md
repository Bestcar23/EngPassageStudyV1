# EFR Presenter Static Upload for Vercel

이 폴더는 이미 빌드가 끝난 정적 배포본입니다.

## GitHub 업로드 방법
1. 이 ZIP을 압축 해제합니다.
2. 안의 파일들(index.html, assets, vercel.json 등)을 GitHub 저장소 루트에 업로드합니다.
3. Vercel에서 해당 저장소를 Import 합니다.

## 배포 설정
- Framework Preset: Other
- Build Command: 비움
- Output Directory: 비움 또는 `.`

`vercel.json`에 설치/빌드 생략 설정이 포함되어 있어, 별도 빌드 없이 정적 파일만 배포됩니다.
