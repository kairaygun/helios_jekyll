# Helios Jekyll Version

<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/mit-license-brightgreen.svg" alt="mit license"></a>
<a href="https://www.ruby-lang.org/en/downloads/"><img src="https://img.shields.io/badge/ruby-2.0.0-red.svg" alt="ruby version"></a>
<img src="https://img.shields.io/badge/platform-osx%20%7C%20linux%20%7C%20unix-lightgrey.svg" alt="versions">
<a href="https://www.npmjs.com/"><img src="https://img.shields.io/badge/npm-1.4.28-yellowgreen.svg"></a>

This is a Jekyll version of the theme Helios: http://html5up.net/helios

- __helios_jekyll__
  - [_config.yml](helios_jekyll/_config.yml)
  - ___layouts__
    - [default.html](helios_jekyll/_layouts/default.html)
    - [style.css](helios_jekyll/_layouts/style.css)
  - ___includes__
    - [banner.html](helios_jekyll/_includes/banner.html)
    - [carousel.html](helios_jekyll/_includes/carousel.html)
    - __css__
      - [main.css](helios_jekyll/_includes/css/main.css)
      - [skel.css](helios_jekyll/_includes/css/skel.css)
    - [features.html](helios_jekyll/_includes/features.html)
    - [footer.html](helios_jekyll/_includes/footer.html)
    - [head.html](helios_jekyll/_includes/head.html)
    - [header.html](helios_jekyll/_includes/header.html)
    - [js.html](helios_jekyll/_includes/js.html)
    - [main.html](helios_jekyll/_includes/main.html)
  - ___posts__
    - __carousel__
  - __css__
    - [font-awesome.min.css](helios_jekyll/css/font-awesome.min.css)
    - __ie__
      - [PIE.htc](helios_jekyll/css/ie/PIE.htc)
      - [backgroundsize.min.htc](helios_jekyll/css/ie/backgroundsize.min.htc)
      - [html5shiv.js](helios_jekyll/css/ie/html5shiv.js)
      - [v8.css](helios_jekyll/css/ie/v8.css)
    - __images__
      - [arrow.svg](helios_jekyll/css/images/arrow.svg)
    - [skel.css](helios_jekyll/css/skel.css)
    - [style-mobile.css](helios_jekyll/css/style-mobile.css)
    - [style-narrower.css](helios_jekyll/css/style-narrower.css)
    - [style-normal.css](helios_jekyll/css/style-normal.css)
    - [style-noscript.css](helios_jekyll/css/style-noscript.css)
    - [style-wide.css](helios_jekyll/css/style-wide.css)
    - [style.css](helios_jekyll/css/style.css)
  - __images__
    - [header.jpg](helios_jekyll/images/header.jpg)
    - [pic01.jpg](helios_jekyll/images/pic01.jpg)
    - [pic02.jpg](helios_jekyll/images/pic02.jpg)
    - [pic03.jpg](helios_jekyll/images/pic03.jpg)
    - [pic04.jpg](helios_jekyll/images/pic04.jpg)
    - [pic05.jpg](helios_jekyll/images/pic05.jpg)
    - [pic06.jpg](helios_jekyll/images/pic06.jpg)
    - [pic07.jpg](helios_jekyll/images/pic07.jpg)
    - [pic08.jpg](helios_jekyll/images/pic08.jpg)
    - [pic09.jpg](helios_jekyll/images/pic09.jpg)
    - [pic10.jpg](helios_jekyll/images/pic10.jpg)
    - [pic11.jpg](helios_jekyll/images/pic11.jpg)
    - [pic12.jpg](helios_jekyll/images/pic12.jpg)
    - [pic13.jpg](helios_jekyll/images/pic13.jpg)
    - [pic14.jpg](helios_jekyll/images/pic14.jpg)
    - [pic15.jpg](helios_jekyll/images/pic15.jpg)
  - [index.html](helios_jekyll/index.html)
  - __js__
    - [init.js](helios_jekyll/js/init.js)
    - [jquery.dropotron.min.js](helios_jekyll/js/jquery.dropotron.min.js)
    - [jquery.min.js](helios_jekyll/js/jquery.min.js)
    - [jquery.onvisible.min.js](helios_jekyll/js/jquery.onvisible.min.js)
    - [jquery.scrolly.min.js](helios_jekyll/js/jquery.scrolly.min.js)
    - [skel-layers.min.js](helios_jekyll/js/skel-layers.min.js)
    - [skel.min.js](helios_jekyll/js/skel.min.js)
  - [list.md](helios_jekyll/list.md)
  - __sidebars__
    - [left-sidebar.html](helios_jekyll/sidebars/left-sidebar.html)
    - [no-sidebar.html](helios_jekyll/sidebars/no-sidebar.html)
    - [right-sidebar.html](helios_jekyll/sidebars/right-sidebar.html)



You can check the build here: http://kaira.one/helios_jekyll

Unlike the original theme, users can change the content of the "Post" and "Article" directly under the _post directory. You can add as many posts you want, and you can even change the image by inputting a different file picture. All you have to do is create a new post with the proper file heading: ```YEAR-MM-DD-FILENAME.markdown``` and include this on the header.

```
---
layout: default
title: Post 1
desc: This is a sample post that is added under the "desc" part of the YAML.
img: pic01.jpg
categories: carousel
---
```
