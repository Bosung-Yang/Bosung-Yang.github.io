# 양보성 - Personal Portfolio

개인 포트폴리오 웹사이트입니다.

## 🚀 배포 방법

### GitHub Pages로 배포하기 (추천)

1. **GitHub 저장소 생성**
   - GitHub에서 새 저장소 생성 (예: `username.github.io`)
   - 또는 기존 저장소 사용

2. **파일 업로드**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/username/username.github.io.git
   git push -u origin main
   ```

3. **GitHub Pages 설정**
   - 저장소 Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Save 클릭

4. **배포 확인**
   - 몇 분 후 `https://username.github.io`에서 확인

### Google Sites로 배포하기

1. **Google Sites 접속**
   - [sites.google.com](https://sites.google.com) 접속

2. **새 사이트 생성**
   - "새 사이트 만들기" 클릭
   - 템플릿 선택 (빈 템플릿 추천)

3. **HTML 코드 삽입**
   - 삽입 → 임베드 → HTML 코드 삽입
   - index.html의 내용을 복사하여 붙여넣기

4. **도메인 설정**
   - 설정 → 사용자 정의 도메인
   - 원하는 도메인 입력

## 📁 파일 구조

```
portfolio/
├── index.html          # 메인 HTML 파일
├── styles.css          # CSS 스타일
├── script.js           # JavaScript 기능
├── bosung.jpg          # 프로필 이미지
├── *.pdf               # 논문 PDF 파일들
└── README.md           # 프로젝트 설명
```

## 🎨 주요 기능

- 반응형 디자인
- 부드러운 스크롤 애니메이션
- 모바일 친화적 네비게이션
- 다크/라이트 모드 지원
- SEO 최적화

## 🔧 커스터마이징

### 색상 변경
`styles.css`에서 다음 변수들을 수정하세요:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --text-color: #2c3e50;
    --bg-color: #ffffff;
}
```

### 내용 수정
`index.html`에서 개인 정보를 수정하세요:
- 이름, 직함
- 자기소개
- 경력 사항
- 학력 정보
- 논문/특허 정보

## 📱 반응형 디자인

- 데스크톱: 1200px 이상
- 태블릿: 768px - 1199px
- 모바일: 767px 이하

## 🛠 기술 스택

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Font Awesome (아이콘)
- Google Fonts (Noto Sans KR)

## 📄 라이선스

MIT License

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request 