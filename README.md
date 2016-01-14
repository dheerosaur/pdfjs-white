## pdf.js with white backgrounds, borders

This is created from a build of the PDF.js library.

## How to update?

Download the gh-pages directory from the original pdf.js repo. The one I last downloaded comes from "From examples" section in [FAQ](https://github.com/mozilla/pdf.js/wiki/Setup-PDF.js-in-a-website#from-examples).

## Using compressed JavaScript

For performance reasons, I minified these files that would actually be in viewer.html and put them in build/all.min.js. Command used:

    uglifyjs web/compatibility.js web/l10n.js build/pdf.js web/viewer.js > build/all.min.js
