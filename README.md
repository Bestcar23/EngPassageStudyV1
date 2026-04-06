# EFR Presenter Static Upload for Vercel

최종 정적 배포본입니다.

반영 사항
- 학습 모드 버튼 추가
- C열(단어·숙어) / D열(요약문) 순환 표시
- Google Apps Script 웹앱 URL 최신값 반영
  - https://script.google.com/macros/s/AKfycbytgLZIG6A0NsS1ci0KOWWx9JkLdpF7_rI_whwSH4rkOsvKR-9VnU1moIn_eTBY6YfP/exec

시트 구성
- 시트 이름: Sheet1
- A열: 지문 번호/제목
- B열: 지문 본문
- C열: 단어 및 숙어
- D열: 요약문

GitHub 업로드 방법
1. ZIP을 압축 해제합니다.
2. 안의 파일들(index.html, assets, vercel.json, README.md)을 GitHub 저장소 루트에 업로드합니다.
3. Vercel에서 해당 저장소를 Import 하거나, 이미 연결된 저장소라면 push 후 재배포합니다.

Vercel 권장 설정
- Framework Preset: Other
- Build Command: 비움
- Output Directory: 비움 또는 `.`
