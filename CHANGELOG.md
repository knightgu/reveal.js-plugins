# Changelog

The versioning scheme is uses the first two numbers of the version of `reveal.js` that was used when updating the plugins. The last number refers to the version of the plugin collection.

## Unpublished

### New features

- Added `loadcontent` plugin
- Plugins now work in strict mode

### Breaking changes

- In `animate` plugin, external svgs must now be loaded with `loadcontent` plugin, `data-src` is no longer supported to load external svg files to be animated 
- Removed deprecated config from `anything` plugin
- Removed deprecated buttons from `chalkboard` plugin
- Removed `embed-tweet` plugin, `loadcontent` plugin can be used instead


## 4.2.0

- Seminar plugin now works with socket.io v4.6.1: Make sure to update seminar server and client library, e.g., by using
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/socket.io/4.6.1/socket.io.js"></script>
```

## 4.1.5

- Last version before starting changelog.