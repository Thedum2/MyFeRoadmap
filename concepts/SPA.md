# SPA

#개념

SPA는 초기 한 번의 앱 셸을 내려받고, 이후 화면 전환을 클라이언트에서 처리하는 웹 애플리케이션 구조다. 문서 전체 교체 대신 필요한 데이터만 갱신해 반응성을 높인다.

전통적인 페이지 단위 이동에서는 매 전환마다 전체 HTML을 다시 받아야 했다. SPA는 이 비용을 줄이기 위해 라우팅과 상태 관리를 브라우저 런타임으로 가져온다.

![[assets/images/SPA-structure-wikimedia.png]]

low-level에서는 JavaScript가 라우트를 해석하고 API 응답을 받아 DOM을 부분 갱신한다. 초기 번들 로드 비용은 크지만, 이후 상호작용 전환은 빠른 편이다.

한계는 초기 로딩, SEO 대응, 복잡한 상태 관리다. 그래서 코드 분할, SSR, 하이드레이션 같은 보완 전략과 함께 쓰는 경우가 많다.

## 관련 개념
[[MPA]]
[[Client Side Rendering]]
[[Code Splitting]]
[[Hydration]]
