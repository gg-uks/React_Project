# 🎬 React Movie Project - TMDB 기반 영화 탐색기

> TMDB API를 활용해 영화 정보를 탐색할 수 있는 React 프로젝트입니다.  
> Vite + Tailwind CSS로 빠르고 반응형 UI를 구현했습니다.

---

## 📁 프로젝트 구조

```
my-project/
├── public/
├── src/
│   ├── api/           # TMDB API 호출 관련 함수
│   ├── assets/        # 이미지, 아이콘 등의 정적 리소스
│   ├── components/    # 재사용 가능한 UI 컴포넌트
│   ├── hooks/         # 커스텀 훅 정의
│   ├── pages/         # 페이지 단위 컴포넌트
│   ├── routes/        # 라우팅 설정
│   ├── util/          # 유틸 함수
│   ├── App.jsx        # 전체 앱 구조
│   ├── main.jsx       # 엔트리 포인트
│   └── index.css      # 전역 스타일 (Tailwind)
├── .gitignore
├── index.html
├── README.md
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
```


## 🌟 주요 기능

- 🎬 인기 영화 목록 불러오기
- 🔍 영화 제목 검색
- 🏷️ 장르 필터링
- 📱 반응형 디자인 (모바일/데스크탑 대응)
- 💨 Vite로 빠른 빌드, Tailwind로 깔끔한 스타일링


- ## 🔌 사용 기술

| 분류         | 기술 스택                      |
|--------------|-------------------------------|
| 프론트엔드    | React, React Router DOM       |
| 스타일링      | Tailwind CSS         |
| API 호출      | Axios, TMDB API               |
| 번들러        | Vite                          |
| 상태관리 (선택) | React Context or useState 사용 |
