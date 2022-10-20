# vue3-image-view

[npm](https://www.npmjs.com/package/vue3-image-view)


## Installation

use NPM -- is recommended

```sh{1}
$ npm install vue3-image-view
```

use yarn

```sh
$ yarn add vue3-image-view
```

use pnpm

```sh
$ pnpm install vue3-image-view
```

## To use example

```js
// main.ts
import { createApp } from 'vue';
import App from './App.vue';
import vue3ImageView from 'vue3-image-view';
import 'vue3-image-view/dist/style.css';

const app = createApp(App);
app.use(vue3ImageView).mount('#app');
```

```js
// Component.vue
<template>
   <vue3-image-view controllerBtnText="O-h-y-o" :imageWrap="imageWrap" />
</template>

<script>
const imageWrap = [
  {
    url: 'https://gw.alipayobjects.com/zos/antfincdn/cV16ZqzMjW/photo-1473091540282-9b846e7965e3.webp',
  },
  {
    url: 'https://gw.alipayobjects.com/zos/antfincdn/cV16ZqzMjW/photo-1473091540282-9b846e7965e3.webp',
  },
  {
    url: 'https://gw.alipayobjects.com/zos/antfincdn/LlvErxo8H9/photo-1503185912284-5271ff81b9a8.webp',
  },
];
</script>
```
