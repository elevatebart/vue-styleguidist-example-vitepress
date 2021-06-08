---
title: "CounterButton"
position: 2
category: "components"
---

Button that counts how many times it was pressed and exposes a `@public` method to reset itself.

## Events

| Event name | Properties                                                                 | Description           |
| ---------- | -------------------------------------------------------------------------- | --------------------- |
| after      | **count** `number` - the count<br>**second** `boolean` - another parameter | After increment event |

---

Don't forget that you can debug it with [vue-devtools](https://github.com/vuejs/vue-devtools)

```vue live
<CounterButton />
```
