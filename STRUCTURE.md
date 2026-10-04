# STRUCTURE · kjricecake-sample

```
kjricecake-sample/
├─ index.html            단일 파일 (CSS·JS 인라인)
├─ wrangler.toml         name = kjricecake-sample → kjricecake-sample.lgt3232.workers.dev
├─ .assetsignore         img/·문서·index_*.html·kj-roof-w.webp 배포 제외
├─ kj-yeonsung.woff2     제목 폰트 서브셋 (Yeon Sung, OFL)
├─ kj-gowun-400/700.woff2 본문 폰트 서브셋 (Gowun Batang, OFL)
├─ kj-logo.webp          로고 투명 (원색) · 헤더
├─ kj-logo-w.webp        로고 투명 (흰 글자 + 다홍 떡) · 푸터
├─ kj-roof.webp          로고 처마 곡선 · 섹션 구분
├─ kj-gift-bojagi.webp   히어로 (노리개 선물세트)
├─ kj-siru.webp          이야기 (나무 떡 틀)
├─ kj-*.webp             메뉴 6 · 답례/선물 6 · 갤러리 10
├─ og-kj.jpg             공유 썸네일 1200×630
├─ img/                  다올 제공 원본 (배포 제외)
├─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(스티키) → `#top` 히어로 → `#story` 이야기 → `#menu` 우리 떡 → `#gift` 답례·선물(먹 바탕) → `#gallery` 방앗간 → `#record` 발자취 → `#order` 주문 → `#visit` 오시는 길(구글 지도) → 푸터.

## 반응형
모바일 1열(메뉴·선물·갤러리 2열) / ≥720 메뉴·선물 3열, 갤러리 4열 / ≥980 히어로·이야기·주문·오시는길 2단. 내비 링크는 ≤860에서 숨김(전화 주문 버튼만).

## 텍스트 수정 시
폰트가 서브셋이라 **새 글자를 넣으면 그 글자만 다른 폰트로 보일 수 있음** → 문구 바꾸면 서브셋 다시 생성.
