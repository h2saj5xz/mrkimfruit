# 미스터킴 과일나라 - Mr.kim Fruit

호치민 신선식품 전문배송 서비스 웹사이트

## 🍎 프로젝트 소개

한국, 미국, 뉴질랜드 등지에서 엄선한 최상급 신선 과일을 호치민 지역에 직배송하는 서비스의 랜딩 페이지입니다.

## 🚀 깃헙 페이지 배포 방법

### 1. 저장소 설정
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/사용자명/저장소명.git
git push -u origin main
```

### 2. GitHub Pages 활성화
1. GitHub 저장소 페이지로 이동
2. Settings > Pages 메뉴 선택
3. Source를 "Deploy from a branch" 선택
4. Branch를 "main" 선택, 폴더는 "/ (root)" 선택
5. Save 클릭

### 3. 배포 완료
몇 분 후 `https://사용자명.github.io/저장소명/` 에서 사이트 확인 가능

## 📁 프로젝트 구조

```
mrkimfruit/
├── index.html              # 메인 페이지
├── logo.png               # 로고 이미지
├── images/                # 상품 이미지
│   ├── 1.jpg ~ 12.jpg
└── public/
    └── images/            # 이벤트 배너
        ├── event-banner-desktop.png
        └── event-banner-mobile.png
```

## 🛠️ 로컬 테스트

브라우저에서 `index.html` 파일을 직접 열거나, 간단한 HTTP 서버로 실행:

```bash
# Python 3
python3 -m http.server 8000

# 브라우저에서 http://localhost:8000 접속
```

## 📞 연락처

- 💬 카카오톡: [오픈채팅방](https://open.kakao.com/o/ge0sctV)
- 📱 Zalo: 0919835944

## 📄 라이선스

© 2024 미스터킴 과일나라. All rights reserved.
