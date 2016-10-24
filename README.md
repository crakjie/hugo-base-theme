# Hugo base theme

Hugo theme based on the [gohugo](https://gohugo.io) website

# Installation

Navigate to your site folder and run the following commands :

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/crakjie/hugo-base-theme.git

## How to use
 - Place a image in `static/img/` and update `mainIcon` in config.toml
 - You can change the header image by adding a new image in the `static/img/` folder of the theme
 - Create posts to display your services. Use the follow as an example:

### post

```toml
+++
date = 2014-10-13T20:07:19Z
draft = true
title = "First"
description = "Ceci est mon premier post \n bla bla bla"
weight = 1
icon = "pacman"
+++

Hello first post
```
### carousel

Create a carousel.md file in /content/carousel

```toml
+++
date = 2014-10-13T19:54:21Z
draft = true
title = "About"
weight = 5
icon = "circlestar"
[[carousel]]
  quote = "First quote"
  author  ="John Do"
  url = ""
  quote_date = "13 August"
[[carousel]]
  quote = "Second quote"
  author  ="Nhoj Od"
  url = ""
  quote_date = "14 August"
+++
```



## Demo
View gohugo.io theme in action [here](https://gohugo.io)
View audrey-carpentras.com in action [here](http://audrey-carpentras.com/)

#Have a look, Have a try
```
git clone https://github.com/crakjie/hugo-base-theme.git
cd hugo-base-theme/exempleSite
hugo server -t hugo-base-theme
```

===

Work also with YAML header

For more Hugo details, read [documentation](http://gohugo.io/overview/introduction/).


## Config

Example of config.toml file:
```toml
baseurl = "https://www.example.com"
languageCode = "fr-fr"
title = "my new web site"
[params]
  description = "I <3 making web site"
  mainIcon = "/img/hugo.png"

[[params.social]]
    title = "twitter"
    url = "https://twitter.com/SBootstrap"
[[params.social]]
    title = "github"
    url = "https://github.com/IronSummitMedia/startbootstrap"
[[params.social]]
    title = "linkedin"
    url = ""
```
