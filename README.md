# 2020 那些關於 Vue 的事

## Vue 的第一個參數是 [Options](https://vuejs.org/v2/api/index.html#Options-Data)，它用來登錄 Vue 實體所需的對象。
* 註冊一個 Vue 實例的掛載目標。
* 需要一個輸出取得結果的資料。
* 一個向後端取得資料的 Click 事件。

Vue 並不能巢狀
```

```

## 資料雙向綁定
v-text / v-html / v-model

```=
<div id="app">
  {{ message }}
  <div v-html="message"></div>
  <div v-text="message"></div>
  <input type="text" v-model="message"></br>
  <input type="text" v-text="message">
</div>

<script>
var app = new Vue({
  el: '#app',
  data: {
    message: '哈囉'
  }
})
</script> 
```

## About MVVM

![](https://docs.microsoft.com/zh-tw/xamarin/xamarin-forms/enterprise-application-patterns/mvvm-images/mvvm.png)

> Vuejs 是以資料狀態操作畫面
> 傳統 jquery 是直接操作畫面上DOM元素
> Vue.js 在操作 DOM 元素的時候 是透過資料的狀態去變動它

## v-bind 動態屬性指令

[Vue.js 指令](https://cn.vuejs.org/v2/api/#%E6%8C%87%E4%BB%A4)

v-text 等同 {{ }}


