# 김문정 - AI 교육 전문가 홈페이지

> AI 전문가이자 현직 교사 김문정의 디지털 명함 홈페이지

## 🎯 프로젝트 소개

현장 경험과 기술의 융합으로 교육의 미래를 만들어가는 AI 교육 전문가 김문정의 공식 홈페이지입니다.

### 주요 기능
- ✨ **반응형 디자인**: 모든 기기에서 완벽한 사용자 경험
- 🎨 **모던 UI/UX**: AI/Tech 느낌의 그라데이션과 애니메이션
- 🚀 **프로젝트 쇼케이스**: 6개의 AI 기반 교육 플랫폼 소개
- 📺 **YouTube 통합**: 주요 교육 콘텐츠 임베드
- 📞 **협업 문의**: 강의/컨설팅 요청을 위한 연락 폼
- 🎯 **SEO 최적화**: 검색 엔진 친화적 구조

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Custom CSS with CSS Grid & Flexbox
- **Icons**: Font Awesome 6
- **Fonts**: Pretendard (한글 최적화)
- **Deployment**: Vercel 배포 준비 완료

## 🚀 배포 가이드

### 1. GitHub 업로드

```bash
# 1. GitHub에서 새 저장소 생성
# 2. 로컬에서 Git 초기화
git init
git add .
git commit -m "Initial commit: AI 교육 전문가 홈페이지"

# 3. 원격 저장소 연결 (YOUR_USERNAME을 본인 GitHub 계정으로 변경)
git remote add origin https://github.com/YOUR_USERNAME/kimmunje-homepage.git
git branch -M main
git push -u origin main
```

### 2. Vercel 배포

#### 방법 1: Vercel CLI (추천)
```bash
# Vercel CLI 설치
npm i -g vercel

# 프로젝트 폴더에서 배포
vercel

# 첫 배포 시 설정
# - Set up and deploy? Y
# - Which scope? (개인 계정 선택)
# - Found project.json. Deploy? Y
# - What's your project's name? kimmunje-homepage
# - In which directory? ./
```

#### 방법 2: Vercel 웹사이트
1. [vercel.com](https://vercel.com) 접속
2. GitHub 계정으로 로그인
3. "New Project" 클릭
4. GitHub 저장소 선택
5. "Deploy" 클릭

### 3. 커스텀 도메인 (선택사항)
Vercel 대시보드에서 도메인 설정 가능:
- `kimmunje.com`
- `portfolio.kimmunje.com` 등

## 📁 프로젝트 구조

```
kimmunje-homepage/
├── index.html          # 메인 홈페이지
├── README.md          # 프로젝트 설명
└── .gitignore         # Git 제외 파일
```

## 🎨 디자인 특징

### 색상 팔레트
- **Primary**: #4F46E5 (Indigo) - 신뢰감과 전문성
- **Secondary**: #06B6D4 (Cyan) - 혁신과 기술
- **Accent**: #EC4899 (Pink) - 창의성과 열정
- **Neutral**: #374151 (Gray) - 안정감

### 핵심 디자인 요소
- **그라데이션 배경**: AI/Tech 분위기 연출
- **카드 기반 레이아웃**: 정보의 체계적 구성
- **부드러운 애니메이션**: 사용자 경험 향상
- **반응형 그리드**: 모든 화면 크기 대응

## 📝 콘텐츠 업데이트 가이드

### 프로젝트 추가
`index.html`의 프로젝트 섹션에서 다음 블록을 복사하여 수정:

```html
<div class="project-card">
    <div class="project-thumbnail">
        <i class="fas fa-새아이콘"></i>
    </div>
    <div class="project-info">
        <h3 class="project-title">새 프로젝트명</h3>
        <p class="project-description">프로젝트 설명</p>
        <a href="프로젝트URL" class="project-link" target="_blank">
            <i class="fas fa-external-link-alt"></i> 사이트 방문
        </a>
    </div>
</div>
```

### 유튜브 영상 추가
YouTube 섹션에서 영상 ID만 변경하면 됩니다:

```html
<iframe src="https://www.youtube.com/embed/새영상ID" title="영상제목"></iframe>
```

## 🔧 성능 최적화

- **최적화된 이미지**: WebP 형식 권장
- **CSS 압축**: 배포 시 자동 최적화
- **캐싱 전략**: Vercel의 CDN 활용
- **SEO 메타태그**: 검색 엔진 최적화 적용

## 📊 분석 도구 연결

### Google Analytics 추가 (선택사항)
`</head>` 태그 직전에 추가:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🔄 업데이트 및 유지보수

### 정기 업데이트 권장사항
- 새 프로젝트 추가
- YouTube 영상 업데이트
- 연락처 정보 확인
- 브라우저 호환성 테스트

## 📞 지원

프로젝트 관련 문의나 기술적 지원이 필요하시면 언제든 연락해주세요.

---

*"AI 시대, 교육의 미래를 함께 만들어갑니다"* - 김문정