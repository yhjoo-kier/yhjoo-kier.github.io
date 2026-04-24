# yhjoo-kier.github.io

Younghwan의 개인 학술 홈페이지입니다. Jekyll 기반으로 제작되었으며 GitHub Pages로 자동 배포됩니다.

- 색상 테마: **Classic Navy** (프로페셔널 학술 스타일)
- 폰트: Merriweather (제목·세리프), Inter (본문·산세리프)
- 레이아웃: Home / Research / Publications / CV

---

## 🚀 배포하기

이미 저장소를 클론한 상태라면, 이 폴더에서 바로 커밋·푸시만 하면 됩니다.

```bash
git add .
git commit -m "Initial commit: Jekyll academic site"
git push origin main
```

푸시 후 GitHub 저장소 → **Settings → Pages** 에서 **Source: Deploy from a branch / Branch: main / (root)** 로 설정해주세요. (이미 기본값이면 그대로 두셔도 됩니다.)

1~3분 뒤 **`https://yhjoo-kier.github.io`** 로 접속하면 사이트가 뜹니다.

---

## 📂 폴더 구조

```
yhjoo-kier.github.io/
├── _config.yml           # 사이트 전역 설정
├── Gemfile               # Jekyll 의존성 (로컬 개발용)
├── index.html            # 홈페이지
├── research.md           # Research 페이지
├── publications.html     # Publications 페이지
├── cv.html               # CV 페이지
├── _layouts/
│   ├── default.html      # 기본 레이아웃
│   └── page.html         # 일반 페이지 레이아웃
├── _includes/
│   ├── header.html       # 상단 네비게이션
│   └── footer.html       # 하단 연락처
└── assets/css/style.css  # Classic Navy 테마
```

---

## ✏️ 커스터마이징

- **기본 정보**: `_config.yml` → 제목, 소개, 이메일, 소셜 링크
- **홈 내용**: `index.html` → 자기소개, 연구 관심사, 뉴스
- **프로필 사진**: `assets/images/profile.jpg` 업로드 후 `index.html`의 `<div class="hero-avatar">Y</div>`를 `<img class="hero-avatar" src="{{ '/assets/images/profile.jpg' | relative_url }}">`로 교체
- **출판물**: `publications.html`의 `<li>` 블록 복제
- **CV**: `cv.html`의 `<div class="cv-entry">` 블록 복제
- **색상**: `assets/css/style.css` 최상단 `:root`의 CSS 변수 수정

---

## 🖥️ 로컬 미리보기 (선택)

```bash
bundle install
bundle exec jekyll serve
```
→ `http://localhost:4000`
