
## bootstrap-bower-typeahead

test3
This is the bower repository for the typeahead component of of the [angular-ui/bootstrap project](https://github.com/angular-ui/bootstrap) project.

### Usage

Include the js file into your HTML with a `<script>` tag or your preferred tool.

Use `ui-typeahead-tpls.js` to use the default html templates (recommended). Alternatively, Use `ui-typeahead.js` if you wish to create your own html templates.

Then, be sure to include the module as a dependency for your app:
```js
angular.module('myApp', ['ui.bootstrap.typeahead']
```



And if you are using `ui-typeahead-tpls.js`, be sure to additionally include the bundled html templates as dependencies:
```js
angular.module('myApp', [
  'ui.bootstrap.typeahead',
  'template/typeahead/typeahead-match.html',
  'template/typeahead/typeahead-popup.html'
])
```

