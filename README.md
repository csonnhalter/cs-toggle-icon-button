[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/csonnhalter/cs-scroll)
# \<cs-toggle-icon-button\>

A button that changes between two icons on tap with an optional tooltip. A wrapper to `<paper-icon-button>` and `<paper-tooltip>`.
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="cs-toggle-icon-button.html">
    <link rel="import" href="../iron-icons/iron-icons.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<cs-toggle-icon-button tip="Press me and I will change!" ></cs-toggle-icon-button>
<cs-toggle-icon-button do-icon="icons:create" done-icon="icons:done"></cs-toggle-icon-button>
```