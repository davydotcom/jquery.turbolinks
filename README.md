# jQuery Turbolinks

Do you like [Turbolinks](https://github.com/rails/turbolinks)? It's easy and fast way to improve user experience of surfing on your website.

But if you have a large codebase with lots of `$(el).bind(...)` Turbolinks will surprise you. Most part of your JavaScripts will stop working in usual way. It's because the nodes on which you bind events no longer exist.

I wrote jquery.turbolinks to solve this problem in [my project](http://amplifr.com). It's easy to use: just require it *after* `jquery.js` and `tubrolinks.js`, but before other scripts.

Sponsored by [Evil Martians](http://evilmartians.com/).

## Usage

Gemfile:
``` js
gem 'jquery-turbolinks'
```

JavaScript manifest file:
``` js
//= require jquery.turbolinks
```

And it just works!

# Changelog

This project uses [Semantic Versioning](http://semver.org/) for release numbering.

## 0.1.0 (October 3, 2012)

* First, initial release

# Contributors

Idea and code by [@kossnocorp](http://koss.nocorp.me/).

# [The MIT License](https://github.com/kossnocorp/jquery.turbolinks/blob/master/LICENSE.md)
