# Dream Lecture — 모바일 레이아웃 테스트 빌드

운영 사이트(https://dreamlecture.github.io/)의 **모바일 대응 작업본**입니다.

미리보기: https://kfas-dreamlecture.github.io/test/

## 무엇이 다른가
- PC(769px 이상) 렌더링은 운영 사이트와 100% 동일합니다.
  추가된 CSS는 전부 `@media (max-width: 768px)` 안에만 있습니다.
- 모바일(768px 이하)에서만 레이아웃이 1단으로 접히고 타이포·여백이 축소됩니다.

## 수정된 파일
`index.html`, `home.dc.html`, `visit.dc.html`, `invite.dc.html`,
`hub.dc.html`, `connect.dc.html`, `Chatbot.dc.html`

`robots.txt` 는 검색엔진이 이 테스트본을 색인하지 않도록 막아둔 것입니다.
운영 반영 시에는 삭제하세요.
