### Introduction

This fork:
1. Comments out all code for the codeLanguages popover.
2. Allows for a custom `id` on which to hang the floating Simditor toolbar.

  Edit line 1933 of `lib/simditor.js`:

  ```javascript
  // $(window).on('scroll.simditor-' + this.editor.id, (function(_this) {
  $('#simditor-float').on('scroll.simditor-' + this.editor.id,   (function(_this) {
  ```

### Resources

[Ember addon for Simditor on Github](https://github.com/wecatch/ember-cli-simditor)

[Simditor on Github](https://github.com/mycolorway/simditor)

[Simditor docs and demo](http://simditor.tower.im/)

