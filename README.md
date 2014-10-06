
Sliminimal
==========

I am tired of Middleman project templates that come bundled with too many stuff.

So, this is a minimal and not-so-opinionated Middleman project template,
for development in:

- Slim
- Sass
- CoffeeScript


And common tools are included such as:

* LiveReload
* Autoprefixer
* middleman-deploy


And some default configurations such as:

* Relative assets so you can host your files anywhere. Even in a file system or PhoneGap application!
* bower_components added into Sprocket's search path by default. If you use Bower, then it just works. If you don't, then this configuration doesn't do anything. How unobtrusive!
* config.ru that works with Bundler.
* Deploy to GitHub pages


It has been hand-cherry-picked from my projects.

And now, choose your own CSS and JavaScript framework.

Be it jQuery, Angular, Ember, Polymer, Bootstrap, Bourbon, Bootstrap, Typeplate, Normalize, Modernizr, or write your own from scratch.
It's your choice! Don't want jQuery? Just expel it from Gemfile!


How do I?
---------

Clone and bundle install and middleman.


### Quick Website Setup

```bash
# Installation
git init website && cd website
git pull https://github.com/spacetme/sliminimal.git master
bundle install

# Now, create the desired repo on GitHub
hub create user/repo

# When ready, push
git push -u origin master
```


And below is an example of README.md for your project.


Project Name
============

Setup
-----

```bash
bundle
```

Previewing Locally
------------------

```bash
middleman
```

Building Static Pages
---------------------

```bash
middleman build
```


Deploying
---------

```bash
middleman deploy
```


