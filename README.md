# Nuxt-Study

<img src="https://media.vlpt.us/images/kyusung/post/28e3a048-4388-414a-8063-957602b876d4/nuxtjs-2.jpg" width="400">

## 실행 방법

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

## Vue.js 와의 차이점

- Nuxt Options
    - asyncData, fetch, head, layout 등 Nuxt에서 사용되는 옵션을 제공한다.
- 라우팅 방식
    - Nuxt에서는 라우터를 따로 작성하지 않고 디렉토리의 구조에 따라 라우터가 작동한다.
- 디렉토리 구조
    - src 폴더 내에 있던 폴더들이 외부로 이동하였다.
    - views 폴더와 route 폴더가 합쳐져 pages 폴더가 되었다.
- 레이아웃 적용
    - layouts 폴더에 페이지에 사용되는 레이아웃을 작성하고, 각각의 페이지에서 레이아웃을 설정한다.
## 학습 참고 링크

### [Nuxt.js 공식 문서](https://nuxtjs.org)
### [Nuxt.js vs Vue.js - SSR 시작하기](https://velog.io/@bluestragglr/Nuxt.js-vs-Vue.js-SSR-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0)