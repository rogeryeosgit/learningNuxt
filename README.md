# nuxt-app

> My perfect Nuxt.js project

## Build Setup

``` bash
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

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Notes

22/2/2020

- Folders matter for routing
- Creating folders should have index.vue
- Folder driven routing (always have a index.vue in new folder)
- "_" means its a dynamic url
- nuxt-link does not call server again for reload of page (Supposed to be SPA)
- route validation can be done only in nuxt
- Under layouts folder, default and error.vue is reserved
- "~" refers to project root folder
- If components are in default layout then it appears everywhere
- style "scoped" only affects page where style appears
