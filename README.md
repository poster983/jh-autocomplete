# \<jh-autocomplete\>
A lit (3.0) autocomplete input element
## This repo is an updated and modified version of [kennethklee/nega-autocomplete](https://github.com/kennethklee/nega-autocomplete)

A simple autocomplete web component.

See: [Demo](https://kennethklee.github.io/nega-autocomplete/demo/).

# Usage

## Installation

```shell
npm install --save jh-autocomplete
```

## In an html file

```html
<html>
  <head>
    <script type="module">
      import 'jh-autocomplete/jh-autocomplete.js';
    </script>
  </head>
  <body>
    <jh-autocomplete items="[&quot;dog&quot;,&quot;cat&quot;,&quot;bird&quot;,&quot;fish&quot;,&quot;rabbit&quot;,&quot;fox&quot;,&quot;bear&quot;]">
      <input type="text" placeholder="Animals" />
    </jh-autocomplete>
  </body>
</html>
```

## Improvements 
* Lit 2.0 (lit-element 3.0) support
* `keyValue` property: Will populate the items array from the keys and will return the value of that key when selected.


# Contributing

Feel free to fork and send over PRs. Still a lot of places this can be improved, i.e. styling, more options, or better behaviors.