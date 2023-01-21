# Flex-Box Architecture
The structure of a flexible layout is based on dividing elements to:  
* containers (parent elements) 
* and items (child elements). 

---

# Flex-Box Architecture
The structure of a flexible layout is based on dividing elements to:  
* <span class="text-indigo-500">**containers (parent elements)**</span>
*  and items (child elements). 

<img src="/assets/01-container.svg" class="rounded" />

---

# Flex-Box Architecture
The structure of a flexible layout is based on dividing elements to:  
* containers (parent elements)
* and <span class="text-yellow-500">**items (child elements)**</span>. 

<img src="/assets/02-items.svg" class="rounded" />


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
