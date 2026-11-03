# 절에간성경 FOOD MARKET — 미팅용 디자인 시안

PC/모바일 반응형, 영상·쇼츠 탐색, 상품 상세, 검색, 카테고리, 찜, 장바구니 인터랙션을 포함한 **프론트엔드 시연용** 웹사이트입니다.

## 로컬 실행

Node.js 20.19+ 또는 22.12+ 환경에서:

```bash
npm install
npm run dev
```

터미널에 표시되는 주소(보통 http://localhost:5173)를 브라우저에서 여세요.

## Vercel 배포

1. 이 폴더를 GitHub 저장소에 업로드합니다.
2. Vercel에서 **Add New → Project → Import Git Repository**를 선택합니다.
3. Framework Preset은 **Vite**, Build Command는 `npm run build`, Output Directory는 `dist`로 설정합니다.
4. **Deploy**를 누르면 공유 가능한 URL이 생성됩니다.

## 주의

- 이 사이트는 디자인/미팅용 샘플입니다. **실제 결제, 주문, 로그인, 배송, 재고 관리 기능은 없습니다.**
- 상품·가격·영상 제목은 가상의 샘플이며 실제 유튜브 영상은 연결되어 있지 않습니다. 영상 미리보기는 플레이스홀더입니다.
- 상품 사진은 Unsplash 외부 이미지 URL을 사용하므로 인터넷 연결이 필요합니다. 실제 운영 전 상업적 사용권과 상품 일치 여부를 확인하고 정식 이미지를 교체하세요.
- 실제 운영 시 Spring Boot API와 연결할 수 있도록 `products`, `videos` 샘플 데이터를 별도로 정의했습니다.
