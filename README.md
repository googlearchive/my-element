Source code of the codelab (How to Contribute to the Web Components ecosystem)[https://codelabs.developers.google.com/codelabs/web-components-how-to-contribute/]

----

# \<my-element\>

Given a current and previous value, it computes the difference and renders a symbol.

<!-- 
  The next comment block is used by webcomponents.org to enable inline demo.
  Visit https://www.webcomponents.org/publish for more details.
-->
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-loader.js"></script>
    <link rel="import" href="my-element.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<my-element current="10" previous="0"></my-element>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## License

[MIT](https://opensource.org/licenses/MIT)
