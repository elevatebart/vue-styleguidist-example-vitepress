---
title: "DropDown"
position: 3
category: "components"
---

## DropDown

### Slots

| Name    | Description                      | Bindings |
| ------- | -------------------------------- | -------- |
| default | where the options will be listed |          |

---

<a href="https://github.com/vue-styleguidist/vue-styleguidist/edit/dev/examples/docgen-nuxt/components/DropDown/ReadMe.md" class="docgen-edit-link">edit on github</a>

A drop down is composed of mutiple components.

The dropdown itself and its sub-components.

Use the `@requires` doclet to list the subparts of a component.

```vue live
<DropDown>
  <MyOption val="1">option 1</MyOption>
  <MyOption val="2">option 2</MyOption>
</DropDown>
```

---

## MyOption

### Props

| Prop name | Description                      | Type   | Values | Default |
| --------- | -------------------------------- | ------ | ------ | ------- |
| val       | value associated with the option | string | -      |         |

### Slots

| Name    | Description                  | Bindings |
| ------- | ---------------------------- | -------- |
| default | text displayed in the option |          |
