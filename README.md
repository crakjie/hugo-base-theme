# Hugo base theme

Hugo theme based on [gohugo](https://gohugo.io)

## How to use
 - Place a image in `static/img/`
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
### carrousel


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

===

Work also with YAML header

For more Hugo details, read [documentation](http://jekyllrb.com/).

## Config

exemple of config.toml file
```toml
baseurl = "http://yourSiteHere"
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
