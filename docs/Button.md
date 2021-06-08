---
title: "Button"
position: 1
category: "components"
---

The only true button.

- **Author**: [Me](mailto:hey@hey.com)
- **Since** 1.2.3

## Props

| Prop name | Description                                                       | Type   | Values                     | Default                                                               |
| --------- | ----------------------------------------------------------------- | ------ | -------------------------- | --------------------------------------------------------------------- |
| color     | The color for the button.                                         | string | -                          | '#333'                                                                |
| size      | The size of the button                                            | string | `small`, `normal`, `large` | 'normal'                                                              |
| onClick   | Gets called when the user clicks on the button<br/>`@ignore` true | func   | -                          | event => {<br> console.log('You have clicked me!', event.target)<br>} |

## Slots

| Name    | Description       | Bindings                                                                                     |
| ------- | ----------------- | -------------------------------------------------------------------------------------------- |
| default | Content of button | **test** `boolean` - describe the binding<br>**message** `string` - describe the message bng |

---

Use vue live right here too

````markdown
```jsx live
<Button>I’m transparent!</Button>
```
````

```jsx live
<Button>I’m transparent!</Button>
```

To render an example as highlighted source code remove the live modifier

```html
<button>I’m transparent!</button>
```

---

<a href="https://github.com/vue-styleguidist/vue-styleguidist/edit/dev/examples/docgen-nuxt/components/Button/Readme.md" class="docgen-edit-link">edit on github</a>

Basic button:

```vue live
<Button>Push Me</Button>
```

Big pink button:

```vue live
<Button size="large" color="deeppink">
  Click Me
</Button>
```

And you _can_ **use** `any` [Markdown](http://daringfireball.net/projects/markdown/) here.

Fenced code blocks with `vue`, `js`, `jsx` or `javascript` languages are rendered as a interactive playgrounds:

```jsx live
<Button>Push Me</Button>
```

You can also use the Single File Component Format

```vue live
<template>
  <div class="wrapper">
    <Button @click.native="pushButton">Push Me</Button>
    clicks : {{ this.numClicks }}
  </div>
</template>
<script>
// You can also use 'exports.default = {}' style module exports.
export default {
  data() {
    return { numClicks: 0 };
  },
  methods: {
    pushButton() {
      this.numClicks += 1;
      this.dogName = this.numClicks;
    }
  }
};
</script>
<style scoped>
.wrapper {
  padding: 10px;
}
.text-name {
  color: red;
}
</style>
```

---

<a href="https://github.com/vue-styleguidist/vue-styleguidist/edit/dev/examples/docgen-nuxt/components/Button/Second-ReadMe.md" class="docgen-edit-link">edit on github</a>

## This is the second readme

one can also load markdown using the `@examples` doclets
