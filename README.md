# 신촌 꾼 낚시카페 · 즉시 룰렛 (GitHub Pages 템플릿)

QR 찍자마자 자동으로 한 번만 스핀되고 당첨을 보여주는 단일 HTML 페이지입니다.

## 바로 사용하기
1. 이 저장소를 템플릿으로 사용하거나 ZIP을 업로드하세요.
2. `index.html`만 있어도 동작합니다. (이미 완성본)
3. **GitHub Pages 설정**
   - 저장소 → **Settings → Pages**
   - Source: *Deploy from a branch*
   - Branch: `main` / 폴더: `/ (root)` → **Save**
   - 잠시 후 상단에 배포 주소가 표시됩니다. 예) `https://YOUR-ID.github.io/kkun-roulette/`

## URL 파라미터
- `token`: 영수증/팔찌/회원번호 등 (프론트 1회 제한 보조용)
- `campaign`: 화면 상단 배지에 표시할 이벤트명

예시:
```
https://YOUR-ID.github.io/kkun-roulette/?token=PALCHI15&campaign=현장룰렛
```

## 경품/확률 수정
`index.html`의 `PRIZES` 배열을 수정하세요.
- `name`: 상품명 (이모지 포함 가능)
- `note`: 안내 문구 (예: "👉 수령은 카운터에서!")
- `weight`: 확률 가중치 (전체 합은 자동 계산)
- `color`: 섹터 색상 (HEX)

## 주의
- 이 페이지의 1회 제한은 **프론트(브라우저 저장소)** 기반 보조입니다. 완전 차단은 서버 검증을 추가하세요.
- 모바일(iOS/Android) 호환에 맞춰 자동 스핀만 동작하며 **다시 돌리기 버튼은 없습니다**.

---
© 신촌 꾼 낚시카페
