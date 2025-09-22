# 김개발 - 소프트웨어 엔지니어 포트폴리오

![Portfolio Preview](https://via.placeholder.com/800x400/667eea/ffffff?text=김개발+포트폴리오)

개인 포트폴리오 웹사이트로, 소프트웨어 엔지니어 김개발의 경력, 기술, 프로젝트를 소개하는 반응형 웹사이트입니다.

## 🚀 주요 기능

- **반응형 디자인**: 데스크톱, 태블릿, 모바일 모든 기기에서 최적화된 사용자 경험
- **타이핑 애니메이션**: 메인 타이틀의 동적 타이핑 효과
- **스킬 바 애니메이션**: 스크롤 시 기술 스택 시각화
- **스무스 스크롤**: 부드러운 섹션 간 네비게이션
- **모바일 메뉴**: 햄버거 메뉴를 통한 모바일 네비게이션
- **연락처 폼**: 클라이언트와의 소통을 위한 연락처 폼
- **타임라인**: 경력 사항을 시각적으로 표현

## 🛠️ 기술 스택

### Frontend
- **HTML5**: 시맨틱 마크업
- **CSS3**: 
  - CSS Grid & Flexbox 레이아웃
  - CSS 애니메이션 & 트랜지션
  - 반응형 디자인 (Media Queries)
  - CSS 변수 활용
- **Vanilla JavaScript**:
  - DOM 조작
  - 이벤트 처리
  - Intersection Observer API
  - 스크롤 최적화

### 디자인 & UX
- **폰트**: Noto Sans KR (한국어 최적화)
- **색상 팔레트**: 
  - Primary: #3498db (Blue)
  - Secondary: #2ecc71 (Green)
  - Background: Gradient (Purple to Blue)
- **애니메이션**: CSS Keyframes, JavaScript 기반 애니메이션

## 📁 프로젝트 구조

```
AILLM/
├── index.html          # 메인 HTML 파일
├── style.css           # 스타일시트
├── script.js           # JavaScript 로직
└── README.md           # 프로젝트 문서
```

## 🎨 섹션 구성

### 1. 홈 (Hero Section)
- 개인 소개 및 타이핑 애니메이션
- CTA 버튼 (연락하기, 프로젝트 보기)
- 프로필 이미지 플레이스홀더

### 2. 소개 (About)
- 개인 경력 및 전문성 소개
- 통계 정보 (경력, 프로젝트 수, 고객 만족도)

### 3. 기술 (Skills)
- Frontend, Backend, Database, DevOps 카테고리별 기술 스택
- 프로그레스 바를 통한 숙련도 시각화

### 4. 경력 (Experience)
- 타임라인 형태의 경력 사항
- 회사별 역할 및 주요 성과

### 5. 프로젝트 (Projects)
- 주요 프로젝트 3개 소개
- 기술 스택 태그 및 링크

### 6. 연락처 (Contact)
- 연락처 정보 및 소셜 링크
- 연락처 폼 (유효성 검사 포함)

## 🚀 시작하기

### 설치 및 실행

1. **저장소 클론**
   ```bash
   git clone [repository-url]
   cd AILLM
   ```

2. **로컬 서버 실행**
   ```bash
   # Python 3 사용
   python -m http.server 8000
   
   # 또는 Node.js 사용
   npx http-server
   ```

3. **브라우저에서 확인**
   ```
   http://localhost:8000
   ```

### 개발 환경 설정

별도의 빌드 도구나 패키지 매니저가 필요하지 않습니다. 순수 HTML, CSS, JavaScript로 구성되어 있어 바로 실행 가능합니다.

## 📱 반응형 디자인

- **데스크톱**: 1200px 이상
- **태블릿**: 768px - 1199px
- **모바일**: 767px 이하

### 모바일 최적화
- 햄버거 메뉴 네비게이션
- 터치 친화적 버튼 크기
- 최적화된 폰트 크기 및 간격

## ⚡ 성능 최적화

- **스크롤 이벤트 최적화**: Throttle 함수 적용 (60fps)
- **애니메이션 최적화**: CSS Transform 및 Opacity 활용
- **이미지 최적화**: SVG 아이콘 및 플레이스홀더 사용
- **폰트 최적화**: Google Fonts preconnect 적용

## 🎯 주요 JavaScript 기능

### 1. 타이핑 애니메이션
```javascript
// 멀티 텍스트 타이핑 효과
function multiTypeWriter(element, texts, typeSpeed, deleteSpeed, pauseTime)
```

### 2. 스킬 바 애니메이션
```javascript
// Intersection Observer를 활용한 스크롤 기반 애니메이션
const skillObserver = new IntersectionObserver(callback, options)
```

### 3. 스무스 스크롤
```javascript
// 네비게이션 링크 클릭 시 부드러운 스크롤
window.scrollTo({ top: targetPosition, behavior: 'smooth' })
```

### 4. 폼 유효성 검사
```javascript
// 이메일 형식 검사 및 필수 필드 확인
const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
```

## 🎨 커스터마이징

### 색상 변경
`style.css`에서 CSS 변수를 수정하여 색상 테마를 변경할 수 있습니다:

```css
:root {
  --primary-color: #3498db;
  --secondary-color: #2ecc71;
  --text-color: #333;
}
```

### 콘텐츠 수정
- `index.html`에서 개인 정보, 경력, 프로젝트 정보 수정
- `script.js`에서 타이핑 텍스트 배열 수정

## 📄 라이선스

이 프로젝트는 개인 포트폴리오용으로 제작되었습니다.

## 📞 연락처

- **이메일**: kim.developer@email.com
- **전화**: +82 10-1234-5678
- **위치**: 서울, 대한민국

---

⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요!
