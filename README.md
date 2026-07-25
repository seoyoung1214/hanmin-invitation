# 한민고등학교 동문 네트워킹 초대장

한민고등학교 동문 네트워킹 행사의 디지털 초대장을 모아두는 저장소입니다.
매회 행사마다 폴더를 하나씩 추가하며 초대장을 쌓아갑니다.

## 구조

```
hanmin-invitation/
├── index.html      # 초대장 목차 (대표 페이지)
├── logo.png        # 공용 로고
├── 1st/            # 제1회 초대장
│   └── index.html
└── 2nd/            # 제2회 초대장
    └── index.html
```

## 초대장 목록

| 회차 | 날짜 | 시간 | 장소 | 폴더 |
|------|------|------|------|------|
| 제1회 | 2026. 04. 24 (금) | 19:45 입장 · 20:00 ~ 22:30 | 서울살롱 (신촌) | [1st/](1st/) |
| 제2회 | 2026. 07. 31 (금) | 20:00 ~ 22:30 | 서울살롱 (신촌) | [2nd/](2nd/) |

## 미리보기

브라우저에서 각 폴더의 `index.html`을 열거나, GitHub Pages가 켜져 있다면 아래 주소로 확인할 수 있습니다.

- 목차 : `https://seoyoung1214.github.io/hanmin-invitation/`
- 제1회 : `https://seoyoung1214.github.io/hanmin-invitation/1st/`
- 제2회 : `https://seoyoung1214.github.io/hanmin-invitation/2nd/`

## 새 초대장 추가하기

1. 가장 최근 회차의 폴더를 복사해 새 폴더를 만듭니다. (예: `3rd/`)
2. 폴더 안 `index.html`의 회차, 날짜, 장소, 컨셉, 연락처 등 내용을 수정합니다.
3. 루트 `index.html`의 초대장 목록 맨 위에 새 회차 카드를 추가합니다.
4. 이 README의 초대장 목록 표에도 한 줄 추가합니다.

## 기술 스택

- HTML5 / CSS3 (단일 파일, 별도 빌드 없음)
- Google Fonts — Nanum Myeongjo, Noto Sans KR, Cormorant Garamond

## 제작

© 2026 Design & Development by Seoyoung Kim
