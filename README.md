# Santu' sketches

1. npm install bootstrap --save
2. npm install bootstrap --save
3. npm install lightbox2 --save
4. npm install popper.js --save (But don't include in scripts section in angular.json, it breaks lightbox2!)

in angular.json
---------------

"styles": [
  "node_modules/lightbox2/dist/css/lightbox.min.css",
  "node_modules/bootstrap/dist/css/bootstrap.min.css",
  "src/styles.css"
],
"scripts": [
  "node_modules/jquery/dist/jquery.min.js",
  "node_modules/lightbox2/dist/js/lightbox-plus-jquery.min.js",
  "node_modules/bootstrap/dist/js/bootstrap.min.js"
]