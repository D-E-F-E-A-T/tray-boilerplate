# Tray Boilerplate

It's simple, just a boilerplate for Tray projects made at **Santa Fé/FALOMI**. 

Has corrections for Tray CSS/JS and include some ready-to-use components like:

- Dynamic two-levels menu (mobile)
- Dynamic product video
- Full product description with touch gestures (mobile)
- Custom search autocomplete
- Custom quantity input
- Catalog pages with on-demand products (load more button)
- OpenGraph tags
- New style for **search**, **cart**, **register** and **login** pages with accesibility and responsive design enhanced

# Custom Bootstrap

We really don't use all css components of Bootstrap, so for performance enhancement, I made a custom config using only these components:

 - Labels
 - Panels
 - Responsive Embed

The Bootstrap CSS is included in [tray-boilerplate.css](https://github.com/jofelipe/tray-boilerplate/blob/master/css/)

# Installation

  - Clone or download this repository.
  - Change the ID of your store (6 characters) in these files: 

js/tray-boilerplate.js
```js
var storeId = XXXXXX;
```

layouts/default.html
```js
jQuery('.central-saudacao h2').append('<a href="/loja/logout.php?loja=XXXXXX" class="link-logout"> [ Sair ]</a>');
```

  - And finally, have fun!

License
----

Free for use, customization and whatever you want to do :)
