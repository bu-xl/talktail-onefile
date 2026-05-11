Talktail 랜딩페이지 (v2 · 한/영 + IR 데이터 반영)
===============================================

[가장 빠른 공유 방법]
talktail-onefile.html 파일 하나만 보내면 됩니다.
받는 사람이 더블클릭하면 브라우저에서 바로 열립니다.
인터넷 연결만 필요합니다 (한글/영문 폰트 자동 로드).


[파일 구성]
- talktail-onefile.html  ★ 모든 내용 통합한 단일 파일 (107KB)
                            · 메일, 메신저, USB로 공유할 때 추천
                            · 더블클릭만으로 바로 열림

- index.html             분리형 본체 (HTML)
- styles.css             스타일시트 (디자인)
- i18n.js                한국어/영어 번역 사전
                            · 위 3개 파일은 같은 폴더에 함께 둬야 동작
                            · 호스팅이나 코드 수정에 적합

- talktail-landing.zip   위 모든 파일을 묶은 압축본
- README.txt             본 안내 파일


[웹 링크로 공개하기 (URL 발급)]

방법 1) Netlify Drop  (가장 간단 · 회원가입 불필요)
  1. https://app.netlify.com/drop 접속
  2. talktail-onefile.html 파일 또는 압축 해제한 폴더 전체를 끌어다 놓기
  3. 자동으로 발급되는 URL을 복사해서 공유

방법 2) Vercel, Cloudflare Pages, GitHub Pages
  · 도메인을 따로 연결하거나 장기 운영