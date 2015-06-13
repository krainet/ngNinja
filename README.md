# [ngNinja](http://github.com/krainet/ngNinja) 

Base project with [AngularJS](http://angularjs.org) for kickstarting


## New Features

- A feature


## Quick Start

Install Node.js and then:

```sh
$ git clone git://github.com/krainet/ngNinja
$ cd ngNinja
$ sudo npm -g install grunt-cli karma bower
$ sudo npm install
$ bower install
$ grunt watch
```

Finally, open `http://localhost:9001` in your browser.

Happy hacking!

## Purpose

`ngNinja` is a simple AngularJS kickstarter project.
around: [Twitter Bootstrap](http://getbootstrap.com),
[Angular UI](http://angular-ui.github.io),
[Angular Bootstrap](http://angular-ui.github.io/bootstrap),
[Font Awesome](http://fortawesome.github.com/Font-Awesome), and
[LESS](http://lesscss.org). Lastly, it contains a sophisticated
[SASS](http://sass-lang.com). Syntactically Awesome Style Sheets
[Grunt](http://gruntjs.org)-based build system to ensure maximum productivity.

All you have to do is clone it and start coding!

## Philosophy

Philosiphy

## Learn

### Overall Directory Structure

At a high level, the structure looks roughly like this:

```
ngNinja/
  |- grunt-tasks/
  |- karma/
  |- src/
  |  |- app/
  |  |  |- <app logic>
  |  |- assets/
  |  |  |- <static files>
  |  |- common/
  |  |  |- <reusable code>
  |  |- less/
  |  |  |- main.less
  |- vendor/
  |  |- angular-bootstrap/
  |  |- bootstrap/
  |  |- placeholders/
  |- .bowerrc
  |- bower.json
  |- Gruntfile.js
  |- module.prefix
  |- module.suffix
  |- package.json
```

### Detailed Installation


### The Build System



### Live Reload!

`ngNinja` also includes [Live Reload](http://livereload.com/), so you no
longer have to refresh your page after making changes! You need a Live Reload
browser plugin for this:

- Chrome - [Chrome Webstore](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei)
- Firefox - [Download from Live Reload](http://download.livereload.com/2.0.8/LiveReload-2.0.8.xpi)
- Safari - [Download from Live Reload](http://download.livereload.com/2.0.9/LiveReload-2.0.9.safariextz)
- Internet Explorer - Surely you jest.

Note that if you're using the Chrome version with `file://` URLs (as is the
default with `ngNinja`) you need to tell Live Reload to allow it. Go to
`Menu -> Tools -> Extensions` and check the "Allow access to file URLs" box next
to the Live Reload plugin.

When you load your page, click the Live Reload icon in your toolbar and
everything should work magically. w00t!

If you'd prefer to not install a browser extension, then you must add the
following to the end of the `body` tag in `index.html`:

```html
<script src="http://localhost:35729/livereload.js"></script>
```

Boom!

## Roadmap


### To Do

See the [issues list](http://github.com/krainet/ngNinja/issues). And
feel free to submit your own!

### Contributing

Make sure to check out the [Contributing Guide](./CONTRIBUTING.md).

So join the team! We're good people.
