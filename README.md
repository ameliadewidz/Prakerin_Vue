# vue-token-login

> demo vue + token log in demo 

- Log in for the first time, send the account password to the backend
- The backend is based on the ```secret key + username + Expiration time ```generated Token，return to front end
- After the front end gets it, it is stored in localStroage and in Vuex
- Every time a request is sent at header add in Token 
## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
