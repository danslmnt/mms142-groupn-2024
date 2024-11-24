Group N's MMS 142 Activity (Jekyll mediator template)
========

Hello, everyone! This is Group N's group activity repository. This report tackles cryptocurrency as a disruptor of traditional finance systems by revisiting its origins/history and exploring its possible global future. We used the 'mediator' template on Jekyll Themes.

Members:

1. Ruiz, Hannah Jane

2. Ruste, Asleya Faye

3. Salamante, Odessa Danielle

4. Santiago, Janrome Kenneth

5. Sapnu, Diego Miguel

6. Sare, Naomie Maxine

7. Sharpe, Megan

8. Sigua, Janna Arielle

9. Simo, Daphne Sarah

10. Sison, Adrian Dominic

11. Sta Clara, Kaoru Jo Michaela

12. Subido, Alexandra Izabel

13. Tagriza, Angel


Below is the default Read Me file content for the 'mediator' template!

--------

A medium inspired Jekyll blog theme. The basic idea came from the Ghost theme
[Readium 2.0](http://www.svenread.com/readium-ghost-theme/). I use mediator on my own blog [The Base](http://blog.base68.com).

Screenshots
--------
![screenshot](/assets/images/screenshot1.jpg)
![screenshot](/assets/images/screenshot2.jpg)
![screenshot](/assets/images/screenshot3.jpg)

Features
-------
* Fully Responsive layout
* Use header images in articles, if you want to (add tag "image" and url to the image in the front matter section of a post)
* Minimal design
* Featured article support
* FontAwesome implemented for easy use of icons fonts
* Free & Open Source Font usage

Getting Started
---
- [Fork this repository](https://github.com/dirkfabisch/mediator)
- Clone it: `git clone https://github.com/YOUR-USER/mediator`
- Install the requried gems ([GitHub Pages](https://github.com/github/pages-gem), [Bourbon](https://github.com/thoughtbot/bourbon) and [Jekyll](https://github.com/jekyll/jekyll), [Jemoji](https://github.com/jekyll/jemoji)): `bundle install`
- Run the jekyll server: `bundle exec jekyll serve`

You should have a server up and running locally at <http://localhost:4000>.

Configuration
-----

The main settings happen in side of the _config.yml file:

### Site

Main settings for the site

* **title**: name of your site
* **description**: description of your site
* **logo**: small logo for the site (300x * 300x)
* **cover**: large background image on the index page

* **name**: name site owner
* **email**: mail address of the site owner
* **author**: author name
* **author_image**: small image of author (300x * 300px)
* **disqus**: add a disqus forum for your post

### Social

The template allows to add all major social platforms to your site.
Fill the the form for each platform. If you leave the share_* entries empty, the sharing buttons below a post are not shown.  If you leave the **url** and **desc** empty the icons are not shown on the index page, but the share icons on the article pages remains untouched (Thanks to [Phil](https://github.com/philsturgeon))

* **icon**:	name of social platform (must match a name of [font-awsome](http://fortawesome.github.io/Font-Awesome/) icon set )
* **url**:	url of your account
* **desc**: slogan of the platform
* **share_url**: share url
* **share_title**: first part of url for the title
* **share_link**: second part of the share url for the link to the post

The Liquid template engine will magical combine the different parts to a share url.

```
http://twitter.com/share?text=post_title&amp;url=post_url
````

See [_config.yml](https://github.com/dirkfabisch/mediator/blob/master/_config.yml) for more examples.

Licensing
---------

[MIT](https://github.com/dirkfabisch/mediator/blob/master/LICENCE) with no added caveats, so feel free to use this on your site without linking back to me or using a disclaimer or anything silly like that.

Contact
-------
I'd love to hear from you at [@dirkfabisch](https://twitter.com/dirkfabisch). Feel free to open issues if you run into trouble or have suggestions. Pull Requests always welcome.
