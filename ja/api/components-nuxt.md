---
title: "API: <nuxt> コンポーネント"
description: レイアウト内でページコンポーネントを表示します。
---

# &lt;nuxt&gt; コンポーネント

> このコンポーネントは [レイアウト](/guide/views#レイアウト) 内でのみ、ページコンポーネントを表示するために使われます。

**Props**:
- nuxtChildKey: `string`
  - このpropsは`<router-view/>`に設定され、動的なページと別のルートの内部でトランジションを行うのに便利です。
  - Default: `$route.fullPath`
  
例（`layouts/default.vue`）:

```html
<template>
  <div>
    <div>My nav bar</div>
    <nuxt/>
    <div>My footer</div>
  </div>
</template>
```

実際の例を見たいときは [レイアウトの例](/examples/layouts) を参照してください。
