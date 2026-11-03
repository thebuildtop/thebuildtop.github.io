# 더빌드탑 홈페이지

주소: https://thebuildtop.github.io

## 구성
- `index.html` — 홈페이지 본문 (소개 · 시공 사례 · 공사 과정 · 공사 범위 선택 · 상담 신청)
- `js/process-data.js` — 공정 안내 (주거 17단계 · 상업 15단계 · 외부·방수 11단계)
- `js/cases.js` — 시공 사례 목록
- `images/cases/` — 시공 사례 사진

## 시공 사례 사진 추가
1. 사진을 `images/cases/` 폴더에 올립니다. (가로 4:3 비율, 1600px 정도 권장)
2. `js/cases.js`에 한 줄을 추가합니다.
   `{ title: "사례 이름", type: "res", desc: "한 줄 설명", img: "파일이름.jpg" },`
   - type: `res` 주거 / `com` 상업 공간 / `ext` 외부·방수
