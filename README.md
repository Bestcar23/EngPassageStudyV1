# EFR Presenter Static Upload for Vercel

이 폴더는 이미 빌드가 끝난 정적 배포본입니다.

## 포함된 최신 수정사항
- Google Apps Script 연동 URL 반영
- 학습 모드 버튼 추가
- C열 단어/숙어, D열 요약문 순환 표시
- 활성 지문 번호 버튼 테두리 개선
- 중첩 인라인 서식 처리 개선

## GitHub 업로드 방법
1. 이 ZIP을 압축 해제합니다.
2. 안의 파일들(index.html, assets, vercel.json 등)을 GitHub 저장소 루트에 업로드합니다.
3. Vercel에서 해당 저장소를 Import 합니다.

## 배포 설정
- Framework Preset: Other
- Build Command: 비움
- Output Directory: 비움 또는 `.`

`vercel.json`에 설치/빌드 생략 설정과 SPA rewrite 설정이 포함되어 있어, 별도 빌드 없이 정적 파일만 배포됩니다.
