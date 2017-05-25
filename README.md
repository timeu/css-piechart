[![Build Status](https://travis-ci.org/timeu/css-piechart.svg?branch=master)](https://travis-ci.org/timeu/css-piechart) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/timeu/css-piechart)

# &lt;css-piechart&gt;

> A web-component to draw a piechart using Polymer and CSS3.

**This branch (master) works only with Polymer 2.x. For a Polymer 1.x version check out the 1.x branch**

## Versions (Polymer 2.x vs Polymer 1.x)
The *master* branch and all *2.x.x* releases require `Polymer 2.x`.
For `Polymer 1.x` support use *1.x.x* releases and the [1.x branch](https://github.com/timeu/css-piechart/tree/1.x).

## Demo
> [Check it live](https://www.webcomponents.org/element/timeu/css-piechart).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install --save css-piechart
```

Or [download as ZIP](https://github.com/timeu/css-piechart/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

  ```html
<script src="../webcomponentsjs/webcomponents-lite.js"></script>
  ```

2. Import Custom Element:

  ```html
<link rel="import" href="../css-piechart/css-piechart.html">
  ```

3. Start using it!

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="css-piechart.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
  <css-piechart size="250" data="[10,20,50,20]"></css-piechart>
```


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/timeu/css-piechart/releases) list.

## License

[MIT License](http://timeu.mit-license.org/) © Ümit Seren
