# Vue 관련 여러가지 scaffold 저장

## vue 3이 기본 생성 버전이 되었고 vue 2.x에 비해 달라진것들이 많아서 샘플 골격 프로젝트 저장용
- 일부 비 익숙하거나 자료가 없는 것들도 많아서 일부는 2.x 스타일...
- 사용하다가 차츰 업데이트 처리 하기

### 메모
- vuex-persistedstate
- vue-bootstrap3 이 알파버전이라 지원이 적다...
  - https://cdmoro.github.io/bootstrap-vue-3
  - 테마도 딱히 찾기 힘든 상태
- 아직까지는 vue2.x, bootstrap4.x 기반으로 하는게 나을 듯. 
  - bootstrap-vue 무료 테마도 제공한다(Argon). 레포지토리 내 참조
  - 아니면 admin-lte 같은 테마의 js/css만 받아서 써도 무방은 할듯.(대신 jquery씀..)
- vue3++ 기반은 대외서비스 할때나 써야지..(2022.07기준)

--- 

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

