# Next.js Tutorial 학습 기록

## [Demo](https://dashboard-1-3135jhxtv-ryomijs-projects.vercel.app/)

## 기술 스택
### 프레임워크 & 언어
- Next.js 15
- React 19
- TypeScript 5.7.2

### 스타일링
- Tailwind CSS 3.4.16
- clsx

### 데이터베이스 & API
- @vercel/postgres
- next-auth 5.0.0-beta.25

### 유틸리티
- bcrypt - 비밀번호 해싱
- use-debounce - 검색 최적화
- zod - 데이터 유효성 검증

### 개발 도구
- ESLint
- Turbopack
- PostCSS
- Autoprefixer

## 기본 설정

1. [패키지 매니저 선택 (npm vs yarn vs pnpm)](https://hushed-guavaberry-fff.notion.site/Next-js-15-npm-vs-yarn-vs-pnpm-162dc9f9c7ff80dd944fd484ab785a0e?pvs=4)
2. [clsx를 사용한 조건부 스타일링](https://www.notion.so/clsx-162dc9f9c7ff80888bcce4cc47c505e1)
3. [폰트 최적화](https://hushed-guavaberry-fff.notion.site/Next-js-CLS-162dc9f9c7ff8030a2e5d60ac6c26a6d)
4. [Next.js 15와 React 19 이해](https://hushed-guavaberry-fff.notion.site/Next-js-15-React-19-161dc9f9c7ff806da104f4be95ca86be)

## [학습 기록](https://www.notion.so/Next-js-15-133dc9f9c7ff803b9ae6e411bdbdb788)

### UI & 레이아웃

- [Layout 이해하기](https://hushed-guavaberry-fff.notion.site/Layout-162dc9f9c7ff80a3b38cf9e8098c4d59)
- [Link 컴포넌트를 이용한 네비게이션 최적화](https://hushed-guavaberry-fff.notion.site/Link-162dc9f9c7ff8086905af4efd2446395)
- [이미지 최적화](https://hushed-guavaberry-fff.notion.site/Next-js-162dc9f9c7ff806b9c72c215a9223cf7)

### 라우팅 & 데이터

- [쿼리 파라미터 관리 (searchParams/useSearchParams)](https://hushed-guavaberry-fff.notion.site/searchParams-useSearchParams-params-usePathname-166dc9f9c7ff804ba8bae2f58ef7340c)
- [경로 정보 활용 (params/usePathname)](https://hushed-guavaberry-fff.notion.site/searchParams-useSearchParams-params-usePathname-166dc9f9c7ff804ba8bae2f58ef7340c)
- [데이터 페칭 방법 선택하기](https://hushed-guavaberry-fff.notion.site/166dc9f9c7ff8031aba4dc6fac53b301)
- [Request Waterfall / Static Rendering / Parallel Data Fetching](https://hushed-guavaberry-fff.notion.site/Request-Waterfall-Static-Rendering-Parallel-Data-Fetching-166dc9f9c7ff8030847ef117b035e778)

### 상태 관리 & 성능

- [Next.js의 렌더링 방식: Static vs Dynamic](https://hushed-guavaberry-fff.notion.site/Next-js-Static-vs-Dynamic-168dc9f9c7ff80f2b39cd96ffcc28e5c)
- [Next.js 스트리밍](https://hushed-guavaberry-fff.notion.site/Next-js-168dc9f9c7ff80ae92f6c4b7f9dcf8ce)
- [Partial Prerendering (PPR)](https://hushed-guavaberry-fff.notion.site/v-canary-Partial-Prerendering-PPR-16bdc9f9c7ff80f99dadddf997c65541)
- [use-debounce: Debouncing 구현](https://hushed-guavaberry-fff.notion.site/use-debounce-Debouncing-16cdc9f9c7ff80bd99bcd611e1a6134e)
- [Next.js에서 데이터 변경: Server Actions 활용](https://hushed-guavaberry-fff.notion.site/Next-js-Server-Actions-16cdc9f9c7ff80f0a280c03ffb95b480)

### 에러 처리 & 폼

- [Next.js의 에러 처리 (try/catch / error.tsx / not-found.tsx)](https://hushed-guavaberry-fff.notion.site/Next-js-try-catch-error-tsx-not-found-tsx-16ddc9f9c7ff8087bc56c65a02e7b5b1)
- [Form Error 처리 - useActionState](https://hushed-guavaberry-fff.notion.site/Form-Error-useActionState-16ddc9f9c7ff803f860aeb099af79a56)
- [FormData Methods](https://hushed-guavaberry-fff.notion.site/FormData-Methods-16cdc9f9c7ff80879e5aefcea9d6e6e4)

### 인증 & 보안

- [NextAuth.js: Next.js에서 인증 구현하기](https://hushed-guavaberry-fff.notion.site/NextAuth-js-Next-js-Authentication-16ddc9f9c7ff809db545e6393af78d07)
- [메타데이터: 정적/동적 메타데이터 구현 가이드](https://hushed-guavaberry-fff.notion.site/16ddc9f9c7ff80899824d757349f2d5b)

## 고급 기능

- [Next.js의 데이터 재검증(Revalidation)](https://hushed-guavaberry-fff.notion.site/Next-js-Revalidation-168dc9f9c7ff80a69e83f99406399cbe)
- [CDN 캐싱](https://hushed-guavaberry-fff.notion.site/CDN-168dc9f9c7ff80f188bbe18382649ce7)
- [CSR vs 동적 렌더링](https://hushed-guavaberry-fff.notion.site/CSR-v-s-16ddc9f9c7ff8033804af174db7bc80d)
- [React와 HTML의 form action 차이점](https://hushed-guavaberry-fff.notion.site/React-HTML-form-action-16cdc9f9c7ff80e8a87ad352374a11c6)
- [Tanstack Query](https://hushed-guavaberry-fff.notion.site/React-HTML-form-action-16cdc9f9c7ff80e8a87ad352374a11c6)
- [ImageResponse](https://hushed-guavaberry-fff.notion.site/ImageResponse-133dc9f9c7ff80359137e9ce61eb4534)

## 참고 자료

- Next.js 공식 문서
- React 공식 문서
- TypeScript 문서
- zod 공식 문서
