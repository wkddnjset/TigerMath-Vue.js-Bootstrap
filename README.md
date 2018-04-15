# TigerMath-Vue.js-Bootstrap
TigerMath LandingPage Using Vue.js And Bootstrap

## Start Vue.js [![Build Status](https://circleci.com/gh/vuejs/vue-cli/tree/dev.svg?style=shield)](https://circleci.com/gh/vuejs/vue-cli/tree/dev) [![Windows Build status](https://ci.appveyor.com/api/projects/status/487fqt71e4kf46iv/branch/dev?svg=true)](https://ci.appveyor.com/project/yyx990803/vue-cli-6b0a6/branch/dev)

### Getting Start [[Github](https://github.com/vuejs/vue-cli/edit/dev/README.md)]

``` sh
npm install -g @vue/cli
vue create my-project
cd my-project
npm run serve
```
### Install Bootstrap [[Document](https://bootstrap-vue.js.org/docs/components/alert)]

```sh
npm i bootstrap-vue
```

**main.js**
```js
import Vue from 'vue'
import BootstrapVue from 'bootstrap-vue'

Vue.use(BootstrapVue);

```
**App.vue**
```html
<script>
...
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
...
</script>
```
