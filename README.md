# 👁️ 1984 마이크로사이트 (1984 Microsite)

> **"WAR IS PEACE | FREEDOM IS SLAVERY | IGNORANCE IS STRENGTH"**
>
> 본 마이크로사이트는 조지 오웰의 소설 《1984》 속 통제 체제와 감시 사회의 핵심 메시지를 사용자가 직접 인터랙션을 통해 경험할 수 있도록 설계된 인터랙티브 웹 디자인 프로젝트입니다.

---

## 📸 주요 기능 및 인터랙션 (Key Features)

### 1. 감시자의 눈동자 (The Watching Eye)
* 화면 상단 중앙에 위치한 거대한 눈동자는 마우스 포인터의 움직임을 실시간으로 추적하여 사용자를 응시합니다.
* 사용자가 늘 감시받고 있다는 압박감과 통제감을 시각적으로 극대화합니다.
* 눈동자를 클릭하면 《1984》 기획 의도를 담은 시스템 경고 팝업이 노출됩니다.

### 2. 가상 일기장 모니터링 (Winston's Notepad)
* 윈스턴의 일기장을 본뜬 메모장 인터랙션입니다.
* 사용자가 자유롭게 글을 입력할 수 있으며, 굵게/기울임/밑줄 및 폰트 변경, 크기 조절 등의 텍스트 서식 툴바를 지원합니다.
* **실시간 사상 검열 시스템**: 입력창에 사상통제 단어(`자유`, `평화`, `혁명`, `사랑` 등)를 입력하면 사상경찰의 모니터링 경고와 함께 자동으로 글자가 붉게 검열되거나 경고음/경고창 효과를 연출합니다.

### 3. 오세아니아 계급 피라미드 (Oceania Hierarchy)
* 오세아니아 사회의 권력 구조를 직관적인 피라미드 인포그래픽으로 시각화했습니다.
* **내부 당원(Inner Party)**, **외부 당원(Outer Party)**, **노동자(Proles)** 영역 또는 인포그래픽 노드에 마우스를 올리면 실시간 툴팁을 통해 계급별 특징과 인구 비율을 직관적으로 보여줍니다.

### 4. 실시간 텔레스크린 (Telescreen Live Broadcast)
* 빅 브라더의 선전 영상이 상시 재생되는 텔레스크린 모듈입니다.
* **2분 증오 (HATE) 인터랙션**: 증오 버튼을 누르면 화면에 크랙(Crack)과 글리치(Glitch) 효과가 나타나며 시각적 충격을 유도합니다.
* **감시 채팅방 (Monitoring Chat)**: 텔레스크린 옆에 실시간 채팅 모니터링 창이 있어 사용자가 직접 선전 문구나 반응을 입력하여 브로드캐스트할 수 있으며, 시민들의 후원금 리액션 알림 등이 주기적으로 시뮬레이션됩니다.

### 5. 1984 vs 2026 비교 카드 (Modern Parallels)
* 소설 속 감시 장치와 현대(2026년)의 기술적 통제를 비교하는 3D 플립 카드 섹션입니다.
  * 텔레스크린 vs 스마트폰/CCTV
  * 빅 브라더 vs 인공지능 알고리즘
  * 2분 증오 vs 온라인 마녀사냥 & 사이버 불링
  * 진리부 vs 가짜 뉴스 & 왜곡 정보
  * 사상죄 vs 필터 버블 & 확증 편향
* 마우스 오버 시 카드가 입체적으로 회전하며 소설의 설정과 현대 사회의 단면을 직관적으로 대응시켜 줍니다.

### 6. 도서 소개 및 라이브러리 (Library.exe)
* Three.js 기반의 입체 도서 렌더링 영역과 도서 상세 소개를 연동한 하단 섹션입니다.
* 교보문고 도서 구매 링크, 북스타그램 연동, 도서 트레일러 유튜브 링크 등 다양한 연계 콘텐츠로의 연결을 지원합니다.

---

## 🛠️ 기술 스택 (Tech Stack)
* **Markup**: Semantic HTML5, SVG (Dynamic Masking)
* **Styling**: Vanilla CSS3, CRT Glitch/Scanline Effects, responsive 3D card flips
* **Logic**: Vanilla JavaScript (ES6)
* **Libraries**:
  * [GSAP & ScrollTrigger](https://greensock.com/gsap/) - 고성능 스크롤 트리거 기반 타임라인 애니메이션
  * [Three.js](https://threejs.org/) - 웹 브라우저 기반 3D 그래픽 라이브러리

---

## 🚀 배포 및 실행 방법 (Deployment & Setup)

### 로컬 실행 방법
본 프로젝트는 순수 정적 웹 애플리케이션으로, 별도의 빌드 단계 없이 브라우저에서 `index.html`을 바로 열어 실행할 수 있습니다.

```bash
# 1. 저장소 클론
git clone https://github.com/ejffjd1818/1984_2st.git

# 2. 프로젝트 폴더로 이동
cd 1984_2st

# 3. 로컬 서버 실행 (VS Code Live Server 등을 이용하거나 단순히 index.html을 브라우저에 드래그)
```

### GitHub Pages 배포 방법
1. GitHub 리포지토리 페이지(`https://github.com/ejffjd1818/1984_2st`)에 접속합니다.
2. 우측 상단의 **Settings** 메뉴를 클릭합니다.
3. 좌측 사이드바의 **Code and automation** -> **Pages** 탭을 클릭합니다.
4. **Build and deployment** -> **Source**에서 `Deploy from a branch`를 선택합니다.
5. **Branch**를 `main` (또는 `/ (root)`)으로 선택하고 **Save**를 누릅니다.
6. 약 1~2분 후 배포가 완료되면 페이지 상단에 제공되는 URL을 통해 전 세계 어디서나 접속할 수 있습니다.
