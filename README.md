# Summernote Prettyprint Plugin

Plugin that beautify code generated by summernote editor.

## Installation

```bash
(sudo) npm install -g bower
bower install
```

```html
<!-- Bootstrap -->
<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
<script src="../bower_components/jquery/dist/jquery.min.js"></script>
<!-- Include all compiled plugins (below), or include individual files as needed -->
<link rel="stylesheet" href="../bower_components/bootstrap/dist/css/bootstrap.min.css"/>
<script src="../bower_components/bootstrap/dist/js/bootstrap.min.js"></script>

<link rel="stylesheet" href="../bower_components/summernote/dist/summernote.css"/>
<script src="../bower_components/summernote/dist/summernote.min.js"></script>

<!-- A prismjs with some languages pre-selected -->
<link rel="stylesheet" href="../src/css/prism.css">
<script src="../src/js/prism.js" async></script>
<script src="../src/js/summernote-code-beautify-plugin.js"></script>
```

## Usage

Add `div` into `body`; this targeted element will later be rendered to summernote editing tool.

```html
<div id="summernote"></div>
```
Run the script below when document is ready!

```html
<script>
  $(document).ready(function() {
    $('#summernote').summernote({
      toolbar: [
        ['insert', ['prettify']]
      ]
    });
  });
</script>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Todo

- [ ] Add button parameter option
- [x] Add languages support in option

## Credits

TODO: Write credits

## License

[License](LICENSE)
