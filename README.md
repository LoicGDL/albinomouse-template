#AlbinoMouse for Shaarli#

AlbinoMouse is a template for [ Shaarli](https://github.com/shaarli/Shaarli) maintained by [alexis j](http://liens.effingo.be).

Live demo (frontend) : [http://liens.effingo.bej](http://liens.effingo.be)

GitHub : https://github.com/alexisju/albinomouse-template/

Screenshot  with "[am_menu](https://github.com/alexisju/am_menu)" and "[social](https://github.com/alexisju/social)" plugins  :

![screenshot](https://raw.githubusercontent.com/alexisju/albinomouse-template/master/inc/screenshot.png)

### Installation ###

To download this theme, visit [this page](https://github.com/alexisju/albinomouse-template/archive/master.zip) and choose the most recent version matching the version of your Shaarli installation. Both use the same notation.

Put the `albinomouse-template` folder into the `tpl` directory of your Shaarli installation.

You can also directly run `git clone https://github.com/alexisju/albinomouse-template.git` into the `tpl` directory 

In your Shaarli installation, open the `data/config.json.php`  and change the `raintpl_tpl` parameter to `tpl\/albinomouse-template/`.

```json
{
    "resource": {
        "raintpl_tpl": "tpl\/albinomouse-template/",
        [...]
    }
}
```

Since Shaarl version 0.8.2, you can change or activate this template directly trough the admin panel of your Shaarli.

Follow this link to know more about [Shaarli templates] (https://github.com/shaarli/Shaarli/wiki/Theming)

### Plugins ###

I highly recomend you to use this template at least with [AM_Menu](https://github.com/alexisju/am_menu).

You can also use this follwing plugin developped for AlbinoMouse template : 

 - [Social](https://github.com/alexisju/social) : share easily your links on social networks ;
 - [Qrcode](https://github.com/alexisju/am_qrcode) : an alternative QR Code plugin ;
 - [Go to top](https://github.com/alexisju/gototop) : add a "go to top" link.

### Licences ###

  - AlbinoMouse :  [licence GPLv3] (inc/albinomouse-licence.txt)
  - Glyphicons Halflings (http://getbootstrap.com) : [MIT Licence] (inc/fonts/glyphicon-licence.txt)
  - OpenSans (http://opensans.com) : [Apache Licence version 2.0] (inc/fonts/opensans-license.txt)

### Credit ###

This template is directly inspired by [AlbinoMouse for WordPress](https://wpzoo.ch/en/themes/albinomouse/) maintained by Stefan Brechbühl.

------------------------------------------------------------------------------

Shaarli Material was tested and validated on Shaarli 0.8.2.

You can download Shaarli via the Github project page : https://github.com/shaarli/Shaarli
