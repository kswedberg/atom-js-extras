# JS Extras

JavaScript extras that either add to or judiciously clobber the Atom defaults.

If you want to use the "end line" key maps in your CSS and HTML files, too, just add these lines to your `keymaps.cson` file:

```
'atom-text-editor[data-grammar~="css"]:not([mini]),
atom-text-editor[data-grammar~="html"]:not([mini])':
  'ctrl-;': 'js-extras:end-line'
  'ctrl-,': 'js-extras:end-line-comma'
  'ctrl-enter': 'js-extras:end-new-line'
```
# Credits

Just about all of the snippets and key maps come from these packages:

* https://github.com/extrabacon/atom-turbo-javascript
* https://github.com/zenorocha/atom-javascript-snippets
* https://github.com/dead-horse/atom-nodejs-snippets
