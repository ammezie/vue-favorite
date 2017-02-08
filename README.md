# vue-favorite

A Vue favorite/like/recommend component.

> Note: vue-favorite uses font-awesome by default and you will be required to pull it in your templates.


## Installation

```
npm install vue-avatar
```

## Usage

```
import Vue from 'vue'
import Favorite from './Favorite.vue'

new Vue({
  el: '#app',
  components: { Favorite }
})
```

## Browser Usage

```
<script src="path/to/vue/vue.min.js"></script>
<script src="path/to/vue-avatar/dist/vue-favorite.js"></script>

new Vue({
  el: '#app',
  components: { Favorite }
})
```

After that, you can use it in your templates:

```
<favorite
    :post=1
    :favorited=false
></favorite>
```

## Props

| Name | Required | Type | Decsription |
|------|:--------:|------|-------------|
| post | Y        |Number| ID of the post
| favorited | Y        |Boolean| determine whether the post has been marked as favorite


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```