Brunch + Karma
==============

Getting Started
---------------

```bash
npm install -g bower brunch
brunch new https://github.com/mikew/brunch-karma myapp
cd myapp
brunch watch --server
```

That's it. Visit `http://localhost:3333/`, as you save files in `app/` that
page will update.

Features
--------

- Javascript
- Coffeescript
- CSS
- Sass
- Karma

Testing
-------

**Using [Karma][karma]:**

```bash
node_modules/.bin/karma start
```

**Using PhantomJS:**

```bash
node_modules/.bin/karma start --browsers PhantomJS
# --reporters junit --single-run can come in handy as well.
```

**Using the browser:**

Run `brunch watch --server` and open `http://localhost:3333/test/`
in your browser.

[brunch]: http://brunch.io/
[karma]: http://karma-runner.github.io/
