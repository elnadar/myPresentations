---
layout: two-cols
---

<template v-slot:default>

# Page 2

This is a page with the layout `center` and a background image.

```ts
  function add(
    a: Ref<number> | number,
    b: Ref<number> | number
  ) {
    return computed(() => unref(a) + unref(b))
  }
```
</template>

<template v-slot:right>

# Page 2

This is a page with the layout `center` and a background image.

```ts {2,3}
  function add(
    a: Ref<number> | number,
    b: Ref<number> | number
  ) {
    return computed(() => unref(a) + unref(b))
  }
```
</template>
