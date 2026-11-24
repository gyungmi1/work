임경미 UI/UX 포트폴리오 (HTML / CSS / JS 버전)
==============================================

■ 폴더 구성
  index.html        페이지 전체 (모든 텍스트·링크는 여기서 수정)
  css/style.css     모든 스타일 (맨 위 :root 에서 색상·폰트·크기 변경)
  js/main.js        동작 (스크롤, 탭 필터, 더보기, 문의하기 팝업)
  images/           공통 이미지 (bg.jpg 배경, profile.jpg 프로필)
  portfolio/        포트폴리오 이미지만 (portfolio-01 ~ 08.jpg)
  files/            이력서 PDF 를 resume.pdf 이름으로 넣어주세요

■ 실행
  index.html 을 더블클릭하면 브라우저에서 열립니다. (설치 불필요)

■ 자주 하는 수정
  - 텍스트 수정            : index.html 에서 해당 문구 찾아 수정
  - 포트폴리오 이미지 교체  : portfolio/ 의 파일을 같은 이름으로 교체
  - 포트폴리오 카드 추가    : index.html 의 <article class="pf-card ..."> 블록을 복사해서 추가
                             (data-category = web / ui / promotion / other)
  - SNS 주소               : index.html 맨 아래 footer 의 href 수정
  - 문의 메일 수신 주소     : js/main.js 맨 위 CONTACT_EMAIL 수정

■ 문의하기 → gyungmi0803@naver.com 메일 전송 (FormSubmit 사용)
  [최초 1회 설정 - 약 3분]
   1) 사이트를 웹에 올립니다. (GitHub Pages / Netlify / 호스팅 등, 또는 VS Code "Live Server")
   2) 올린 주소에서 "지금 바로 문의하기" → 내용 입력 → "문의 보내기" 로 테스트 전송합니다.
   3) 네이버 메일함(스팸함도 확인)에 FormSubmit 확인 메일이 옵니다.
      메일 안의 "Activate Form" 버튼을 누르면 활성화 끝!
   4) 이후부터는 방문자가 보낸 문의가 [포트폴리오 문의] 이름 제목으로 네이버 메일에 도착합니다.
  [참고]
   - index.html 을 더블클릭해서 로컬로 연 상태에서는 전송이 막힐 수 있습니다. (정상)
     이때는 안내 문구와 함께 "메일 앱으로 보내기" 버튼이 나타납니다.
   - 수신 주소를 바꾸려면 js/main.js 맨 위의 CONTACT_EMAIL 만 수정하세요.
   - 스팸 방지용 숨김 입력칸(_honey)이 들어 있으니 index.html 에서 지우지 마세요.
   - 무료 서비스이므로 문의가 안 올 때는 네이버 스팸함과 FormSubmit 활성화 여부를 먼저 확인하세요.

■ 폰트
  Inter 폰트를 Google Fonts 로 불러옵니다. 인터넷이 없으면 맑은 고딕 등으로 대체 표시됩니다.
