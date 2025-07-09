---
layout: page
title: Natural Language Processing Group at Utrecht University
---

## About Us

Welcome to the homepage of UU-NLP, the Natural Language Processing Group in the Department of Information and Computing Science at Utrecht University. We are a highly interdisciplinary team working on computational models of Natural Language, led by [Albert Gatt](https://albertgatt.github.io/). 

Our work centres around a number of core themes, including:
Models for automatic text generation and their evaluation;
Computational methods to study the relationship between [language and society](https://nlpsoc.github.io/);
Methods to model the interface between language and speech with other modalities, especially vision;
The challenges of [meaning variation](https://sites.google.com/view/dealingwithmeaningvariation/home) arising from subjective bias, ambiguity and vagueness.
In our research, we collaborate with a broad network of researchers, including colleagues in [Humanities](https://www.uu.nl/onderzoek/institute-for-language-sciences) and the [Social Sciences](https://nlp.sites.uu.nl/). [UU-NLP] forms part of [NLP@U](https://www.uu.nl/en/research/applied-data-science/special-interest-group-text-mining), the UU Joint Special Interest Group in Natural Language Processing.

### Create a repository from this template

* [Go to this repository page on Github](https://github.com/nicolas-van/bootstrap-4-github-pages).
* Click the `Star` button on the top right. (OK, this step is facultative, but that would make you a nice person)
* Click the `Use this template` button on the top right of the page.

### Choose a name for your repository

Here we have two possibilities:

* **You want a user or organization website**

  In this case your website's URL will be `http://<your username>.github.io` where `<your username>` is your Github user name.

  Choose the repository name `<your username>.github.io`.

* **You want a project website**

  In this case your website's URL will be `http://<your username>.github.io/<whatever you want>` where `<whatever you want>` can be any valid name for a Github repository.

  Choose the repository name `<whatever you want>`.

### Activate Github Pages on your repository

Go in the `Settings` page of your repository, in the `Github Pages`, under the `Source` parameter, choose `master branch` then `Save`.

### That's it

Your Github Pages website with customizable Bootstrap 5 is now up and running, you can access it using the URL displayed by Github in the `Github Pages` settings.

## Customization Guide

### Modify the configuration

You should at least edit the `_config.yml` file to edit your website's metadata, like the title, description and repository URL.

### Change your theme

This website uses the [Minty](https://bootswatch.com/minty/) Bootstrap theme by default. And you don't want to use the same theme everyone else uses do you?

You can of course modify anything in the `_includes`, `_layouts` and `_sass` folders to customize both the HTML or CSS of your website, possibly referring to the [Bootstrap documentation](https://getbootstrap.com/) or the [Jekyll documentation](https://jekyllrb.com/) when needed. This is a normal part of web development and it is outside the scope of this guide.

But if you don't know where to start I can recommend you to import a theme from [Bootswatch](https://bootswatch.com/).

* Go on [Bootswatch](https://bootswatch.com/) and choose a theme that you like.
* Using the top bar, download its `_variables.scss` and `_bootswatch.scss` files.
* Copy the content of `_variables.scss` in `_sass/_variables.scss`.
* Copy the content of `_bootswatch.scss` in `_sass/_bootstrap_customization.scss`.

That's it, you now have a totally different appearance for you website.

### Modify the content

You probably don't want the present guide to be the front page of your website, so you should edit the `index.md` file. You probably also want to edit or delete the `CONTRIBUTING.md`, `README.md` and `LICENSE.md` files.

Aside from that you can of course create new pages and posts like with any Jekyll website by refering to the [Jekyll documentation](https://jekyllrb.com/).

### Run Jekyll on your computer to speed up testing

Editing your website's content or theme directly on Github is completely possible but, due to the time Github Pages takes to update your website, it will probably be much more effective to work using a local Jekyll installation.

To do so:

* Install the [requirements for Jekyll](https://jekyllrb.com/docs/installation/).
* Type `bundle install` at the root of your project to install the necessary Ruby dependencies.
* Type `bundle exec jekyll serve` to launch the test Jekyll web server that will re-compile your work if you edit it.
* You can then open `http://localhost:4000` in your web browser to see your work-in-progress website.

Please note that, to ensure maximum compatibility with Github Pages, the `Gemfile` of this project references the `github-pages` gem, not Jekyll directly. This implies some differences in behavior compared to the official documentation of Jekyll.

## Known issues

* Bootstrap 5 should normally be post-processed using [Autoprefixer](https://github.com/postcss/autoprefixer). Even if it is possible to use autoprefixer with Jekyll, it is not possible with a classic Github Pages installation without adding some kind of pre-processing before publication. Since this project mostly aims compatibility with Github Pages I prefer to keep it that way. The consequences of this choice is that some Bootstrap features could not work as expected on older browsers.

## How to contribute

Like this project ? [Consider adding a star on Github](https://github.com/nicolas-van/bootstrap-4-github-pages).

[You can also see the contribution guide](https://github.com/nicolas-van/bootstrap-4-github-pages/blob/master/CONTRIBUTING.md).

## Websites using Bootstrap 4 Github Pages

* [My personal blog](https://nicolas-van.github.io/)
* [the wavelet's profile](https://thewavelet.github.io/)
* [William Moore's website](https://will2bill.com/)
* [roseblood.github.io](https://roseleblood.github.io/)
* [borislouis.github.io](https://borislouis.github.io/)
* [dariusnwadike.github.io](https://dariusnwadike.github.io/)
* [libcoap.net](https://libcoap.net/)

## Other Github Pages related projects

I'm a fan of Github Pages for the possibilities it offers to anyone to publish a website for free. I have multiple projects that could be of interest if that's your case too:

* [Easy Markdown to Github Pages](https://nicolas-van.github.io/easy-markdown-to-github-pages/)
* [Parcel Github Pages Boilerplate](https://github.com/nicolas-van/parcel-github-pages-boilerplate)

