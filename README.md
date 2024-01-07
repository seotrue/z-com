##  create-next-app@laste
  
- 퍼블릭: 넥스트 서버에서 누구나 접근 
- src 
    - app :  라우팅


next dev
npm run dev


### 브라우저 주소 app 폴더에 반영
- RootLayout: 레이아웃이 children을 받아서 page을 렌더링 시켜줌
  

### 폴더 구조
-app
  -(afterLogin) // 실제 url에는 영향을 끼치지 않고 그룹화 할수 있다
  not-found.tsx
 -i
  -flow
    - login
    - signup
 - compose
   - tweet
     - page.tsx
 - explore
   - page.tsx
 - home
   - layout.tsx // 홈의 개별적은 레이아  RootLayout -> HomeLayout-> Home
 - [username]// 다이나믹 라우팅 slug
   - status
     - [id]
       - page.tsx
     - page.tsx
 - layout.tsx // 전체의 레이아웃

### templete 와 layout의 차이
- 리랜더링이 되구 싶으면 templete=> 페이지를 넘너뒬때 기록하고 싶을때 gmt 하고 싶을대 
 
### styles
- 단위 dvw/dvh

#### iterceoting Routing /  Parallel Routing
