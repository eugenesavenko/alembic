---
title: About Alembic
feature_text: |
  ## Alembic
  A Jekyll boilerplate theme designed to be a starting point for any Jekyll website
feature_image: "https://unsplash.it/1300/400?image=971"
image: "https://unsplash.it/600/400?image=971"
---

Alembic is a starting point for [Jekyll](https://jekyllrb.com/) projects. Rather than starting from scratch, this boilerplate is designed to get the ball rolling immediately. Install it, configure it, tweak it, push it.

{% include button.html text="Fork on GitHub" icon="github" link="https://github.com/daviddarnes/alembic" %} {% include button.html text="Install Alembic" link="https://github.com/daviddarnes/alembic#installation" %} {% include button.html text="Tip me $5" link="https://www.paypal.me/daviddarnes/5usd" color="#333333" %}

## Features

- Available as a starter kit or as [Jekyll 3.3 theme gem](http://jekyllrb.com/docs/themes/)
- Tested in all major browsers, that includes IE as well as Edge
- Extensive set of shortcodes to include various elements; such as buttons, icons, figure images and more
- Solid typographic framework from [Sassline](https://sassline.com/)
- Configurable navigation via a single file
- Modular Jekyll components
- Easily interchangeable sidebar
- Contact form built in using [Formspree](https://formspree.io/)
- Works on [GitHub Pages](https://pages.github.com/) out of the box
- Built with [Jekyll](https://jekyllrb.com/) 3.3
- Designed with [Siteleaf](http://www.siteleaf.com/) in mind
- Has documentation


## Installation

### As a Boilerplate / Fork

1. [Fork the repo](https://github.com/daviddarnes/alembic#fork-destination-box)
2. Clone down the repo with `$ git clone git@github.com:username/reponame.git`
3. Delete the `demo/` folder and `screenshot.png` files
4. Change the `CNAME` record to your projects' record
5. Install bundler with `$ gem install bundler`
6. Install gems with `$ bundle install`
7. Run Jekyll with `$ bundle exec jekyll serve --watch`
8. Begin hacking for your project

### As a Jekyll 3.3 theme gem

1. Download the starter `/demo` content, [quick download link](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/daviddarnes/alembic/tree/master/demo)
2. Install bundler with `$ gem install bundler`
3. Install gems with `$ bundle install`
4. Run Jekyll with `$ bundle exec jekyll serve --watch`
5. Begin hacking for your project


### Boilerplate & Theme differences

The boilerplate kit is better for more drastic hacking and changes, a project that's quite different to any other and needs a lot of custom work done. Additionally you'll only be able to use this method if you want to host it on GitHub Pages, as [themes can't be submitted](https://pages.github.com/themes/)... yet.

Using the theme will allow you to receive updates made and will be more programmatic. To make your own changes you'll need to overwrite the files with your own. For example: If I want to change the colours of my site I'll need to copy the [`_colors.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_colors.scss) file and create my own in `_sass/colors.scss` with my own changes. This is the same for all files within the theme, which means your own project will be more lean than if you were to use the boilerplate.
