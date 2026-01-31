# test_01
mai hero 교_스네이크 게임 코드
🐍 Snake Game (HTML · CSS · JavaScript)
화살표 키로 조작하는 클래식 스네이크 게임입니다.
HTML, CSS, JavaScript가 하나의 파일에 통합되어 있기 때문에 브라우저에서 바로 실행할 수 있습니다.

🎮 데모

👉 snake-game.html 파일을 브라우저로 열면 바로 실행됩니다.
Chrome, Edge, Firefox 등 최신 데스크톱 브라우저를 권장합니다.


✨ 주요 기능

▶️ 자동 시작 (브라우저에서 열면 바로 플레이)
🎯 화살표 키 이동
⏸ 일시정지 / 계속 (Space)
🔄 재시작 (R 키)
⚡ 속도 변경(난이도 설정)
⭐ 최고 점수(LocalStorage 저장)
📱 반응형 캔버스 (창 크기에 따라 보드 자동 조절)
🧩 단일 HTML 파일로 구성(설치 불필요)


⌨️ 조작 방법

























기능키보드이동↑ ↓ ← →일시정지 / 계속Space재시작R속도 변경화면 상단 드롭다운

📦 설치 및 실행

이 저장소를 다운로드하거나 클론합니다.
Shellgit clone https://github.com/your-id/your-repo.git더 많은 선 표시

프로젝트 폴더로 이동:
Shellcd your-repo더 많은 선 표시

snake-game.html 파일을 더블 클릭하거나 브라우저로 열기


📁 파일 구조
.
├── snake-game.html   # 단일 파일 게임
└── README.md


🖼 스크린샷 (선택)
아래처럼 넣을 수 있어요:
!게임 화면


🛠 기술 스택

HTML5 Canvas
JavaScript ES6
CSS3 (반응형 디자인)


🚀 커스터마이징 가능 요소
코드 내에서 아래 부분을 바꾸면 기능을 확장할 수 있습니다.

보드 크기 변경
JavaScriptconst COLS = 21;const ROWS = 21;더 많은 선 표시

점수 증가량 변경
JavaScriptscore += 10;더 많은 선 표시

벽 통과 모드(토로이드)
JavaScriptnewHead.x = (newHead.x + COLS) % COLS;newHead.y = (newHead.y + ROWS) % ROWS;더 많은 선 표시


필요하면 모바일 터치 버튼, 장애물 모드, 스킨 테마 등도 추가해 드릴 수 있어요!

📄 라이선스
MIT License
자유롭게 수정 · 배포 가능합니다.

🙋 문의 / 개선 제안
이슈 또는 PR 환영합니다!
필요하시면 저는 김나영 님의 스타일에 맞춰 문서 / UI / 기능 개선도 도와드릴 수 있어요.
