# vuex-practice

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

## Notes

- What is Vuex?: Vuex is a state management pattern + library for Vue.js applications.
- Central Store: a centralized store for all the components in an application
- Using Computed Properties
- Getters: a getter
- Mutations: a setter
  - Using store state in a component simply involves returning the state within a `computed property`, because the store state is reactive. Triggering changes simply means committing mutations in component methods.